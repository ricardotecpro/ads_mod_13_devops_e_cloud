# Quiz 02 - Introdução

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. O que acontece na comunicação síncrona (Sync)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O serviço envia a mensagem e esquece</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O serviço envia a requisição e aguarda a resposta para continuar">O serviço envia a requisição e aguarda a resposta para continuar</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">A comunicação só ocorre via rádio</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O banco de dados é desligado
    *Explicação: No modelo síncrono, a execução fica bloqueada até que o destino retorne o dado.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. Qual o principal perigo da comunicação síncrona em excesso?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O código fica muito curto</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Cascateamento de falhas (um serviço lento trava todos os outros)">Cascateamento de falhas (um serviço lento trava todos os outros)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Economia exagerada de memória</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O sistema fica rápido demais
    *Explicação: Se um serviço na cadeia falhar ou demorar, todos os serviços "acima" dele também sofrerão.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. Qual a função do API Gateway?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Armazenar as senhas dos desenvolvedores</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Atuar como ponto único de entrada para roteamento e segurança">Atuar como ponto único de entrada para roteamento e segurança</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Substituir o roteador Wi-Fi da empresa</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Processar scripts de interface visual
    *Explicação: O Gateway centraliza preocupações transversais como autenticação, log e roteamento.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. O que é "Rate Limiting"?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Aumentar a velocidade da internet</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Limitar a quantidade de requisições que um cliente pode fazer em um tempo">Limitar a quantidade de requisições que um cliente pode fazer em um tempo</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Cobrar por cada clique no botão</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Diminuir a fonte do texto
    *Explicação: Rate limiting protege o sistema contra abusos ou ataques de negação de serviço (DoS).*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. No Service Discovery, como os serviços são localizados?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Por endereços IP fixos escritos no código</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Via um registro dinâmico que mantém os endereços atualizados">Via um registro dinâmico que mantém os endereços atualizados</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Através de busca no Google</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Usando GPS
    *Explicação: Em ambientes elásticos (Docker/K8s), os IPs mudam sempre, exigindo um "Discovery" dinâmico.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">6. Qual o papel do "Load Balancer"?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Medir o peso dos servidores físicos</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Distribuir a carga de trabalho entre várias instâncias do mesmo serviço">Distribuir a carga de trabalho entre várias instâncias do mesmo serviço</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Equilibrar o gasto de energia</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Organizar as pastas do projeto
    *Explicação: Ele garante que nenhuma instância fique sobrecarregada enquanto outras estão ociosas.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">7. O que caracteriza a comunicação Assíncrona (Async)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Uso obrigatório de cabos de fibra ótica</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O uso de mensageria (filas) onde o chamador não espera a resposta imediata">O uso de mensageria (filas) onde o chamador não espera a resposta imediata</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Comunicação em tempo real por vídeo</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Bloqueio total do banco de dados
    *Explicação: É ideal para processos longos ou para aumentar a resiliência do sistema.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">8. O que é um "Circuit Breaker" (Disjuntor)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Um fusível físico no servidor</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Um padrão que interrompe chamadas para um serviço falho para evitar sobrecarga">Um padrão que interrompe chamadas para um serviço falho para evitar sobrecarga</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Um hacker que invade sistemas</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O botão de desligar do computador
    *Explicação: Ele protege o sistema impedindo que requisições inúteis sejam feitas a um serviço que já se sabe estar fora do ar.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">9. Qual destas é uma responsabilidade típica de um Gateway?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Desenhar o logo da empresa</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Compilar código C++</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Agregação de respostas e Autenticação">Agregação de respostas e Autenticação</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Formatar o HD do servidor
    *Explicação: O Gateway pode unir dados de 3 serviços diferentes e entregar um único JSON ao frontend.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">10. Qual ferramenta é comumente usada para implementar Service Discovery?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Microsoft Word</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Netflix Eureka / Consul">Netflix Eureka / Consul</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Adobe Photoshop</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">WhatsApp
    *Explicação: Eureka e Consul são soluções populares para gerenciar a agenda de serviços em microsserviços.*</div>
  <div class="quiz-feedback"></div>
</div>

