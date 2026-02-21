# Quiz 14 - Introdução

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. O que é um "Efeito Colateral" no React?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">É um bug que trava o computador</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Uma ação que acontece fora do fluxo normal de renderizar a interface (ex: buscar dados, timers)">Uma ação que acontece fora do fluxo normal de renderizar a interface (ex: buscar dados, timers)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">É o nome de uma biblioteca de animação</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">É quando o CSS muda a cor do botão
    *Explicação: Efeitos saem do campo puro de "desenhar componentes" e tocam o mundo externo.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. Qual o segundo parâmetro do `useEffect`?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Um número inteiro</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O array de dependências">O array de dependências</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O nome do componente</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Um arquivo CSS
    *Explicação: Esse array decide quando o efeito deve ser re-executado.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. O que acontece se passarmos um array de dependências vazio `[]`?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O efeito nunca roda</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O efeito roda em todo "re-render"</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O efeito roda apenas uma vez, quando o componente é montado (aparece na tela)">O efeito roda apenas uma vez, quando o componente é montado (aparece na tela)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O app fecha com erro
    *Explicação: É o padrão usado para buscar dados iniciais de uma API.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. Como fazemos para que um efeito rode toda vez que o estado `tema` mudar?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">useEffect(() => { ... })</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">useEffect(() => { ... }, [])</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! useEffect(() => { ... }, [tema])">useEffect(() => { ... }, [tema])</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">useEffect([tema], () => { ... })
    *Explicação: Incluir a variável no array obriga o React a monitorá-la.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. O que a função `fetch()` retorna?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O dado final em formato JSON</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Uma Promise (Promessa)">Uma Promise (Promessa)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Um número de erro</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Uma string de texto
    *Explicação: Chamadas de rede são assíncronas; o fetch promete que trará o dado no futuro.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">6. Para que serve o `.then(res => res.json())`?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para salvar o dado no disco</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para fechar a conexão</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Para converter a resposta bruta da rede em um objeto Javascript que possamos usar">Para converter a resposta bruta da rede em um objeto Javascript que possamos usar</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para criptografar os dados
    *Explicação: A resposta inicial é um objeto de rede; precisamos extrair o corpo dela em JSON.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">7. Qual a maneira correta de lidar com o estado de "Carregando"?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Usar um cronômetro de 5 segundos</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Criar um estado booleano `isLoading` e exibi-lo enquanto a API não responde">Criar um estado booleano `isLoading` e exibi-lo enquanto a API não responde</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Pedir para o usuário clicar em "Refresh"</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Não precisa lidar, o React faz sozinho
    *Explicação: Feedback para o usuário é essencial para uma boa experiência (UX).*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">8. O que acontece se você atualizar um estado dentro de um `useEffect` sem o array `[]`?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O estado não muda</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Pode gerar um loop infinito (o efeito muda o estado, que re-renderiza, que roda o efeito...)">Pode gerar um loop infinito (o efeito muda o estado, que re-renderiza, que roda o efeito...)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O site fica mais rápido</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O computador reinicia
    *Explicação: Este é um dos erros mais comuns de iniciantes no React.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">9. Onde devemos colocar a chamada `fetch` para que ela não rode milhares de vezes sem necessidade?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Fora do componente</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">No meio do JSX</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Dentro de um `useEffect` com dependências controladas">Dentro de um `useEffect` com dependências controladas</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Dentro do CSS
    *Explicação: O useEffect isola a lógica de disparos de rede.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">10. Se quisermos limpar um timer ou fechar um socket quando o componente sumir da tela, onde fazemos isso?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Em outro componente</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">No `useState`</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Na função de "cleanup" retornada pelo `useEffect`">Na função de "cleanup" retornada pelo `useEffect`</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Deletando o arquivo
    *Explicação: O useEffect permite retornar uma função que o React chama ao "desmontar" o componente.*</div>
  <div class="quiz-feedback"></div>
</div>

