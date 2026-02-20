# Quiz 15 - Projeto Prático Integrador 🏗️

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. Qual a principal vantagem de usar uma "Esteira de CI/CD" no projeto prático?</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. CI/CD elimina o erro humano em tarefas repetitivas e garante que o código no ar seja o mesmo que foi testado.">Deixar o projeto mais lento para ter mais tempo de café</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! CI/CD automatiza o processo de build, teste e deploy, garantindo entregas mais rápidas e seguras.">Automatizar o processo desde o código até o deploy, reduzindo erros manuais</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. CI/CD elimina o erro humano em tarefas repetitivas e garante que o código no ar seja o mesmo que foi testado.">Economizar espaço no disco rígido do desenvolvedor</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. CI/CD elimina o erro humano em tarefas repetitivas e garante que o código no ar seja o mesmo que foi testado.">A esteira serve apenas para exercício escolar</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. Por que devemos usar Terraform para criar a infraestrutura do projeto em vez de criar manualmente no portal da Cloud?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Com IaC (Terraform), sua infraestrutura é documentada, versionada e pode ser replicada em segundos sem erro humano.">Porque permite que a infraestrutura seja versionada (Git) e recriada rapidamente de forma idêntica</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Com IaC (Terraform), sua infraestrutura é documentada, versionada e pode ser replicada em segundos sem erro humano.">Porque o portal da Cloud é proibido para profissionais</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Com IaC (Terraform), sua infraestrutura é documentada, versionada e pode ser replicada em segundos sem erro humano.">Porque o Terraform é gratuito e a Cloud não</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Com IaC (Terraform), sua infraestrutura é documentada, versionada e pode ser replicada em segundos sem erro humano.">Não há diferença entre criar manual ou via código</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. Onde você deve guardar as senhas do banco de dados para que o GitHub Actions possa usá-las?</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Nunca coloque senhas no código. Use o cofre de segredos do GitHub (Secrets).">Dentro do arquivo README.md</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O GitHub Secrets criptografa esses dados e os injeta de forma segura apenas durante a execução da automação.">No GitHub Secrets (Configurações do Repositório)</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Nunca coloque senhas no código. Use o cofre de segredos do GitHub (Secrets).">Comentadas no código fonte da aplicação</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Nunca coloque senhas no código. Use o cofre de segredos do GitHub (Secrets).">Em um arquivo chamado `senhas.txt` na raiz do projeto</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. O que significa "Dockerizar" sua aplicação no contexto do projeto integrador?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O Docker garante que a aplicação rode igual no seu PC, no CI e na Cloud.">Empacotar a aplicação e suas dependências em um container para que rode em qualquer lugar</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O Docker garante que a aplicação rode igual no seu PC, no CI e na Cloud.">Colocar o logo de uma baleia no site</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O Docker garante que a aplicação rode igual no seu PC, no CI e na Cloud.">Deletar a aplicação e usar uma pronta do Docker Hub</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O Docker garante que a aplicação rode igual no seu PC, no CI e na Cloud.">Transformar o código em uma imagem JPEG</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. Qual a função do arquivo `Dockerfile` no projeto?</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O Dockerfile é a 'receita de bolo' que o Docker usa para montar o ambiente da sua aplicação.">Guardar a lista de compras do time</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Ele contém todas as instruções passo-a-passo para criar a imagem da aplicação.">Servir como a "receita" com as instruções para montar a imagem do container</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O Dockerfile é a 'receita de bolo' que o Docker usa para montar o ambiente da sua aplicação.">É onde o Terraform lê as configurações de nuvem</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O Dockerfile é a 'receita de bolo' que o Docker usa para montar o ambiente da sua aplicação.">Substituir o arquivo `index.html` do site</div>
  <div class="quiz-feedback"></div>
</div>
