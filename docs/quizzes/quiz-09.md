# Quiz 09 - Introdução

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. Qual a diferença entre Autenticação e Autorização?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Autenticação é sobre permissões, Autorização é sobre identidade</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Autenticação checa quem você é, Autorização checa o que você pode fazer">Autenticação checa quem você é, Autorização checa o que você pode fazer</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Autenticação é para o backend, Autorização é para o frontend</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">É a mesma coisa, apenas nomes diferentes
    *Explicação: Primeiro você prova quem é (Login), depois o sistema checa se você tem acesso (Roles).*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. O que significa a sigla JWT?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Java Web Tool</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! JSON Web Token">JSON Web Token</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Javascript Web Transfer</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Just Web Ticket
    *Explicação: É um padrão de mercado para transmissão segura de informações como objetos JSON.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. Quantas partes compõem um token JWT?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Uma parte única</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Duas partes (Dados e Assinatura)</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Três partes (Header, Payload e Signature)">Três partes (Header, Payload e Signature)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Quatro partes (Header, Payload, Signature e Expire)
    *Explicação: As três partes são unidas por pontos para formar o token completo.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. O que é o "Payload" do JWT?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O algoritmo de criptografia</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">A senha do banco de dados</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O corpo do token, onde ficam os dados do usuário (ex: id, nome)">O corpo do token, onde ficam os dados do usuário (ex: id, nome)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">A chave secreta do servidor
    *Explicação: É aqui que guardamos as "alegações" (claims) sobre o usuário logado.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. Por que a "Assinatura" (Signature) é a parte mais importante para a segurança?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque ela deixa o token colorido</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Porque ela garante que o Payload não foi alterado por terceiros">Porque ela garante que o Payload não foi alterado por terceiros</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque ela esconde o nome do usuário</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque ela faz o token expirar mais rápido
    *Explicação: Se alguém mudar um único caractere no Payload, a assinatura deixará de ser válida.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">6. O que significa dizer que o JWT é "Stateless" (Sem Estado)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Que o servidor não tem banco de dados</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Que o servidor não precisa guardar informações da sessão do usuário na memória">Que o servidor não precisa guardar informações da sessão do usuário na memória</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Que o token nunca expira</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Que o usuário não precisa de internet
    *Explicação: Toda a informação necessária para validar o usuário está dentro do próprio token.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">7. Onde o Payload do JWT pode ser lido?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Apenas pelo servidor que tem a chave secreta</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Por qualquer pessoa, pois ele é apenas codificado (Base64), não encriptado">Por qualquer pessoa, pois ele é apenas codificado (Base64), não encriptado</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Apenas por usuários com permissão de Admin</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Em lugar nenhum, ele é invisível
    *Explicação: CUIDADO! Nunca guarde senhas ou dados sensíveis no Payload, pois qualquer um pode ler.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">8. Qual o objetivo do campo "expiresIn" (ou 'exp')?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Mudar o nome do usuário</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Definir um tempo de validade para o token, após o qual ele será rejeitado">Definir um tempo de validade para o token, após o qual ele será rejeitado</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Apagar o banco de dados</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Aumentar a velocidade da API
    *Explicação: Tokens não devem ser eternos; limitando a duração, reduzimos riscos de roubo de sessão.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">9. Onde o frontend geralmente envia o JWT para o servidor?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">No corpo da mensagem (Body)</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! No cabeçalho (Header) de autorização: `Authorization: Bearer <token>`">No cabeçalho (Header) de autorização: `Authorization: Bearer <token>`</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">No nome do arquivo</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Por e-mail
    *Explicação: O padrão Bearer Token nos headers HTTP é a forma mais comum de enviar o JWT.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">10. O que acontece se o servidor perder a "Chave Secreta"?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Os usuários ganham acesso livre</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Todos os tokens emitidos anteriormente se tornam inválidos instantaneamente">Todos os tokens emitidos anteriormente se tornam inválidos instantaneamente</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O banco de dados é deletado</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Nada, a chave secreta não é importante
    *Explicação: Sem a chave, o servidor não consegue mais verificar se as assinaturas dos tokens são legítimas.*</div>
  <div class="quiz-feedback"></div>
</div>

