# Engenharia de Requisitos

Etapas da engenharia de requisitos:

**Existem quatro atividades principais do processo de engenharia de requisitos:**

***1. Estudo de viabilidade.*** ***É feita uma estimativa acerca da possibilidade de se satisfazerem as necessidades do usuário identificado usando-se tecnologias atuais de software e hardware.** Verifica se é rentável.*

***2. Elicitação e análise de requisitos. Esse é o processo de derivação dos requisitos do sistema por meio da observa­ção dos sistemas existentes, além de discussões com os potenciais usuários e compradores, análise de tarefas, entre outras etapas.*** Pode envolver desenvolvimento ou prototipação de alguns módulos.

***3. Especificação de requisitos.*** ***É a atividade de traduzir as informações obtidas durante a atividade de análise em um documento que defina um conjunto de requisitos.*** Incluem-se requisitos de usuário e de sistema.

***4. A validação de requisitos.*** ***Essa atividade verifica os requisitos quanto a realismo, consistência e completude.*** Verifica erros na documentação.

---

**O gerenciamento de requisitos é o processo de compreensão e controle das mudanças nos requisitos do sistema.**

---

Tipos de requisitos

Os requisitos de negócio são elaborados em atividades de análise de negócio, anteriores a criação do projeto.

Requisitos funcionais e não-funcionais, respectivamente: o que um sistema deve fazer **E**

sob que restrições.

*R**equisitos de sistema:** referem-se à especificação técnica e detalhada das ações, condições e restrições operacionais do software. Para programadores.*

***Requisitos de usuário**: são declarações, em uma linguagem natural com diagramas, de quais serviços o sistema deverá fornecer a seus usuários e as restrições com as quais este deve operar. Para o cliente e usuário final do sistema.*

Um ator é um agente que assume um papel específico em um caso de uso. Pode ser uma pessoa ou um dispositivo que usa o sistema. *Usuário é diferente de ator.*

**Requisitos funcionais (comportamento)**

- São declarações de serviços que o sistema deve fornecer, de como o sistema deve reagir e de como o sistema deve se comportar em determinadas situações.
- Em alguns casos, os requisitos funcionais também podem explicitar o que o sistema não deve fazer.
- **Completude:** todos os serviços requeridos pelo usuário devem ser definidos.
- **Consistência:** os requisitos não devem ter definições contraditórias.

**Requisitos não funcionais (restrição do produto/processo)**

- São restrições aos serviços ou funções oferecidos pelo sistema.
- Sub-classificado em:  requisitos de produto, requisitos organizacionais e requisitos externos.
- Incluem restrições de timing, restrições no processo de desenvolvimento e restrições impostas pelas normas.
- São requisitos que não estão diretamente relacionados com os serviços oferecidos pelo sistema a seus usuários.
- Eles podem estar relacionados às propriedades emergentes do sistema, como confiabilidade, tempo de resposta, SEGURANÇA e ocupação de área.

**Requisitos de usuário**: eles devem especificar somente o comportamento externo do sistema. O documento de requisitos não deve incluir detalhes da arquitetura ou projeto do sistema.

**Requisitos de sistema** são versões expandidas dos requisitos de usuário. Devem descrever apenas o comportamento externo do sistema e suas restrições operacionais. Eles não devem se preocupar com a forma como o sistema deve ser projetado ou implementado.

---

Elicitação de requisitos - Técnicas

**A** casos de uso são técnicas eficazes para elicitar requisitos ligados à interação do usuário com o sistema **(casos de uso)**. No entanto, não são tão eficazes para descobrir requisitos não funcionais ou requisitos de negócios.

- *Uma variante de caso de uso é um cenário que apresenta as visões do usuário, esta apresenta informações mais detalhadas e fácil compreensão.*
    - Cenários descrevem a interação entre o usuário e o sistema.
    - uma técnica de elicitação de requisitos é a utilização de **cenários** que descrevem uma situação **REAL** que o usuário conhece do seu cotidiano, facilitando que o mesmo expresse facilmente o que faz e, portanto, o que deseja do sistema.

