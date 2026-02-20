# Quiz 14 - Segurança e DevSecOps 🛡️

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. O que significa o termo "Shift Left" na segurança?</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Shift Left significa adiantar a segurança para as fases iniciais do desenvolvimento.">Mover a segurança para o final do projeto</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Significa integrar testes e validações de segurança o mais cedo possível no ciclo de desenvolvimento.">Integrar a segurança o mais cedo possível no ciclo de desenvolvimento (desde o código)</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Shift Left significa adiantar a segurança para as fases iniciais do desenvolvimento.">Deletar o código antigo e começar de novo</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Shift Left significa adiantar a segurança para as fases iniciais do desenvolvimento.">Mudar o teclado para o lado esquerdo</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. No "Modelo de Responsabilidade Compartilhada", de quem é a responsabilidade pela segurança dos dados?</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O provedor cuida da infraestrutura, mas VOCÊ é responsável pelos seus dados e configurações.">Apenas do provedor de Cloud (AWS/Azure/GCP)</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O provedor cuida da infraestrutura física, mas o cliente é responsável por proteger seus próprios dados e acessos.">Do Cliente (usuário da nuvem)</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O provedor cuida da infraestrutura, mas VOCÊ é responsável pelos seus dados e configurações.">Do provedor de internet</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. O provedor cuida da infraestrutura, mas VOCÊ é responsável pelos seus dados e configurações.">De ninguém, a nuvem é segura por natureza</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. O que o "Princípio do Menor Privilégio" defende?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Dar apenas o acesso estritamente necessário reduz drasticamente a superfície de ataque em caso de invasão.">Que cada usuário ou serviço deve ter apenas as permissões mínimas necessárias para realizar sua função</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Dar apenas o acesso estritamente necessário reduz drasticamente a superfície de ataque em caso de invasão.">Que os estagiários não devem ter senha</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Dar apenas o acesso estritamente necessário reduz drasticamente a superfície de ataque em caso de invasão.">Que senhas devem ser curtas para serem fáceis de lembrar</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Dar apenas o acesso estritamente necessário reduz drasticamente a superfície de ataque em caso de invasão.">Que apenas o dono da empresa pode acessar o site</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. Qual a diferença entre SAST e SCA?</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. SAST olha o código que você escreve; SCA olha o código que você baixa (bibliotecas).">SAST é para Python e SCA é para Javascript</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! SAST analisa o SEU código fonte; SCA analisa as vulnerabilidades em BIBLIOTECAS externas.">SAST analisa o seu código interno; SCA analisa as bibliotecas de terceiros (dependências)</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. SAST olha o código que você escreve; SCA olha o código que você baixa (bibliotecas).">São ferramentas de cores diferentes</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. SAST olha o código que você escreve; SCA olha o código que você baixa (bibliotecas).">Ambas fazem a mesma coisa no banco de dados</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. Por que usar Secret Scanning no projeto?</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Impede que dados sensíveis sejam expostos publicamente no GitHub ou outros repositórios.">Para descobrir segredos de outros programadores</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Impede que dados sensíveis sejam expostos publicamente no GitHub ou outros repositórios.">Para detectar e impedir que senhas ou chaves de API sejam enviadas para o repositório de código</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Impede que dados sensíveis sejam expostos publicamente no GitHub ou outros repositórios.">Para contar quantas linhas de código o projeto tem</div>
  <div class="quiz-option" data-correct="false" data-feedback="❌ Incorreto. Impede que dados sensíveis sejam expostos publicamente no GitHub ou outros repositórios.">Para ver se o código está bonito</div>
  <div class="quiz-feedback"></div>
</div>
