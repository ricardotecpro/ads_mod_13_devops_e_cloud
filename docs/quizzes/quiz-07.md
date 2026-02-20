# Quiz 07 - Containers e Virtualização 🐳

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. Qual a principal diferença entre um Container e uma Máquina Virtual (VM)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Containers compartilham o Kernel do sistema operacional, o que os torna muito mais leves e rápidos que as VMs.">Containers são mais pesados que as VMs</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Containers compartilham o Kernel do Host e são muito mais leves, enquanto VMs rodam um SO completo.">Containers compartilham o Kernel do sistema operacional hospedeiro, enquanto as VMs rodam um sistema operacional completo</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Containers compartilham o Kernel do sistema operacional, o que os torna muito mais leves e rápidos que as VMs.">VMs não precisam de hardware para rodar</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Containers compartilham o Kernel do sistema operacional, o que os torna muito mais leves e rápidos que as VMs.">Não há diferença técnica entre eles</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. O que significa dizer que um container é "Isolado"?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O isolamento garante que o que acontece em um container não afeta outro, nem o sistema hospedeiro.">Significa que ele roda em um ambiente separado, sem interferir em outros containers ou no sistema operacional hospedeiro</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O isolamento garante que o que acontece em um container não afeta outro, nem o sistema hospedeiro.">Significa que ele não pode se conectar à internet</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O isolamento garante que o que acontece em um container não afeta outro, nem o sistema hospedeiro.">Significa que ele só pode ser acessado por uma pessoa por vez</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O isolamento garante que o que acontece em um container não afeta outro, nem o sistema hospedeiro.">Significa que ele apaga todos os arquivos após ser desligado</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. Qual o problema que os containers resolvem de forma mais eficaz?</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. A padronização do ambiente garante que "se funciona na minha máquina, funciona em qualquer lugar".">O preço alto dos computadores</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! A padronização do ambiente resolve o problema de incompatibilidade entre diferentes máquinas.">O problema de o software funcionar na máquina do desenvolvedor, mas não no servidor ("Na minha máquina funciona")</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. A padronização do ambiente garante que "se funciona na minha máquina, funciona em qualquer lugar".">A velocidade da digitação dos programadores</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. A padronização do ambiente garante que "se funciona na minha máquina, funciona em qualquer lugar".">A falta de criatividade no design de sites</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. O que é uma "Imagem" no contexto de containers?</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. A imagem é o "projeto" estático, o container é esse projeto em execução.">Uma foto da tela do computador</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! A imagem é um pacote imutável que contém tudo o que é necessário para rodar a aplicação.">Um arquivo estático (template) que contém o código, bibliotecas e dependências da aplicação</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. A imagem é o "projeto" estático, o container é esse projeto em execução.">O logotipo que aparece no ícone do container</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. A imagem é o "projeto" estático, o container é esse projeto em execução.">O manual de instruções impresso do software</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. Qual a vantagem de usar containers em arquiteturas de Microserviços?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Containers permitem escalar e atualizar cada microserviço de forma independente e rápida.">Permite escalar e atualizar partes específicas da aplicação de forma independente e rápida</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Containers permitem escalar e atualizar cada microserviço de forma independente e rápida.">Faz com que todos os microserviços falem a mesma língua obrigatoriamente</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Containers permitem escalar e atualizar cada microserviço de forma independente e rápida.">Impede que o sistema tenha mais de 10 funções</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Containers permitem escalar e atualizar cada microserviço de forma independente e rápida.">Diminui a segurança do sistema para facilitar o acesso do desenvolvedor</div>
  <div class="quiz-feedback"></div>
</div>

