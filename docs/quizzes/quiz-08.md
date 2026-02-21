# Quiz 08 - Introdução

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. Por que o backend nunca deve confiar nos dados vindos do frontend?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para economizar bateria do servidor</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Porque a requisição pode ter sido interceptada, alterada ou burlada">Porque a requisição pode ter sido interceptada, alterada ou burlada</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque o frontend é sempre feito por iniciantes</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque os navegadores são lentos
    *Explicação: Segurança baseada em "confiança" no cliente é uma vulnerabilidade grave.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. Qual a diferença entre Validar e Sanitizar?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Validar limpa o dado, Sanitizar checa a regra</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Validar checa se o dado está correto, Sanitizar "limpa" o dado de impurezas (espaços, tags HTML)">Validar checa se o dado está correto, Sanitizar "limpa" o dado de impurezas (espaços, tags HTML)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">São a mesma coisa com nomes diferentes</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Validar é para banco SQL, Sanitizar é para NoSQL
    *Explicação: Validar diz "SIM ou NÃO", Sanitizar diz "AGORA ESTÁ LIMPO".*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. Para que servem bibliotecas como Zod ou Joi?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para acelerar a conexão com o banco</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Para definir e aplicar esquemas de validação de forma declarativa e robusta">Para definir e aplicar esquemas de validação de forma declarativa e robusta</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para desenhar gráficos no painel do administrador</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para comprimir arquivos PDF
    *Explicação: Essas bibliotecas removem o excesso de "if/else" e centralizam as regras de entrada.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. O que é o princípio DRY (Don't Repeat Yourself)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Beber água durante o código</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Evitar a duplicação de lógica, transformando repetir em funções ou serviços únicos">Evitar a duplicação de lógica, transformando repetir em funções ou serviços únicos</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Escrever o código o mais rápido possível</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Não usar a tecla Backspace
    *Explicação: Código repetido é difícil de manter; se a regra muda, você esquece de atualizar em algum lugar.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. O que um Middleware de Erro Global faz?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Impede que o computador trave</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Captura qualquer erro não tratado e envia uma resposta padronizada ao cliente">Captura qualquer erro não tratado e envia uma resposta padronizada ao cliente</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Apaga os logs do servidor</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Avisa o usuário que a internet caiu
    *Explicação: Centralizar o erro evita que o servidor "morra" e permite um tratamento profissional de falhas.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">6. Por que NÃO devemos enviar o Stack Trace (detalhes técnicos do erro) para o usuário final?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque gasta muitos dados de internet</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Por segurança, pois revela detalhes da estrutura do banco e do código (ajuda hackers)">Por segurança, pois revela detalhes da estrutura do banco e do código (ajuda hackers)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque o usuário não entende inglês</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque o Stack Trace é feio
    *Explicação: Informações técnicas sobre o erro devem ser logadas internamente, nunca expostas publicamente.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">7. Qual a vantagem de usar nomes de funções altamente descritivos?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O código fica mais colorido no editor</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Melhora a legibilidade e facilita a manutenção por outros desenvolvedores (ou por você no futuro)">Melhora a legibilidade e facilita a manutenção por outros desenvolvedores (ou por você no futuro)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O compilador processa nomes longos mais rápido</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Ocupa menos espaço no servidor
    *Explicação: Código deve ser lido como um livro; o nome da função deve dizer exatamente O QUE ela faz.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">8. O que caracteriza um Erro 400 (Bad Request)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O servidor parou de funcionar</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O cliente enviou dados inválidos ou incompletos que o sistema não aceita">O cliente enviou dados inválidos ou incompletos que o sistema não aceita</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O usuário não tem permissão para acessar</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">A página não existe
    *Explicação: Erros 400 indicam que a culpa é do "lado de lá" (cliente/requisição).*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">9. O que caracteriza um Erro 500 (Internal Server Error)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O usuário digitou a senha errada</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Ocorreu uma falha inesperada na lógica ou infraestrutura do servidor">Ocorreu uma falha inesperada na lógica ou infraestrutura do servidor</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O link está quebrado</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">A conta do usuário foi deletada
    *Explicação: Erros 500 indicam que algo "quebrou" no backend e precisa de reparo.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">10. Como o Clean Code ajuda na escalabilidade de um projeto?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Comprimindo o banco de dados</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Mantendo o código organizado e modular, facilitando a adição de novas funcionalidades">Mantendo o código organizado e modular, facilitando a adição de novas funcionalidades</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Diminuindo o preço da hospedagem</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Aumentando o número de acessos simultâneos
    *Explicação: Um código limpo é como um quebra-cabeça bem encaixado; é fácil adicionar peças novas.*</div>
  <div class="quiz-feedback"></div>
</div>

