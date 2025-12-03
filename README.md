# Portfólio - Trabalho de Graduação
## Jhonny Freitas Dutra
### Curso Superior de Tecnologia em Banco de Dados
### Faculdade de Tecnologia de São José dos Campos - Prof. Jessen Vidal

---

## Introdução

Este portfólio apresenta minha trajetória ao longo dos três anos e meio do Curso Superior de Tecnologia em Banco de
Dados na FATEC São José dos Campos - Prof. Jessen Vidal. Reúno aqui uma coletânea dos principais projetos que desenvolvi
durante minha graduação, todos realizados no contexto da metodologia de ensino API (Aprendizagem por Projeto
Integrador).

A metodologia API funciona através da formação de grupos a cada semestre, onde desenvolvemos soluções de software para
empresas parceiras da instituição. Durante os seis semestres do curso, tive a oportunidade de trabalhar em projetos
reais, enfrentando desafios do mercado de trabalho e aplicando conhecimentos teóricos na prática. Cada projeto
representou uma oportunidade única de crescimento técnico e pessoal, permitindo-me desenvolver competências tanto
técnicas (hard skills) quanto comportamentais (soft skills).

Ao longo desta jornada, participei de projetos que abrangeram diferentes tecnologias e domínios de conhecimento, desde
desenvolvimento web full-stack até soluções de Business Intelligence e ETL. Neste portfólio, documenta não apenas os
projetos que desenvolvi, mas também minha evolução como profissional, minhas contribuições técnicas e as aprendizagens
que obtive em cada etapa.

Aqui apresento detalhadamente cada um dos projetos de API dos quais participei, além de outros trabalhos relevantes que
contribuíram para minha formação profissional. Compartilho minhas experiências, os desafios que enfrentei e as
conquistas que alcancei durante esse período.

---

## Sobre Mim

Meu nome é Jhonny Freitas Dutra, um Full-Stack Software Engineer focado em integrações, dados e automação. Atualmente
atuo como TVC (Temporary/Vendor/Contractor) na Google através da HCLTech, onde tenho a oportunidade de trabalhar com
tecnologias de ponta, desenvolvendo serviços Java/gRPC, interfaces Angular, e pipelines de dados de Snowflake para
[Spanner](https://static.googleusercontent.com/media/research.google.com/en//archive/spanner-osdi2012.pdf) (Banco
de Dados do Google).

Minha experiência profissional também inclui trabalhos com tecnologias geoespaciais e ESG (Environmental, Social, and
Governance), onde atuei em parceria com especialistas de domínio (Engenheiros Ambientais) para transformar análises
complexas em serviços back-end confiáveis, utilizando ferramentas como PostGIS, Leaflet e Google Earth Engine.

Além do desenvolvimento de software, tenho experiência na elaboração de Technical Design Documents (TDDs) e na resolução
de problemas em produção através de análise SQL, correlação de logs (Datadog) e implementação de mudanças de código
seguras e escopadas.

