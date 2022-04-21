# Anotações das Aulas 1 à 4
#### Aula 1: Pilares do Pensamento Computacional
**Decomposição**: Dado um problema complexo devemos quebrá-lo em problemas menores. Portanto mais fáceis e gerenciáveis.
Processo de quebrar e determinar partes menores e gerenciáveis: **Análise**
Combinar os elementos recompondo os problemas originais: **Síntese**
Ordem de execução de tarefas menores: *Sequencial* (em fila, dependentes); *Paralelo* (ao mesmo tempo). 
Como decompor? Identificar ou coletar dados > Agregar os dados > Funcionalidade > Decomposição
Reconhecimento de Padrões: Modelo base, Estrutura Invariante e Repetição

Como o computador reconhece/simula padrões? Representação de atributos, Aprendizado: conceito associado ao objeto, Armazenar dados, Regras de decisão. 
Aplicações: Classificação de dados, reconhecimento de imagem, reconhecimento de fala, análise de cenas, classificação de documentos.
Machine Learning, Redes Neurais, Inteligência Artificial e Ciência de Dados]

**Abstração**: Processo intelectual de isolamento de um objeto da realidade
**Generalização**: na lógica, é a operação intelectual que consiste em reunir numa classe geral, um conjunto de seres ou fenômenos similares.
Pontos Essenciais > Representação

**Algoritmos**: Pensamento Computacional
**Processamento de Dados**: o computador recebe, manipula e armazena dados. 
*Resolução de problemas Step By Step* conforme o que o programador determinou
**Algoritmo**: Descreve o problema por meio de ferramentas narrativas, fluxograma ou pseudocódigo. É uma sequência de passos com objetivos definidos para execução de tarefa específicas e conjunto de operações que resulta em um sucessão finita de ações. Instruções executadas passo a passo para concluir a tarefa.
Como construir um algoritmo; Compreensão do problema, Definição de dados de entrada, Definir processamento, Utilizar um método de construção, Teste e Diagnóstico.


#### Aula 2: Introdução à Lógica e a Programação
***Programar é resolver problemas***
O que é lógica? 
Coerência de raciocínio, de ideias,..., sequência coerente, regular e necessária de acontecimento, coisas.
**Lógica de Programação**: Significa apenas contextualizar a lógica na programação de computadores, buscando a melhor sequência de ações para solucionar um problema.
Metacognição
**Abstração**: Habilidade de concentrar nos aspectos essenciais de um contexto qualquer, ignorando características menos importantes ou acidentais.

**Algoritmos e Pseudocódigo**
Algoritmo: é uma sequência de passos que resolve um problema.

Pseudocódigo: é uma forma genérica de escrever um algoritmo, utilizando linguagem simples (nativa, ou seja, em português ou idioma de quem o escreve, de forma a ser entendida por qualquer pessoa).

**Fluxograma, Variáveis e Constantes**
Fluxograma: é uma ferramenta utilizada para representar graficamente um algoritmo, isto é, a sequência lógica e coerente do fluxo de dados. É também um tipo de diagrama e pode ser entendido como uma representação esquemática de um processo. Podemos entendê-lo, na prática, como a documentação dos passos necessários para a execução de um processo qualquer. 

Variáveis: Na programação, uma variável é um objeto (uma posição, frequentemente localizada na memória) capaz de reter e representar um valor ou expressão. Também definido como: um espaço na memória do computador destinado a um dado que é alterado durante a execução do algoritmo. 
Exemplo utilizado: notas médias escolares
As variáveis e as constantes podem ser classificadas basicamente de quatro tipos: numéricas, caracteres, alfanuméricas ou lógicas (verdadeiro ou falso, sim ou não).
As constantes são valores imutáveis e não são alterados durante a vida útil do programa.
Exemplo: o valor de pi=3,14, raio, etc.
Site download Flowgorithm: http://www.flowgorithm.org/ 