**C** a etnografia é uma técnica de observação na qual um analista faz uma imersão no ambiente de trabalho em que o sistema será usado com o objetivo de compreender os processos operacionais e extrair os requisitos de apoio para esses processos.

**D** uma técnica de elicitação de requisitos é a utilização de entrevistas que costumam ser uma mistura de abordagens fechadas e abertas. No primeiro caso, é utilizado um conjunto predefinido de perguntas e, no segundo caso, não existe uma agenda predefinida.

Ponto de vista: especificação das diferentes visões 

---

**Obtenção de Requisitos**

Destaca três tipos genéricos de pontos de vista, os quais podem ser utilizados como um meio de classificação de *stakeholders* e outras fontes de requisitos.

- ***Pontos de vista de interação**:*
    
    *representam **pessoas ou outros sistemas que interagem diretamente com o sistema**. No sistema de caixa eletrônico bancário, exemplos de pontos de vista de interação são os clientes do banco e o banco de dados de contas bancárias.*
    
- ***Pontos de vista indiretos**:*
    
    *representam os stakeholders que **não usam o sistema diretamente, mas que influenciam** os requisitos de alguma forma. No sistema de caixa eletrônico bancário, exemplos de pontos de vista indiretos são a gerencia do banco e o pessoal de proteção do banco.*
    
- ***Pontos de vista de domínio**:*
    
    *representam **características e restrições de domínio que influenciam os requisitos do sistema.** No sistema de caixa eletrônico bancário, um exemplo de vista de domínio são os padrões desenvolvidos para comunicação entre bancos.*
    

---

**Desenvolvimento de sistemas**

Um processo de desenvolvimento de software mostra planejamento, projeto, codificação e implantação.

O processo para **desenvolvimento dos requisitos** consiste em três passos:

- **Organizar** os requisitos das partes interessadas em um escopo da solução: foco na abrangência e sem profundidade ainda.
- **Desenvolvimento** dos requisitos das partes interessadas, resolução de conflitos, eliminação de redundâncias e superação de lacunas de informação.
- **Fechar** um pacote de requisitos com a profundidade suficiente para encaminhar um conjunto de especificações para atualizar a arquitetura; implementar e testar as unidades que compõem o software.

**Teste de requisitos**

A validação de software ou, mais genericamente, a verificação e validação (V & V).

**Verificação**: é um conjunto de tarefas que garante que o software implemente corretamente uma **função especifica**. *”Estamos construindo certo o produto?”. O que é feito: “inspeções e revisões a cada estágio do processo de software, desde a definição de requisitos de usuário até o desenvolvimento do programa.” atende a seus requisitos funcionais e não funcionais.*

**Validação**: é um conjunto de tarefas que asseguram que um software foi criado e pode ser rastreado segundo os requisitos do **cliente (expectativas do cliente)**. *”Estamos construindo o produto certo?”. Demonstrar **ACEITAÇÃO** das PARTES INTERESSADAS. **O teste de validação proporciona a garantia final de que o software satisfaz a todos os requisitos funcionais, comportamentais e de desempenho.***

**Teste de integridade: erros associados às interfaces.**

**Teste de unidade) Foca em cada componente individualmente,**

**Teste Alfa**: Semelhante ao **teste de aceitação,** o teste alfa usa o sistema de forma não planejada disponibilizando o sistema para um pequeno grupo de pessoas. **aceitação interna**.

**Teste Beta:** Realizado por um grande número de pessoas, a execução do sistema ocorre de forma não planejada por pessoas desconhecidas, que não possuem nenhuma relação com a equipe ou empresa desenvolvedora. Frequentemente o teste é utilizado como uma forma de **aceitação externa.** 

**Teste de sistema: *O teste de sistema verifica se todos os elementos se combinam corretamente e se a função e o desempenho globais do sistema são obtidos.***

O teste de regressão possui como conceito chave a reexecução de um mesmo conjunto de testes.

Teste de inpeção: Metodo de analise estatica para verificar a qualidade de um produto de software.

Teste de estresse: queremos testar um software além de suas forças (**recursos computacionais em quantidades, frequência ou volumes anormais**) é

