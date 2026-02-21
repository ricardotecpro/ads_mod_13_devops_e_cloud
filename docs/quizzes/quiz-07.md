# Quiz 07 - Introdução

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. Qual a função do PostgreSQL em uma arquitetura backend?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Criar a interface visual</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Armazenar dados de forma persistente e relacional">Armazenar dados de forma persistente e relacional</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Enviar e-mails automaticamente</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Compilar o código Javascript
    *Explicação: O PostgreSQL é um Sistema de Gerenciamento de Banco de Dados (SGBD) que garante que os dados não se percam.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. O que significa a sigla CRUD?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Create, Remove, Update, Delete</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Create, Read, Update, Delete">Create, Read, Update, Delete</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Clear, Read, Unit, Deploy</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Code, Run, Update, Debug
    *Explicação: CRUD representa as quatro operações básicas de manipulação de dados em qualquer sistema.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. Qual o comando SQL usado para buscar dados em uma tabela?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">INSERT</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">UPDATE</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! SELECT">SELECT</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">DELETE
    *Explicação: O SELECT é o comando fundamental para realizar consultas no banco de dados.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. Para que serve o padrão Repository?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para salvar arquivos PDF no servidor</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Para isolar a lógica de acesso ao banco da lógica de negócio">Para isolar a lógica de acesso ao banco da lógica de negócio</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para criar rotas no Express</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para acelerar o download do app
    *Explicação: O Repository centraliza as chamadas ao banco, facilitando a troca de tecnologia sem afetar o resto do sistema.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. O que é uma Primary Key (Chave Primária)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">A senha master do servidor</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Um identificador único para cada registro (linha) em uma tabela">Um identificador único para cada registro (linha) em uma tabela</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O nome da tabela principal</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O primeiro campo de um formulário HTML
    *Explicação: A PK garante que não existam dois registros idênticos e facilita a busca rápida.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">6. Quando usamos uma Foreign Key (Chave Estrangeira)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para traduzir o banco de dados</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Para criar um link (relacionamento) entre duas tabelas diferentes">Para criar um link (relacionamento) entre duas tabelas diferentes</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para encriptar os dados</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para mudar o nome das colunas
    *Explicação: A FK é o que permite conectar, por exemplo, um Pedido ao Usuário que o realizou.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">7. O que acontece se rodarmos um `DELETE FROM usuarios` sem a cláusula `WHERE`?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O banco pede confirmação</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Todos os registros da tabela "usuarios" serão apagados!">Todos os registros da tabela "usuarios" serão apagados!</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Apenas o primeiro registro é apagado</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O comando dá erro de sintaxe
    *Explicação: Sem o WHERE, o comando afeta todas as linhas da tabela. Muito cuidado!*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">8. O que são "Migrations"?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Pessoas que mudam de país</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Arquivos que versionam a estrutura do banco de dados (schema)">Arquivos que versionam a estrutura do banco de dados (schema)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">A troca de servidor de hospedagem</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Um tipo de loop em Javascript
    *Explicação: Migrations garantem que todos os desenvolvedores tenham a mesma versão da estrutura do banco.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">9. Qual o tipo de relacionamento quando um Autor pode escrever vários livros?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">1:1 (Um para um)</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! 1:N (Um para muitos)">1:N (Um para muitos)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">N:N (Muitos para muitos)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">N:1 (Muitos para um)
    *Explicação: Um único recurso pai (Autor) está ligado a múltiplos recursos filhos (Livros).*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">10. Por que o Service deve chamar o Repository em vez de rodar SQL direto?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para o código ficar mais longo</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Para seguir o princípio de responsabilidade única e facilitar testes">Para seguir o princípio de responsabilidade única e facilitar testes</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque SQL é uma linguagem antiga</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque o computador processa Services mais rápido
    *Explicação: Separar as camadas torna o sistema modular: o Service dita O QUE fazer, o Repository sabe COMO buscar.*</div>
  <div class="quiz-feedback"></div>
</div>