*Exercícios práticos de criação de fluxograma no Flowgorithm*
**Expressões Aritméticas**: são expressões que utilizam operadores aritméticos e funções aritméticas envolvendo constantes e variáveis. Ex: 50+50; total+50.
**Operadores aritméticos**: soma +, subtração -, multiplicação * , divisão /, potenciação ^, porcentagem %.
**Expressões literais**: são expressões com constante e/ou variáveis que tem como resultado valores literais. Iremos utilizar as expressões literais na atribuição de valor para uma variável ou constante. Ex: nome=”José da Silva”, media=(nota1+nota2+nota3+nota4)/4.
**Expressões Relacionais**: são expressões compostas por outras expressões ou variáveis numéricas com operadores relacionais. As expressões relacionais retornam valores lógicos (verdadeiro/falso).
**Tomadas de Decisão**: necessidade de decidir o que fazer dependendo de alguma condição encontrada durante a execução.
**Concatenação**: É um termo usado em computação para designar a operação de unir o conteúdo de duas strings*. (*string é uma sequência de caracteres). Agrupamento de duas ou mais células que, incluindo fórmulas, textos ou outras informações contidas no seu interior, dá origem a um único resultado.
Exemplo: Flowgorithm: Entrada de nome, sobrenome e idade. Como se fosse uma conversa com o usuário. Concatenação é útil para criar exibições para usuário. 

*INTRODUÇÃO AO PORTUGOL*
**Estrutura de Repetição**: Dentro da lógica de programação é uma estrutura que permite executar mais de uma vez o mesmo comando ou conjunto de comandos, de acordo com uma condição ou um contador.
**LINGUAGENS DE PROGRAMAÇÃO**: É uma linguagem escrita e formal que especifica um conjunto de instruções e regras usadas para gerar programas (software). Um software pode ser desenvolvido para rodar em um computador, dispositivo móvel ou em qualquer equipamento que permita sua execução.
“O que é óbvio para você, certamente não é óbvio para uma máquina. E se você quer que a máquina faça algo para você, você precisa, ‘falar com ela’.”
**A função das linguagens de programação é servir como um meio de comunicação entre computadores e humanos.**
Linguagem **Alto Nível**: São aquelas cuja sintaxe se aproxima mais da nossa linguagem e se distanciam mais da linguagem de máquina. (Javascript, Phyton, C++, etc)
Linguagem **Baixo Nível**: É aquela que se aproxima mais da linguagem de máquina. Essas são as que você precisa ter o conhecimento direto da arquitetura do computador para fazer alguma coisa. (Assembly)
**Compiladas**: é uma linguagem de programação em que o código fonte, é executado diretamente pelo sistema operacional ou pelo processador, após ser traduzido por meio de um processo chamado compilação. (C++, etc)
**Interpretadas**: é uma linguagem de programação em que o código fonte é executado por um programa de computador chamado interpretador, que em seguida é executado pelo sistema operacional ou processador. (Javascript, Phyton, etc)
**PORTUGOL**: É uma pseudo linguagem que permite ao leitor desenvolver algoritmos estruturados em português de forma simples e intuitiva, independentemente de linguagem de programação. Permite ao programador pensar no problema em si e não no equipamento que irá executar o algoritmo. 
Baixar Portugol: https://github.com/UNIVALI-LITE/Portugol-Studio/releases/

