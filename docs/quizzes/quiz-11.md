# Quiz 11 - Introdução

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. Por que não é recomendado que o Access Token dure muitos dias?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque ele ocupa muito espaço no servidor</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Por segurança: se for roubado, o hacker terá acesso por pouco tempo">Por segurança: se for roubado, o hacker terá acesso por pouco tempo</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque o navegador apaga tokens longos automaticamente</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque o Google não permite
    *Explicação: Tokens curtos minimizam o estrago em caso de vazamento de credenciais.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. Para que serve o Refresh Token?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para mudar a senha do usuário</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Para pedir um novo Access Token sem que o usuário tenha que digitar a senha novamente">Para pedir um novo Access Token sem que o usuário tenha que digitar a senha novamente</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para aumentar a velocidade da internet</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para carregar imagens mais rápido
    *Explicação: Ele garante uma boa experiência de uso (UX) sem sacrificar a segurança.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. O que significa a sigla CORS?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Central-Order-Resource-System</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Cross-Origin Resource Sharing">Cross-Origin Resource Sharing</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Code-Origin-Restriction-Safe</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Chrome-Only-Response-System
    *Explicação: É o mecanismo que define quais sites externos podem acessar sua API.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. Quem aplica o bloqueio de CORS?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O Provedor de Internet</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O Microprocessador do celular</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O Navegador (Chrome, Firefox, Safari)">O Navegador (Chrome, Firefox, Safari)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O Teclado do usuário
    *Explicação: O navegador bloqueia a leitura da resposta se o servidor não enviar os headers de permissão corretos.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. Qual a função da biblioteca Helmet?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Proteger o servidor contra quedas físicas</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Configurar automaticamente diversos headers de segurança no HTTP">Configurar automaticamente diversos headers de segurança no HTTP</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Aumentar o brilho da tela</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Traduzir o app para inglês
    *Explicação: O Helmet ajuda a esconder detalhes do servidor e prevenir ataques como XSS.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">6. O que é "Rate Limiting"?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O limite de velocidade do Wi-Fi</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Uma técnica para limitar o número de requisições que um usuário/IP pode fazer em um tempo">Uma técnica para limitar o número de requisições que um usuário/IP pode fazer em um tempo</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Quando o app fica lento de propósito</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O limite de amigos que alguém pode ter
    *Explicação: É essencial para evitar ataques de força bruta (Brute Force) e ataques de negação de serviço (DoS).*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">7. Por que devemos evitar `origin: '*'` no CORS em produção?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque o servidor fica pesado</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Porque qualquer site malicioso do mundo poderia tentar roubar dados da sua API">Porque qualquer site malicioso do mundo poderia tentar roubar dados da sua API</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque o Google penaliza sites assim</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque os usuários não gostam
    *Explicação: O ideal é listar apenas os domínios oficiais que você confia.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">8. O que é o ataque XSS (Cross-Site Scripting)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Quando o banco de dados é deletado</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Quando um invasor consegue injetar scripts maliciosos em páginas vistas por outros usuários">Quando um invasor consegue injetar scripts maliciosos em páginas vistas por outros usuários</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Quando o cabo USB desconecta</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Quando a senha é muito curta
    *Explicação: O invasor pode usar isso para roubar tokens ou cookies de outros usuários.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">9. Qual desses é o lugar mais seguro para guardar o Refresh Token no navegador?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">localStorage</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">sessionStorage</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Cookie com a flag HttpOnly">Cookie com a flag HttpOnly</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">No histórico de navegação
    *Explicação: Cookies HttpOnly não podem ser lidos via Javascript, o que protege contra ataques XSS.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">10. O que acontece em um "Refresh Token Rotation"?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O token muda de cor</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Sempre que um novo Access Token é pedido, o Refresh Token antigo é invalidado e um novo é gerado">Sempre que um novo Access Token é pedido, o Refresh Token antigo é invalidado e um novo é gerado</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O usuário é obrigado a trocar a senha</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O servidor reinicia
    *Explicação: É uma camada extra de segurança para detectar se um Refresh Token foi roubado.*</div>
  <div class="quiz-feedback"></div>
</div>

