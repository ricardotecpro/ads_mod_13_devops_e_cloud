# Quiz 12 - Infraestrutura como Código (IaC) 💻

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. O que é "Infraestrutura como Código" (IaC)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. IaC é sobre automatizar a criação de recursos de TI usando arquivos de configuração.">É um código que conserta o hardware do servidor sozinho</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! IaC permite gerenciar e provisionar infraestrutura através de arquivos de definição legíveis por máquina.">A prática de gerenciar e provisionar infraestrutura através de arquivos de definição, em vez de processos manuais</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. IaC é sobre automatizar a criação de recursos de TI usando arquivos de configuração.">É o manual de instruções impresso do servidor</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. IaC é sobre automatizar a criação de recursos de TI usando arquivos de configuração.">Um programa para digitar textos rápidos</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. Qual a principal vantagem de versionar a infraestrutura no Git?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Ter o histórico de mudanças permite auditoria, rastreabilidade e reversão de erros (rollback).">Saber exatamente quem mudou o quê na infraestrutura e poder voltar versões em caso de erro</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Ter o histórico de mudanças permite auditoria, rastreabilidade e reversão de erros (rollback).">Deixar o Git mais pesado e difícil de usar</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Ter o histórico de mudanças permite auditoria, rastreabilidade e reversão de erros (rollback).">Para que o servidor possa ler as mensagens de commit</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Ter o histórico de mudanças permite auditoria, rastreabilidade e reversão de erros (rollback).">Não há vantagem em colocar infraestrutura no Git</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. O que significa uma ferramenta ser "Declarativa" (como o Terraform)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. No modelo declarativo, você foca no RESULTADO, e a ferramenta cuida do PROCESSO.">Que ela declara guerra a outros provedores de cloud</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! No modelo declarativo, você descreve o 'estado desejado' e a ferramenta se encarrega de alcançá-lo.">Que você descreve o 'estado final' desejado, e a ferramenta descobre como chegar lá</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. No modelo declarativo, você foca no RESULTADO, e a ferramenta cuida do PROCESSO.">Que ela obriga o desenvolvedor a declarar todas as variáveis no topo do arquivo</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. No modelo declarativo, você foca no RESULTADO, e a ferramenta cuida do PROCESSO.">Que ela funciona apenas se você declarar o imposto de renda</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. O que o comando `terraform plan` faz?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O `plan` é uma simulação de segurança antes de aplicar as mudanças reais.">Mostra uma prévia das mudanças que o Terraform fará na infraestrutura real</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O `plan` é uma simulação de segurança antes de aplicar as mudanças reais.">Executa as mudanças imediatamente sem perguntar</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O `plan` é uma simulação de segurança antes de aplicar as mudanças reais.">Deleta todos os servidores para começar do zero</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O `plan` é uma simulação de segurança antes de aplicar as mudanças reais.">Cria um desenho (planta baixa) do datacenter</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. Por que é perigoso deletar o arquivo `terraform.tfstate`?</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Sem esse arquivo, o Terraform 'esquece' o que ele já criou e pode tentar criar tudo de novo, gerando conflitos.">Because ele contém o código fonte da aplicação</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Sem esse arquivo, o Terraform 'esquece' o que ele já criou e pode tentar criar tudo de novo, gerando conflitos.">Porque ele é a 'memória' do Terraform sobre quais recursos já existem na nuvem</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Sem esse arquivo, o Terraform 'esquece' o que ele já criou e pode tentar criar tudo de novo, gerando conflitos.">Porque ele guarda as senhas dos usuários do site</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Sem esse arquivo, o Terraform 'esquece' o que ele já criou e pode tentar criar tudo de novo, gerando conflitos.">Não é perigoso, o Terraform reconstrói esse arquivo sozinho do zero</div>
  <div class="quiz-feedback"></div>
</div>