*Exercícios no Portugol*
DESVIOS CONDICIONAIS E COMENTÁRIOS - PORTUGOL
**SE**: É utilizada a palavra reservada se, a condição a ser testada entre parênteses e as instruções que devem ser executadas entre chaves caso o desvio seja verdadeiro”. Ex: se(media>=7){escreva(“Parabéns! Você foi aprovado!”)}
**SE-SENAO**: Se a condição for falsa um outro conjunto de comandos deve ser executado. Ex: senao{escreva(“Infelizmente você foi reprovado!")
Adicionar comentários: usar // (ideal para explicar a função, etapa e para que serve o algoritmo que você criou: boa prática profissional, já que outras pessoas vão usar o seu algoritmo).
**CASO**: Este comando é similar ao se e senao, e reduz a complexidade na escolha de diversas opções. Apesar de suas similaridades com o se, ele possui algumas diferenças.
**LAÇOS/ESTRUTURA DE REPETIÇÃO** NO PORTUGOL: Dentro da lógica de programação é uma estrutura que permite executar mais de uma vez o mesmo comando ou conjunto de comandos, de acordo com uma condição ou um contador.
**MATRIZES E VETORES**
Uma matriz é uma coleção de variáveis de mesmo tipo, acessíveis com um único nome e armazenados contiguamente na memória. A individualização de cada variável de um vetor é feita através de uso de índices. Os vetores são matrizes de uma só dimensão.


#### Aula 3: Git e GitHub
**Git**: sistema de versionamento de código distribuído, criado em 2005 pelo Linus Torvalds.
**GitHub**: empresa da Microsoft, que serve como um repositório complementar do Git.
Serve para: Controle de versão, armazenamento em nuvem, trabalho em equipe, melhorar seu código, reconhecimento do seu trabalho. 
*Navegação básica no terminal & instalação*
GUI(Graphic User Interface)  x CLI (Linha de comando, digitação)
Diferenças de comando Git: Windows vs.Unix (Mac, Linux, etc)
**REALIZANDO A INSTALAÇÃO DO GIT**
site:https://git-scm.com/ (Instalação no Linux e no Mac também é diferente, mas tem tudo explicado no site).

TÓPICOS FUNDAMENTAIS PARA ENTENDER O FUNCIONAMENTO DO GIT
**SHA1**: Significa Secure Hash Algorithm (algoritmo de hash seguro), é um conjunto de funções hash criptográficas projetadas pela NSA. A encriptação gera conjunto de caracteres identificador de 40 dígitos.
Objetos Internos do Git: **Blobs, Trees, Commits**
**CHAVES SSH e Tokens**: criar conta no github 
**Chave SSH** é o cadastro da máquina local, a que eu estou usando, como uma máquina confiável no Github. São duas chaves, uma pública e uma privada.
**Tokens de Acesso Pessoal**: Gera um token no GitHub e guardar num drive, ou email. 

COMANDOS GIT
**git init**
**git add**
**git commit**
**git status**
**ls**
(Para abrir uma pasta existente digitar o código cd nomedapasta/) 
Para adicionar a modificação no git: **git add**. Depois checar com **git status** 

*Exercícios no Git*

(Git é um repositório local, a sua máquina, o ambiente de desenvolvimento. O GitHub é um repositório remoto, onde outros desenvolvedores podem ter acesso ao código que você criou e/ou realizar o trabalho em equipe.)

*Exercícios criação de repositório no GitHub*

#### Aula 4: Introdução ao SCRUM
Processo de Desenvolvimento de um software: concepção, análise e design, desenvolvimento, teste e implantação.
Em projetos tradicionais (Waterfall), você corre o risco de descobrir que estava errado depois de meses. Com o SCRUM, você descobre que estava errado em no máximo 30 dias. O QUE É SER ÁGIL? A agilidade, nesse sentido, é fazer coisas complexas de forma simples e ter capacidade de responder rapidamente a mudanças. 
SCRUM é um dos frameworks de gerenciamento de gerenciamento de projetos ágeis.
Projetos usando equipes pequenas e multidisciplinares produzem os melhores resultados.
Características do time SCRUM: equipes capazes de se auto-organizarem; as tarefas são do time e todos são responsáveis; forte comprometimento com os resultados. 
Start-Ups utilizam muito o framework ágil porque trabalham com MVP (minimum viable product): vai evoluindo conforme o feedback de usuários.

PAPÉIS E RESPONSABILIDADES DE CADA UM DO TIME SCRUM
**Product Owner (PO)**: o dono do produto, representante da área de Negócios, PO não é um comitê, define as funcionalidades do software (Product Backlog), prioriza as funcionalidades de acordo com o valor do negócio, garante que o time de desenvolvimento entendas os itens do Backlog no nível necessário. 
**Scrum Master (SM)**: garantir o uso correto do SCRUM, Scrum Master não é Gerente de Projetos, age como um facilitador, auxilia o Product Owner no planejamento e estimativas do backlog, auxilia a equipe a remover impedimentos, treina o time em autogerenciamento e interdisciplinaridade. 
**Time de Desenvolvimento (DEV)**: de 3 a 9 pessoas, multidisciplinar, possui habilidades suficientes para desenvolver, testar, criar e desenhar, ou seja, tudo que for necessário para entregar o software funcionando.

CERIMÔNIAS DO SCRUM
**Time Box**: tempo máximo para fazer uma cerimônia ou Sprint. **Sprint**, corrida ou arrancada, é o principal evento do SCRUM, tem duração de 30 dias corridos ou menos. A composição da Sprint: planejamento da sprint, reuniões diárias (daily meeting), revisão da sprint (review) e retrospectiva da sprint. Daily meeting time-box, ou stand up meeting: 15 minutos. 
Time DEV apresenta para o PO o trabalho feito. Time Box: 4h (Sprint 30 dias).
Reunião da equipe para Lições Aprendidas: Transparência. Time Box: 3h (Sprint 30 dias).

FUNDAMENTOS DE UM PROJETO ÁGIL
Gestão de Projetos Ágeis com SCRUM
Papéis e responsabilidades - Product Owner: O Product Owner (PO) representa o profissional que tem a visão do que será desenvolvido, as necessidades a serem atendidas, o público que vai utilizar os serviços e os objetivos a serem alcançados. O PO é quem entende a demanda e extrai o maior valor possível. **Refining e Planning**.
**Release Planning**: liberação ou lançamento de software ou de nova versão oficial de produto de software. Cada vez que um produto de software é criado ou modificado, o fabricante e seus desenvolvedores decidem sobre como distribuir o novo produto ou a modificações às pessoas que o utilizam.
Existem 2 tipos de Release Planning: Release Planning de Múltiplas Squads e Release Planning de Projeto.
ANALISANDO O ESCOPO E DEFININDO PRIORIDADES
**Product Backlog**: é composto por **épicos e estórias**. Épicos: incremento sem muito detalhamento, ajuda a te direcionar para os caminhos que deve seguir. Estória: detalhamento dos épicos. Um épico normalmente se divide em várias estórias, onde ficam descritos o que deve acontecer e suas regras de negócio.
PAPEL DO PO NA TRANSFORMAÇÃO DIGITAL
A transformação digital é um processo no qual as empresas fazem uso da tecnologia para melhorar o desempenho, aumentar o alcance e garantir resultados melhores. É uma mudança estrutural nas organizações dando um papel essencial para a tecnologia.
CONCEITOS E PLANEJAMENTO DE TAREFAS: tarefa > estória > épico.
Critérios de Aceite: é uma lista de critérios que precisam ser alcançados para que a User Story atenda os requisitos do usuário e seja aceita pelo Product Owner. Os critérios de aceitação têm o objetivo de definir limites para as user stories. Ajudar o PO a detalhar em alto nível o que é necessário para entregar valor ao cliente. 
Estimativa e Planejamento: Planning Poker, mensuração do esforço e complexidade das tarefas ou estórias.  
CLIENTE / STAKEHOLDER: é uma pessoa ou grupo que legitima as ações de uma organização e que tem um papel direto ou indireto na gestão e resultados dessa mesma organização. Desta forma, um stakeholder pode ser afetado positiva ou negativamente, dependendo das suas políticas e formas de atuação. Alguns exemplos de stakeholder de uma empresa podem ser os seus funcionários, gestores, gerentes, proprietários, fornecedores, concorrentes, ONGs, clientes, o Estado, credores, sindicatos e diversas outras pessoas ou empresas que estejam relacionadas com uma determinada ação ou projeto.
ROTINAS DE UM TIME ÁGIL
Daily e Retrospectiva: stand-up meeting (time de desenvolvimento), retro (time de desenvolvimento e o scrum master). Refinamento (time dev, sm e po). Sprint Review Meting (o time dev apresenta o produto desenvolvido para o sm, o po, stakeholders e todos os interessados.)
