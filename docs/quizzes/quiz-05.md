# Quiz 05 - Introdução

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. Qual a principal responsabilidade da camada de Controller?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Salvar dados no banco de dados</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Gerenciar a requisição HTTP e retornar a resposta adequada">Gerenciar a requisição HTTP e retornar a resposta adequada</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Fazer cálculos complexos de impostos</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Criar a interface gráfica do usuário
    *Explicação: O Controller age como um intermediário entre o mundo externo (HTTP) e a lógica interna do sistema.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. O que é um "Handler" em um sistema de rotas?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Um tipo de vírus de computador</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! A função específica que é executada quando uma rota é chamada">A função específica que é executada quando uma rota é chamada</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O nome do servidor de hospedagem</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O arquivo onde guardamos as senhas
    *Explicação: Cada rota (Verbo + Path) é mapeada para um Handler que processa aquela ação específica.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. Qual a melhor forma de capturar o ID de um usuário para uma busca individual (ex: /usuarios/10)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Query Param (?id=10)</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Path Param (/usuarios/:id)">Path Param (/usuarios/:id)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Request Body ({ "id": 10 })</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Através de um cookie
    *Explicação: Path Params são ideais para identificar recursos de forma única e hierárquica na URI.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. Quando devemos usar "Query Params"?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para enviar a senha do usuário</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Para filtros, ordenação e paginação (ex: ?cor=azul)">Para filtros, ordenação e paginação (ex: ?cor=azul)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para atualizar o nome de um produto</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para deletar o banco de dados
    *Explicação: Query Params são usados para modificar ou filtrar a representação dos dados retornados.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. Em qual objeto da requisição costuma vir o JSON enviado via POST?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">req.params</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">req.query</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! req.body">req.body</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">req.headers
    *Explicação: O Body é a parte da mensagem HTTP reservada para o transporte de dados complexos e volumosos.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">6. Qual analogia melhor define o papel do Controller?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O cozinheiro que prepara o prato</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O garçom que anota o pedido e entrega o prato">O garçom que anota o pedido e entrega o prato</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O dono do restaurante que cuida do banco de dados</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O cliente que come a comida
    *Explicação: O Controller apenas coordena a entrada e a saída, delegando a "preparação" para outras camadas.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">7. Por que a Injeção de Dependência é útil nos Controllers?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para o código ficar mais pesado e seguro</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Para facilitar a troca de comportamentos e a criação de testes automatizados">Para facilitar a troca de comportamentos e a criação de testes automatizados</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para economizar espaço no HD</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque o Google obriga
    *Explicação: Receber dependências prontas torna o Controller menos acoplado e mais fácil de manter.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">8. O que acontece se o Controller não retornar um Status Code?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O servidor explode</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O cliente pode receber um status padrão (ex: 200) que não condiz com o resultado real">O cliente pode receber um status padrão (ex: 200) que não condiz com o resultado real</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O computador trava</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">A internet cai
    *Explicação: É vital ser explícito sobre o que aconteceu (201 para sucesso, 400 para erro, etc).*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">9. Onde configuramos o mapeamento de Verbo + Path no backend?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">No banco de dados</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! No arquivo de roteamento (Router)">No arquivo de roteamento (Router)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">No arquivo de interface (CSS)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Dentro do arquivo de imagem .png
    *Explicação: O roteador é quem diz: "Se chegar esse verbo nesse caminho, chame essa função".*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">10. Qual a vantagem de padronizar as respostas de erro em JSON?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para o erro ficar mais bonito</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Para que o frontend consiga ler a mensagem e exibir um alerta amigável ao usuário">Para que o frontend consiga ler a mensagem e exibir um alerta amigável ao usuário</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para economizar bateria do servidor</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para esconder o código do erro
    *Explicação: Um JSON de erro estruturado permite que o app reaja de forma inteligente a falhas.*</div>
  <div class="quiz-feedback"></div>
</div>

