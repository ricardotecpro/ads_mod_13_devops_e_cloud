# Aula 07 - Containers e Virtualização 🐳

!!! tip "Objetivo"
    **Objetivo**: Entender o que são containers, como eles se diferenciam das Máquinas Virtuais (VMs) tradicionais e por que eles se tornaram o padrão da indústria para Deploy de aplicações.

---

## 1. O Problema: "Na minha máquina funciona!" 🤷‍♂️

Um dos maiores desafios do desenvolvimento é garantir que o software rode da mesma forma no computador do desenvolvedor e no servidor de produção. Diferenças de sistema operacional, bibliotecas e versões causam erros inesperados.

A **Conteinerização** resolve isso empacotando a aplicação com **tudo** o que ela precisa para rodar.

---

## 2. Containers vs Máquinas Virtuais (VMs) ⚔️

Antigamente, usávamos VMs para isolar aplicações. Mas as VMs são pesadas.

| Característica | Máquina Virtual (VM) | Container (Docker) |
| :--- | :--- | :--- |
| **Peso** | Pesada (Gigas) | Leve (Megas) |
| **Velocidade** | Minutos para ligar | Segundos para ligar |
| **Isolamento** | Completo (Hardware virtual) | Processos isolados no SO |
| **Sistema Operacional** | Possui um SO completo dentro | Compartilha o Kernel do Host |

---

## 3. O que é um Container? 📦

Pense em um container como uma "caixa" que contém:
*   O código da sua aplicação.
*   O runtime (ex: Node.js, Python, Java).
*   As bibliotecas dependentes.
*   Variáveis de ambiente e arquivos de configuração.

Tudo o que está dentro da caixa é **imutável** e **portável**. Se rodar no seu PC, vai rodar igual em qualquer lugar que tenha Docker.

---

## 4. Como funciona o Docker? 🏗️

O Docker é a ferramenta que popularizou os containers. Ele trabalha com três conceitos básicos:

1.  **Dockerfile**: A "receita do bolo". Um arquivo de texto com as instruções para criar a imagem.
2.  **Imagem**: O "bolo pronto e congelado". É o arquivo que contém a aplicação pronta para rodar.
3.  **Container**: O "bolo sendo servido". É a imagem em execução (um processo vivo).

---

## 5. Benefícios para o DevOps 💎

*   **Padronização**: O ambiente é o mesmo em Dev, Teste e Prod.
*   **Escalabilidade**: Você pode subir 100 containers em segundos se o tráfego aumentar.
*   **Eficiência**: Mais aplicações rodando no mesmo hardware comparado a VMs.
*   **Microserviços**: Facilita a divisão de uma aplicação grande em partes menores e independentes.

---

## 6. Exercício de Fixação 🧠

1.  Por que os containers são considerados mais eficientes que as Máquinas Virtuais?
2.  O que significa dizer que um container é "portável"?
3.  Qual a função do Dockerfile no processo de criação de um container?

---

**Próxima Aula**: Vamos colocar a mão na massa e criar nosso primeiro container! [Docker na Prática](./aula-08.md) 🚀
