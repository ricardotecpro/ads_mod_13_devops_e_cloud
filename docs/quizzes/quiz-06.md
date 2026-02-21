# Quiz 06 - Introdução

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. O que acontece se colocarmos toda a lógica de negócio dentro do Controller?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O app fica mais rápido</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O código fica difícil de testar, manter e reutilizar (o famoso "Controller Gordo")">O código fica difícil de testar, manter e reutilizar (o famoso "Controller Gordo")</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O banco de dados se apaga sozinho</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O roteamento para de funcionar
    *Explicação: Acoplar lógica de negócio ao transporte HTTP cria dívida técnica e dificulta a evolução do sistema.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. Qual a principal responsabilidade do Service?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Definir as rotas do app</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Executar as regras de negócio, validações e cálculos">Executar as regras de negócio, validações e cálculos</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Gerar as respostas JSON para o cliente</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Configurar a porta do servidor
    *Explicação: O Service é onde o conhecimento do domínio da aplicação (as regras do "negócio") reside.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. Como um Service deve notificar o Controller sobre uma falha de validação?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Retornando um número 400</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Lançando uma exceção ou erro (throw Error)">Lançando uma exceção ou erro (throw Error)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Enviando um e-mail para o administrador</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Mudando a cor do console
    *Explicação: O lançamento de erros permite que o Controller capture o fluxo e decida qual resposta HTTP enviar.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. Por que o Service não deve acessar os objetos `req` ou `res`?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque eles são secretos</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Para manter o Service independente do protocolo de transporte (podendo ser usado em gRPC, CLI, etc)">Para manter o Service independente do protocolo de transporte (podendo ser usado em gRPC, CLI, etc)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque isso gasta muita internet</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para economizar linhas de código
    *Explicação: A camada de serviço deve ser "cega" para o transporte, focando apenas nos dados e regras.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. O que define uma "Regra de Negócio"?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O nome das variáveis do sistema</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! As diretrizes que ditam como o serviço deve operar (ex: "só maiores de 18 podem comprar")">As diretrizes que ditam como o serviço deve operar (ex: "só maiores de 18 podem comprar")</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O tipo de servidor onde o app está rodando</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">A cor do logotipo da empresa
    *Explicação: Regras de negócio são as "leis" do funcionamento daquela aplicação específica.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">6. Qual a vantagem de reutilizar um Service em diferentes Controllers?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Nenhuma, é melhor copiar o código</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Consistência: a regra é aplicada da mesma forma em todo o sistema">Consistência: a regra é aplicada da mesma forma em todo o sistema</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Economiza espaço de memória no disco</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Deixa o site mais colorido
    *Explicação: Centralizar a regra no Service garante que, se a lei mudar, você só precisa alterar em um lugar.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">7. O que é um DTO (Data Transfer Object)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Um tipo de cabo para conectar servidores</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Um objeto simples usado para transportar dados entre camadas sem expor a lógica interna">Um objeto simples usado para transportar dados entre camadas sem expor a lógica interna</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O nome do motor de busca do Google</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Um comando do terminal Linux
    *Explicação: DTOs ajudam a filtrar campos sensíveis (como senhas) antes de enviá-los ao mundo externo.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">8. O que significa "Separation of Concerns" (Separação de Preocupações)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Cada desenvolvedor deve trabalhar sozinho</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Cada camada do sistema deve ter uma responsabilidade única e bem definida">Cada camada do sistema deve ter uma responsabilidade única e bem definida</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O banco de dados deve ficar em outro país</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O site deve ter várias cores diferentes
    *Explicação: Dividir o sistema em Controller, Service e Repository é aplicar esse princípio fundamental.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">9. Qual o momento ideal para chamar o Service dentro de uma rota?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Antes de receber a requisição</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Após o Controller validar os parâmetros básicos de entrada">Após o Controller validar os parâmetros básicos de entrada</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Depois que a resposta já foi enviada ao cliente</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Nunca, o Controller deve fazer tudo
    *Explicação: O Controller "limpa" a entrada e passa os dados "puros" para o Service processar.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">10. Como o Controller deve tratar o retorno de um Service?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Ignorando o resultado</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Capturando o dado retornado e devolvendo em um JSON com Status 200/201">Capturando o dado retornado e devolvendo em um JSON com Status 200/201</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Pedindo para o usuário reiniciar o computador</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Exibindo o código fonte na tela
    *Explicação: O Controller é o tradutor final que comunica o sucesso ou erro do Service para o cliente HTTP.*</div>
  <div class="quiz-feedback"></div>
</div>

