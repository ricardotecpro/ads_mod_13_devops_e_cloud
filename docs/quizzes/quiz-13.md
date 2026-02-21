# Quiz 13 - Introdução

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. O que acontece quando o valor de um "State" muda no React?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O computador reinicia</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O React re-seta (redesenha) o componente na tela com os novos dados">O React re-seta (redesenha) o componente na tela com os novos dados</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O código Javascript é deletado</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Nada, o desenvolvedor deve atualizar a tela manualmente
    *Explicação: A reatividade automática é um dos maiores poderes do React.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. Qual a forma correta de criar um estado para guardar um número?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">let x = 0;</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">const x = 0;</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! const [x, setX] = useState(0);">const [x, setX] = useState(0);</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">val x by state(0);
    *Explicação: Usamos o "Array Destructuring" para pegar a variável e a função disparadora.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. Por que não podemos fazer `contador = contador + 1` diretamente?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque gasta muita energia</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque o Javascript proíbe</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Porque o React não ficará sabendo da mudança e não atualizará a tela">Porque o React não ficará sabendo da mudança e não atualizará a tela</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque isso apaga o banco de dados
    *Explicação: A função `set...` é quem avisa ao React que algo mudou.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. O que é um Hook?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Um erro CSS</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Uma função especial (como useState) que permite "enganchar" recursos do React em componentes de função">Uma função especial (como useState) que permite "enganchar" recursos do React em componentes de função</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Um tipo de cabo USB</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O vilão do Peter Pan
    *Explicação: Hooks revolucionaram o React, removendo a necessidade de usar "Classes" complexas.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. Qual o evento correto para detectar o clique em um botão no React?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">onclick</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! onClick (com o C maiúsculo)">onClick (com o C maiúsculo)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">click</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">on-press
    *Explicação: Eventos no React seguem o padrão CamelCase.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">6. Como você adiciona um novo elemento em um array de estado `lista` sem quebrar a imutabilidade?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">lista.push(novo)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">lista += novo</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! setLista([...lista, novo])">setLista([...lista, novo])</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">setLista(novo)
    *Explicação: Usamos o "Spread Operator" (...) para criar uma cópia da lista original com o novo item.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">7. Em um "Input Controlado", quem manda no valor que aparece na caixinha de texto?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O usuário</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O Teclado</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O Estado (State)">O Estado (State)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O CSS
    *Explicação: O valor do input é amarrado ao estado, garantindo que o JS tenha controle total do que é digitado.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">8. O que o parâmetro `e` em `onChange={(e) => ...}` representa?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Erro</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Estilo</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O Objeto de Evento que contém dados como `target.value`">O Objeto de Evento que contém dados como `target.value`</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Email
    *Explicação: O evento contém todas as informações sobre a interação que acabou de acontecer.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">9. Qual o valor inicial de `cont` em `const [cont, setCont] = useState(10)`?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">0</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">null</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! 10">10</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">undefined
    *Explicação: O valor dentro dos parênteses do useState define o ponto de partida.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">10. Se um componente pai muda seu estado, o que acontece com seus componentes filhos?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Eles param de funcionar</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Eles também são re-renderizados pelo React">Eles também são re-renderizados pelo React</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Eles ficam travados</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Eles mudam de cor sozinhos
    *Explicação: O fluxo de dados no React é descendente; se o pai muda, a árvore abaixo dele se atualiza.*</div>
  <div class="quiz-feedback"></div>
</div>

