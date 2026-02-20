# Quiz 06 - Entrega Contínua (CD) 🚚

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. Qual a diferença entre Continuous Delivery e Continuous Deployment?</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. No Delivery há uma aprovação manual; no Deployment o processo é 100% automático até a produção.">Nenhuma, são nomes diferentes para a mesma coisa</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! No Delivery o deploy para produção exige aprovação humana, no Deployment é automático.">No Delivery a decisão de ir para produção é humana; no Deployment é automática</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. No Delivery há uma aprovação manual; no Deployment o processo é 100% automático até a produção.">Delivery é para comida e Deployment é para software</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. No Delivery há uma aprovação manual; no Deployment o processo é 100% automático até a produção.">Deployment é apenas para ambientes de teste</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. O que é um ambiente de "Staging" (ou Homologação)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. É um ambiente idêntico à produção usado para validar a versão antes do lançamento final.">A pasta onde o desenvolvedor guarda o código no seu próprio PC</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! É uma cópia fiel do ambiente de produção usada para testes finais.">Um ambiente idêntico ao de produção usado para validar o software antes do lançamento</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. É um ambiente idêntico à produção usado para validar a versão antes do lançamento final.">Um servidor lento usado apenas para economizar dinheiro</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. É um ambiente idêntico à produção usado para validar a versão antes do lançamento final.">O computador do cliente final</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. Como funciona a estratégia de deploy "Blue-Green"?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Você alterna o tráfego entre dois ambientes idênticos para evitar downtime.">Mantém dois ambientes idênticos; você sobe a versão nova no ambiente inativo e depois "vira a chave" do tráfego</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Você alterna o tráfego entre dois ambientes idênticos para evitar downtime.">Significa que você pinta os servidores de azul e verde</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Você alterna o tráfego entre dois ambientes idênticos para evitar downtime.">Atualiza um servidor por vez até completar todos</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Você alterna o tráfego entre dois ambientes idênticos para evitar downtime.">Deleta o banco de dados antigo antes de criar o novo</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. O que é um "Canary Release"?</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. É a liberação gradual para uma pequena parcela de usuários para testar o impacto.">Um tipo de programa que detecta vírus</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Libera a nova versão para apenas uma pequena porcentagem de usuários inicialmente.">Liberar a nova versão para um pequeno grupo de usuários antes de liberar para todos</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. É a liberação gradual para uma pequena parcela de usuários para testar o impacto.">Atualizar o sistema apenas durante a madrugada</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. É a liberação gradual para uma pequena parcela de usuários para testar o impacto.">Mudar a senha de todos os usuários</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. Qual o papel da Infraestrutura como Código (IaC) no CD?</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. IaC garante que os ambientes sejam criados de forma idêntica e automatizada através de roteiros.">Serve para deixar o site mais rápido</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Garante que os ambientes de teste e produção sejam configurados exatamente da mesma forma através de código.">Garantir que os ambientes sejam padronizados e recriáveis automaticamente</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. IaC garante que os ambientes sejam criados de forma idêntica e automatizada através de roteiros.">Permite que o próprio usuário final programe o servidor</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. IaC garante que os ambientes sejam criados de forma idêntica e automatizada através de roteiros.">Substitui o papel do desenvolvedor backend</div>
  <div class="quiz-feedback"></div>
</div>

