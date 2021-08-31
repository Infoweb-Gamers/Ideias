#  **Metodos Ágeis**

* [Manifesto Agil](#manifesto-agil)
* [Scrum](#scrum)
* [Kanban](#kanban)
* [XP](#xp-xtreme-programming)
* [Lean](#lean)
* [FDD](#fdd-feature-driven-deveploment))
* [Crystal](#crystal)
* [ASD](#asd-adaptive-software-development)

## **Manifesto Agil**
Em 2001, um grupo de 17 renomados desenvolvedores de software, agruparam e aprimoraram os diversos conceitos de metodologias ágeis existentes e assinaram o “Manifesto para o Desenvolvimento Ágil de Software”, que passou então a ser muito difundido pelas comunidades de desenvolvimento.

Esse manifesto basicamente reúne 4 valores e 12 princípios que devem ser mantidos em mente:
### Valores
1. Os indivíduos e as interações entre eles mais que os processos e as ferramentas;
2. O software funcionando mais do que uma documentação completa e abrangente;
3. A colaboração com e dos clientes mais do que as negociações de contratos e;
4. Respostas a mudanças mais do que seguir o plano inicial.

### Princípios
1. A maior prioridade é satisfazer o cliente, através da entrega adiantada e contínua de software de valor;
2. Aceitar mudanças de requisitos, mesmo no fim do desenvolvimento. Processos ágeis se adequam a mudanças, para que o cliente possa tirar vantagens competitivas;
3. Entregar software funcionando com frequência, preferencialmente em semanas;
4. Cooperação diária entre pessoas que entendem do ‘negócio’ e desenvolvedores;
5. Projetos surgem através de indivíduos motivados, entre os quais existe relação de confiança.
6. A maneira mais eficaz e eficiente de transmitir informações são através de conversas cara a cara;
7. Software funcionais são a principal medida de progresso do projeto;
8. Processos ágeis promovem um ambiente sustentável. Os patrocinadores, desenvolvedores e usuários, devem ser capazes de manter indefinidamente, passos constantes;
9. Contínua atenção à excelência técnica e bom design, aumenta a agilidade;
10. Simplicidade é essencial. Cultivar a arte de maximizar a quantidade de trabalho que não precisou ser feito;
11. As melhores arquiteturas, requisitos e projetos emergem de equipes auto-organizadas;
12. Em intervalos regulares, o time reflete em como se tornar mais efetivo, então, se ajustam e otimizam seu comportamento de acordo.

## **Scrum**
Scrum é uma metodologia ágil para gestão e planejamento de projetos de software.

No Scrum, os projetos são dividos em **ciclos** (tipicamente mensais) chamados de **Sprints**. O **Sprint** representa um Time Box dentro do qual um conjunto de atividades deve ser executado. Metodologias ágeis de desenvolvimento de software são iterativas, ou seja, **o trabalho é dividido em iterações, que são chamadas de Sprints no caso do Scrum**.

**As funcionalidades a serem implementadas em um projeto são mantidas em uma lista que é conhecida como Product Backlog.** No início de cada Sprint, faz-se um **Sprint Planning Meeting**, ou seja, **uma reunião de planejamento na qual o Product Owner prioriza os itens do Product Backlog e a equipe seleciona as atividades que ela será capaz de implementar durante o Sprint que se inicia.** As tarefas alocadas em um Sprint **são transferidas do Product Backlog para o Sprint Backlog**.

A cada dia de uma Sprint, a equipe faz uma breve reunião (normalmente de manhã), chamada **Daily Scrum**. O objetivo é disseminar conhecimento sobre o que foi feito no dia anterior, identificar impedimentos e priorizar o trabalho do dia que se inicia.

Ao final de um Sprint, a equipe apresenta as funcionalidades implementadas em uma **Sprint Review Meeting**. Finalmente, faz-se uma **Sprint Retrospective** e a equipe parte para o planejamento do próximo Sprint. E o ciclo se repete. Veja a ilustração abaixo:

![Scrum_Processo](http://www.desenvolvimentoagil.com.br/images/scrum/ciclo_scrum.gif)

## **Kanban**

David J. Anderson (um pioneiro no campo de Lean/Kanban para trabalho de conhecimento) formulou o método Kanban como uma abordagem para mudanças de sistemas e o processo evolutivo, incremental, para organizações de trabalho de conhecimento. Ele foca na conclusão de tarefas e seus princípios mais importantes podem ser divididos em quatro princípios básicos e seis práticas.

### Princípios

* **1º Princípio: Começar Com O Que Você Já Faz**

    A flexibilidade do Kanban faz com que ele funcione com os processos, sistemas e fluxos de trabalho existentes, sem interromper o que já está sendo feito com sucesso; ele irá, naturalmente, destacar os problemas que precisam ser resolvidos e ajudará a avaliar e planejar mudanças para que sua implementação seja a mais tranquila possível. A versatilidade do Kanban permite que ele seja introduzido incrementalmente, e simpaticamente, em todos os tipos de organizações, sem o medo de um excesso de compromisso ou choque de cultura. Isto torna o Kanban fácil de ser implementado em qualquer tipo de negócio, já que não há necessidade de grandes mudanças.

* **2º Princípio: Aceitar a Busca por uma Mudança Evolutiva e Incremental**

    O método Kanban foi projetado para criar mínima resistência, e assim, encorajar pequenas mudanças incrementais e evolutivas ao processo atual. No geral, grandes mudanças são desencorajadas, porque geralmente enfrentam resistência, devido ao medo ou à incerteza.

* **3º Princípio: Respeitar os Processos, as Funções & Responsabilidades Atuais**

    O Kanban reconhece que processos, funções, responsabilidades e títulos existentes possuem valor e, geralmente, valem a pena ser preservados. O método Kanban não proíbe a mudança, mas também não a prescreve como uma ‘panaceia universal’. É designado a promover e encorajar mudanças lógicas e incrementais, sem incitar o medo de mudança.

* **4º Princípio: Encorajar Atos de Liderança em Todos os Níveis**

    Este é o mais novo princípio Kanban. Ele o lembra de que algumas das melhores lideranças vêm dos atos diários de pessoas na linha de frente de seus times. É importante que todo mundo adote a mentalidade de melhoria constante (Kaizen), para atingir um desempenho ótimo a nível de time/departamento/empresa. Isto não pode ser uma atividade a nível de gerência.

### As 6 Práticas do Kanban

* **1ª Prática: Visualizar o Fluxo de Trabalho**

    A primeira, e mais importante, coisa para você é entender o que é necessário para mover um item de pedido para um produto entregável. Somente após entender como o fluxo de trabalho funciona atualmente, você pode melhorá-lo ao fazer os ajustes necessários. Para visualizar seu processo com um sistema Kanban, você precisará de um quadro com cartões e colunas. Cada coluna no quadro representa um passo no seu fluxo de trabalho. Cada cartão Kanban representa um item de trabalho. Quando você começar a trabalhar no item X, você o move da coluna “Pedido” e quando ele é completado, você o move para “Concluído”. Desta maneira, você pode acompanhar facilmente o progresso e visualizar os gargalos.

* **2ª Prática: Limitar Trabalho em Progresso**

    Alterar o foco do time no meio do caminho irá, em geral, prejudicar o processo, e o foco em diversas tarefas é uma rota certa para a perda de tempo e ineficiência; uma função primária do Kanban é certificar que há um número manejável de itens ativos em progresso, a qualquer dado momento. Se não houver limites de trabalho em progresso, você não está praticando Kanban. A limitação de WIP significa que um sistema puxado foi implementado em partes ou todo o fluxo de trabalho. A definição de um número máximo de itens por etapa certifica de que um cartão somente é puxado para o próximo passo quando há uma capacidade disponível para isso. Tais restrições destacarão, rapidamente, áreas problemáticas no seu fluxo para que você possa identificá-las e resolvê-las.

* **3ª Prática: Gerenciar o Fluxo**

    A ideia de implementar um sistema Kanban é criar um fluxo saudável. Por fluxo, nós estamos nos referindo ao movimento de itens de trabalho através do processo de produção. Nós estamos interessados na velocidade e suavidade do movimento. Então, a gestão do fluxo está relacionada à gestão do trabalho, mas não das pessoas. Em vez de microgerenciar as pessoas e tentar mantê-las ocupadas todo o tempo, nós devemos nos focar no gerenciamento dos processos de trabalho e entender como podemos acelerar o trabalho. Idealmente, nós queremos um fluxo rápido e tranquilo. Isto significa que nosso sistema está criando valor rapidamente. Desta maneira, nós podemos minimizar o tempo de ciclo médio para a produção, evitando o custo de atrasos, mas de maneira previsível.

* **4ª Prática: Construir Políticas de Processo Explícitas**

    Você não pode melhorar algo que não entende. É por isso que o processo deve ser definido, publicado e socializado claramente. As pessoas não associariam e participariam de algo que não acreditam ser bem-sucedido. Quando todo mundo está familiar com um objetivo comum, ela são capazes de trabalhar e tomar decisões com relação a mudanças que o moverão em uma direção positiva.

* **5ª Prática: Feedback Loops**

    Para uma mudança positiva ocorrer, ser bem-sucedida e continuar, uma coisa precisa ser feita. A filosofia Lean suporta a suposição de que reuniões regulares são necessárias para a transferência de conhecimento (feedback loops). Tais são as reuniões diárias para sincronização do time. Elas ocorrem em frente do quadro Kanban e cada membro explica aos outros o que ele/ela fez no dia anterior e o que fará hoje. Há também as reuniões de revisão de entrega de serviço, revisão de operações e revisão de risco. A frequência depende de vários fatores, mas a ideia é que elas sejam regulares, em um horário fixo, diretas ao ponto e nunca tomem mais tempo que o necessário. O tempo médio ideal para reuniões diárias deve ser de 10-15 minutos, e as outras devem atingir até uma hora, dependendo do tamanho do time e dos tópicos.

* **6ª Prática: Melhorar a Colaboração (usando modelos & o método científico)**

    A maneira para atingir melhoria contínua e mudança sustentável dentro de uma organização é através de uma visão compartilhada de um futuro melhor e o entendimento coletivo dos obstáculos que precisam ser superados. Os times que possuem um entendimento compartilhado das teorias sobre trabalho, fluxo de trabalho, processo e risco, têm uma probabilidade maior de construir uma compreensão compartilhada de um problema e sugerir passos em direção a melhorias, que podem ser aceitos em consenso.

## **XP (Xtreme Programming)**

Como vimos acima, o XP possui um conjunto de princípios e valores, onde os princípios tendem a ser mais concretos que os valores. O conjunto de valores servem como um critério que norteiam as pessoas envolvidas no desenvolvimento do software, além de se complementarem. São eles: comunicação, simplicidade, feedback, coragem e respeito.

Além desses valores, existe um conjunto de princípios que deve ser seguido por equipes que forem usar XP em projetos, sendo o feedback rápido, presumir simplicidade, abraçar mudanças, trabalho de alta qualidade, pequenos passos, melhoria, diversidade, reflexão. As práticas consistem no núcleo principal do processo. Elas evidenciam os valores que nos ajudarão a ter sucesso no projeto. São elas:

1. **Cliente presente**: O cliente deve participar ativamente do processo de desenvolvimento. Tudo precisa da comunicação com o cliente. Ele deve receber o melhor resultado possível a cada semana, ver o progresso no sistema, ser informado de mudanças de planos, etc. Escute, para que saiba qual é o problema a ser resolvido.

2. **Planejamento**: O desenvolvimento utilizando o XP é feito em iterações. Uma iteração é um período curto de tempo (1 ou 2 semanas) onde a equipe desenvolve um conjunto de funcionalidades. Sendo assim, no início da semana, desenvolvedores e clientes se reúnem para priorizar as funcionalidades. Essa reunião chama-se jogo de planejamento e nela já devem estar criadas as estórias. Se uma estória for muito grande, ela deve ser dividida em tarefas com duração máxima de alguns dias. Essas estórias devem ser escritas pelo cliente, pois assim ele consegue pensar melhor em cada funcionalidade. O planejamento é importante para que você sempre faça a coisa mais importante a ser feita.

3. **Stand Up Meeting**: São reuniões feitas em pé e de curta duração - mas muito produtiva, para que o time se mantenha alinhado, para saber o que cada um está fazendo exatamente, em que ponto está o projeto e se alguém está tendo problemas para executar suas tarefas. Ainda que apareça algum problema, essa reunião não tem o propósito de pensar em soluções.

4. **Programação em par**: É uma programação em par (dupla) em um único computador. Como é apenas um computador, o software sempre é revisto por duas pessoas diminuindo assim a possibilidade de falhas. Busca-se sempre a evolução da equipe melhorando a qualidade do código fonte. Ela é uma das práticas primordiais do XP, pois dois programadores fazendo o trabalho juntos acaba agregando muito para o trabalho em equipe.

5. **Testes constantes**: É utilizado o Desenvolvimento Orientado a Testes (Test Driven Development), o conhecido TDD. Primeiro crie os testes unitários e depois crie o código para que o teste funcione, essa abordagem é complexa no início, mas os testes unitários são essenciais para que a qualidade do projeto seja mantida.

6. **Refatoração**: É um processo que permite a melhoria contínua da programação, o mínimo de introdução de erros e mantendo compatibilidade com o código já existente. Refatorar melhora a clareza, leitura do código e facilita a manutenção. Além disso, o código fica mais coeso e você tem um melhor aproveitamento, evitando duplicação no código fonte.

7. **Padronização do código**: Como todo mundo trabalha no desenvolvimento do mesmo software, a equipe de desenvolvimento precisa estabelecer regras para programar e todos devem seguir essas regras, assim parecerá que todo código fonte foi digitado pela mesma pessoa. A padronização de código também é muito importante, porque o XP preza isso, o trabalho em equipe, se uma pessoa faz de um jeito e a outra faz de outro, isso fica muito confuso e futuramente pode ter problemas na revisão deste código.

8. **Design simples**: Essa prática se encaixa no princípio da simplicidade e é basicamente seguir o que o usuário está pedindo, por conta disso o design do software acaba sendo mais simplista. Além disso, o software acaba ficando mais fácil de ser alterado. Com essa metodologia você consegue alterar o código quando precisar, sem comprometer a qualidade.

9. **Metáfora**: Procura facilitar a comunicação com o cliente, entendendo qual a realidade dele. É preciso traduzir as palavras do cliente para o significado que ele espera dentro do projeto.

10. **Ritmo sustentável**: Manter um ritmo de trabalho com qualidade, onde eles estejam atentos e dispostos.

11. **Semana de 40 horas**: É trabalhar com qualidade buscando ter um ritmo de trabalho saudável, 40h por semana, 8h por dia, sem horas extras.

12. **Integração contínua**: Sempre que for produzido uma nova funcionalidade você nunca deve esperar uma semana para integrar com a versão atual do sistema. Isso só aumenta a possibilidade de conflitos e possibilidade de erros no código fonte. Integrar de forma contínua permite saber o status real da programação.

13. **Releases curtos**: As liberações de pequenas versões funcionais do projeto auxiliam muito no processo de aceitação por parte do cliente que já pode testar uma parte do sistema. As versões chegam ainda ser menores que as produzidas em outras metodologias incrementais, como o RUP. Os releases são pequenos pedaços do produto que são entregues ao cliente antes do tempo, assim o cliente não precisa esperar o produto todo ficar pronto para ver.

## **Lean**

Também conhecido como método enxuto, esse conceito busca eliminar os desperdícios, em diversos níveis, dentro das empresas. Seja em seus processos, gestão, administrativo, produção e outras áreas, a metodologia lean é usada para lidar com os problemas de forma sistêmica e otimizar vários pontos em um negócio.  

Tudo aquilo que não é estritamente necessário para realizar determinado trabalho é visto como excesso, que pode ser eliminado. Esse processo é feito de forma contínua dentro da organização, identificando e cortando todos os desperdícios para aumentar os resultados, entregando mais valor aos clientes.  

Existem algumas palavras-chave ao pensarmos no método enxuto:

* Qualidade/maior valor ao cliente;
* Menor tempo;
* Aprimoramento contínuo; 
* Otimização dos processos; 
* Eliminação dos desperdícios.

Essas características ajudam as empresas a repensar seus processos internos, solucionando alguns problemas, definindo prioridades e, no fim de tudo, entregando um produto ou serviço melhor ao cliente — tudo com menos gastos e elementos desnecessários. 

## **FDD (Feature Driven Deveploment)**

O FDD busca o desenvolvimento por funcionalidade, ou seja, por um requisito funcional do sistema. É pratico para o trabalho com projetos iniciais ou projetos com codificações existentes. Apesar de ter algumas diferenças entre o FDD e o XP, é possível utilizar as melhores práticas de cada metodologia. O FDD atua muito bem em conjunto com o Scrum, pois o Scrum atua no foco do gerenciamento do projeto e o FDD atua no processo de desenvolvimento.

O FDD possui cinco processos básicos.

* Desenvolvimento de modelo abrangente (Análise orientada por objetos);
* Construção de lista de funcionalidades (Decomposição funcional);
* Planejar por funcionalidade (Planejamento incremental);
* Detalhe por funcionalidade (Desenho orientado a objetos);
* Construção por funcionalidade (Programação e teste orientado a objetos).

Assim como acontece na metodologia XP, o FDD faz uso de teste de software. Desta forma é possível utilizar TDD, aliás, é indicada a utilização deste para manter a qualidade do software.

O FDD, assim como a teoria de sistemas afirma, entende que a soma das partes é maior do que o todo. Desta forma, apesar de criar um modelo abrangente baseado no todo que será desenvolvido, esta fase inicia-se com o detalhamento do domínio do negócio com divisão de áreas que serão modeladas. O modelo só está pronto quando todos da equipe estiverem de acordo, o planejamento é feito com base na lista de funcionalidades. Se fossemos trabalhar com FDD em conjunto com o Scrum, a lista de funcionalidades seria utilizada no backlog de produtos, como histórias de usuários a serem desenvolvidas.

Com base na lista de funcionalidades, deve-se planejar por funcionalidade, mas este planejamento é incremental. Isto em conjunto com o Scrum, deve ser analisado como etapa de desenvolvimento do incremento, então este planejamento é feito com base no que será desenvolvido naquele incremento.

Vamos novamente ao Scrum, separando o que será feito na Sprint. Colocamos no backlog da Sprint. O que está no backlog da sprint são funcionalidades que serão desenvolvidas durante a sprint (que pode ser de duas a quatro semanas), estas tarefas são então planejadas com maior rigor, neste ponto, temos então o planejamento incremental, ou seja, planejamos apenas o que vamos desenvolver. Nesta etapa os envolvidos no processo resumem-se apenas à equipe, ou seja, os desenvolvedores, analistas, testadores, etc., que vão atuar no processo. Eles devem selecionar os itens com base no tempo que eles possuem e nas qualificações atuais da equipe.

Após o planejamento, é feito o detalhamento, nesta fase é de extrema importância que o desenho esteja de acordo com o que o cliente deseja, então é mantido contato constante com o cliente, como em todas as metodologias ágeis.

Esta documentação é a base para o desenvolvimento, não deve-se perder tempo com documentação que não será utilizada, mas é necessário documentar.

Posteriormente inicia-se a fase de desenvolvimento, esta fase é a etapa de desenvolvimento e teste real.

O desenvolvimento também é incremental, e indica-se a utilização de testes do início ao fim do processo, além da utilização de integração continua.

Um ponto que diverge do XP é que no FDD é incentivado o desenvolvedor como único responsável pelo módulo que este desenvolve, já no XP, o código é comunitário.

![FDD](https://arquivo.devmedia.com.br/artigos/Fabio_Gomes_Rocha/FDD/FDD1.jpg)
Figura 1: Integração contínua

A utilização da integração continua permite que a equipe esteja em contato constante com o cliente, tornando o processo ágil e com entregas constantes.

Como cada fase apresentada acima é específica e curta, e as fases se completam, são necessários relatórios para manter o controle, para analisar a quantidade de recursos que estão sendo desenvolvidos, semelhante ao burndow e o burnup do Scrum.

Segundo a metodologia, o percentual de tempo gasto em cada etapa é:

* Levantamento do domínio da aplicação = 1%;
* Projeto = 40%;
* Inspeção do projeto = 3%;
* Desenvolvimento = 45%;
* Inspeção do código = 10%;
* Integração = 1%.

Além disso, o FDD possui as chamadas melhores práticas que indicam boas práticas ao desenvolver com o FDD, são elas:

* Modelagem Orientada a Objetos do Domínio;
* Desenvolvimento por funcionalidade;
* Classe proprietária, ou seja, a unidade é feita individualmente, evitando-se assim conflitos na equipe;
* Equipes de recursos: são equipes pequenas, destinadas a desenvolver recursos necessários ao projeto, de forma secundária;
* Inspeção é realizada constantemente para garantir a boa qualidade do código e do projeto;
* Gerenciamento de configuração;
* Integração contínua para demonstrar constantemente as funcionalidades ao cliente e;
* Visibilidade de progressos e resultados.

## Crystal

Segundo o criador Cockburn, as pessoas de uma equipe possuem diferentes talentos e habilidades, sendo um diferencial durante o desenvolvimento de um projeto, já que as pessoas têm uma importância muito grande no desempenho do projeto. Além disso, foi criada para atender vários tipos de projetos e equipes que precisam de táticas para resolver diversos problemas.

Não há uma metodologia Crystal e sim diferentes tipos de metodologia Crystal para diferentes tipos de projeto, por isso chamamos de família Crystal. É uma família de metodologias que une diferentes modelos de processo, mas com elementos centrais que são comuns a todas, além dos papéis e práticas específicas de cada uma.

Segundo os autores da metodologia, acredita-se que a metodologia adequada é baseada no tamanho da equipe e nos riscos envolvidos no projeto. Por isso, a família Crystal é dividida em cores, onde deve-se escolher a cor que mais for apropriada para cada projeto, de acordo com o nível de criticidade e o tamanho da equipe. Quanto mais escura for a cor, mais crítico é o sistema e, consequentemente, será utilizada a metodologia mais “pesada”.

Por exemplo, um projeto com 50 pessoas envolvidas precisa de uma metodologia mais pesada do que um projeto com 10 pessoas. Você pode avaliar seu projeto por duas visões: número de pessoas e criticidade do sistema.

A criticidade é dividida em 4 níveis: (C) conforto, (D) baixo custo, (E) alto custo e (L) risco de vida. Assim você consegue escolher a melhor metodologia para aquele projeto, adotando um conjunto de políticas adequadas para cada situação.

Algumas práticas da metodologia são:

* a entrega em intervalos regulares;
* o monitoramento do progresso;
* envolvimento direto com o cliente;
* inspeções constantes a cada incremento;
* os feedback que servem para ajuste do produto e da metodologia caso necessário.

Você pode utilizar as metodologias da família Crystal em projetos de alta ou baixa criticidade. A ideia de Crystal é permitir que cada organização implemente as atividades que lhe pareçam adequadas.

## **ASD (Adaptive Software Development)**

Adaptive Software Development (ASD) ou Desenvolvimento de Software Adaptativo é uma técnica para o desenvolvimento de softwares, proposta por Jim Highsmith. Este modelo concentra-se na colaboração humana e na auto-organização da equipe. Tem foco de atuação principalmente nos problemas de sistemas complexos, para grandes desenvolvimentos. O método estimula fortemente o desenvolvimento com repetições e uma constante prototipação.

Bem como em metodologias ágeis, sua operação é em ciclos e em cada interação ocorrerão certas mudanças e até alguns erros. Este ciclo fornece aprendizado e adaptação contínuos ao estado emergente do projeto.

Baseado no ciclo de aprendizado colaborativo, o ASD define o seu ciclo de vida para projetos, isso faz com que os ciclos colaboração e aprendizado - que veremos mais à frente, sejam preenchidas com as suas respectivas práticas. Nesse sentido, o aprendizado é um elemento-chave para que possamos conseguir uma equipe auto-organizada.

### Características do metodologia ASD

* **Focado na missão:** objetivos muito bem definidos, porém podem ser ajustados de acordo com o desenvolvimento do projeto;

* **Orientado a riscos**;

* **Orientado a componentes:** as atividades de desenvolvimento não devem ser orientadas a tarefas, mas, focadas nas funcionalidades do desenvolvimento do software;

* **Iterativo**;

* **Tolerante a mudanças:** incorpora as mudanças que aparecem no meio do projeto. Como é algo frequente em desenvolvimento de software, é mais importante se adaptar à elas ao invés de tentar controlar.

### Ciclo de vida do modelo

Um projeto de ASD é composto por um ciclo de três fases:

* **Especulação:** Nessa fase o projeto é iniciado e se estabelecem os principais objetivos e metas do projeto, requisitos básicos que serão necessários e as limitações com as quais você trabalhará. Após completar cada ciclo tudo é revisto e ajustado, podendo sofrer mudanças. Tudo isso para que o projeto esteja na realidade que a equipe está trabalhando.

* **Colaboração:** A colaboração ajuda bastante no levantamento de necessidades, especificações, etc. Por isso, deve-se existir confiança, ter críticas construtivas, trabalho árduo e promover a comunicação dos problemas e em atitudes que contribuem para o trabalho em equipe.

* **Aprendizado:** consiste na compilação de tudo o que foi aprendido do início até o final, o que foi bom e o que foi ruim para que possamos melhorar no futuro.

### Vantagens:

* É utilizada para aprender com os erros e iniciar o ciclo de desenvolvimento novamente

* Utiliza as informações sobre as mudanças para melhorar o desempenho do software

* Promove o trabalho em equipe

### Desvantagens:

Erros que não são detectados anteriormente afetará a qualidade do produto e consequentemente no custo
