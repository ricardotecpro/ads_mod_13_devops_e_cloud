# Quiz 04 - Introdução

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. O que é o OpenAPI (OAS)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Uma linguagem de programação para backend</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Uma especificação padrão para descrever e documentar APIs RESTful">Uma especificação padrão para descrever e documentar APIs RESTful</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Um navegador web para desenvolvedores</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Um banco de dados em nuvem
    *Explicação: O OpenAPI define um formato padrão para descrever recursos, rotas e respostas de uma API.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. Qual a principal diferença entre OpenAPI e Swagger?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Swagger é pago e OpenAPI é gratuito</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! OpenAPI é a especificação e Swagger é o conjunto de ferramentas (UI, Editor, etc)">OpenAPI é a especificação e Swagger é o conjunto de ferramentas (UI, Editor, etc)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">OpenAPI foi substituída pelo Swagger em 2021</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Não há diferença, são nomes para a mesma cor
    *Explicação: Pense no OpenAPI como as "regras" e no Swagger como as "ferramentas" que usam essas regras.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. Para que serve o Swagger UI?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para editar o banco de dados diretamente</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Para gerar uma página visual e interativa onde se pode testar os endpoints documentados">Para gerar uma página visual e interativa onde se pode testar os endpoints documentados</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para compilar o código Java para o servidor</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para baixar músicas gratuitas
    *Explicação: O Swagger UI lê o arquivo YAML/JSON e cria uma interface amigável para humanos.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. Qual o objetivo principal de um "Mock de API"?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Substituir o backup do sistema</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Simular o comportamento de uma API real para permitir o desenvolvimento paralelo">Simular o comportamento de uma API real para permitir o desenvolvimento paralelo</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Aumentar a segurança contra vírus</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Esconder o endereço IP do servidor
    *Explicação: Mocks permitem que o Frontend programe contra um servidor "de mentira" enquanto o real não está pronto.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. O que significa "Developer Experience" (DX)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O tempo que o desenvolvedor gasta jogando videogame</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! A facilidade e satisfação de um desenvolvedor ao usar sua ferramenta ou API">A facilidade e satisfação de um desenvolvedor ao usar sua ferramenta ou API</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">A quantidade de memória RAM do monitor</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O nome do sistema operacional dos servidores
    *Explicação: Uma boa DX significa documentação clara, erros úteis e facilidade de integração.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">6. Qual formato de arquivo é mais utilizado para escrever especificações OpenAPI?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">.html</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! .yaml ou .json">.yaml ou .json</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">.docx</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">.pdf
    *Explicação: YAML é preferido por ser mais legível por humanos e suportar identação clara.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">7. Por que retornar mensagens de erro explicativas no corpo da resposta (Body) é uma boa prática?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para o log ficar mais colorido</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Para ajudar o consumidor da API a entender exatamente o que errou sem precisar perguntar ao autor">Para ajudar o consumidor da API a entender exatamente o que errou sem precisar perguntar ao autor</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque o HTTP obriga a escrever textos longos</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para ocupar mais espaço no servidor
    *Explicação: Um erro `400` com a mensagem `"Data de nascimento é obrigatória"` economiza horas de suporte.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">8. Qual componente do Swagger permite digitar e validar a especificação da API em tempo real?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Swagger Hub</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Swagger Editor">Swagger Editor</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Swagger Inspector</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Swagger Play
    *Explicação: O Editor valida a sintaxe YAML e mostra o preview da documentação instantaneamente.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">9. Em qual fase do projeto o "Design de Contrato" deve ocorrer?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Somente no fim do projeto para arquivar</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! No início, antes mesmo de começar a codificar as rotas (API First)">No início, antes mesmo de começar a codificar as rotas (API First)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Apenas se o cliente pedir</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Nunca, é perda de tempo
    *Explicação: No API First, o contrato é acordado primeiro para que as equipes de Front e Back trabalhem em sintaxe.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">10. Qual ferramenta pode ser usada para subir um mock server local a partir de uma collection?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Microsoft Excel</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Postman / Mockoon">Postman / Mockoon</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Notepad++</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Windows Paint
    *Explicação: Postman e Mockoon facilitam a criação de respostas estáticas baseadas em rotas.*</div>
  <div class="quiz-feedback"></div>
</div>

