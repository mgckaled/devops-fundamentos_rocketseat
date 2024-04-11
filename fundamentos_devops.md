<!-- markdownlint-disable MD024 -->

# Fundamentos de DevOPS

## Sumário

- [Fundamentos de DevOPS](#fundamentos-de-devops)
  - [Sumário](#sumário)
  - [Módulo 1 - Cultura](#módulo-1---cultura)
    - [Conceitos](#conceitos)
      - [O que é DEVOPS?](#o-que-é-devops)
    - [Aulas](#aulas)
      - [Aula 1 - Contexto de um mundo sem DevOps](#aula-1---contexto-de-um-mundo-sem-devops)
      - [Aula 2 - Qual é a ideia do DevOps](#aula-2---qual-é-a-ideia-do-devops)
      - [Aula 3 - DevOps no dia a dia e SRE](#aula-3---devops-no-dia-a-dia-e-sre)
      - [Aula 4 - Síndrome da Pessoa Herói](#aula-4---síndrome-da-pessoa-herói)
    - [Quiz](#quiz)
  - [Módulo 2 - CALMS](#módulo-2---calms)
    - [Conceitos](#conceitos-1)
      - [O que é o framewor CALMS?](#o-que-é-o-framewor-calms)
      - [O que é GitOps/IaC?](#o-que-é-gitopsiac)
      - [O que é CI/CD?](#o-que-é-cicd)
    - [Aulas](#aulas-1)
      - [Aula 1 - Adotando a cultura DevOps](#aula-1---adotando-a-cultura-devops)
      - [Aula 2 - Automatizando tudo](#aula-2---automatizando-tudo)
      - [Aula 3 - Focando no valor e errando rápido](#aula-3---focando-no-valor-e-errando-rápido)
      - [Aula 4 - Metrificando e descentralizando conhecimento](#aula-4---metrificando-e-descentralizando-conhecimento)
      - [Aula 5 - Conhecendo as três maneiras](#aula-5---conhecendo-as-três-maneiras)
    - [Quiz](#quiz-1)

## Módulo 1 - Cultura

### Conceitos

#### O que é DEVOPS?

DevOps é uma cultura de desenvolvimento de software que promove a colaboração e integração entre equipes de desenvolvimento de software (Dev) e operações de TI (Ops). O termo "DevOps" é uma junção das palavras "desenvolvimento" (Development) e "operações" (Operations).

A principal ideia por trás do DevOps é eliminar as barreiras entre desenvolvimento e operações, permitindo uma entrega de software mais rápida e eficiente. Isso é alcançado através da automação de processos, integração contínua, entrega contínua, monitoramento e feedback constante.

Em resumo, DevOps busca melhorar a colaboração entre desenvolvedores, administradores de sistemas e outros profissionais de TI para que possam criar, testar e entregar software de forma mais rápida, frequente e confiável.

### Aulas

#### Aula 1 - Contexto de um mundo sem DevOps

O DevOps surgiu em 2008 para unir desenvolvimento e operações, promovendo descentralização de conhecimento e feedback contínuo. Automatização é essencial para aumentar a produtividade e reduzir tarefas repetitivas. A cultura DevOps permite experimentar novas tecnologias e melhorar processos. Na próxima aula, vamos explorar a rotina de uma pessoa DevOps, a diferença que o DevOps faz em uma organização e a relação entre DevOps e SRE.

#### Aula 2 - Qual é a ideia do DevOps

Nessa aula vamos aprender a importância da cultura no DevOps, destacando a separação entre desenvolvimento e operações em empresas sem essa cultura. Vamos discutir problemas de comunicação, centralização de conhecimento, falta de feedback e a importância da automatização. A implementação do DevOps visa resolver esses desafios, promovendo colaboração, aprendizado contínuo e eficiência por meio da automação. O instrutor destaca a necessidade de entender a origem e a aplicação do DevOps nas organizações.

#### Aula 3 - DevOps no dia a dia e SRE

Nesta aula, abordamos a importância do DevOps e do SRE no dia a dia das empresas. Exploramos a integração entre equipes, documentação contínua, feedback, testabilidade e a agilidade na entrega de funcionalidades. Destacamos a engenharia de confiabilidade de sites (SRE) e recomendo o livro sobre o tema. Explico como o SRE atua na implementação técnica, automatização e agilidade. Discuto a diferença entre DevOps como cultura e SRE como cargo técnico. Na próxima aula, abordarei desafios culturais mesmo com a implementação do DevOps. Até lá!

#### Aula 4 - Síndrome da Pessoa Herói

Nesta aula, discutimos o problema da Síndrome da Pessoa Herói no contexto da cultura DevOps. Essa síndrome ocorre quando uma única pessoa detém o conhecimento e a expertise para resolver problemas críticos em fluxos específicos, criando um gargalo na organização. Para evitar essa situação, é crucial promover a comunicação, a documentação e o compartilhamento de conhecimento entre os membros do time. A cultura DevOps precisa ser constantemente observada e aprimorada para eliminar dependências e promover a autonomia e o trabalho em equipe. A partir do próximo módulo, exploraremos frameworks específicos para auxiliar na implementação da cultura DevOps de forma eficaz.

### Quiz

1 - *Qual é o principal objetivo do DevOps?* **Resposta**: Integrar equipes de desenvolvimento e operações

2 - *Qual é o termo usado para descrever a dependência excessiva de uma pessoa com conhecimento especializado em um determinado fluxo de trabalho?* **Resposta**: Síndrome do super-herói

3 - *Como o DevOps aborda a centralização de conhecimento?* **Resposta**: Descentralizando o conhecimento técnico

4 - *Quais são os principais pontos da cultura DevOps mencionados nas aulas?* **Resposta**: Integração, Testabilidade, Descentralização, Automatização

5 - *Qual é o papel do Site Reliability Engineer (SRE) dentro da cultura DevOps?* **Resposta**: Cuidar da parte técnica, como automatização de deploy

6 - *Por que é importante evitar a síndrome da pessoa herói em uma organização DevOps?* **Resposta**: Para evitar gargalos e dependência excessiva

7 - *Qual é o principal benefício da descentralização de conhecimento na cultura DevOps?* **Resposta**: Estimular a colaboração entre equipes

8 - *Por que a testabilidade é considerada importante na cultura DevOps?* **Resposta**: Para experimentar e validar ideias rapidamente

## Módulo 2 - CALMS

### Conceitos

#### O que é o framewor CALMS?

O termo "CALMS" é um acrônimo que representa um conjunto de princípios fundamentais para a adoção eficaz de práticas DevOps. Ele foi proposto por Jez Humble, co-autor do livro "Continuous Delivery", e se tornou uma referência importante na comunidade DevOps. CALMS representa os seguintes princípios:

- **Cultural (Cultura)**: Enfatiza a importância da cultura organizacional na implementação do DevOps. Isso inclui a promoção da colaboração, comunicação eficaz, confiança e responsabilidade compartilhada entre equipes de desenvolvimento e operações.

- **Automation (Automação)**: Destaca a automação de processos como um componente chave do DevOps. Isso envolve a automação de testes, integração contínua, entrega contínua e implantação automatizada, entre outros aspectos, para aumentar a eficiência e reduzir erros humanos.

- **Lean (Enxuto)**: Baseia-se nos princípios Lean Manufacturing, que visam eliminar desperdícios e melhorar a eficiência. No contexto DevOps, isso significa identificar e eliminar processos redundantes, atrasos e atividades que não agregam valor ao cliente.

- **Measurement (Medição)**: Ressalta a importância da coleta de métricas e dados para avaliar o desempenho do processo de desenvolvimento e operações. Isso permite a identificação de áreas de melhoria e a tomada de decisões baseadas em dados.

- **Sharing (Compartilhamento)**: Encoraja o compartilhamento de conhecimento, experiências e ferramentas entre equipes. Isso promove a colaboração, a inovação e a resolução de problemas de forma mais eficaz.

#### O que é GitOps/IaC?

GitOps e IaC (Infrastructure as Code) são dois conceitos relacionados que têm sido fundamentais na prática moderna de DevOps e na automação de infraestrutura.

1. **Infrastructure as Code (IaC)**:
   IaC é uma abordagem para gerenciar e provisionar infraestrutura de TI usando código, em vez de configuração manual. Isso significa que a infraestrutura de um ambiente, como servidores, redes e serviços em nuvem, é descrita em arquivos de código, geralmente usando linguagens como YAML ou JSON. Esses arquivos de código são então versionados, revisados e gerenciados como qualquer outro código-fonte. Ao adotar a IaC, os processos de implantação e gerenciamento de infraestrutura se tornam mais consistentes, reprodutíveis e escaláveis.

2. **GitOps**:
   GitOps é uma prática que estende os princípios do DevOps para a infraestrutura e operações de TI. A ideia central do GitOps é usar o Git como o ponto central de controle para todas as mudanças na infraestrutura. Isso significa que todas as alterações na infraestrutura são descritas em repositórios Git e são refletidas automaticamente no ambiente real por meio de automação. O GitOps enfatiza a automação, a observabilidade e a governança da infraestrutura como código, permitindo a entrega contínua e confiável de mudanças na infraestrutura.

Em resumo, IaC e GitOps são abordagens que visam tornar o gerenciamento de infraestrutura mais ágil, consistente e automatizado, permitindo que equipes de desenvolvimento e operações colaborem de forma mais eficaz e entreguem software com mais rapidez e confiabilidade.

#### O que é CI/CD?

CI/CD é uma prática de desenvolvimento de software que combina integração contínua (Continuous Integration - CI) e entrega contínua/implantação contínua (Continuous Delivery/Continuous Deployment - CD). Essas práticas são essenciais para acelerar o ciclo de vida de desenvolvimento de software e melhorar a qualidade do produto final.

1. **Integração Contínua (CI)**:
   A integração contínua é uma prática em que os desenvolvedores integram suas alterações de código no repositório compartilhado (como Git) com frequência, várias vezes ao dia. Cada integração é automaticamente verificada por meio de compilações automatizadas e testes unitários. Se ocorrerem problemas durante a integração, os desenvolvedores são notificados imediatamente, permitindo correções rápidas e evitando problemas maiores no futuro. A CI garante que o código seja integrado e testado continuamente, o que ajuda a identificar bugs mais cedo no ciclo de desenvolvimento.

2. **Entrega Contínua (CD)**:
   A entrega contínua é uma prática em que o código testado e validado é automaticamente preparado para implantação em produção. Isso envolve a automação de todo o processo de build, teste e implantação do software. Com a entrega contínua, as equipes podem implantar alterações de forma rápida, segura e repetível em qualquer ambiente, seja desenvolvimento, teste ou produção. A entrega contínua reduz o tempo e o esforço necessários para disponibilizar novas funcionalidades para os usuários finais.

O CD é frequentemente dividido em dois conceitos relacionados:

- **Continuous Delivery (Entrega Contínua)**: Refere-se à prática de preparar o software para implantação automatizada em qualquer ambiente de produção, mas ainda requer intervenção humana para aprovar a implantação final.

- **Continuous Deployment (Implantação Contínua)**: Vai um passo além e automatiza completamente o processo de implantação, com as alterações sendo implantadas automaticamente em produção sem a necessidade de intervenção humana.

Em resumo, CI/CD é uma abordagem para desenvolvimento de software que enfatiza a automação, integração e entrega rápida e confiável de alterações de código, permitindo que as equipes de desenvolvimento entreguem software de alta qualidade de forma mais eficiente e rápida.

### Aulas

#### Aula 1 - Adotando a cultura DevOps

Nesta aula, abordamos o framework COMS, uma ferramenta para medir e acompanhar a implementação da cultura DevOps em uma organização. Através de um diagnóstico cultural, o COMS avalia se a empresa já está no modo DevOps ou se ainda está distante. O diagnóstico considera aspectos como a resolução de problemas, a busca por culpados versus a resolução em equipe, e a existência de um processo de pós-mortem para aprender com os erros. O objetivo é identificar falhas nos processos e implementar medidas para mitigá-las, evitando que se repitam no futuro. Nas próximas aulas, exploraremos o COMS em mais detalhes.

#### Aula 2 - Automatizando tudo

Nesta aula, exploramos o pilar de Automação (A) dentro do framework COMS. O foco está em dois aspectos: entrega contínua e GitOps/IAC. A entrega contínua deve ser automatizada para reduzir o tempo gasto em tarefas repetitivas e garantir agilidade na implantação. Já o GitOps/IAC visa estabelecer uma única fonte de verdade para recursos em nuvem, centralizando o gerenciamento no Git e garantindo maior segurança, economia e manutenabilidade. Abordaremos esses tópicos em detalhes em módulos específicos.

#### Aula 3 - Focando no valor e errando rápido

Nesta aula, aprofundamos o pilar LEAN (L) do framework COMS. O LEAN visa entregas rápidas e iteráveis, focando em alto valor e baixa complexidade. Através do desenvolvimento de MVPs e features em fatias, o LEAN incentiva uma cultura experimental, permitindo errar rápido e corrigir rápido. É importante observar a aplicação para diagnosticar erros rapidamente e evitar estresse na equipe e nos clientes. O foco deve estar sempre no que traz valor, permitindo avanços mais rápidos e melhores feedbacks. As próximas aulas abordarão os pilares M e S do COMS.

#### Aula 4 - Metrificando e descentralizando conhecimento

Nesta aula, exploramos os pilares M (mensuração) e S (compartilhamento de conhecimento) do framework COMS. A mensuração envolve métricas negociais e técnicas para avaliar o desempenho da aplicação e tomar decisões informadas. O objetivo é descobrir erros antes que impactem os usuários, promover a melhoria contínua e a entrega contínua. O compartilhamento de conhecimento visa descentralizar o conhecimento, evitando a Síndrome da Pessoa-Herói. Através da documentação, calls, processos de incidente e mensuração, o conhecimento é disseminado na equipe, liberando tempo para novos aprendizados e impulsionando a produtividade. O COMS pode ser aplicado no dia-a-dia para avaliar a maturidade DevOps da organização. As próximas aulas abordarão métodos de pesquisa sobre implementação de DevOps e a parte técnica, com foco em containers.

#### Aula 5 - Conhecendo as três maneiras

Esta aula introdutória ao DevOps apresenta as "Três Maneiras" como um guia para implementar a cultura DevOps e melhorar o fluxo de trabalho, a comunicação e o aprendizado organizacional. Abordando os conceitos de forma prática e contextualizada, a aula oferece ferramentas para diagnosticar o estado atual da sua organização e implementar as "Três Maneiras" de forma gradual, começando pela primeira: acelerar o fluxo de desenvolvimento. A segunda maneira se concentra em estabelecer um processo de feedback contínuo entre Dev e Ops, enquanto a terceira foca no aprendizado contínuo e na experimentação para aumentar a produtividade e o conhecimento organizacional. Ao final da aula, você estará preparado para aplicar as "Três Maneiras" em sua organização e iniciar sua jornada na cultura DevOps.

### Quiz

1 - *Qual é o significado de "CALMS" no contexto do framework discutido no módulo?* **Resposta:** É um método para avaliar a capacidade de uma empresa de adotar processos de DevOps

2 - *Por que a Automatização é considerada crucial no contexto do DevOps?* **Resposta:** Porque promove a entrega contínua e a eficiência operacional

3 - *Qual é a importância do conceito Lean dentro do framework CALMS?* **Resposta:** Promove entregas rápidas e iterativas, evitando desperdícios de tempo e esforço

4 - *Qual é o objetivo principal da mensuração/medição no contexto do DevOps?* **Resposta:** Fornecer feedbacks e insights para a melhoria contínua de processos

5 - *Como a ultima letra do framework CALMS, "S", contribui para a implementação eficaz do DevOps?* **Resposta:** Promovendo uma cultura de compartilhamento de conhecimento

6 - *Quais são os pilares das "Três Maneiras" de implementação do DevOps?* **Resposta:** Acelerar o fluxo, ampliar o feedback e experimentar e aprender
