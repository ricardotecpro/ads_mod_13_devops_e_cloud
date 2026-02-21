# Quiz 03 - Introdução

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. O que significa o termo "Stateless" no REST?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O servidor armazena o estado do cliente em variáveis globais</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O servidor não guarda informações sobre sessões anteriores; cada requisição é independente">O servidor não guarda informações sobre sessões anteriores; cada requisição é independente</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O app não precisa de internet para funcionar</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O banco de dados nunca muda
    *Explicação: Stateless garante que o servidor possa escalar horizontalmente sem se preocupar em sincronizar sessões de usuários entre máquinas.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. Qual a regra de ouro para nomear URIs no REST?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Usar verbos de ação (ex: /getUsers)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Usar letras maiúsculas para destacar</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Usar substantivos no plural (ex: /usuarios)">Usar substantivos no plural (ex: /usuarios)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Colocar a senha do usuário na URL
    *Explicação: URIs devem representar recursos (coisas), e não ações. A ação é definida pelo Verbo HTTP.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. Qual verbo HTTP deve ser usado para criar um novo recurso?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">GET</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! POST">POST</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">PUT</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">DELETE
    *Explicação: O POST é o método padrão para submeter dados para a criação de novos recursos no servidor.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. Qual a diferença fundamental entre PUT e PATCH?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">PUT é mais rápido que PATCH</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">PATCH remove o recurso e PUT cria um novo</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! PUT substitui o recurso inteiro, enquanto PATCH faz atualizações parciais">PUT substitui o recurso inteiro, enquanto PATCH faz atualizações parciais</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Não há diferença, ambos fazem a mesma coisa
    *Explicação: Use PUT para "trocar" o objeto todo e PATCH para mudar apenas um campo (ex: mudar apenas o preço de um produto).*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. Qual código de status indica que um recurso foi criado com sucesso?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">200 OK</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! 201 Created">201 Created</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">204 No Content</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">404 Not Found
    *Explicação: O 201 é específico para sinalizar que o POST resultou na criação física de um novo elemento.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">6. O que significa ser um método "Idempotente"?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Que ele gasta muita energia</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Que múltiplas requisições idênticas têm o mesmo efeito que uma só">Que múltiplas requisições idênticas têm o mesmo efeito que uma só</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Que ele só funciona com números inteiros</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Que ele apaga o banco de dados
    *Explicação: GET, PUT e DELETE são idempotentes. Se você deletar o mesmo ID 10 vezes, o resultado final (o recurso não existir) é o mesmo.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">7. Por que o JSON é preferido em relação ao XML em APIs modernas?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque ele é colorido</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Porque é mais leve, menos verboso e mais fácil de ler/processar em JS">Porque é mais leve, menos verboso e mais fácil de ler/processar em JS</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque o XML foi proibido pelo Google</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque JSON aceita emojis e XML não
    *Explicação: O JSON tem uma sintaxe muito mais limpa e mapeia quase diretamente para objetos em linguagens modernas.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">8. O que o status code 403 Forbidden indica?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Que a página não existe</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Que o usuário não está logado</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Que o usuário está logado, mas não tem permissão para aquele recurso">Que o usuário está logado, mas não tem permissão para aquele recurso</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Que o servidor explodiu
    *Explicação: Diferente do 401 (sem login), o 403 diz que você é conhecido, mas "não tem entrada permitida aqui".*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">9. Em REST, o que compõe uma Interface Uniforme?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Usar a mesma cor em todos os botões</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Uso de URIs para recursos, métodos HTTP padrão e representações de dados (JSON/XML)">Uso de URIs para recursos, métodos HTTP padrão e representações de dados (JSON/XML)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Ter apenas um arquivo de código para tudo</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Usar apenas um tipo de fonte de texto
    *Explicação: É o conjunto de regras que torna a API previsível e fácil de aprender por outros desenvolvedores.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">10. Qual a função do cabeçalho "Content-Type" em uma requisição?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Dizer o nome do autor da API</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Informar ao servidor qual o formato dos dados que estão sendo enviados (ex: application/json)">Informar ao servidor qual o formato dos dados que estão sendo enviados (ex: application/json)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Aumentar a segurança da senha</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Definir a cor de fundo do site
    *Explicação: Sem o Content-Type, o servidor pode não saber como interpretar o corpo (body) da mensagem recebida.*</div>
  <div class="quiz-feedback"></div>
</div>

