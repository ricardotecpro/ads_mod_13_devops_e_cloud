# Quiz 10 - Introdução

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. O que significa a sigla RBAC?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Real-Binary-Authentication-Code</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Role-Based Access Control">Role-Based Access Control</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Route-Based Authorization Check</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Restricted-Backend-Access-Control
    *Explicação: É o padrão de mercado para gerenciar permissões baseadas em "perfis" ou "papéis" do usuário.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. No RBAC, a quem atribuímos as permissões de acesso?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">A cada usuário individualmente por seu CPF</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! A um perfil (Role) que pode ser compartilhado por vários usuários">A um perfil (Role) que pode ser compartilhado por vários usuários</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Apenas ao dono da empresa</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Ao endereço IP do computador
    *Explicação: Atribuir a perfis facilita a manutenção, especialmente em sistemas com muitos usuários.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. Qual o código HTTP para "Acesso Negado" (Usuário identificado, mas sem permissão)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">401 Unauthorized</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">404 Not Found</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! 403 Forbidden">403 Forbidden</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">500 Internal Error
    *Explicação: O 403 indica que o servidor entendeu quem é você, mas proibiu a ação.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. Qual a ordem correta dos middlewares em uma rota protegida?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Primeiro Autorização, depois Autenticação</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Primeiro Autenticação, depois Autorização">Primeiro Autenticação, depois Autorização</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Ambos devem rodar ao mesmo tempo</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Apenas um é necessário
    *Explicação: Primeiro desvendamos QUEM é o usuário (Token), para depois checar O QUE ele pode fazer.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. O que um Middleware de Autorização faz se o usuário não tem o nível necessário?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Reinicia o servidor</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Interrompe a requisição e retorna um erro 403 ao cliente">Interrompe a requisição e retorna um erro 403 ao cliente</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Envia a requisição para outra rota aleatória</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Formata o banco de dados
    *Explicação: O middleware age como uma trava que impede a execução do código do Controller.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">6. Por que o Erro 401 (Unauthorized) é retornado quando o token JWT é inválido?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque o usuário é feio</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Porque a identidade do usuário não pôde ser confirmada">Porque a identidade do usuário não pôde ser confirmada</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque o servidor está desligado</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque o sistema está em manutenção
    *Explicação: 401 significa "Quem é você? Não te conheço ou seu crachá é falso".*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">7. Em um sistema de E-commerce, quem deve ter permissão para a rota `DELETE /produtos/:id`?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Todos os clientes</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Apenas usuários com a Role 'ADMIN' ou 'GERENTE'">Apenas usuários com a Role 'ADMIN' ou 'GERENTE'</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Qualquer pessoa sem login</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Apenas o programador que criou o site
    *Explicação: Ações destrutivas devem ser restritas a perfis de alta confiança.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">8. O que é "Hierarquia de Roles"?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Uma lista de nomes em ordem alfabética</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Quando perfis superiores (ex: Admin) herdam automaticamente as permissões de perfis inferiores">Quando perfis superiores (ex: Admin) herdam automaticamente as permissões de perfis inferiores</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O tamanho da letra no banco de dados</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">A ordem de criação dos usuários
    *Explicação: Facilita o código, evitando ter que listar 'ADMIN' em todas as rotas simples.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">9. O que acontece se chamarmos a função `next()` dentro de um middleware?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O servidor para</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O processamento passa para o próximo middleware ou para o Controller">O processamento passa para o próximo middleware ou para o Controller</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O usuário é deslogado</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Uma nova aba abre no navegador
    *Explicação: O `next()` é o sinal verde para a requisição seguir seu fluxo.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">10. Qual a principal vantagem de centralizar a autorização em middlewares?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O app fica mais bonito</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Segurança e Reuso: você protege rotas inteiras com uma única linha de código">Segurança e Reuso: você protege rotas inteiras com uma única linha de código</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O banco de dados fica mais rápido</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Os usuários ganham descontos
    *Explicação: Centralizar evita que você esqueça de colocar "if" em algum Controller, deixando brechas de segurança.*</div>
  <div class="quiz-feedback"></div>
</div>

