# Quiz 01 - Introdução

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. Qual a principal característica de uma arquitetura Monolítica?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">É composta por vários serviços independentes</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O sistema é um único bloco de código onde tudo está acoplado">O sistema é um único bloco de código onde tudo está acoplado</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">É escrita apenas em JavaScript</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Não utiliza banco de dados
    *Explicação: No monólito, todas as funcionalidades residem em um único processo e base de código.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. Qual vantagem é mais associada aos Microsserviços?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Simplicidade de deploy inicial</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Baixo custo de infraestrutura</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Escalabilidade granular e isolamento de falhas">Escalabilidade granular e isolamento de falhas</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Facilidade em depurar logs centralizados
    *Explicação: Microsserviços permitem escalar apenas a parte do sistema que precisa de mais fôlego (ex: pagamentos).*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. O que é "Escalabilidade Horizontal"?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Aumentar a memória RAM de um único servidor</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Adicionar mais máquinas ou instâncias para dividir a carga">Adicionar mais máquinas ou instâncias para dividir a carga</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Trocar o banco de dados SQL por NoSQL</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Aumentar o tamanho das tabelas
    *Explicação: É o ato de adicionar mais "trabalhadores" ao sistema ao invés de aumentar o poder de um só (vertical).*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. Qual o papel de uma API (Application Programming Interface)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Criar o design da interface do usuário</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Permitir a comunicação e troca de dados entre sistemas">Permitir a comunicação e troca de dados entre sistemas</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Servir como o sistema operacional do servidor</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Substituir o banco de dados
    *Explicação: APIs são os contratos de comunicação entre o backend e seus clientes ou outros serviços.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. Sobre Microsserviços, o que significa ser "Poliglota"?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Falar várias línguas humanas</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! A liberdade de usar diferentes linguagens/tecnologias para cada serviço">A liberdade de usar diferentes linguagens/tecnologias para cada serviço</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Rodar apenas em servidores internacionais</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Usar apenas tradução automática nas rotas
    *Explicação: Um serviço pode ser em Node.js e outro em Java, dependendo da necessidade técnica.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">6. Qual destas ferramentas é usada para testar requisições para uma API sem precisar de frontend?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Photoshop</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Postman / Insomnia">Postman / Insomnia</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Excel</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Docker
    *Explicação: Clients HTTP como o Postman permitem enviar verbos como GET, POST, etc., e ver a resposta direta.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">7. O que acontece se um módulo de um monólito tiver um "Memory Leak" crítico?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Apenas aquele módulo para de funcionar</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O banco de dados se apaga automaticamente</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Provavelmente todo o sistema ficará instável ou sairá do ar">Provavelmente todo o sistema ficará instável ou sairá do ar</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">O sistema migra sozinho para microsserviços
    *Explicação: Como tudo roda no mesmo processo, falhas críticas afetam o bloco inteiro.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">8. Qual o formato de dados mais comum usado hoje para comunicação entre serviços?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">XML</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! JSON">JSON</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">CSV</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">TXT
    *Explicação: O JSON é leve, legível por humanos e o padrão de facto para APIs REST.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">9. Por que Microsserviços são considerados mais complexos operacionalmente?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque exigem mais linhas de código</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Devido à necessidade de monitorar muitos serviços, redes e consistência distribuída">Devido à necessidade de monitorar muitos serviços, redes e consistência distribuída</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque só funcionam com Linux</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Porque requerem hardware da NASA
    *Explicação: Manter 50 serviços conversando entre si exige muito mais automação e observabilidade.*</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">10. Qual ferramenta ajuda a garantir que o ambiente de desenvolvimento seja idêntico ao de produção?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Git</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">Postman</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Tente novamente.">VS Code</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Docker (Containerização)
    *Explicação: O Docker isola o serviço e suas dependências em um container que roda igual em qualquer lugar.*">Docker (Containerização)
    *Explicação: O Docker isola o serviço e suas dependências em um container que roda igual em qualquer lugar.*</div>
  <div class="quiz-feedback"></div>
</div>

