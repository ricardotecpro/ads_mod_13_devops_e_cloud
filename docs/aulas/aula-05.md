# Aula 05 - Integração Contínua (CI) ⚙️

!!! tip "Objetivo"
    **Objetivo**: Entender o conceito de Integração Contínua (CI), por que ela é fundamental para o DevOps e como as ferramentas automatizam o processo de build e teste cada vez que um commit é feito.

---

## 1. O que é Integração Contínua (CI)? 🔄

A **Integração Contínua** é a prática de integrar o código de todos os desenvolvedores em um repositório compartilhado várias vezes ao dia. 

Cada integração é verificada por um **Build Automatizado** e por **Testes Automatizados**, permitindo que as equipes detectem problemas rapidamente.

### O Problema do "Integration Hell" 😵‍💫
Antes do CI, os desenvolvedores trabalhavam isolados por semanas. Na hora de juntar tudo (merge), o sistema quebrava de tantas formas que levava dias para consertar. O CI resolve isso ao integrar **pequenas mudanças constantemente**.

---

## 2. O Pipeline de CI 🏗️

Um pipeline de CI geralmente segue este fluxo:

```mermaid
graph LR
    Code(["Código"]) --> Commit(["Commit/Push"])
    Commit --> Build(["Build/Compilação"])
    Build --> Unit(["Testes Unitários"])
    Unit --> Static(["Análise Estática"])
    Static --> Artifact(["Artefato Gerado"])
```

### Automação de CI (Termynal) 💻

<div id="termynal" data-termynal markdown>
<span data-ty="input">git push origin develop</span>
<span data-ty>Iniciando Pipeline...</span>
<span data-ty="progress"></span>
<span data-ty>Rodando Pytest... [PASSED]</span>
<span data-ty>Análise de Lint... [SUCCESS]</span>
<span data-ty>Geração de Imagem: v1.0.5</span>
<span data-ty>Status: Pipeline Completo! ✅</span>
</div>

1.  **Commit/Push**: O gatilho que inicia o processo.
2.  **Build**: O servidor baixa as dependências e o código é transformado em algo executável (se necessário).
3.  **Testes Unitários**: Scripts que testam as menores partes do código (funções e classes).
4.  **Análise Estática (Lint)**: Verifica se o código segue boas práticas e padrões de estilo.
5.  **Artefato**: O resultado final (um arquivo .bin, uma imagem Docker, etc) pronto para ser testado mais a fundo.

---

## 3. Benefícios do CI 💎

*   **Feedback Rápido**: O desenvolvedor sabe em minutos se quebrou algo.
*   **Qualidade do Código**: Erros não chegam a branches estáveis.
*   **Confiança**: O time sabe que o código no repositório está "saudável".
*   **Documentação Viva**: Os testes automatizados explicam como o sistema deveria funcionar.

---

## 4. Ferramentas Populares de CI 🛠️

Existem muitas ferramentas no mercado. As mais usadas hoje são:

*   **GitHub Actions**: Integrado diretamente no GitHub (vamos focar nele!).
*   **Jenkins**: O "vovô" do CI, muito poderoso e customizável.
*   **GitLab CI**: Integrado ao GitLab.
*   **CircleCI / Travis CI**: Soluções de mercado focadas em facilidade de uso.

---

## 5. Prática Sugerida: O Primeiro Pipeline 🚀

Imagine que você tem um projeto Python. Um arquivo de workflow do GitHub Actions (`.github/workflows/main.yml`) seria assim:

```yaml
name: CI Pipeline
on: [push] # Gatilho
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - name: Instalar Dependências
        run: pip install -r requirements.txt
      - name: Rodar Testes
        run: pytest
```

---

## 6. Exercício de Fixação 🧠

1.  Qual a diferença entre um Build Manual e um Build de CI?
2.  O que acontece se um teste falhar durante o pipeline de CI?
3.  Por que o feedback rápido é considerado a maior vantagem do CI?

---

**Próxima Aula**: Agora que o código está integrado e testado, como levamos ele para o usuário? Vamos falar de [Entrega Contínua (CD)](./aula-06.md)! 🚚
