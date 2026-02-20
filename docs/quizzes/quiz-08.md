# Quiz 08 - Docker na Prática 🚀

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. O que o comando `docker run` faz?</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O `run` é o comando mais completo, pois prepara e coloca o processo no ar.">Apenas baixa uma imagem do servidor</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O `docker run` cria um novo container a partir de uma imagem e o inicia imediatamente.">Cria um novo container a partir de uma imagem e o inicia</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O `run` é o comando mais completo, pois prepara e coloca o processo no ar.">Apaga todos os containers parados</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O `run` é o comando mais completo, pois prepara e coloca o processo no ar.">Renomeia o computador do usuário</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. Para que serve o arquivo `Dockerfile`?</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O Dockerfile é a 'receita' que descreve cada camada do ambiente que queremos construir.">Para guardar as senhas do sistema</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! É um roteiro de instruções usado para construir uma imagem personalizada de container.">É um arquivo de texto com instruções para construir uma imagem Docker automaticamente</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O Dockerfile é a 'receita' que descreve cada camada do ambiente que queremos construir.">Para listar os contatos da equipe de DevOps</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O Dockerfile é a 'receita' que descreve cada camada do ambiente que queremos construir.">Para configurar o brilho da tela do terminal</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. O que faz o parâmetro `-p 8080:80` no comando `docker run`?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O mapeamento de portas permite que o tráfego externo chegue até o processo isolado do container.">Mapeia a porta 8080 do computador hospedeiro para a porta 80 interna do container</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O mapeamento de portas permite que o tráfego externo chegue até o processo isolado do container.">Aumenta a velocidade do processador em 80%</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O mapeamento de portas permite que o tráfego externo chegue até o processo isolado do container.">Define o número máximo de usuários que podem acessar o site</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O mapeamento de portas permite que o tráfego externo chegue até o processo isolado do container.">Diz para o Docker baixar 80 novas imagens</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. Qual o benefício de usar 'Volumes' no Docker?</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Volumes conectam o storage do container ao host, protegendo os dados importantes de deleções acidentais.">Deixa o container mais bonito no terminal</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Permite que os dados persistam (não sejam perdidos) mesmo que o container seja deletado.">Permitir a persistência de dados fora do ciclo de vida do container</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Volumes conectam o storage do container ao host, protegendo os dados importantes de deleções acidentais.">Aumentar o volume do som das notificações do sistema</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Volumes conectam o storage do container ao host, protegendo os dados importantes de deleções acidentais.">Compactar arquivos para economizar espaço em disco</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. O que o comando `docker ps` mostra?</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O `ps` lista os processos (containers) vivos, mostrando IDs, imagens e status.">O preço de todas as nuvens de cloud</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Lista todos os containers que estão em execução no momento.">Lista os containers que estão rodando no momento</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O `ps` lista os processos (containers) vivos, mostrando IDs, imagens e status.">Mostra o histórico de todas as versões do Docker já instaladas</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O `ps` lista os processos (containers) vivos, mostrando IDs, imagens e status.">Cria uma nova conta no Docker Hub</div>
  <div class="quiz-feedback"></div>
</div>
