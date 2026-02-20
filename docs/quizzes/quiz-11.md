# Quiz 11 - Deploy em Cloud 🚀

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. O que é o processo de "Deploy"?</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Deploy é levar para produção o que foi feito localmente.">Apagar o código antigo do computador do desenvolvedor</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Deploy é o ato de disponibilizar a aplicação em um ambiente de execução (servidor) para os usuários.">Disponibilizar a aplicação em um servidor para que ela possa ser acessada pelos usuários</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Deploy é levar para produção o que foi feito localmente.">Comprar um novo computador para a empresa</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Deploy é levar para produção o que foi feito localmente.">Traduzir o site para outro idioma</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. Qual o papel de um "Registry" (como o Docker Hub) no deploy?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O Registry funciona como um repositório centralizado de imagens prontas para serem baixadas pelos servidores.">Armazenar as imagens Docker prontas para que o servidor de produção possa baixá-las</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O Registry funciona como um repositório centralizado de imagens prontas para serem baixadas pelos servidores.">Registrar o nome dos desenvolvedores que trabalharam no projeto</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O Registry funciona como um repositório centralizado de imagens prontas para serem baixadas pelos servidores.">Aumentar a velocidade do banco de dados</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O Registry funciona como um repositório centralizado de imagens prontas para serem baixadas pelos servidores.">Trocar a senha do usuário automaticamente</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. O que é um serviço de "PaaS" (Platform as a Service) no contexto de deploy?</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. PaaS como Heroku ou Render automatizam o deploy, bastando conectar o GitHub.">Um serviço onde você precisa configurar todo o hardware e SO manualmente</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! PaaS como Heroku ou Render automatizam o deploy, bastando conectar o GitHub.">Um serviço que automatiza o deploy e a gestão da infraestrutura, permitindo focar no código</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. PaaS como Heroku ou Render automatizam o deploy, bastando conectar o GitHub.">Um programa que desenha telas para o site</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. PaaS como Heroku ou Render automatizam o deploy, bastando conectar o GitHub.">Um tipo de banco de dados super rápido</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. Por que usar Variáveis de Ambiente em vez de colocar segredos (senhas) direto no código?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Segredos no código podem ser vazados se o repositório for exposto. Variáveis são injetadas apenas na execução.">Por segurança: evita que senhas vazem no repositório de código e facilita trocar configurações sem mudar o código</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Segredos no código podem ser vazados se o repositório for exposto. Variáveis são injetadas apenas na execução.">Porque o código fica mais curto e fácil de ler</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Segredos no código podem ser vazados se o repositório for exposto. Variáveis são injetadas apenas na execução.">Para que o Google possa ler as senhas e ajudar se você esquecer</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Segredos no código podem ser vazados se o repositório for exposto. Variáveis são injetadas apenas na execução.">As variáveis de ambiente não servem para segurança</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. O que significa o conceito "Serverless" aplicado a containers?</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Serverless significa que o provedor gerencia tudo e você só paga pelo tempo de processamento real.">Significa que a aplicação roda sem nenhum servidor real por trás</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Serverless significa que o provedor gerencia tudo e você só paga pelo tempo de processamento real.">Significa que você não gerencia servidores e paga apenas pelos recursos consumidos durante a execução</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Serverless significa que o provedor gerencia tudo e você só paga pelo tempo de processamento real.">Significa que o site só funciona se o servidor estiver desligado</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Serverless significa que o provedor gerencia tudo e você só paga pelo tempo de processamento real.">É um servidor que não tem teclado nem mouse</div>
  <div class="quiz-feedback"></div>
</div>