Os testes de usabilidade visam avaliar o grau com que os usuários podem interagir com as aplicações

*Os testes de carga visa determinar se aplicação conseguirá responder de forma satisfatória a várias condições de carga, tais como número de usuários utilindo recursos ao mesmo tempo, transações, dentre outras coisas, sem ir além das forças da aplicação.*

***Os testes de desempenho** avaliam o desempenho de um sistema sob uma carga de trabalho específica. Esses testes **ajudam a medir a confiabilidade, a velocidade, a escalabilidade e a capacidade de resposta de um aplicativo**. **Por exemplo, o teste de desempenho pode observar tempos de resposta ao executar um grande número de solicitações, ou ver como o sistema se comporta com quantidade significativa de dados.** Ele pode determinar se um aplicativo atende aos requisitos de desempenho, localizar gargalos, medir a estabilidade durante picos de tráfego e muito mais.*

*Os testes funcionais têm como foco os requisitos de negócios de uma aplicação. Eles só verificam a saída de uma ação e não verificam os estados intermediários do sistema ao executar essa ação.*

---

Métricas

**VELOCIDADE**

Transações processadas/segundo

Tempo de resposta de usuário/evento

Tempo de atualização de tela

**TAMANHO**

Megabytes

Número de chips de memória ROM

**FACILIDADE DE USO**

Tempo de treinamento

Número de frames de ajuda

**CONFIABILIDADE (quanto tempo o sistema pode operar sem a ocorrências de falhas.)**

Tempo médio para falha

Probabilidade de indisponibilidade

Taxa de ocorrência de falhas

Disponibilidade

**ROBUSTEZ**

Tempo de reinício após falha

Percentual de eventos que causam falhas

Probabilidade de corrupção de dados em caso de falha

**PORTABILIDADE**

Percentual de declarações dependentes do sistema-alvo

Número de sistemas-alvo

---

**Projeto e implementação de software**

1. Projeto de arquitetura, no qual você pode identificar a estrutura geral do sistema, os componentes principais
(algumas vezes, chamados subsistemas ou módulos), seus relacionamentos e como eles são distribuídos.
2. Projeto de interface, no qual você define as interfaces entre os componentes do sistema. Essa especificação de interface deve ser inequívoca. Com uma interface precisa, um componente pode ser usado de maneira que outros componentes não precisam saber como ele é implementado. Uma vez que as especificações de interface são acordadas, os componentes podem ser projetados e desenvolvidos simultaneamente.
3. Projeto de componente, no qual você toma cada componente do sistema e projeta seu funcionamento. Pode-se tratar de uma simples declaração da funcionalidade que se espera implementar, com o projeto específico para cada programador. Pode, também, ser uma lista de alterações a serem feitas em um componente reusável ou um modelo de projeto detalhado. O modelo de projeto pode ser usado para gerar automaticamente uma implementação.
4. Projeto de banco de dados, no qual você projeta as estruturas de dados do sistema e como eles devem ser representados em um banco de dados. Novamente, o trabalho aqui depende da existência de um banco de dados a ser reusado ou da criação de um novo banco de dados.

---

Estrutura

(1) Processo de teste

(2) Rastreabilidade de requisito

(3) Itens testados

(4) Cronograma de testes

(5) Procedimento de registro de testes

(6) Requisitos de *hardware* e *software*

(7) Restrições

Características

( 4  ) cronograma global de testes e alocação de recursos para esse cronograma, obviamente vinculado ao cronograma mais geral de desenvolvimento de projeto.

( 7  ) restrições que afetam o processo de teste, como falta de pessoal, devem ser antecipadas nesta seção.

( 1  ) descrição das fases principais do processo de teste.

(  2  ) usuários são os mais interessados em que o sistema atenda a seus requisitos e que os testes sejam planejados de maneira que todos os requisitos sejam individualmente testados.

(  3 ) produtos do processo de software a serem testados devem ser especificados.

(  5 ) não é suficiente realizar simplesmente os testes, os resultados dos testes devem ser sistematicamente registrados.

( 6  ) esta seção deve estabelecer as ferramentas de *software* necessárias e a utilização estimada de *hardware.*