Estou sempre buscando me aprimorar e expandir meus conhecimentos. Tenho um grande interesse em pesquisa operacional e
otimização combinatória, área na qual pretendo iniciar meu mestrado no próximo ano. Essa paixão me levou a contribuir
para projetos open-source relacionados ao tema, como o [librko](https://github.com/dutrajy/librko), um fork do
[RKO_Cpp_v2.0](https://github.com/RKO-solver/RKO_Cpp_v2.0), onde pude aplicar e desenvolver meus conhecimentos em
algoritmos de otimização e meta-heurísticas.

## Contato
- **Email:** dutrajy@gmail.com
- **GitHub:** [https://github.com/dutrajy/](https://github.com/dutrajy/)
- **LinkedIn:** [https://www.linkedin.com/in/dutrajy/](https://www.linkedin.com/in/dutrajy/)

---

## Meus Projetos

### 1º Semestre - API 1

**Repositório:** [https://github.com/pontopython/api-bd1](https://github.com/pontopython/api-bd1)

#### Empresa Parceira
A empresa parceira deste primeiro projeto foi a própria FATEC São José dos Campos - Prof. Jessen Vidal, representada
pelos professores da instituição. Este projeto foi fundamental para estabelecer a metodologia de trabalho que seria
seguida nos semestres seguintes.

#### Sobre o Projeto
O projeto consistiu no desenvolvimento de um sistema de avaliação democratizada baseado na técnica de avaliação 360°.
O objetivo era criar uma solução computacional que permitisse aplicar esta metodologia de avaliação, onde cada
participante é avaliado por diferentes perspectivas: autoavaliação, avaliação pelos membros do time e avaliações
adicionais de outros colegas.

O sistema foi desenvolvido utilizando metodologia ágil SCRUM, organizado em 4 sprints ao longo do semestre. A solução
permitia que líderes de time criassem e gerenciassem times, organizassem sprints, e que os membros realizassem
avaliações completas de 360°. Além disso, incluía funcionalidades de dashboard para visualização de métricas e
notas, gestão de turmas por administradores, e um sistema robusto de permissões e hierarquias de usuários.

A arquitetura do projeto era baseada em Python, utilizando uma estrutura modular organizada em diferentes componentes
para usuários, times, avaliações, sprints e turmas. O sistema operava através de uma interface de linha de comando
(CLI) interativa, proporcionando uma experiência fluida para os diferentes tipos de usuários (Administrador, Líder de
Time, Usuário regular e Fake Client).

#### Minha Contribuição
Como já trabalhava como desenvolvedor de software antes de iniciar a faculdade, trouxe minha experiência profissional
para este projeto acadêmico. Minhas principais contribuições incluíram:

**Desenvolvimento do Sistema de Autenticação:** Implementei o fluxo completo de login e logout, incluindo o loop
principal do menu que diferenciava as opções disponíveis conforme o tipo de usuário autenticado (Administrador, Líder
de Time, Usuário regular).

**Gestão de Times:** Desenvolvi funcionalidades relacionadas à criação e gestão de times, incluindo a capacidade de
adicionar membros aos times, listar times, e implementar validações para evitar duplicatas na criação e edição de
times e turmas.

**Sistema de Avaliações:** Implementei e refinei o sistema de avaliações 360°, incluindo funcionalidades para
restringir a criação de avaliações apenas para usuários que ainda não foram avaliados, correções em lógicas de
avaliação, e validações para garantir a integridade do processo avaliativo.

**Gestão de Usuários e Permissões:** Desenvolvi o sistema de tipos de usuário com seleção interativa, especificação de
categorias de usuário nos times, e implementei permissões e restrições diferenciadas. Criei menus específicos para
diferentes perfis (líder de grupo e fake client), e implementei limitações na seleção de Líder de Time (LT) e Product
Owner (PO).

**Validações e Regras de Negócio:** Implementei validações importantes como a prevenção de duplicatas em turmas e
times, restrições na criação de avaliações, e pré-seleção de turmas para melhorar a experiência do usuário.

**Integração e Melhorias de UX:** Desenvolvi funcionalidades para melhorar a experiência do usuário, como a
pré-seleção de turmas e diferenciação de menus conforme o perfil. Também testei e integrei bibliotecas como Python
Rich para melhorar a apresentação visual do sistema.

**Code Review e Integração:** Participei ativamente do processo de code review e merge de pull requests, garantindo a
qualidade do código e a integração adequada de features desenvolvidas por diferentes membros da equipe.

#### Hard Skills Desenvolvidas
- **Linguagens de Programação:** Python
- **Arquitetura de Software:** Estrutura modular, separação de responsabilidades, design de sistemas CLI
- **Gestão de Estado:** Implementação de sistemas de sessão e autenticação
- **Validação de Dados:** Regras de negócio, prevenção de duplicatas, validações de integridade
- **Ferramentas de Controle de Versão:** Git, GitHub (pull requests, code review)
- **Metodologias Ágeis:** SCRUM (sprints, backlog, entregas incrementais)
- **Bibliotecas Python:** Python Rich (para melhorias de UX em CLI)
- **Sistema de Arquivos:** Manipulação de arquivos para persistência de dados

#### Soft Skills Desenvolvidas
- Liderança técnica (como desenvolvedor experiente, auxiliei colegas menos experientes)
- Trabalho em equipe e colaboração efetiva
- Comunicação técnica (explicação de conceitos e soluções)
- Code review e mentoria de código
- Gestão de tempo entre trabalho profissional e projetos acadêmicos
- Resolução de problemas complexos de regras de negócio
- Adaptação de experiência profissional para contexto acadêmico

#### Conclusão
O primeiro semestre foi uma experiência interessante onde pude aplicar minha experiência profissional como
desenvolvedor de software em um contexto acadêmico. Embora já tivesse conhecimento técnico, a metodologia API me
permitiu trabalhar em equipe com colegas que estavam começando na área, o que foi uma oportunidade valiosa para
desenvolver habilidades de mentoria e comunicação técnica.

Foi desafiador adaptar-me à metodologia de projeto integrador e conciliar as demandas do projeto acadêmico com meu
trabalho profissional. No entanto, essa experiência reforçou minha capacidade de trabalhar em equipe, fazer code
reviews construtivos e compartilhar conhecimento. O projeto estabeleceu as bases para minha jornada acadêmica,
demonstrando como experiência profissional e aprendizado acadêmico podem se complementar efetivamente.

---

### 2º Semestre - API 2

**Repositório:** [https://github.com/oJavaLi/API-2-Semestre](https://github.com/oJavaLi/API-2-Semestre)

#### Empresa Parceira
A empresa parceira deste projeto foi a **2RP Net**, uma empresa data-driven com mais de 20 anos de experiência no
mercado de tecnologia. A empresa desenvolve soluções customizáveis e modulares para diversos setores, incluindo
monitoramento transacional, análise de documentos, biometria facial e gestão de escalas de colaboradores. A empresa
oferece serviços de consultoria, análise de dados, gestão de big data e soluções especializadas para adquirentes,
financeiras, bancos, varejistas e outros setores.

Esta parceria teve um significado especial para mim, pois já havia trabalhado na 2RPNet como Back-End Developer
(Junho de 2021 a Dezembro de 2021) antes de iniciar a faculdade. Ter trabalhado profissionalmente na empresa me deu
uma compreensão única do contexto organizacional e das necessidades de negócio, o que enriqueceu significativamente
minha contribuição para o projeto acadêmico.

#### Sobre o Projeto
O projeto consistiu no desenvolvimento de um sistema para controle efetivo da jornada extra de trabalho dos
colaboradores, identificando e registrando as horas extras e os sobreavisos. O sistema permite que colaboradores
realizem o lançamento de suas horas trabalhadas, diferenciando entre horas extras e sobreavisos para um controle mais
preciso e pagamento adequado.

A solução implementa um fluxo de aprovação hierárquico, onde as horas trabalhadas precisam ser aprovadas pelo gestor
da equipe e posteriormente pelo setor de Recursos Humanos. O sistema também inclui dashboards para visualização de
métricas em tempo real, permitindo que colaboradores acompanhem suas horas aprovadas/reprovadas, e que o RH monitore
a carga trabalhada conforme as necessidades do Centro de Responsabilidade (CR).

O projeto foi desenvolvido utilizando Java como linguagem principal, com JavaFX para a interface gráfica, resultando
em uma aplicação desktop que roda localmente. O banco de dados MySQL foi utilizado para persistência dos dados. A
arquitetura seguia padrões de desenvolvimento orientado a objetos, organizada em camadas para separação de
responsabilidades, permitindo uma aplicação robusta e mantível para uso interno da empresa.

#### Minha Contribuição
Tendo já trabalhado na 2RPNet anteriormente, pude trazer minha experiência profissional e conhecimento do contexto
empresarial para o projeto acadêmico. Minhas principais contribuições incluíram:

**Sistema de Parametrização:** Desenvolvi e corrigi funcionalidades relacionadas à parametrização do sistema,
permitindo a configuração flexível de regras e parâmetros que controlam o comportamento da aplicação. Implementei
correções na lógica de parametrização e trabalhei na estruturação de tabelas relacionadas a essa funcionalidade.

**Aprovação Parcial pelo Gestor e Administrador:** Implementei a funcionalidade de aprovação parcial de horas extras
e sobreavisos, permitindo que gestores e administradores aprovem apenas parte das horas solicitadas quando necessário,
proporcionando maior flexibilidade no processo de aprovação hierárquico.

**Relatórios e Discriminação de Verbas:** Desenvolvi funcionalidades de relatórios que discriminam as verbas
relacionadas às horas extras e sobreavisos, permitindo uma visualização detalhada dos valores a serem pagos aos
colaboradores. Esta funcionalidade foi essencial para o RH realizar análises financeiras precisas.

**Correções em Gestão de Usuários:** Corrigi problemas relacionados à categoria de usuário na funcionalidade de mudança
de senha, garantindo que as permissões e categorias de usuário fossem corretamente mantidas durante operações de
atualização de credenciais.

**Code Review e Integração:** Realizei code review e merge de múltiplas branches do projeto, incluindo integrações de
funcionalidades como parametrização, funções de edição e relatórios. Minha experiência profissional me permitiu
garantir a qualidade do código e a integração adequada de diferentes features desenvolvidas pela equipe.

**Desenvolvimento Java/JavaFX:** Contribuí para o desenvolvimento da aplicação desktop utilizando Java e JavaFX,
trabalhando tanto na lógica de negócio quanto na interface gráfica, garantindo uma experiência de usuário fluida e
intuitiva.

#### Hard Skills Desenvolvidas
- **Linguagens de Programação:** Java
- **Frameworks de Interface:** JavaFX (desenvolvimento de aplicações desktop com interface gráfica)
- **Banco de Dados:** MySQL (design de esquema, queries, relacionamentos, criação de tabelas)
- **Arquitetura:** Programação Orientada a Objetos, separação em camadas, design patterns
- **Desenvolvimento Desktop:** Aplicações JavaFX para uso local
- **Ferramentas de Desenvolvimento:** NetBeans IDE, Git, GitHub (code review, merge de branches)
- **Metodologias Ágeis:** SCRUM (4 sprints, backlog do produto, entregas incrementais)
- **Ferramentas de Colaboração:** Slack para comunicação em equipe
- **Modelagem de Dados:** Design de banco de dados relacional, normalização
- **Relatórios e Visualização de Dados:** Geração de relatórios detalhados com discriminação de verbas

#### Soft Skills Desenvolvidas
- Liderança técnica (aplicação de experiência profissional no contexto acadêmico)
- Trabalho em equipe com conhecimento prévio do contexto empresarial
- Comunicação com stakeholders (conhecimento prévio da empresa parceira)
- Code review e mentoria técnica
- Integração entre experiência profissional e aprendizado acadêmico
- Pensamento crítico sobre requisitos de negócio
- Flexibilidade para adaptar soluções técnicas às necessidades do cliente

#### Conclusão
O segundo semestre foi especialmente significativo por trabalhar com a 2RPNet, empresa onde já havia atuado
profissionalmente. Esta experiência única me permitiu combinar meu conhecimento técnico adquirido no trabalho anterior
com o aprendizado acadêmico da metodologia API.

Ter trabalhado na empresa antes me deu uma compreensão profunda do contexto de negócio e das necessidades
organizacionais, o que enriqueceu significativamente minhas contribuições técnicas. Pude aplicar minha experiência
profissional em desenvolvimento backend e conhecimento da empresa para ajudar a equipe a desenvolver uma solução
alinhada com as necessidades reais do cliente.

Esta experiência reforçou a importância de integrar conhecimento técnico profissional com aprendizado acadêmico,
demonstrando como experiência prévia pode ser valiosa em projetos acadêmicos. Foi gratificante poder contribuir tanto
tecnicamente quanto através de mentoria, compartilhando conhecimentos com colegas da equipe.

---

### 3º Semestre - API 3 - DoisRPonto

**Repositório:** [https://github.com/oJavaLi/doisrponto](https://github.com/oJavaLi/doisrponto)

#### Empresa Parceira
A empresa parceira deste projeto foi novamente a **2RP Net**, proporcionando continuidade na parceria estabelecida no
semestre anterior. Esta continuidade permitiu um aprofundamento maior no entendimento das necessidades da empresa e a
oportunidade de evoluir a solução desenvolvida anteriormente para uma arquitetura mais moderna e escalável.

#### Sobre o Projeto
O projeto DoisRPonto foi uma evolução significativa em relação ao sistema desenvolvido no segundo semestre. Mantendo o
mesmo objetivo de controle de horas excedentes dos colaboradores (diferenciando entre hora extra e sobreaviso), desta
vez desenvolvemos uma aplicação web completa ao invés de uma aplicação desktop.

O sistema continua permitindo que colaboradores registrem suas horas excedentes, diferenciando entre horas extras e
sobreavisos, e implementa o fluxo de aprovação hierárquico onde gestores de equipe e o setor de Recursos Humanos
aprovam as horas trabalhadas. A grande evolução técnica deste projeto foi a migração para uma arquitetura web moderna,
utilizando Spring Boot no backend para criar APIs RESTful, e um frontend simples e eficiente desenvolvido com HTML,
CSS e JavaScript puro, sem o uso de frameworks de frontend.

Esta arquitetura web ofereceu vantagens significativas: acesso multiplataforma através de navegadores, facilidade de
atualização e manutenção, melhor separação entre frontend e backend, e preparação para futuras expansões ou integrações
com outros sistemas. O uso de Spring Boot proporcionou uma estrutura robusta, com injeção de dependências, gerenciamento
automático de configurações e facilidade para criar endpoints REST bem estruturados.

#### Minha Contribuição
No terceiro semestre, assumi responsabilidades mais complexas no projeto DoisRPonto, aplicando meus conhecimentos de
arquitetura web e APIs REST. Minhas principais contribuições incluíram:

**Desenvolvimento Backend com Spring Boot:** Desenvolvi endpoints REST para as funcionalidades do sistema, incluindo
APIs para lançamento de horas extras e sobreavisos, gerenciamento de usuários, fluxo de aprovação hierárquico, e
consulta de relatórios. Implementei controllers, services e repositories seguindo os padrões do Spring Framework,
garantindo uma arquitetura limpa e manutenível.

**Arquitetura de APIs REST:** Projetei e implementei a estrutura de APIs RESTful do sistema, definindo endpoints
semânticos, códigos de status HTTP apropriados, e estruturas de resposta consistentes. Trabalhei na separação de
responsabilidades entre camadas (Controller, Service, Repository), aplicando boas práticas de desenvolvimento web.

**Integração Frontend-Backend:** Trabalhei na integração entre o frontend (HTML/CSS/JavaScript) e o backend (Spring
Boot), implementando chamadas AJAX/fetch para consumir as APIs REST. Garanti que a comunicação entre frontend e backend
fosse eficiente, com tratamento adequado de erros e validações tanto no cliente quanto no servidor.

**Gestão de Usuários e Permissões:** Implementei funcionalidades relacionadas à gestão de usuários com diferentes
níveis de acesso (Colaborador, Gestor, RH), incluindo autenticação e autorização no contexto web. Trabalhei na criação
de mecanismos de segurança e controle de acesso baseados em roles.

**Sistema de Aprovação Hierárquico:** Desenvolvi o fluxo de aprovação onde gestores aprovam as horas de seus
colaboradores e o RH realiza a aprovação final. Implementei a lógica de negócio para diferentes níveis de aprovação,
garantindo a rastreabilidade e auditabilidade do processo.

**Banco de Dados e Persistência:** Trabalhei com JPA/Hibernate para mapeamento objeto-relacional, criando entidades,
relacionamentos e queries. Otimizei consultas ao banco de dados e implementei transações adequadas para garantir a
integridade dos dados.

**Code Review e Mentoria:** Como desenvolvedor com experiência em desenvolvimento web, participei ativamente do code
review, auxiliando colegas no entendimento de conceitos de APIs REST, Spring Boot e desenvolvimento full-stack.

#### Hard Skills Desenvolvidas
- **Linguagens de Programação:** Java, JavaScript
- **Backend Framework:** Spring Boot (REST APIs, Dependency Injection, Spring Data JPA)
- **Frontend:** HTML5, CSS3, JavaScript (vanilla, sem frameworks)
- **APIs REST:** Design de APIs RESTful, HTTP methods, status codes, JSON
- **Banco de Dados:** MySQL, JPA/Hibernate (ORM, queries, relacionamentos)
- **Arquitetura:** Arquitetura em camadas (Controller, Service, Repository), MVC, separação frontend/backend
- **Desenvolvimento Web:** AJAX/fetch, comunicação cliente-servidor, tratamento de erros
- **Ferramentas de Desenvolvimento:** Git, GitHub, IDE para desenvolvimento Java/Spring
- **Metodologias Ágeis:** SCRUM, sprints, backlog
- **Segurança Web:** Autenticação, autorização, controle de acesso baseado em roles

#### Soft Skills Desenvolvidas
- Liderança técnica em arquitetura web
- Planejamento estratégico de APIs e endpoints
- Mentoria de colegas em tecnologias web
- Visão arquitetural (separação de responsabilidades, escalabilidade)
- Gestão de complexidade em projetos full-stack
- Comunicação técnica sobre design de APIs
- Proatividade na identificação de melhorias arquiteturais

#### Conclusão
O terceiro semestre foi um marco importante na minha trajetória técnica. O projeto DoisRPonto me proporcionou a
oportunidade de evoluir de uma aplicação desktop para uma arquitetura web moderna, utilizando Spring Boot e APIs REST.
Esta transição foi fundamental para desenvolver meu entendimento sobre desenvolvimento full-stack e arquitetura de
aplicações web.

Trabalhar com Spring Boot apresentou um desafio técnico interessante e enriquecedor. Minha experiência profissional
anterior era principalmente com desenvolvimento backend em Python, então migrar para Java e aprender Spring Boot foi uma
experiência de aprendizado valiosa. Embora os conceitos fundamentais de desenvolvimento backend fossem similares, a
ecologia do Java e as convenções do Spring Framework me permitiram expandir meu conhecimento e desenvolver habilidades
em uma stack tecnológica diferente.

Aprender Spring Boot me permitiu aplicar conceitos avançados de desenvolvimento Java, como injeção de dependências,
programação orientada a aspectos, e frameworks ORM, enquanto comparava e contrastava com minha experiência em Python.
Esta diversificação tecnológica foi extremamente benéfica, pois me mostrou que os princípios fundamentais de
desenvolvimento de software transcendem linguagens específicas, enquanto cada ecossistema oferece suas próprias
vantagens e padrões.

O desenvolvimento do frontend com JavaScript puro me deu uma base sólida no entendimento de como frameworks modernos
funcionam por baixo dos panos, e a experiência de integrar frontend e backend me preparou para trabalhar com
arquiteturas mais complexas.

Esta experiência fortaleceu minha paixão por desenvolvimento de software e me deu confiança para trabalhar com
arquiteturas mais sofisticadas e diferentes stacks tecnológicos. Comecei a desenvolver um olhar mais crítico sobre
decisões técnicas e a importância de pensar na manutenibilidade, escalabilidade e separação de responsabilidades. O
projeto me preparou tecnicamente para os desafios mais complexos dos próximos semestres e reforçou minha capacidade de
adaptar-me a diferentes tecnologias e paradigmas de programação.

---

### 4º Semestre - API 4

**Repositórios:**
- Frontend: [https://github.com/api-4-sem/api-front/tree/develop](https://github.com/api-4-sem/api-front/tree/develop)
- Backend: [https://github.com/api-4-sem/api-back](https://github.com/api-4-sem/api-back)
- API: [https://github.com/api-4-sem/api](https://github.com/api-4-sem/api)

#### Empresa Parceira
A empresa parceira deste projeto foi a **Oracle**, uma das maiores empresas de tecnologia do mundo, especializada em
soluções de banco de dados, cloud computing, sistemas empresariais e tecnologias de software. O projeto foi
desenvolvido
para atender às necessidades do programa Oracle PartnerNetwork (OPN), um programa global que conecta a Oracle com seus
parceiros de negócios ao redor do mundo.

Trabalhar com a Oracle representou uma oportunidade única de desenvolver uma solução para uma empresa de grande porte
com requisitos complexos e padrões de qualidade elevados, proporcionando uma experiência próxima ao ambiente corporativo
real.

#### Sobre o Projeto
O projeto consistiu no desenvolvimento de um **Sistema de Gerenciamento de Parceiros** para o programa Oracle
PartnerNetwork. O sistema foi projetado para acompanhar o progresso dos parceiros da Oracle no programa OPN, facilitar
o cadastro de novos parceiros e gerenciar as informações dos parceiros já existentes na empresa.

A solução implementada possui uma arquitetura moderna e bem estruturada, com separação clara de responsabilidades
entre três componentes principais: frontend, backend e API. Esta separação permite escalabilidade, manutenibilidade e
facilita o trabalho em equipe, com diferentes desenvolvedores podendo trabalhar em diferentes camadas de forma
independente.

**Frontend - Vue.js:** O frontend foi desenvolvido utilizando Vue.js, um framework JavaScript progressivo para
construção de interfaces de usuário. A escolha do Vue.js permitiu criar uma aplicação web moderna, reativa e eficiente.
O framework facilitou a organização do código em componentes reutilizáveis, gerenciamento de estado da aplicação e
comunicação com as APIs backend através de requisições HTTP. A arquitetura do frontend foi organizada seguindo as
melhores práticas do Vue.js, com componentes modulares, rotas configuradas e integração eficiente com o backend através
da camada de API.

**Backend - Arquitetura em Camadas:** O backend foi desenvolvido utilizando Spring Boot, seguindo uma arquitetura em
camadas bem definida que se assemelha aos princípios de Clean Architecture e Domain-Driven Design (DDD). A estrutura
do projeto organiza o código em camadas distintas: controllers (camada de apresentação, responsável por receber
requisições HTTP), services (camada de aplicação, contendo a lógica de negócio), e repositories (camada de
infraestrutura, responsável pela persistência de dados). Esta organização garante a separação de responsabilidades,
facilita testes unitários e de integração, e torna o código mais manutenível e escalável. A arquitetura também seguiu
princípios de DDD, com entidades de domínio bem definidas e serviços que encapsulam as regras de negócio relacionadas
ao gerenciamento de parceiros e avaliações.

**Camada de API:** A camada de API fornece uma interface padronizada para comunicação entre frontend e backend,
garantindo que os contratos sejam bem definidos e que a integração seja eficiente e confiável. Os endpoints RESTful
seguem padrões consistentes de nomenclatura, estrutura de resposta e tratamento de erros.

O sistema permite o acompanhamento detalhado do progresso dos parceiros no programa OPN, incluindo funcionalidades de
avaliação de parceiros, métricas e estatísticas, notificações, e gerenciamento de informações relevantes para a Oracle
manter relações estratégicas com seus parceiros e garantir que o programa OPN funcione de forma eficiente.

#### Minha Contribuição
No quarto semestre, trabalhei em um projeto com arquitetura mais robusta e separação de responsabilidades. Minhas
principais contribuições incluíram:

**Sistema de Avaliações de Parceiros:** Desenvolvi funcionalidades relacionadas ao sistema de avaliação de parceiros,
que é um componente central do gerenciamento do programa OPN. Implementei a funcionalidade de criação de avaliações,
incluindo um novo formato de avaliação que permitia maior flexibilidade e detalhamento nas avaliações realizadas. Criei
também a funcionalidade de listagem de avaliações de parceiros, permitindo que os usuários visualizem e gerenciem as
avaliações existentes.

**Métricas e Estatísticas:** Implementei funcionalidades de métricas e estatísticas das avaliações de uma empresa,
proporcionando insights valiosos sobre o desempenho e progresso dos parceiros no programa OPN. Esta funcionalidade
permite que a Oracle analise dados agregados e tome decisões informadas sobre o gerenciamento da rede de parceiros.

**Sistema de Notificações:** Desenvolvi a funcionalidade de notificação de empresas ao receberem avaliações, garantindo
que os parceiros sejam informados imediatamente quando novas avaliações forem registradas. Esta funcionalidade melhora a
comunicação e o engajamento no programa OPN.

**Aprimoramento de Endpoints:** Trabalhei no aprimoramento de endpoints existentes, incluindo a inclusão de informações
adicionais no retorno de avaliações. Esta melhoria enriqueceu os dados disponíveis para o frontend, permitindo uma
visualização mais completa e útil das informações de avaliação.

**Desenvolvimento Backend com Spring Boot:** Todas essas funcionalidades foram implementadas seguindo a arquitetura em
camadas do projeto, utilizando Spring Boot e seguindo os princípios de Clean Architecture. Desenvolvi services para
encapsular a lógica de negócio, controllers para expor os endpoints REST, e trabalhei com repositories para persistência
de dados.

**Validações e Regras de Negócio:** Implementei validações apropriadas e regras de negócio para garantir a integridade
dos dados e a consistência do sistema de avaliações. Garanti que as avaliações fossem criadas e processadas
corretamente, respeitando as regras do programa OPN.

#### Hard Skills Desenvolvidas
- **Frontend:** Vue.js (componentes, roteamento, gerenciamento de estado), HTML, CSS, JavaScript
- **Backend:** Spring Boot, Java
- **Arquitetura:** Clean Architecture, Domain-Driven Design (DDD), arquitetura em camadas (Controller, Service,
Repository), separação frontend/backend/API
- **APIs REST:** Design de APIs RESTful, endpoints, estrutura de respostas, códigos de status HTTP
- **Banco de Dados:** JPA/Hibernate, Oracle Database, modelagem de dados, queries e relacionamentos
- **Desenvolvimento Full-Stack:** Integração entre Vue.js frontend e Spring Boot backend
- **Ferramentas de Desenvolvimento:** Git, GitHub, ferramentas de desenvolvimento colaborativo
- **Metodologias Ágeis:** SCRUM, sprints, trabalho em equipe multidisciplinar
- **Padrões de Design:** Separação de responsabilidades, injeção de dependências, design de serviços

#### Soft Skills Desenvolvidas
- Coordenação entre diferentes componentes de arquitetura
- Documentação técnica clara e precisa
- Code review construtivo
- Arquitetura de soluções escaláveis
- Comunicação com diferentes perfis técnicos (frontend, backend, arquitetos)
- Trabalho em equipe multidisciplinar
- Visão sistêmica de aplicações complexas

#### Conclusão
O quarto semestre trouxe uma maturidade significativa para minha atuação técnica e uma evolução importante no meu
entendimento de arquitetura de software. Trabalhar em uma arquitetura separada entre frontend, backend e API me ensinou
a importância da comunicação entre camadas e da definição clara de contratos, habilidades fundamentais para desenvolver
sistemas de grande escala.

Trabalhar com Vue.js no frontend foi uma experiência enriquecedora que complementou minha experiência em backend.
Aprender um framework moderno de frontend diferente me deu uma compreensão mais completa do desenvolvimento full-stack e
me permitiu entender melhor como as diferentes partes de uma aplicação web trabalham juntas de forma integrada.

No backend, trabalhar com uma arquitetura que seguia princípios de Clean Architecture e DDD foi especialmente valioso.
Minha experiência anterior em desenvolvimento backend, principalmente com Python, me deu uma base sólida em lógica de
negócio e arquitetura de software, e neste projeto pude aplicar e expandir esses conhecimentos trabalhando com Spring
Boot e uma arquitetura em camadas bem definida. A experiência me permitiu ver como os princípios de arquitetura
limpa podem ser aplicados em diferentes linguagens e frameworks, reforçando que as boas práticas de design transcendem
tecnologias específicas.

Este projeto foi crucial para desenvolver minha capacidade de pensar em sistemas maiores e mais complexos, preparando-me
para projetos profissionais mais desafiadores. A experiência de trabalhar com Vue.js, Spring Boot e uma arquitetura bem
estruturada me tornou um desenvolvedor mais completo e versátil, preparado para trabalhar em projetos de grande escala e
com diferentes stacks tecnológicos.

---

### 5º Semestre - API 5 - DataViz (bytelabs)

**Repositórios:**
- Projeto Principal: [https://github.com/bytelabss/ByteLabss-API5sem](https://github.com/bytelabss/ByteLabss-API5sem)
- Frontend Vue: [https://github.com/bytelabss/frontend-vue-API5](https://github.com/bytelabss/frontend-vue-API5)
- Database: [https://github.com/bytelabss/database-API5](https://github.com/bytelabss/database-API5)
- Backend Spring: [https://github.com/bytelabss/backend-spring-API5](https://github.com/bytelabss/backend-spring-API5)

#### Empresa Parceira
A empresa parceira deste projeto foi a **Pro4Tech**, uma empresa especializada em transformação digital que oferece
soluções inovadoras em diversas áreas tecnológicas. A Pro4Tech atua com desenvolvimento web e mobile, inteligência
artificial generativa, Business Intelligence, automação de processos (RPA), Internet das Coisas (IoT) e soluções de
produtividade. A empresa utiliza metodologias ágeis como Design Sprint e Design Thinking para criar soluções digitais
eficientes, considerando viabilidade tecnológica e financeira. Trabalhar com a Pro4Tech representou uma oportunidade de
desenvolver uma solução focada em análise de dados e Business Intelligence para uma empresa que valoriza inovação e
transformação digital.

#### Sobre o Projeto
O projeto **DataViz**, desenvolvido pelo grupo **bytelabs**, consistiu no desenvolvimento de um **Sistema de Análise de
Dados para Recrutamento e Processo Seletivo** para a Pro4Tech. O sistema foi projetado para analisar dados relacionados
a processos de recrutamento e seleção de candidatos, fornecendo insights valiosos através de dashboards interativos e
visualizações de dados.

O projeto permitiu que a Pro4Tech visualizasse e analisasse métricas importantes do processo de recrutamento, como
tempo médio de contratação por vaga, taxa de conversão de candidatos, eficiência de diferentes canais de recrutamento,
e outras estatísticas relevantes para otimizar os processos de RH. O sistema transformava dados brutos de recrutamento
em informações acionáveis através de dashboards customizáveis, facilitando a tomada de decisões estratégicas na área de
recursos humanos e permitindo que gestores acompanhassem o desempenho dos processos seletivos de forma visual.

A solução implementada possui uma arquitetura moderna e bem estruturada, com separação clara entre frontend, backend,
banco de dados e componentes de ETL. O projeto foi organizado em múltiplos repositórios, facilitando o trabalho
colaborativo e a manutenção do código.

**Frontend - Vue.js Avançado:** O frontend foi desenvolvido utilizando Vue.js com uma implementação mais avançada do que
no projeto anterior. O framework foi utilizado para criar uma interface moderna e interativa, com dashboards
customizáveis, visualizações de dados dinâmicas, e componentes reutilizáveis. A arquitetura do frontend incluiu
gerenciamento de estado, roteamento, e integração eficiente com APIs do backend para buscar e visualizar dados de
recrutamento.

**Backend - Spring Boot:** O backend foi desenvolvido utilizando Spring Boot, seguindo uma arquitetura em camadas que
seguiu princípios similares aos do projeto anterior, mas com foco específico em processamento e análise de dados. A
arquitetura organizou o código em controllers, services e repositories, garantindo separação de responsabilidades e
facilitando a manutenção e evolução do sistema.

**ETL e Data Warehouse - MySQL:** O projeto implementou um componente ETL (Extract, Transform, Load) que extraía dados
de fontes transacionais, transformava esses dados aplicando regras de negócio e agregações, e carregava os dados
transformados em um Data Warehouse no MySQL. O Data Warehouse utilizou um modelo de dados baseado no esquema estrela
(Star Schema), uma arquitetura otimizada para consultas analíticas. Este modelo permitiu armazenar dados de forma
denormalizada em tabelas de fatos e dimensões, facilitando consultas complexas e análises de dados relacionados a
processos de recrutamento. Os dados processados pelo ETL eram posteriormente consumidos pelo Dashboard, permitindo
visualizações rápidas e eficientes das métricas de recrutamento. O uso do modelo estrela e do ETL introduziu conceitos
importantes de Business Intelligence e data warehousing, preparando o terreno para projetos mais complexos de análise.

#### Minha Contribuição
No quinto semestre, atuei no projeto DataViz do grupo bytelabs, que apresentou uma arquitetura madura e foco em análise
de dados. Minhas principais contribuições incluíram:

**Testes de Carga e Análise de Performance - DevOps:** Realizei testes de carga usando [Locust.io](https://locust.io/),
uma ferramenta open-source para testes de carga escrita em Python. Executei testes de carga para cada um dos endpoints
da aplicação, validando que o deploy em uma instância EC2 t2.medium atenderia à quantidade de clientes demandada pelo
cliente. Nesta análise, identifiquei que o bottleneck da aplicação poderia estar na parte de autenticação, pois a
geração do JWT é CPU-intensive (CPU-bound). Porém, as demais requisições ao sistema se utilizavam do cache automático do
próprio MySQL para queries repetidas, otimizando significativamente o desempenho. Como a autenticação é uma requisição
que
acontece muito menos frequentemente que as outras operações, concluí que uma única máquina seria suficiente para atender
à demanda de acessos requisitada pelo cliente. Esta análise técnica foi fundamental para validar a arquitetura.

**Desenvolvimento Frontend - Dashboard e Visualizações:** Desenvolvi funcionalidades importantes no frontend Vue.js,
incluindo o layout do dashboard principal, implementação de gráficos e visualizações de dados. Trabalhei na criação de
componentes para exibir métricas de recrutamento, como o tempo médio de contratação por vaga, e na estilização dos
gráficos para garantir uma apresentação visual clara e profissional dos dados. Também implementei melhorias no layout
responsivo, garantindo que a aplicação funcionasse adequadamente em diferentes dispositivos.

**Configuração de Deploy e DevOps:** Implementei a configuração da base URL da API no frontend para diferentes ambientes
(desenvolvimento, produção), permitindo que o sistema fosse deployado de forma eficiente e confiável. Trabalhei na
configuração de variáveis de ambiente e na preparação do projeto para deployment, garantindo que as configurações fossem
adequadas para cada ambiente.

**Testes de Integração:** Participei ativamente do desenvolvimento e ajustes de testes de integração, tanto no frontend
quanto no backend. Trabalhei na implementação e correção de testes que garantiam a qualidade e confiabilidade do
sistema.
Os testes focaram especialmente nas integrações entre frontend e backend e na validação dos endpoints de API.

**Code Review e Integração:** Participei ativamente do code review e do processo de integração de código através de pull
requests, garantindo que o código seguisse os padrões estabelecidos pelo projeto. Minha experiência em desenvolvimento
full-stack me permitiu contribuir tanto para questões de frontend quanto de backend, revisando e integrando código de
diferentes membros da equipe.

#### Hard Skills Desenvolvidas
- **Frontend:** Vue.js (componentes avançados, roteamento, gerenciamento de estado), HTML, CSS, JavaScript
- **Backend:** Spring Boot, Java, APIs RESTful
- **Banco de Dados:** Modelo Estrela (Star Schema), Data Warehouse, Business Intelligence, queries analíticas, MySQL
- **ETL:** Extract, Transform, Load, processamento de dados, transformações de dados
- **Arquitetura:** Arquitetura em camadas, separação frontend/backend, design de APIs
- **Análise de Dados:** Processamento e análise de dados, agregações, visualizações
- **DevOps:** Configuração de deploy, variáveis de ambiente, preparação para produção, testes de carga, análise de
performance, AWS EC2, Locust.io
- **Performance:** Análise de bottlenecks, otimização de cache, testes de carga, CPU profiling
- **Ferramentas de Desenvolvimento:** Git, GitHub, submodules
- **Metodologias Ágeis:** SCRUM, sprints, trabalho em equipe multidisciplinar

#### Soft Skills Desenvolvidas
- Liderança técnica em projetos complexos
- Mentoria de colegas
- Visão estratégica de produto e análise de dados
- Gestão de expectativas com stakeholders
- Trabalho sob pressão em projetos de grande escala
- Comunicação entre diferentes áreas (desenvolvimento, dados, negócios)

#### Conclusão
O quinto semestre consolidou muito do conhecimento técnico adquirido ao longo do curso e introduziu novos conceitos
importantes relacionados a análise de dados e Business Intelligence. Trabalhar com tecnologias como Vue.js e Spring Boot
em um projeto com arquitetura bem definida foi uma experiência enriquecedora, e o trabalho com modelo de dados em
esquema estrela me introduziu aos conceitos de data warehousing e análise de dados.

Minha experiência anterior em desenvolvimento backend me permitiu contribuir efetivamente para o projeto, aplicando
conceitos que já conhecia enquanto aprendia novas tecnologias e paradigmas, como o modelo estrela para análise de dados
e conceitos de Business Intelligence.
A experiência de trabalhar com dashboards e visualizações de dados me deu uma compreensão mais ampla de como sistemas de
software podem ser utilizados não apenas para operações transacionais, mas também para análise e tomada de decisões.

Este projeto me permitiu aplicar muitos dos conceitos aprendidos anteriormente e me preparou para o desafio final do
sexto semestre, que viria a focar ainda mais em dados e ETL. A experiência também reforçou minha paixão por
desenvolvimento full-stack e minha capacidade de trabalhar em projetos complexos que integram múltiplas tecnologias e
conceitos de diferentes áreas do conhecimento.

---

### 6º Semestre - API 6 - Sistema de Análise de Dados de Tickets (NoDesk)

**Repositórios:**
- Frontend: [https://github.com/NoDesk-6BD/6sem2025Frontend](https://github.com/NoDesk-6BD/6sem2025Frontend)
- Backend: [https://github.com/NoDesk-6BD/6sem2025Backend](https://github.com/NoDesk-6BD/6sem2025Backend)
- Main: [https://github.com/NoDesk-6BD/6sem2025Main](https://github.com/NoDesk-6BD/6sem2025Main)

#### Empresa Parceira
A empresa parceira deste projeto foi novamente a **Pro4Tech**, continuando a parceria estabelecida no semestre anterior.
Esta continuidade permitiu um aprofundamento ainda maior no contexto organizacional da empresa e um entendimento mais
refinado das necessidades de negócio. Trabalhar novamente com a Pro4Tech representou uma oportunidade de desenvolver uma
solução mais complexa e abrangente, focada em análise de dados de sistemas de tickets e Business Intelligence, aplicando
conceitos avançados de ETL, compliance com LGPD e uso de inteligência artificial para predições.

#### Sobre o Projeto
O projeto consistiu no desenvolvimento de um **Sistema de Análise de Dados de Tickets** para a Pro4Tech, desenvolvido
pelo grupo **NoDesk**. O objetivo era realizar análises dos dados do sistema de tickets da empresa, extraindo dados do
banco de dados SQL Server da empresa, processando esses dados através de diversos processos de ETL para levantar as
métricas e gerar gráficos a serem exibidos em dashboards interativos.

O projeto transformou dados brutos de tickets em informações acionáveis através de processos de ETL, permitindo que a
Pro4Tech visualizasse métricas importantes sobre seu sistema de atendimento, como tempo médio de resolução, volume de
chamados abertos, previsão de demanda futura, e outras estatísticas relevantes para otimização de processos e gestão de
recursos.

Duas características importantes e inovadoras deste projeto foram a preocupação com o uso de **Inteligência Artificial**
para predições (utilizando Prophet para predição de chamados abertos na próxima semana) e a **compliance com LGPD**
(Lei Geral de Proteção de Dados). O sistema implementou encriptação de dados de usuários para deleção segura, utilizando
user_keys em schema separado (simulando um banco de dados separado) de forma que um usuário deletado continue deletado
mesmo com restore do backup - não deletado de fato, mas com dados irrecuperáveis. Além disso, foi implementado um
sistema de aceite de termos para uso da plataforma, garantindo transparência e consentimento.

**Frontend - Nuxt 4 e Vue 3:** O frontend foi desenvolvido utilizando Nuxt 4 (framework baseado em Vue 3) com
TypeScript,
fornecendo uma experiência de desenvolvimento moderna e type-safe. A aplicação utilizou @nuxt/ui para componentes de UI,
ESLint para qualidade de código, e Vitest para testes unitários. O frontend exibiu os dados processados pelo ETL através
de dashboards interativos com gráficos e cards, permitindo visualização clara das métricas.

**Backend - FastAPI e Python:** O backend foi desenvolvido utilizando FastAPI, um framework moderno de Python para
construção de APIs. A aplicação utilizou PostgreSQL como banco de dados principal, Alembic para migrações de banco de
dados, e seguiu uma arquitetura modular organizada em diferentes módulos (auth, core, users, etc.). O backend foi
estruturado utilizando o sistema de injeção de dependências do FastAPI de forma inteligente, facilitando a organização
do código, testes e manutenção. O backend forneceu endpoints RESTful para o frontend consumir as métricas processadas.

**ETL e Data Pipeline:** O projeto implementou processos extensivos de ETL que extraíam dados do banco SQL Server da
empresa cliente, transformavam esses dados aplicando regras de negócio e agregações, e carregavam os dados processados
em diferentes destinos. As métricas processadas foram salvas em **MongoDB** (banco de dados NoSQL), atendendo ao
requisito do semestre de utilizar pelo menos um banco NoSQL. Essas métricas processadas eram posteriormente consumidas
pelo Dashboard do frontend para exibição em gráficos e cards, garantindo performance e eficiência na visualização dos
dados.

**Infraestrutura - Docker Compose:** O projeto fez uso intensivo de Docker Compose para levantar os diversos containers
necessários, incluindo: banco de dados SQL Server do cliente (fonte de dados), Alembic para migrações, PostgreSQL como
banco da aplicação, serviços de ETL, MongoDB para armazenamento de métricas, e outros componentes necessários. Esta
arquitetura containerizada facilitou o desenvolvimento, testes e deploy, garantindo consistência entre ambientes e
facilitando a orquestração dos múltiplos serviços.

**Inteligência Artificial - Prophet:** O projeto implementou uso de IA através da biblioteca Prophet (desenvolvida pelo
Facebook) para predição de chamados abertos na próxima semana. Esta funcionalidade permitiu que a Pro4Tech pudesse
antecipar demandas futuras e planejar recursos adequadamente, demonstrando aplicação prática de machine learning para
análise de séries temporais.

**Compliance LGPD e Segurança de Dados:** O sistema implementou medidas rigorosas de compliance com a LGPD, incluindo
encriptação de dados de usuários para deleção segura. A solução utilizou user_keys armazenadas em schema separado
(simulando um banco de dados separado), garantindo que dados de usuários deletados permaneçam irrecuperáveis mesmo em
caso de restore de backup. Além disso, foi implementado sistema de aceite de termos, garantindo que usuários concordem
com os termos de uso da plataforma antes de acessá-la.

#### Minha Contribuição
O projeto, desenvolvido no último semestre, representou o ápice da minha formação técnica e consolidou todos os
conhecimentos adquiridos ao longo do curso. Minhas principais contribuições incluíram:

**Boilerplate Inicial e Arquitetura do Backend:** Desenvolvi o boilerplate inicial do projeto backend utilizando
FastAPI,
estruturando a arquitetura de forma inteligente através do sistema de injeção de dependências do FastAPI. Esta abordagem
facilitou a organização do código em módulos bem definidos, permitiu testes mais eficientes através de mock de
dependências, e garantiu uma base sólida e escalável. A estrutura inicial estabeleceu os padrões arquiteturais seguidos
por toda a equipe durante o desenvolvimento.

**Desenvolvimento Backend - FastAPI e Python:** Contribuí significativamente para o desenvolvimento do backend
utilizando
FastAPI e Python, implementando endpoints e serviços relacionados ao gerenciamento de dados e métricas. Trabalhei na
criação de APIs RESTful que forneciam dados processados para o frontend, garantindo que as métricas calculadas pelo ETL
fossem disponibilizadas de forma eficiente e confiável. Participei da implementação de funcionalidades de autenticação e
autorização, garantindo segurança e controle de acesso adequados.

**Integração Frontend-Backend:** Participei da integração entre o frontend Nuxt 4 e o backend FastAPI, trabalhando na
configuração e comunicação entre os componentes. Garanti que as chamadas de API fossem adequadas para diferentes
ambientes e que a comunicação entre frontend e backend fosse eficiente e confiável, especialmente para exibição de
dados processados pelo ETL nos dashboards.

**Code Review e Integração:** Participei ativamente do code review e do processo de integração de código através de pull
requests, garantindo que o código seguisse os padrões estabelecidos pelo projeto. Minha experiência em desenvolvimento
full-stack me permitiu contribuir tanto para questões de frontend quanto de backend, revisando e integrando código de
diferentes membros da equipe.

**Infraestrutura e DevOps:** Contribuí para a configuração e manutenção da infraestrutura utilizando Docker Compose,
garantindo que os múltiplos containers (SQL Server, PostgreSQL, MongoDB, serviços de ETL, etc.) fossem orquestrados
adequadamente. Trabalhei na configuração de ambientes de desenvolvimento e na preparação do projeto para deployment.

#### Hard Skills Desenvolvidas
- **ETL (Extract, Transform, Load):** Python, processamento de dados, transformações de dados, pipelines de dados
- **Business Intelligence:** Análise de dados, métricas de negócio, dashboards interativos, visualização de dados
- **Frontend:** Nuxt 4, Vue 3, TypeScript, @nuxt/ui, Vitest, ESLint, Tailwind CSS
- **Backend:** FastAPI, Python, PostgreSQL, Alembic, REST APIs, autenticação e autorização
- **Banco de Dados:** PostgreSQL, SQL Server, MongoDB (NoSQL), schemas separados, migrações de banco de dados
- **Data Pipeline:** Processamento de dados, agregações, armazenamento em NoSQL, consumo de dados processados
- **Arquitetura de Dados:** Modelagem de dados, schemas relacionais e não relacionais, otimização de consultas
- **Inteligência Artificial:** Prophet (Facebook), predição de séries temporais, machine learning aplicado
- **Compliance e Segurança:** LGPD, encriptação de dados, deleção segura de dados, user_keys, aceite de termos
- **Infraestrutura e DevOps:** Docker, Docker Compose, orquestração de containers, configuração de ambientes
- **Testes:** Testes unitários, testes de integração, Vitest, pytest
- **Ferramentas de Desenvolvimento:** Git, GitHub, pre-commit hooks, ESLint, Ruff
- **Metodologias Ágeis:** SCRUM, sprints, trabalho em equipe multidisciplinar

#### Soft Skills Desenvolvidas
- Liderança técnica em projetos complexos e multidisciplinares
- Visão de produto completa, considerando requisitos de negócio e técnicos
- Gestão de projeto em ambiente com múltiplos componentes e tecnologias
- Resolução de problemas complexos envolvendo múltiplas tecnologias
- Tomada de decisão técnica considerando compliance, segurança e performance
- Coordenação entre diferentes áreas (frontend, backend, ETL, infraestrutura)
- Foco em qualidade e segurança de dados (LGPD compliance)

#### Conclusão
Este projeto foi o desafio final e mais completo da minha graduação. A oportunidade de trabalhar com ETL, processamento
de dados, compliance com LGPD, uso de inteligência artificial e arquitetura containerizada me conectou diretamente com a
área de banco de dados que é o foco do curso. Este projeto consolidou todos os conhecimentos adquiridos ao longo dos
semestres anteriores e me permitiu trabalhar em uma solução que integrava múltiplas tecnologias e componentes de forma
completa.

A componente ETL foi especialmente importante, pois me permitiu aplicar conhecimentos de banco de dados de forma prática
e relevante para o negócio, trabalhando com extração de dados de sistemas legados (SQL Server), transformações complexas
e armazenamento em diferentes tipos de bancos (PostgreSQL relacional e MongoDB NoSQL). A experiência com compliance LGPD
e segurança de dados me deu uma compreensão profunda da importância da proteção de dados pessoais e das melhores
práticas para implementar soluções seguras e em conformidade com a legislação.

O uso de inteligência artificial (Prophet) para predições demonstrou como tecnologias modernas podem ser aplicadas para
resolver problemas de negócio reais, e a arquitetura containerizada com Docker Compose consolidou meus conhecimentos de
DevOps e infraestrutura. Desenvolver o boilerplate inicial do backend utilizando injeção de dependências do FastAPI me
permitiu aplicar conceitos avançados de arquitetura de software desde o início do projeto, estabelecendo uma base sólida
para todo o desenvolvimento. Este projeto representou uma integração valiosa entre minha experiência profissional prévia
em desenvolvimento de software e os conhecimentos específicos de banco de dados adquiridos durante a graduação,
consolidando meu perfil como profissional completo em ambas as áreas.

---

### Experiência Profissional

Antes mesmo de iniciar minha trajetória acadêmica, já trabalhava profissionalmente como desenvolvedor de software em
diferentes empresas e projetos. Minha carreira profissional começou em maio de 2020 na **NECTO Systems**, onde atuei
Back-End Developer, desenvolvendo um sistema de gerenciamento de processos para titulação de terras para o INTERPI
(Instituto de Terras do Piauí). O sistema permitia que cidadãos regularizassem suas terras através de um portal cidadão,
emitindo o título certificado pelo INTERPI, que posteriormente poderia ser usado para conseguir a escritura da terra em
cartório. O back office permitia aos funcionários do instituto gerenciar e acompanhar todo o fluxo de processos de
titulação. Implementei serviços com dados georeferenciados usando Django/DRF e GeoDjango/PostGIS para validação de
sobreposição com terras indígenas, territórios quilombolas e áreas protegidas. Também configurei infraestrutura com
NGINX, GitLab CI/CD e Docker Compose.

De junho de 2021 a dezembro de 2021, trabalhei na **2RPNet** como Back-End Developer, desenvolvendo uma plataforma de
escalonamento de força de trabalho para Pernambucanas. Projetei microserviços em Node.js/TypeScript e serviços em
Python, incluindo um protótipo de solver com algoritmo genético para geração automática de escalas, e contribuí para o frontend
em React/Recoil e um aplicativo React Native que integrava uma API de validação de documentos (RG, CNH, etc.) para verificação de autenticidade e detecção de documentos falsificados.

Entre janeiro de 2022 e março de 2023, atuei na **CBDS** como Back-End Developer, sendo alocado como contractor em
empresas dos Estados Unidos. Para a empresa Snap Kitchen, contribuí para o sistema de assinaturas e cobrança utilizando
Flask, SQLAlchemy, Stripe e Celery, investigando e resolvendo problemas de produção através de análise SQL, correlação
de logs no Datadog e implementação de mudanças de código seguras. Para a empresa Weaver, desenvolvi um motor de
compliance baseado em regras com APIs REST em Flask e integrei o frontend Angular para workflows de conformidade.

De março de 2023 a fevereiro de 2024, trabalhei na **SpotSat** como Back-End Developer, revisando e padronizando
microserviços Node.js/TypeScript em PostgreSQL/PostGIS, otimizando serviços Python/Scikit-Learn para classificação de
terras cultiváveis processando imagens de satélite, e automatizando verificações ESG com validação de sobreposição e séries
temporais de desmatamento com Google Earth Engine. Acompanhei e auxiliei no desenvolvimento do frontend feito com React/Leaflet.

Desde março de 2024, trabalho na **HCLTech** como Full Stack Engineer, atuando como TVC (Temporary/Vendor/Contractor)
na Google. Nesta posição, desenvolvo serviços backend em Java com gRPC/Protocol Buffers, interfaces frontend em Angular,
e pipelines de dados de Snowflake para Spanner usando Python. Implementei integrações com sistemas LMS (Docebo/Degreed), desenvolvi um
chatbot FAQ usando Vertex AI Agent Builder, e escrevo Technical Design Documents.

Ao longo desses anos de experiência profissional, trabalhei com tecnologias como Java, Python, TypeScript/JavaScript,
Node.js, frameworks (Spring Boot, Flask, Django/DRF, FastAPI, Express), frontend (React, Angular, Vue), bancos de dados
(PostgreSQL, PostGIS, MySQL, MongoDB, Redis, Spanner, Snowflake), tecnologias geoespaciais (GeoDjango, PostGIS, Leaflet,
Google Earth Engine), e ferramentas de DevOps e cloud (Docker, Docker Compose, GitHub Actions, GitLab CI/CD, AWS, Google
Cloud Platform), além de práticas como microserviços, CI/CD e Clean Code/SOLID.

---

### Preparação para Mestrado: Contribuições ao Framework RKO

Tenho interesse em iniciar meu mestrado em pesquisa operacional e otimização combinatória no próximo ano. Para me
preparar, venho estudando programação linear, algoritmos genéticos e C++ desde o início do ano, focando em frameworks
especializados em otimização combinatória.

Venho estudando o framework **Random-Key Optimizer (RKO)** desenvolvido pelo Dr. Antônio Chaves da UNIFESP de São José
dos Campos ([repositório original](https://github.com/RKO-solver/RKO_Cpp_v2.0)). O RKO é um framework em C++ que
implementa múltiplas metaheurísticas (SA, ILS, VNS, BRKGA, PSO, GA, LNS, GRASP, IPR) para resolver problemas de
otimização combinatória através da representação de soluções por chaves aleatórias. O framework foi projetado para ser
facilmente adaptado a diferentes problemas, exigindo apenas a implementação de funções específicas (read e decoder) no
arquivo Problem.h.

Meu primeiro experimento foi reescrever o algoritmo genético baseado em RKO em C++, criando o projeto
[rkopy](https://github.com/dutrajy/rkopy), onde implementei bindings para Python. Isso permite que desenvolvedores
escrevam o decoder para seu problema de otimização diretamente em Python, facilitando a prototipagem e experimentação.

Posteriormente, realizei um fork do repositório original em [librko](https://github.com/dutrajy/librko), onde apliquei
técnicas de programação orientada a objetos para simplificar significativamente o uso do framework. Ao invés de
modificar múltiplas partes do código, abstraí o problema de otimização em uma classe abstrata (interface), tornando o
framework mais modular e fácil de utilizar. Meu objetivo é, durante o mestrado, organizar o repositório de forma que
seja possível utilizá-lo como uma biblioteca, sem necessidade de fazer fork. Esta foi apenas uma primeira etapa. Com
essa arquitetura, será mais simples criar bindings do código para outras linguagens enquanto mantém o solver em C++
para melhor performance.

Também tenho interesse em aprender a utilizar GPUs para resolver problemas de otimização combinatória usando
metaheurísticas, explorando o paralelismo massivo que essas arquiteturas oferecem.

Esta contribuição foi apresentada ao Dr. Antônio Chaves e me rendeu uma menção no [repositório oficial do
RKO](https://github.com/RKO-solver/RKO_Cpp_v2.0), reconhecendo o trabalho de reestruturação orientada a objetos.

---

## Conclusão

A trajetória de três anos e meio no Curso Superior de Tecnologia em Banco de Dados da FATEC São José dos Campos foi marcada
pela metodologia API (Aprendizagem por Projeto Integrador), que me permitiu trabalhar em projetos reais desde o primeiro
semestre. Embora já tivesse experiência profissional anterior como desenvolvedor de software, o curso foi extremamente
enriquecedor, oferecendo uma perspectiva acadêmica e teórica que complementou minha prática profissional.

A metodologia API foi fundamental para desenvolver habilidades técnicas e competências profissionais essenciais, enquanto
construía soluções que impactavam empresas parceiras como 2RPNet, Oracle e Pro4Tech. O curso me proporcionou a oportunidade
de conhecer de maneira mais aprofundada diferentes tecnologias de banco de dados, compreendendo não apenas seu uso prático,
mas também aspectos fundamentais como funcionamento interno, estratégias de otimização, bancos de dados distribuídos, e
arquiteturas de sistemas de gerenciamento de dados.

Ao longo dos seis semestres, evoluí de um contexto onde tudo era novo até projetos complexos onde pude liderar e
contribuir significativamente. A diversidade tecnológica enfrentada, desde Python e CLI até Vue.js, Spring Boot, FastAPI,
ETL e bancos de dados relacionais e NoSQL, me proporcionou uma visão abrangente do ecossistema de desenvolvimento de
software e preparação para trabalhar com diferentes arquiteturas e padrões.

A experiência profissional paralela na Google/HCLTech como Full Stack Engineer foi crucial, criando uma sinergia entre
teoria e prática. Pude aplicar conhecimentos acadêmicos em ambiente corporativo real e, simultaneamente, trazer insights
profissionais para os projetos acadêmicos. Essa combinação enriqueceu tanto minha formação técnica quanto minha
compreensão sobre desenvolvimento de software em escala.

Além disso, a exploração de pesquisa operacional e otimização combinatória, com contribuições aos projetos rkopy e
librko baseados no framework RKO, me preparou para os próximos passos acadêmicos, especialmente considerando o interesse
em iniciar um mestrado nessa área no próximo ano.

Este portfólio reflete não apenas os projetos desenvolvidos, mas a transformação profissional e pessoal ao longo dessa
jornada. Estou grato à FATEC São José dos Campos, aos professores, colegas de equipe e empresas parceiras que tornaram
essa experiência possível. A graduação marca o início de uma nova fase de aprendizado contínuo, e estou preparado para
os desafios que virão, continuando a contribuir com soluções inovadoras e relevantes.

---

**Jhonny Freitas Dutra**
* Email: dutrajy@gmail.com
* GitHub: [https://github.com/dutrajy/](https://github.com/dutrajy/)
* LinkedIn: [https://www.linkedin.com/in/dutrajy/](https://www.linkedin.com/in/dutrajy/)

---

São José dos Campos, Dezembro de 2025
