# Aula 12 - Infraestrutura como Código (IaC) 💻

!!! tip "Objetivo"
    **Objetivo**: Compreender o conceito de Infraestrutura como Código (IaC), entender a diferença entre provisionamento imperativo e declarativo, e conhecer o Terraform como a ferramenta líder de mercado.

---

## 1. O que é Infraestrutura como Código (IaC)? 🏗️

Antigamente, para criar um servidor, um analista precisava entrar no console da AWS/Azure, clicar em vários botões e preencher formulários.
Com **IaC**, nós escrevemos um arquivo de texto (código) que descreve como a infraestrutura deve ser. O software lê esse arquivo e cria tudo automaticamente.

---

## 2. Por que usar IaC? 💎

*   **Velocidade**: Criar 100 servidores leva o mesmo tempo que criar 1.
*   **Versionamento**: Sua infraestrutura está no Git. Você sabe quem mudou o quê e quando.
*   **Padronização**: Garante que o ambiente de Teste seja **exatamente igual** ao de Produção.
*   **Recuperação**: Se um datacenter inteiro pegar fogo, você roda o código e recria tudo em outro lugar em minutos.

---

## 3. Imperativo vs Declarativo ⚖️

*   **Imperativo (O "Como")**: Você dá ordens passo a passo. "Crie uma VM", "Instale o Docker", "Abra a porta 80". (Ex: Shell Script, AWS CLI).
*   **Declarativo (O "O Que")**: Você descreve o estado final desejado. "Eu quero 1 servidor com Docker e a porta 80 aberta". A ferramenta se vira para chegar lá. (**Terraform** usa este modelo).

---

## 4. Terraform: O Gigante da IaC 🌍

O **Terraform** é a ferramenta mais popular porque é "Cloud Agnostic" (funciona com quase qualquer nuvem).

```hcl
# Exemplo de código Terraform (Linguagem HCL)
resource "aws_instance" "meu_servidor" {
  ami           = "ami-0c55b159cbfafe1f0"
  instance_type = "t2.micro"

  tags = {
    Name = "Servidor-Do-Curso"
  }
}
```

---

## 5. O Fluxo de Trabalho do Terraform 🔄

1.  **Write**: Escreve o código `.tf`.
2.  **Init**: O Terraform baixa os arquivos necessários para falar com a nuvem escolhida.
3.  **Plan**: O Terraform mostra o que ele vai fazer antes de realmente fazer ("Vou criar 2 itens e destruir 0").
4.  **Apply**: O Terraform executa as mudanças na nuvem.

---

## 6. O arquivo State (.tfstate) 🗂️

O Terraform guarda um arquivo (State) que é o "mapa" da sua infraestrutura atual. Nunca delete ou edite este arquivo manualmente! Ele é a memória do Terraform.

---

## 7. Exercício de Fixação 🧠

1.  Qual a principal diferença entre criar um servidor clicando em botões no navegador e criar usando código?
2.  O que significa dizer que o Terraform é "Declarativo"?
3.  Por que é importante colocar o código da infraestrutura em um repositório Git?

---

**Próxima Aula**: Como sabemos se o sistema está saudável depois do deploy? [Monitoramento e Observabilidade](./aula-13.md) 📊
