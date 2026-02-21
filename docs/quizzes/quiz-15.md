# Quiz 15 - Introdução

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. O que é uma SPA (Single Page Application)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Um site que só funciona em um navegador</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Uma aplicação onde o HTML é carregado uma única vez e o Javascript troca o conteúdo da tela">Uma aplicação onde o HTML é carregado uma única vez e o Javascript troca o conteúdo da tela</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Um site que não tem Javascript</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Um aplicativo de celular que não usa internet
    *Explicação: SPAs oferecem uma experiência fluida, parecida com um app nativo, sem recarregamentos de página.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. Qual componente é obrigatório para envolver toda a aplicação que usará rotas?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente."><Route></div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente."><Link></div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! <BrowserRouter>"><BrowserRouter></div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente."><RouterManager>
    *Explicação: Ele é o "contexto" que permite ao React monitorar a URL do navegador.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. Como definimos uma rota específica para a página de contato?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente."><Route url="/contato" component={Contato} /></div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! <Route path="/contato" element={<Contato />} />"><Route path="/contato" element={<Contato />} /></div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente."><Link to="/contato" /></div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente."><a href="/contato">
    *Explicação: No React Router v6, usamos os atributos `path` e `element`.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. Por que não devemos usar a tag `<a>` para navegar entre rotas no React?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque ela é proibida pelo Google</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque ela gasta mais bateria</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Porque ela causa um recarregamento total da página, perdendo o estado do React">Porque ela causa um recarregamento total da página, perdendo o estado do React</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque ela não aceita CSS
    *Explicação: O componente `<Link>` intercepta o clique para manter a troca de telas interna.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. Para que serve o caractere `*` no atributo `path`?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para indicar uma rota secreta</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Como um "coringa" para capturar qualquer URL que não foi definida anteriormente (Página 404)">Como um "coringa" para capturar qualquer URL que não foi definida anteriormente (Página 404)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para multiplicar o número de páginas</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Para aceitar qualquer tipo de arquivo
    *Explicação: É a forma padrão de lidar com links inexistentes.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">6. Qual hook usamos para capturar parâmetros da URL (ex: o ID em `/post/10`)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">useID()</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">useRoute()</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! useParams()">useParams()</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">useQuery()
    *Explicação: Os parâmetros definidos com `:` na rota são extraídos por este hook.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">7. Como redirecionamos o usuário para a Home após ele clicar em um botão de "Sair"?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">window.location.href = "/"</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! const navigate = useNavigate(); navigate("/");">const navigate = useNavigate(); navigate("/");</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente."><Link to="/" /></div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">useRoute("/")
    *Explicação: O hook `useNavigate` permite navegação via lógica de programação.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">8. O que acontece se removermos o componente `<Routes>` e deixarmos apenas os `<Route>`?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O app continua funcionando</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O React Router gerará um erro, pois os Route precisam estar dentro de um provedor de rotas">O React Router gerará um erro, pois os Route precisam estar dentro de um provedor de rotas</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O site fica mais lento</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O menu desaparece
    *Explicação: `<Routes>` é o componente que escolhe qual rota renderizar baseada na URL atual.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">9. Em qual pacote extra encontramos as ferramentas de roteamento do React?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">react-dom</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">react-router</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! react-router-dom">react-router-dom</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">vite-plugin-router
    *Explicação: O `react-router-dom` é a versão específica para navegadores web.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">10. Como definimos um parâmetro dinâmico chamado `slug` na URL?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">path="/blog/slug"</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! path="/blog/:slug"">path="/blog/:slug"</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">path="/blog/{slug}"</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">path="/blog/*slug"
    *Explicação: O uso dos dois pontos (`:`) sinaliza que aquela parte da URL é uma variável.*</div>
  <div class="quiz-feedback"></div>
</div>

