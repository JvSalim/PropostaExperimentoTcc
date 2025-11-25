# Plano de Experimento  
**EXP-IA-US-TESTES-2025**

---

## 1. Identificação básica

### 1.1 Título do experimento

Avaliação experimental do uso de ferramentas de inteligência artificial no entendimento de user stories e na geração de testes automatizados.

### 1.2 ID / código

EXP-IA-US-TESTES-2025

### 1.3 Versão do documento e histórico de revisão

Versão atual do documento: v1.0.  
Histórico de revisão:  
v1.0 – elaboração inicial do plano de experimento para o TCC.

### 1.4 Datas (criação, última atualização)

Data de criação do plano de experimento: 23/11/2025.  
Data da última atualização desta versão: 23/11/2025.

### 1.5 Autores (nome, área, contato)

Autor: João Victor Salim Ribeiro Guimarães Trad.  
Área: Engenharia de Software.  
Vínculo: Estudante do sexto período de Engenharia de Software na Pontifícia Universidade Católica de Minas Gerais (PUC Minas).  
Contato: joao.trad@sga.pucminas.br

### 1.6 Responsável principal (PI / dono do experimento)

Responsável principal (PI) pelo experimento: João Victor Salim Ribeiro Guimarães Trad, estudante do sexto período de Engenharia de Software na Pontifícia Universidade Católica de Minas Gerais, responsável por todas as decisões científicas e operacionais do estudo.

### 1.7 Projeto / produto / iniciativa relacionada

Este experimento está diretamente relacionado ao Trabalho de Conclusão de Curso em Engenharia de Software, cujo tema versa sobre o uso de ferramentas de inteligência artificial para apoiar o entendimento de requisitos expressos como user stories e a geração de testes automatizados. O estudo está inserido em uma iniciativa acadêmica maior de investigação sobre o impacto de ferramentas de IA no processo de desenvolvimento e qualidade de software, tema de alta relevância na indústria de tecnologia e na formação de engenheiros de software contemporâneos.

Do ponto de vista de produto, o experimento estará associado a um ou mais sistemas de pequeno porte utilizados como base de testes, tais como uma API de serviços, um módulo de aplicação web ou um conjunto de katas de programação, que servirão de sistema sob teste para os participantes gerarem testes automatizados. Esses sistemas serão organizados em repositórios controlados (por exemplo, em uma plataforma de versionamento como GitHub ou GitLab), vinculados explicitamente ao código do experimento EXP-IA-US-TESTES-2025, de forma a permitir replicação e reutilização em estudos futuros.

---

## 2. Contexto e problema

### 2.1 Descrição do problema / oportunidade

O desenvolvimento de software em ambientes ágeis costuma ser guiado por user stories, que descrevem o que o sistema deve fazer do ponto de vista do usuário, acompanhadas ou não de critérios de aceitação. Na prática, muitos estudantes e desenvolvedores iniciantes têm dificuldade em transformar essas histórias em casos de teste bem estruturados e em testes automatizados que realmente cubram os cenários importantes do negócio. Ao mesmo tempo, ferramentas de inteligência artificial que apoiam programação e testes, como assistentes de código e modelos de linguagem acessados via navegador, começaram a ser utilizadas espontaneamente por estudantes sem que exista clareza sobre o impacto real desse uso na compreensão das user stories e na qualidade dos testes gerados.

O problema central é que ainda não está claro se o uso dessas ferramentas de inteligência artificial ajuda os estudantes a entender melhor as user stories e a elaborar testes mais completos, ou se apenas acelera a escrita de código e de testes de forma superficial, deixando buracos na cobertura de cenários. Sinais observados em atividades práticas são, por exemplo, testes copiados e adaptados da ferramenta de IA sem relação precisa com os critérios de aceitação, repetição de cenários simples e ausência de testes para casos de erro e bordas, além de estudantes que relatam dificuldade em explicar o que os testes gerados realmente verificam.

Por outro lado, existe uma oportunidade clara de transformar essa prática em objeto de estudo estruturado. Ao planejar um experimento simples, conduzido por um estudante de Engenharia de Software, é possível comparar situações em que os participantes usam um assistente de IA na leitura da user story e na elaboração de testes, com situações em que isso não ocorre. Dessa forma, o trabalho pode produzir evidências concretas sobre os efeitos desse uso na compreensão dos requisitos e na qualidade dos testes, ajudando professores, estudantes e profissionais a tomar decisões mais embasadas sobre como e quando utilizar essas ferramentas em atividades de teste orientadas por user stories.

### 2.2 Contexto organizacional e técnico

O experimento será realizado em contexto acadêmico, no curso de Engenharia de Software da Pontifícia Universidade Católica de Minas Gerais. Os participantes serão estudantes de períodos intermediários ou avançados que já tiveram contato com programação e com noções básicas de testes de software. Esses participantes poderão ser recrutados em disciplinas práticas ou por convite direto, de forma voluntária. O ambiente não é uma empresa de software, mas busca simular de maneira simples uma situação real de desenvolvimento em que user stories são entregues a desenvolvedores para implementação e teste.

Do ponto de vista técnico, o experimento utilizará um cenário único e padronizado para todos os participantes, por exemplo uma pequena aplicação web ou uma API simples escrita em JavaScript com Node e testes em Jest, já implementada previamente. Esse sistema sob teste conterá funcionalidades claras e um conjunto de user stories curtas, além de defeitos semeados de forma controlada no código. Os participantes não precisarão criar a aplicação do zero. A tarefa principal será ler a user story, refinar e esclarecer o entendimento dessas histórias, definir casos de teste em linguagem natural e implementar testes automatizados utilizando o framework escolhido.

As ferramentas necessárias serão limitadas a um editor de código, como Visual Studio Code, um repositório preparado com o projeto base e, no grupo em que houver uso de inteligência artificial, o acesso a um assistente de IA, por exemplo um modelo de linguagem acessível via navegador, desde que autorizado pela instituição e conforme combinado no plano de pesquisa. O processo de desenvolvimento adotado no experimento será propositalmente simples. Cada participante realizará individualmente uma ou duas tarefas curtas, com tempo limitado, em uma sessão que poderá ocorrer em laboratório ou de forma remota com instruções claras. Isso torna o experimento exequível por um único estudante responsável, tanto em termos de preparação quanto de acompanhamento da execução e análise dos dados coletados.

### 2.3 Trabalhos e evidências prévias (internos e externos)

Na literatura de Engenharia de Software existem estudos que analisam a influência de user stories e de critérios de aceitação na qualidade do software, mostrando que requisitos mal escritos ou mal compreendidos tendem a gerar funcionalidades inconsistentes e conjuntos de testes incompletos. Há também trabalhos recentes que investigam o uso de assistentes de código baseados em inteligência artificial, avaliando produtividade, qualidade do código gerado e percepção dos desenvolvedores. Esses estudos costumam apontar ganhos de velocidade e sensação de apoio na programação, mas também alertam para o risco de aceitação acrítica de sugestões, introdução de defeitos e redução do entendimento profundo do código.

Em paralelo, estudos empíricos realizados em cursos de Engenharia de Software mostram que estudantes frequentemente têm dificuldades em derivar casos de teste a partir de requisitos textuais. É comum observar testes que cobrem apenas o fluxo principal, ausência de casos de erro e fraca ligação entre o que está descrito na user story e o que é efetivamente verificado pelos testes automatizados. Em atividades práticas e projetos de disciplinas, muitos estudantes já utilizam ferramentas de IA para pedir exemplos de testes ou para pedir explicações sobre requisitos, mas esse uso raramente é medido de forma sistemática.

Esse conjunto de evidências sugere que o problema abordado pelo experimento é relevante e atual. Por um lado, já existem indícios de que a qualidade da ligação entre requisitos e testes é um ponto frágil. Por outro lado, o uso crescente de ferramentas de IA abre uma oportunidade para melhorar esse cenário, mas também traz novas incertezas. Ainda são raros os estudos simples, aplicáveis em contexto de graduação, que comparam diretamente tarefas de entendimento de user stories e elaboração de testes com e sem uso de IA, usando métricas objetivas e questionários para capturar a percepção dos participantes. O experimento proposto busca contribuir justamente nesse espaço, com um desenho enxuto e realizável por um estudante, mas com potencial para gerar resultados analisáveis e úteis.

### 2.4 Referencial teórico e empírico essencial

O referencial teórico que fundamenta o experimento combina quatro eixos principais.

O primeiro eixo é a engenharia de requisitos, especialmente o uso de user stories em métodos ágeis. User stories podem ser vistas como uma forma de especificação leve que descreve uma necessidade do usuário, geralmente com uma estrutura padrão e com apoio de critérios de aceitação. A teoria destaca que a clareza, a completude e a ausência de ambiguidades nessas histórias influenciam diretamente a capacidade da equipe de implementar e testar corretamente as funcionalidades.

O segundo eixo é a teoria de testes de software. Testes de unidade e testes de integração simples, quando derivam de requisitos de forma sistemática, devem cobrir cenários típicos de uso, casos de erro e situações de fronteira. Métricas como número de casos de teste, cobertura de código e quantidade de defeitos descobertos em um código com falhas semeadas são formas práticas de avaliar a qualidade do conjunto de testes. Em um experimento simples, basta comparar essas métricas entre tarefas realizadas com e sem uso de inteligência artificial, mantendo o mesmo sistema sob teste e user stories equivalentes.

O terceiro eixo é o uso de inteligência artificial aplicada ao desenvolvimento de software. Assistentes de código e modelos de linguagem podem apoiar o desenvolvedor na interpretação de textos, na sugestão de casos de teste em linguagem natural e na geração de trechos de código de teste. Do ponto de vista teórico, essas ferramentas podem atuar como apoio cognitivo na leitura da user story ou como gerador automático de exemplos. Ao mesmo tempo, a teoria alerta que apoio não é garantia de entendimento. Se o estudante aceita as sugestões sem análise crítica, a ferramenta pode reforçar lacunas de compreensão ou esconder defeitos sutis.

O quarto eixo é a engenharia de software empírica, que traz princípios para planejar experimentos controlados em desenvolvimento de software. Um desenho simples, adequado ao nível de TCC, pode consistir em tarefas individuais em que cada participante realiza uma atividade sem uso de IA e outra com uso de IA, em ordem alternada entre os participantes, de modo que cada pessoa funcione parcialmente como seu próprio controle. Em cada tarefa, o participante recebe uma user story, define casos de teste em texto e implementa testes automatizados. O pesquisador mede, por exemplo, quantos casos de teste foram criados, se eles cobrem os critérios de aceitação, qual a cobertura de código obtida e quantos defeitos semeados foram encontrados. Questionários curtos permitem capturar a percepção de entendimento e de esforço.

Esse conjunto de conceitos e resultados empíricos oferece base suficiente para justificar o experimento proposto. Ele mostra que há teoria consolidada sobre user stories, testes e experimentação em engenharia de software, ao mesmo tempo em que aponta lacunas específicas relacionadas ao uso de inteligência artificial em tarefas de entendimento de requisitos e geração de testes. O desenho escolhido é intencionalmente mais simples, para ser exequível por um estudante de graduação, mas ainda assim capaz de produzir dados que permitam testar hipóteses claras e gerar conclusões úteis para a prática e para o ensino.

---

## 3. Objetivos e questões (Goal / Question / Metric)

### 3.1 Objetivo geral (modelo GQM)

No modelo Goal Question Metric (GQM), o objetivo geral do experimento pode ser formalizado do seguinte modo:

Analisar o uso de ferramentas de inteligência artificial na atividade de entendimento de user stories e derivação de testes automatizados, com o propósito de avaliar o impacto sobre a compreensão dos requisitos, sobre a qualidade dos testes e sobre o esforço dos estudantes, do ponto de vista de docentes e pesquisadores em Engenharia de Software, no contexto de disciplinas práticas de programação e testes em um curso de graduação em Engenharia de Software da Pontifícia Universidade Católica de Minas Gerais.

Para deixar o objetivo geral ainda mais estruturado no formato GQM clássico, pode-se explicitar o template de forma tabular:

| Dimensão       | Descrição                                                                                                             |
|----------------|-----------------------------------------------------------------------------------------------------------------------|
| Objeto         | Processo de entendimento de user stories e derivação de testes automatizados por estudantes de Engenharia de Software |
| Propósito      | Analisar e avaliar o impacto do uso de ferramentas de inteligência artificial                                         |
| Foco           | Compreensão de requisitos, qualidade dos testes e esforço/produtividade                                               |
| Ponto de vista | Docentes, coordenação de curso e pesquisadores em Engenharia de Software                                              |
| Contexto       | Disciplinas práticas e atividades acadêmicas em curso de Engenharia de Software da PUC Minas                         |

Esse objetivo geral orienta todo o desenho do experimento, garantindo que as questões de pesquisa e as métricas estejam coerentes e alinhadas com o que se deseja compreender e avaliar.

### 3.2 Objetivos específicos

A partir do objetivo geral, são definidos objetivos específicos que traduzem o que se espera obter de forma concreta com a execução do experimento.

O1. Avaliar o efeito do uso de ferramentas de inteligência artificial no nível de entendimento de user stories por estudantes de Engenharia de Software, considerando tanto o desempenho em instrumentos objetivos de avaliação quanto a capacidade de identificar corretamente critérios de aceitação e evitar interpretações equivocadas.

O2. Avaliar o efeito do uso de ferramentas de inteligência artificial na qualidade dos testes automatizados derivados de user stories, medindo cobertura de código, cobertura de critérios de aceitação e capacidade de detecção de defeitos semeados no sistema sob teste.

O3. Avaliar o efeito do uso de ferramentas de inteligência artificial sobre o esforço e a produtividade dos estudantes na elaboração de testes automatizados a partir de user stories, considerando tempo total de tarefa, quantidade de testes produzidos e relação entre quantidade de testes e tempo disponível.

O4. Caracterizar a percepção, a aceitação e os possíveis riscos percebidos pelos estudantes em relação ao uso de ferramentas de inteligência artificial em tarefas de entendimento de user stories e geração de testes automatizados, incluindo percepção de utilidade, confiança e dependência.

Esses quatro objetivos específicos são suficientemente amplos para capturar diferentes dimensões do fenômeno estudado, mas ao mesmo tempo são claros e mensuráveis, o que viabiliza a análise de resultados e a formulação de conclusões consistentes em nível de TCC.

### 3.3 Questões de pesquisa

Em conformidade com o modelo GQM, cada objetivo específico é detalhado por um conjunto de questões de pesquisa que o experimento deverá responder.

**Objetivo O1 – Entendimento de user stories**

Q1.1. Em que medida o uso de ferramentas de inteligência artificial altera o nível de entendimento das user stories pelos estudantes, conforme medido por um questionário objetivo sobre o conteúdo da história e seus critérios de aceitação.

Q1.2. O uso de ferramentas de inteligência artificial aumenta a proporção de critérios de aceitação corretamente identificados pelos estudantes quando derivam casos de teste em linguagem natural a partir de uma user story.

Q1.3. O uso de ferramentas de inteligência artificial reduz a quantidade de erros de interpretação relevantes das user stories presentes nas descrições de casos de teste produzidas pelos estudantes.

**Objetivo O2 – Qualidade dos testes automatizados**

Q2.1. O uso de ferramentas de inteligência artificial aumenta a cobertura de código por linha e por ramo obtida pelos testes automatizados gerados pelos estudantes a partir das user stories fornecidas.

Q2.2. O uso de ferramentas de inteligência artificial aumenta a proporção de critérios de aceitação que estão efetivamente cobertos por pelo menos um teste automatizado implementado pelos estudantes.

Q2.3. O uso de ferramentas de inteligência artificial aumenta a capacidade dos testes automatizados produzidos pelos estudantes de detectar defeitos semeados previamente no código do sistema sob teste.

**Objetivo O3 – Esforço e produtividade**

Q3.1. O uso de ferramentas de inteligência artificial reduz o tempo total necessário para que os estudantes leiam a user story, planejem os casos de teste em linguagem natural e implementem os testes automatizados.

Q3.2. O uso de ferramentas de inteligência artificial aumenta a produtividade dos estudantes, medida como quantidade de testes automatizados implementados por unidade de tempo, em tarefas de teste orientadas por user stories.

Q3.3. O uso de ferramentas de inteligência artificial altera a distribuição do esforço entre as etapas de leitura da user story, definição de casos de teste em linguagem natural e implementação de testes automatizados.

**Objetivo O4 – Percepção e aceitação**

Q4.1. Como os estudantes avaliam o impacto do uso de ferramentas de inteligência artificial sobre sua compreensão das user stories, em termos de utilidade percebida e clareza dos requisitos.

Q4.2. Como os estudantes avaliam o impacto do uso de ferramentas de inteligência artificial sobre a qualidade e a confiabilidade dos testes automatizados que produziram.

Q4.3. Em que medida os estudantes se sentem dependentes das ferramentas de inteligência artificial para executar tarefas de entendimento de user stories e geração de testes, e quais riscos, limitações e dificuldades eles percebem nesse uso no contexto acadêmico.

### 3.4 Métricas associadas (GQM)

Para responder às questões de pesquisa, são definidas métricas observáveis e mensuráveis. A tabela a seguir mostra a relação entre objetivos, questões e métricas, no espírito do modelo GQM.

#### Tabela GQM: objetivos, questões e métricas

| Objetivo específico | Questão de pesquisa | Métricas associadas |
|---------------------|---------------------|----------------------|
| O1                  | Q1.1                | M1, M16             |
| O1                  | Q1.2                | M2, M3              |
| O1                  | Q1.3                | M3, M14             |
| O2                  | Q2.1                | M4, M5              |
| O2                  | Q2.2                | M6, M2              |
| O2                  | Q2.3                | M7, M8              |
| O3                  | Q3.1                | M9, M12             |
| O3                  | Q3.2                | M10, M11            |
| O3                  | Q3.3                | M9, M10, M14        |
| O4                  | Q4.1                | M16, M1             |
| O4                  | Q4.2                | M13, M7             |
| O4                  | Q4.3                | M15, M14            |

Em seguida, cada métrica é descrita em detalhes, com unidade e fonte de dados, conforme exigido para um trabalho em nível de TCC.

#### Tabela de métricas, descrição e unidade

| Métrica | Descrição                                                                                                                                                              | Unidade                     |
|---------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------|
| M1      | Pontuação de entendimento da user story obtida pelo participante em questionário objetivo, contendo questões sobre funcionalidades, regras e critérios.                | Pontos em escala de 0 a 10 |
| M2      | Proporção de critérios de aceitação descritos na user story que são corretamente identificados e mencionados em casos de teste em linguagem natural.                  | Porcentagem                 |
| M3      | Número de erros de interpretação relevantes identificados nas descrições de casos de teste em linguagem natural, como confusão de regras ou omissões críticas.        | Contagem                    |
| M4      | Cobertura de código por linha obtida pelos testes automatizados do participante, medida por ferramenta de cobertura sobre o sistema sob teste.                        | Porcentagem                 |
| M5      | Cobertura de código por ramo obtida pelos testes automatizados, também medida por ferramenta de cobertura, considerando decisões condicionais do código.              | Porcentagem                 |
| M6      | Proporção de critérios de aceitação que possuem pelo menos um teste automatizado associado, verificada por inspeção entre critérios e casos de teste.                 | Porcentagem                 |
| M7      | Número absoluto de defeitos semeados no código do sistema sob teste que foram efetivamente detectados pelos testes automatizados do participante.                     | Contagem                    |
| M8      | Taxa de detecção de defeitos, calculada como M7 dividido pelo número total de defeitos semeados, expressa em porcentagem.                                             | Porcentagem                 |
| M9      | Tempo total de realização da tarefa, desde o momento em que o participante começa a ler a user story até o momento em que finaliza a implementação dos testes.        | Minutos                     |
| M10     | Número total de testes automatizados implementados pelo participante para a user story em questão, incluindo testes de unidade e de integração simples.               | Contagem                    |
| M11     | Produtividade em testes, calculada como M10 dividido pelo tempo total medido em horas (testes automatizados por hora).                                                | Testes por hora             |
| M12     | Esforço percebido pelo participante para executar a tarefa, medido por escala Likert em questionário pós tarefa, onde 1 representa esforço muito baixo e 5 muito alto.| Nível em escala de 1 a 5    |
| M13     | Grau de confiança do participante nos testes que produziu, medido por escala Likert em questionário, onde 1 indica nenhuma confiança e 5 indica confiança muito alta.| Nível em escala de 1 a 5    |
| M14     | Frequência de uso da ferramenta de inteligência artificial durante a tarefa, medida pelo número de interações relevantes (consultas ou sugestões aceitas) registradas.| Contagem                    |
| M15     | Grau de dependência percebida em relação à inteligência artificial, avaliado por escala Likert em questionário em que o participante indica o quanto conseguiria realizar a tarefa sem IA.| Nível em escala de 1 a 5 |
| M16     | Utilidade percebida da inteligência artificial especificamente para entender a user story, medida em escala Likert em que 1 indica nenhuma utilidade e 5 utilidade muito alta.| Nível em escala de 1 a 5 |

O conjunto de métricas atende ao requisito de possuir mais de dez métricas distintas e assegura que cada questão de pesquisa tem pelo menos duas métricas associadas. Além disso, combina medidas objetivas (cobertura, número de testes, defeitos encontrados, tempo) com medidas subjetivas (percepção de esforço, utilidade, confiança e dependência), o que enriquece a análise e torna o estudo mais interessante do ponto de vista científico e prático.

---

## 4. Escopo e contexto do experimento

### 4.1 Escopo funcional e de processo

O escopo do experimento é definido explicitamente para evitar interpretações divergentes e alinhar as expectativas dos envolvidos. Utiliza-se um template de escopo semelhante ao discutido em sala, adaptado ao contexto deste estudo.

| Dimensão              | Escopo do experimento                                                                                                                                                                                                 |
|-----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Objeto principal      | Processo de entendimento de user stories e derivação de testes automatizados por estudantes de Engenharia de Software                                                                                                 |
| Atividades incluídas  | Leitura de user stories, identificação de critérios de aceitação, definição de casos de teste em linguagem natural, implementação de testes automatizados, execução de testes e resposta a questionários de avaliação. |
| Atividades excluídas  | Implementação ou modificação de código de produção, desenho detalhado de arquitetura, testes de desempenho, segurança e usabilidade, integração contínua, deploy e monitoramento em produção.                        |
| Artefatos incluídos   | User stories pré-definidas, critérios de aceitação, sistema sob teste com defeitos semeados, código de testes automatizados, questionários e formulários de coleta.                                                   |
| Artefatos excluídos   | Documentação completa de requisitos do sistema, artefatos de projeto arquitetural e de modelagem detalhada, documentação de operação em produção.                                                                     |
| Participantes         | Estudantes de Engenharia de Software em período intermediário ou avançado, atuando individualmente nas tarefas do experimento.                                                                                        |
| Ferramentas           | Editor de código, framework de testes automatizados, ferramenta de cobertura, ferramenta de inteligência artificial (para o grupo com IA) e formulários online.                                                     |

Em resumo, o experimento cobre especificamente a cadeia que vai da compreensão da user story até a implementação e execução de testes automatizados, deixando fora do escopo a implementação de funcionalidades e outras fases do ciclo de vida de software.

### 4.2 Contexto do estudo

O estudo será conduzido na Pontifícia Universidade Católica de Minas Gerais, no curso de Engenharia de Software. O contexto é o de disciplinas práticas ou atividades complementares relacionadas a programação, testes de software e engenharia de requisitos. Trata-se de uma organização de ensino superior consolidada, mas o experimento se insere em ambiente acadêmico, não em uma empresa de desenvolvimento de software em operação comercial.

O sistema sob teste será um projeto de pequeno porte, por exemplo uma API de cadastro ou uma aplicação web simples, suficientemente restrito para que os participantes possam compreendê-lo em tempo limitado. Esse sistema será preparado previamente pelo pesquisador, que semeará defeitos de maneira controlada para permitir a avaliação da capacidade dos testes em detectá-los.

Os participantes serão estudantes de períodos intermediários ou avançados, como terceiro ao sexto período, que já tenham cursado disciplinas básicas de programação e tenham ao menos um contato introdutório com testes automatizados. Antes do experimento, será aplicado um breve questionário de caracterização para registrar experiências prévias relevantes, tais como quantidade aproximada de tempo de estudo em programação, familiaridade com user stories, experiência em escrita de testes automatizados e uso anterior de ferramentas de inteligência artificial para programação.

A realização das tarefas poderá ocorrer em laboratório de informática, em ambiente controlado, ou em ambientes pessoais dos estudantes, desde que o contexto técnico seja equivalente. Em ambos os casos, serão fornecidas instruções claras e padronizadas, além dos artefatos necessários, para garantir consistência na execução.

### 4.3 Premissas

O plano experimental baseia-se em algumas premissas consideradas razoáveis, mas que não são totalmente garantidas.

Premissa de infraestrutura adequada: supõe-se que os estudantes terão acesso a máquinas com capacidade suficiente para executar o ambiente de desenvolvimento necessário, incluindo editor de código, interpretador ou compilador, framework de testes e, no grupo com IA, acesso à ferramenta de inteligência artificial.

Premissa de estabilidade do sistema sob teste: supõe-se que o sistema base estará pronto, testado e estável antes da execução do experimento, contendo apenas os defeitos semeados de forma planejada, sem falhas adicionais que possam confundir a análise.

Premissa de disponibilidade de estudantes: supõe-se que haverá um número mínimo de estudantes voluntários interessados em participar, permitindo formar grupos com e sem uso de inteligência artificial e obter dados comparáveis.

Premissa de tempo suficiente: supõe-se que haverá janelas de tempo nos horários das disciplinas ou em períodos definidos para a realização das tarefas, com duração suficiente para que os participantes possam ler a user story, planejar e implementar testes automatizados.

Essas premissas são importantes para a viabilidade do experimento. Caso alguma delas não se concretize, ajustes no desenho poderão ser necessários.

### 4.4 Restrições

O experimento está sujeito a restrições práticas que influenciam suas decisões de desenho.

A principal restrição é o tempo disponível em calendário acadêmico. O estudo precisa caber em um cronograma de TCC e em horários de aulas ou de atividades de laboratório, o que limita o tamanho do sistema sob teste e a quantidade de tarefas que podem ser atribuídas a cada estudante.

Há também restrição de orçamento e de licenças. Como o trabalho é de um estudante de graduação, não há verba específica para aquisição de ferramentas. Assim, o estudo se limita a ferramentas gratuitas, versões educacionais ou já disponíveis institucionalmente.

Outra restrição diz respeito às políticas institucionais para uso de inteligência artificial em atividades acadêmicas. Caso existam normas que definam limites para o uso dessas ferramentas, o experimento deve respeitá-las, o que pode influenciar a escolha de quais ferramentas serão utilizadas e a forma de apresentação dos resultados.

Por fim, existem restrições relacionadas à coleta de dados. O estudo deve respeitar privacidade dos participantes, evitando captura de dados pessoais desnecessários. Logs detalhados de interações com a inteligência artificial podem não estar disponíveis diretamente, de modo que parte da mensuração de uso poderá depender de autorrelatos e observações indiretas.

### 4.5 Limitações previstas

Mesmo com planejamento cuidadoso, algumas limitações de validade externa são esperadas.

A primeira limitação está no fato de o contexto ser acadêmico, com estudantes em formação. Os resultados podem não se generalizar diretamente para desenvolvedores profissionais experientes, que possivelmente usam ferramentas de inteligência artificial de forma mais madura e em sistemas de maior porte.

Outra limitação é o tamanho e a complexidade do sistema sob teste. Para caber no tempo disponível, o sistema será relativamente pequeno e com domínio funcional limitado. Em sistemas grandes, com requisitos complexos e múltiplos módulos, o impacto da inteligência artificial pode ser diferente.

A amostra de participantes também é uma limitação. Mesmo com esforço para recrutar estudantes, o número tende a ser modestamente limitado, o que reduz a capacidade de generalização estatística dos resultados. Ainda assim, o estudo pode produzir evidências relevantes no contexto local e gerar hipóteses para estudos futuros com amostras maiores.

Além disso, a escolha de uma ou duas ferramentas específicas de inteligência artificial restringe a generalização dos resultados para outras ferramentas existentes no mercado, que podem ter comportamentos, interfaces e capacidades distintas.

Essas limitações serão explicitadas na discussão dos resultados e não invalidam o experimento, mas orientam o cuidado na interpretação e na comunicação das conclusões.

---

## 5. Stakeholders e impacto esperado

### 5.1 Stakeholders principais

Os principais stakeholders identificados para este experimento são:

Estudantes de Engenharia de Software que participarão do estudo, atuando diretamente nas tarefas de entendimento de user stories e geração de testes automatizados.

Docentes que ministram disciplinas de programação, engenharia de requisitos, qualidade de software e testes na PUC Minas, interessados em evidências sobre o impacto da inteligência artificial no processo de ensino e aprendizagem.

Coordenação do curso de Engenharia de Software, responsável por diretrizes pedagógicas e por políticas de uso de ferramentas tecnológicas, incluindo inteligência artificial, em trabalhos acadêmicos e projetos de disciplinas.

Comunidade acadêmica de Engenharia de Software, especialmente pesquisadores que atuam com Engenharia de Software Empírica, educação em Engenharia de Software e uso de inteligência artificial em atividades de desenvolvimento.

Profissionais de desenvolvimento e de teste de software, ainda que não participem diretamente do experimento, que podem se interessar pelos resultados para refletir sobre o uso de ferramentas de inteligência artificial em seus contextos de trabalho.

### 5.2 Interesses e expectativas dos stakeholders

Os estudantes esperam compreender melhor se o uso de ferramentas de inteligência artificial realmente contribui para a compreensão de user stories e para a elaboração de testes mais completos, ou se, ao contrário, pode gerar uma sensação enganosa de segurança. Também têm expectativa de que a participação no experimento contribua para sua formação prática, sem exigir carga excessiva de trabalho além da já presente nas disciplinas.

Os docentes buscam evidências para responder a uma pergunta concreta: em atividades de ensino de requisitos e testes, incentivar ou restringir o uso de inteligência artificial ajuda a formar profissionais mais preparados. Com base nos resultados, poderão ajustar a forma como propõem exercícios, projetos e avaliações, seja integrando a inteligência artificial como ferramenta didática, seja definindo atividades em que seu uso deve ser cuidadosamente limitado.

A coordenação do curso tem interesse em dispor de dados empíricos que subsidiem decisões sobre políticas acadêmicas relativas ao uso de inteligência artificial, especialmente em trabalhos avaliativos e TCC. O experimento pode indicar riscos, como dependência excessiva ou perda de raciocínio próprio, e também oportunidades, como apoio à aprendizagem de testes e requisitos.

A comunidade acadêmica de Engenharia de Software tem interesse em estudos empíricos que investiguem fenômenos atuais, como o impacto real de assistentes de código e modelos de linguagem no desenvolvimento e na qualidade de software. Este experimento, embora de escala acadêmica, pode dialogar com outros estudos e contribuir para compor um quadro mais amplo sobre o tema.

Profissionais da indústria, finalmente, podem utilizar resultados e recomendações derivadas do estudo como insumo para delinear práticas de uso de inteligência artificial em times de desenvolvimento, especialmente em fases de definição de testes orientados a requisitos.

### 5.3 Impactos potenciais no processo e no produto

Durante a realização do experimento, haverá impacto direto na organização de algumas aulas ou sessões de laboratório, que precisarão ser parcialmente dedicadas à execução das tarefas. Isso pode exigir pequenos ajustes no cronograma de disciplina, mas, em contrapartida, gera uma experiência prática diferenciada para os estudantes.

No produto de software utilizado como sistema sob teste, o impacto é controlado. O sistema será adaptado para fins didáticos, com defeitos semeados, e poderá ser reaproveitado em atividades futuras. A instrumentação do sistema para coleta de métricas de cobertura e detecção de defeitos também pode se transformar em recurso pedagógico adicional.

Após o experimento, o principal impacto esperado está na melhoria do processo pedagógico. Com base nas evidências coletadas, docentes e coordenação poderão revisar a forma como tratam o uso de inteligência artificial em atividades de requisitos e testes, adotando práticas mais conscientes e transparentes. Do ponto de vista dos estudantes, espera-se que o experimento aumente a consciência sobre o uso crítico dessas ferramentas, incentivando que sejam vistas como apoio à reflexão e não como substituto do raciocínio técnico.

---

## 6. Riscos de alto nível, premissas e critérios de sucesso

### 6.1 Riscos de alto nível

O experimento envolve alguns riscos de nível mais elevado que precisam ser reconhecidos desde o planejamento.

Um risco importante é a baixa adesão de participantes. Caso o número de estudantes voluntários seja muito pequeno, as comparações entre grupos com e sem uso de inteligência artificial podem perder força e a análise estatística fica limitada. Esse risco pode ser mitigado por divulgação antecipada, integração com atividades de disciplina e comunicação clara de que a participação contribui para o TCC e para o próprio aprendizado.

Outro risco é o de falhas técnicas, como problemas com ambientes de desenvolvimento, com instalação de dependências, com a ferramenta de testes ou com o acesso à inteligência artificial. Tais problemas podem consumir tempo da sessão e prejudicar a realização das tarefas. Para reduzir esse risco, o pesquisador deve preparar ambientes com antecedência, testar o sistema sob teste, a instrumentação de métricas e o acesso às ferramentas de inteligência artificial, além de ter alternativas simples em caso de falhas específicas.

Existe também o risco de mudanças nas regras institucionais ou nas políticas das ferramentas de inteligência artificial, como restrição súbita de acesso gratuito ou alterações em termos de uso. Caso isso aconteça próximo ao período de execução, pode ser necessário ajustar o desenho experimental ou até trocar a ferramenta utilizada.

Por fim, há o risco de dados incompletos ou com baixa qualidade. Alguns participantes podem não finalizar a tarefa, esquecer de executar testes, não responder questionários ou registrar tempos de forma inadequada. Esse risco pode ser reduzido com instruções claras, supervisão durante as sessões e uso de mecanismos automáticos de coleta sempre que possível.

### 6.2 Critérios de sucesso globais

Os critérios a seguir definem quando o experimento será considerado bem-sucedido e útil para o TCC.

Primeiro critério: participação adequada. O experimento deve contar com uma quantidade mínima de estudantes que completem as tarefas em ambas as condições analisadas, com e sem uso de inteligência artificial, de forma a permitir comparações significativas, mesmo que em escala modesta.

Segundo critério: execução planejada. As tarefas definidas no plano deverão ser executadas conforme descrito, com leitura de user stories, produção de casos de teste em linguagem natural, implementação de testes automatizados e resposta a questionários, sem desvios significativos que comprometam a comparabilidade entre participantes.

Terceiro critério: coleta de métricas consistente. As métricas M1 a M16 precisam ser coletadas com qualidade razoável, com mínimo de erros e lacunas, permitindo a análise das questões de pesquisa. Isso inclui a medição correta de tempo, o registro de cobertura, a conferência de critérios de aceitação cobertos e a consolidação das respostas subjetivas.

Quarto critério: capacidade de responder às questões de pesquisa. Mesmo que algumas hipóteses específicas venham a ser rejeitadas ou permaneçam inconclusivas, o conjunto de dados coletado deve permitir responder de forma argumentada às questões Q1.1 até Q4.3, gerando conclusões e recomendações para o contexto estudado.

Quinto critério: relevância percebida. O orientador e a banca de TCC devem considerar que o experimento produziu resultados relevantes, que dialogam com a prática de ensino e com a realidade atual de uso de inteligência artificial em desenvolvimento de software, justificando o esforço empregado na execução do estudo.

Se esses critérios forem atendidos, o experimento terá cumprido sua função como parte central de um TCC em Engenharia de Software, demonstrando que se trata de uma pesquisa viável, bem planejada e capaz de produzir contribuições concretas.

### 6.3 Critérios de parada antecipada

Antes da execução ou no início do estudo, algumas condições podem exigir o adiamento ou cancelamento do experimento, para não comprometer a qualidade da pesquisa nem a integridade dos participantes.

Um critério de parada antecipada importante é a indisponibilidade de infraestrutura básica. Se, após tentativas de preparação, não for possível garantir um ambiente mínimo funcional para todos os participantes, com o sistema sob teste estável, ferramentas de teste configuradas e acesso aos recursos necessários, o experimento deverá ser suspenso até que a infraestrutura seja corrigida.

Outro critério é a reprovação ética ou institucional. Se a proposta de usar inteligência artificial, coletar determinados dados ou organizar as sessões entrar em conflito com normas internas, com decisões da coordenação ou com orientações formais sobre o uso de tecnologia em avaliações, o experimento deve ser revisado. Em último caso, se não houver solução aceitável, deve ser cancelado.

Finalmente, alterações significativas no calendário acadêmico ou na disponibilidade de turmas, como suspensão de aulas presenciais ou mudanças de grade, podem inviabilizar o cumprimento do cronograma planejado. Nessa situação, o pesquisador e o orientador precisam reavaliar a viabilidade de execução dentro do prazo de TCC e, se necessário, decidir pelo adiamento ou adaptação do estudo.

Ao explicitar esses critérios de parada antecipada, o plano de experimento mostra maturidade e responsabilidade, o que é fundamental em um trabalho de conclusão de curso. Ao mesmo tempo, o desenho escolhido permanece simples o bastante para ser conduzido por um único estudante, com alcance compatível com a realidade do curso, mas robusto o suficiente para produzir resultados analisáveis e úteis sobre o uso de inteligência artificial em atividades de entendimento de user stories e geração de testes automatizados.
# 7. Modelo conceitual e hipóteses

---

## 7.1 Modelo conceitual do experimento

O modelo conceitual deste experimento parte da ideia de que o uso de ferramentas de inteligência artificial em tarefas de entendimento de user stories e geração de testes automatizados atua como um fator que pode modificar o comportamento dos estudantes e os resultados obtidos em diferentes dimensões. Em termos conceituais, o principal fator estudado é o uso de IA, com dois níveis: ausência de uso de IA (condição controle) e uso de uma ferramenta de IA aprovada (condição tratamento). Esse fator é aplicado sobre tarefas equivalentes, nas quais os participantes recebem user stories, critérios de aceitação e um sistema sob teste com defeitos semeados.

A hipótese conceitual central é que a presença da IA pode aumentar a capacidade dos estudantes de interpretar as user stories, sugerindo casos de teste adicionais, ajudando a estruturar melhor os testes e, potencialmente, elevando a cobertura de código e a taxa de detecção de defeitos. Ao mesmo tempo, o uso da IA pode reduzir o esforço percebido e o tempo necessário para completar as tarefas, uma vez que parte da carga cognitiva é transferida para a ferramenta. No entanto, existe também a possibilidade de efeitos negativos, como dependência excessiva, aceitação acrítica de sugestões erradas e menor compreensão profunda dos requisitos e do código.

Dessa forma, o modelo conceitual relaciona o fator “uso de IA” com um conjunto de variáveis de resposta: entendimento das user stories, qualidade dos testes automatizados (cobertura, aderência a critérios de aceitação, detecção de defeitos), esforço e tempo de execução, além de percepções subjetivas de utilidade, confiança e dependência. A tarefa específica (por exemplo, Tarefa A e Tarefa B) é tratada como um objeto de estudo e como variável de bloqueio ou contexto, de modo que cada participante execute ao menos uma tarefa sem IA e outra com IA, minimizando a influência da dificuldade específica de uma única tarefa.

Em resumo, o modelo conceitual considera que:

1. O uso de IA tende a aumentar entendimento e qualidade dos testes, e a reduzir esforço e tempo, em comparação com a ausência de IA.
2. A tarefa e a experiência prévia dos participantes podem moderar esses efeitos, isto é, estudantes mais experientes podem depender menos da IA, enquanto estudantes menos experientes podem se beneficiar mais ou se tornar mais dependentes.
3. As percepções subjetivas dos estudantes (utilidade, confiança, dependência) são influenciadas pela interação entre o uso de IA, a tarefa executada e os resultados objetivos obtidos (por exemplo, detecção de defeitos).

---

## 7.2 Hipóteses formais (H0, H1)

Com base no modelo conceitual e nas questões de pesquisa definidas anteriormente, são formuladas hipóteses nulas e alternativas para os principais efeitos de interesse. Abaixo, as hipóteses são descritas em linguagem textual clara, associadas às métricas já definidas.

**Hipótese relacionada ao entendimento de user stories**

**H0_Entendimento**: não há diferença significativa entre a pontuação média de entendimento da user story (métrica M1) dos estudantes quando executam a tarefa sem uso de IA e quando executam a tarefa com uso de IA.

**H1_Entendimento**: a pontuação média de entendimento da user story (métrica M1) dos estudantes é maior na condição com uso de IA do que na condição sem uso de IA.

**Hipótese relacionada à cobertura de código pelos testes**

**H0_Cobertura**: não há diferença significativa entre a cobertura média de código por linha e por ramo (métricas M4 e M5) obtida pelos testes automatizados gerados pelos estudantes nas condições com e sem uso de IA.

**H1_Cobertura**: a cobertura média de código por linha e por ramo (métricas M4 e M5) obtida pelos testes automatizados é maior na condição com uso de IA do que na condição sem uso de IA.

**Hipótese relacionada à detecção de defeitos semeados**

**H0_Defeitos**: não há diferença significativa entre a taxa média de detecção de defeitos semeados (métrica M8) entre a condição sem uso de IA e a condição com uso de IA.

**H1_Defeitos**: a taxa média de detecção de defeitos semeados (métrica M8) é maior na condição com uso de IA do que na condição sem uso de IA.

**Hipótese relacionada ao esforço e ao tempo**

**H0_EsforçoTempo**: não há diferença significativa entre o tempo médio de execução da tarefa (M9) e o esforço percebido (M12) nas condições com e sem uso de IA.

**H1_EsforçoTempo**: o uso de IA reduz o tempo médio de execução da tarefa (M9) e o esforço percebido (M12) em comparação com a condição sem uso de IA.

**Hipótese relacionada à percepção de utilidade e dependência**

**H0_Percepção**: o uso de IA não altera significativamente a percepção de utilidade (M16), confiança (M13) e dependência (M15) dos estudantes em relação à tarefa de entender user stories e gerar testes automatizados.

**H1_Percepção**: o uso de IA aumenta a percepção de utilidade (M16) e confiança (M13) dos estudantes em relação à tarefa, e também pode aumentar a sensação de dependência (M15) em relação à ferramenta, em comparação com a condição sem uso de IA.

Essas hipóteses formais permitirão que os dados coletados sejam analisados com métodos estatísticos adequados, testando a presença ou ausência de diferenças significativas entre as condições experimentais.

---

## 7.3 Nível de significância e considerações de poder

O nível de significância estatística adotado para os testes de hipóteses será α igual a 0,05. Isso significa que a probabilidade máxima de rejeitar erroneamente uma hipótese nula verdadeira (erro tipo I) será de cinco por cento para cada teste conduzido. Em outras palavras, quando um resultado for declarado estatisticamente significativo, admite-se uma chance de cinco por cento de que essa decisão seja um falso positivo.

Quanto ao poder estatístico, isto é, a probabilidade de detectar um efeito real quando ele de fato existe, a expectativa é que o estudo tenha poder moderado, compatível com o tamanho de amostra viável em um TCC de graduação. O número exato de participantes dependerá da disponibilidade de estudantes, mas planeja-se buscar um mínimo de duas dezenas de participantes (por exemplo, entre 24 e 40), o que, em um desenho com medidas repetidas para o fator uso de IA, tende a aumentar a sensibilidade dos testes em relação a um desenho puramente entre sujeitos.

Embora não seja realizado um cálculo formal de poder ex ante com base em tamanho de efeito esperado, a combinação de medidas repetidas (cada participante executa uma tarefa com IA e outra sem IA) e o uso de métricas contínuas (tempo, pontuação, cobertura, taxas) favorece a detecção de efeitos de magnitude moderada. Ao interpretar os resultados, a discussão levará em conta não apenas significância estatística, mas também tamanhos de efeito e intervalos de confiança, de modo a contextualizar a importância prática dos achados mesmo quando o poder estatístico não for ideal.

---

# 8. Variáveis, fatores, tratamentos e objetos de estudo

## 8.1 Objetos de estudo

Os objetos de estudo deste experimento são:

1. As user stories e seus critérios de aceitação, que servem como fonte de requisitos funcionais para derivação de casos de teste.
2. O sistema sob teste, composto por uma aplicação simples (por exemplo, uma API ou aplicação web de pequeno porte), preparada previamente com defeitos semeados de forma controlada.
3. Os conjuntos de casos de teste em linguagem natural produzidos pelos estudantes com base nas user stories.
4. Os testes automatizados implementados pelos estudantes, executados sobre o sistema sob teste.
5. As respostas a questionários objetivos de entendimento e questionários subjetivos de percepção, esforço, utilidade, confiança e dependência.

Esses objetos são manipulados e analisados com o objetivo de avaliar como o uso de IA impacta o processo de teste orientado por user stories.

---

## 8.2 Sujeitos / participantes (visão geral)

Os sujeitos do experimento serão estudantes de Engenharia de Software da PUC Minas, preferencialmente entre o terceiro e o sexto período, que já tenham cursado ao menos uma disciplina de programação e tenham tido contato introdutório com conceitos de testes de software. Os participantes atuarão individualmente nas tarefas experimentais, de forma voluntária, após receberem explicações sobre o objetivo do estudo e sobre as atividades a serem realizadas.

Um breve questionário de caracterização será aplicado para registrar informações como período cursado, experiência prévia em desenvolvimento de software, experiência com testes automatizados e nível de familiaridade com ferramentas de inteligência artificial na programação. Essas informações serão utilizadas como variáveis de contexto e possíveis variáveis de bloqueio ou controle.

---

## 8.3 Variáveis independentes (fatores) e seus níveis

O principal fator de interesse no experimento é o uso de IA. Além dele, considera-se a tarefa específica como fator contextual e potencial fator de bloqueio.

**Fator uso de IA**

- **Nível 1: Sem IA.** O participante executa a tarefa de leitura da user story, definição de casos de teste em linguagem natural e implementação de testes automatizados sem utilizar qualquer ferramenta de IA para apoio direto.
- **Nível 2: Com IA.** O participante executa a mesma sequência de atividades (leitura, definição e implementação de testes), mas pode utilizar uma ferramenta de IA aprovada, por exemplo um modelo de linguagem acessível via navegador, para apoiar entendimento, derivação de casos de teste e escrita de código de teste.

**Fator tarefa**

- **Nível 1: Tarefa A.** Conjunto específico de user story e módulo do sistema sob teste associados, com complexidade moderada e domínio funcional definido.
- **Nível 2: Tarefa B.** Outro conjunto de user story e módulo do sistema sob teste, também com complexidade comparável e domínio funcional similar, mas com variações suficientes para evitar mero reaproveitamento literal de soluções.

A combinação destes fatores configura um desenho aproximado de dois por dois, em que as condições principais de interesse são “com IA” e “sem IA”, e a tarefa serve como contexto e base para contrabalançar o efeito de ordem.

---

## 8.4 Tratamentos (condições experimentais)

As condições experimentais podem ser descritas em termos de tratamentos, definidos a partir da combinação entre o fator uso de IA e o fator tarefa. Em termos conceituais, existem duas condições principais:

- **Tratamento controle: Sem IA.** O estudante executa a tarefa designada sem acesso à ferramenta de IA para apoio à compreensão ou à geração de testes.
- **Tratamento com IA: Com IA.** O estudante executa a tarefa designada com acesso à ferramenta de IA, podendo utilizá-la para esclarecer dúvidas sobre a user story, sugerir casos de teste e auxiliar na escrita de testes automatizados.

Para organizar melhor essas condições em relação às tarefas, a tabela a seguir apresenta os fatores, seus tratamentos (níveis) e as combinações possíveis.

### Tabela de fatores, níveis e combinações de tratamento

| Combinação | Fator uso de IA | Fator tarefa | Descrição da condição                                   |
|-----------|------------------|-------------|---------------------------------------------------------|
| C1        | Sem IA           | Tarefa A    | Estudante executa Tarefa A sem uso de IA               |
| C2        | Sem IA           | Tarefa B    | Estudante executa Tarefa B sem uso de IA               |
| C3        | Com IA           | Tarefa A    | Estudante executa Tarefa A com uso de IA               |
| C4        | Com IA           | Tarefa B    | Estudante executa Tarefa B com uso de IA               |

Na prática do desenho escolhido, cada estudante deverá executar duas condições, por exemplo C1 e C4 ou C2 e C3, de forma que cada participante vivencie uma condição com IA e uma condição sem IA, em tarefas distintas. A distribuição das combinações entre os estudantes será planejada para que, no conjunto da amostra, as quatro combinações sejam representadas de maneira balanceada.

---

## 8.5 Variáveis dependentes (respostas)

As variáveis dependentes são as medidas de resultado que refletem o desempenho dos estudantes e os efeitos do uso de IA. Elas estão diretamente associadas às métricas definidas na seção de GQM. Em síntese:

**Variáveis de entendimento de requisitos**

- Pontuação de entendimento da user story, medida pelo questionário objetivo (M1).
- Proporção de critérios de aceitação corretamente identificados em linguagem natural (M2).
- Número de erros de interpretação relevantes nas descrições de casos de teste (M3).

**Variáveis de qualidade dos testes**

- Cobertura de código por linha (M4).
- Cobertura de código por ramo (M5).
- Proporção de critérios de aceitação cobertos por testes automatizados (M6).
- Número de defeitos semeados detectados (M7) e taxa de detecção de defeitos (M8).

**Variáveis de esforço e produtividade**

- Tempo total de tarefa (M9).
- Número de testes implementados (M10) e produtividade em testes por hora (M11).
- Esforço percebido (M12).

**Variáveis de percepção e aceitação**

- Confiança nos testes produzidos (M13).
- Frequência de uso da IA durante a tarefa (M14).
- Dependência percebida em relação à IA (M15).
- Utilidade percebida da IA para entender a user story (M16).

---

## 8.6 Variáveis de controle e de bloqueio

Alguns fatores não são o foco direto de estudo, mas podem influenciar os resultados se não forem considerados. Eles serão tratados como variáveis de controle ou de bloqueio.

- **Experiência prévia em programação:** tempo de estudo em programação e prática em projetos, medidos por questionário de perfil. Podem ser usados para agrupar participantes em faixas de experiência.
- **Experiência prévia com testes automatizados:** nível de familiaridade com frameworks de teste, também medido por questionário. Pode influenciar diretamente a qualidade dos testes produzidos.
- **Experiência prévia com IA em programação:** frequência de uso de ferramentas de IA antes do experimento. Estudantes muito acostumados com IA podem se comportar de maneira diferente de estudantes que nunca usaram.
- **Tarefa específica e ordem de execução:** tarefa A e tarefa B, bem como a ordem em que são executadas (com IA primeiro ou sem IA primeiro), serão usadas como mecanismos de contrabalanço para reduzir o efeito de aprendizagem e de fadiga.

Essas variáveis serão medidas e consideradas na análise, para reduzir a chance de que confundam a interpretação dos efeitos do fator principal uso de IA.

---

## 8.7 Possíveis variáveis de confusão conhecidas

Além das variáveis de controle, existem variáveis de confusão potenciais que podem influenciar os resultados e que, embora não possam ser totalmente controladas, serão monitoradas.

- **Motivação e engajamento:** o grau de motivação individual do estudante no dia do experimento pode impactar esforço, tempo e qualidade do trabalho. Questionários podem incluir questões simples de autoavaliação de motivação.
- **Carga de trabalho e cansaço:** estudantes com alta carga de provas, trabalhos ou cansaço físico podem apresentar desempenho diferente. Sempre que possível, o agendamento das sessões tentará evitar períodos de alta sobrecarga.
- **Familiaridade com o domínio do sistema sob teste:** estudantes que se identificam mais com o domínio funcional (por exemplo, cadastro, e-commerce) podem entender mais rapidamente as user stories. Esse aspecto poderá ser perguntado de forma simples em questionário.
- **Variações de ambiente:** diferenças entre ambiente de laboratório e ambiente pessoal (ruídos, distrações) podem influenciar tempo e esforço. A coleta registrará em que contexto cada sessão ocorreu.

Essas variáveis de confusão serão levadas em conta na interpretação dos resultados, reconhecendo que a validade externa e interna do estudo é influenciada também por esses fatores contextuais.

---

## 8.8 Tabela de variáveis e descrições

A tabela a seguir sintetiza as principais variáveis do experimento, seu tipo e uma breve descrição, bem como sua relação com as métricas quando aplicável.

| Nome da variável                  | Tipo                         | Descrição                                                                                                        | Métrica associada (quando houver) |
|-----------------------------------|------------------------------|------------------------------------------------------------------------------------------------------------------|------------------------------------|
| Uso de IA                         | Independente (fator)         | Indica se o participante executa a tarefa com acesso à ferramenta de IA ou sem acesso à IA                      | Não se aplica diretamente         |
| Tarefa (A ou B)                   | Fator / bloqueio             | Identifica qual conjunto de user story e módulo do sistema está sendo usado na tarefa                           | Não se aplica diretamente         |
| Entendimento da user story        | Dependente                   | Grau de entendimento da user story e critérios de aceitação                                                     | M1                                 |
| Identificação de critérios        | Dependente                   | Proporção de critérios de aceitação corretamente identificados                                                  | M2                                 |
| Erros de interpretação            | Dependente                   | Número de erros relevantes de interpretação presentes em casos de teste em linguagem natural                    | M3                                 |
| Cobertura por linha               | Dependente                   | Cobertura de código por linha obtida pelos testes automatizados                                                 | M4                                 |
| Cobertura por ramo                | Dependente                   | Cobertura de código por ramo obtida pelos testes automatizados                                                  | M5                                 |
| Cobertura de critérios de aceitação | Dependente                 | Proporção de critérios de aceitação com pelo menos um teste automatizado associado                              | M6                                 |
| Defeitos detectados               | Dependente                   | Número absoluto de defeitos semeados identificados pelos testes automatizados                                   | M7                                 |
| Taxa de detecção de defeitos      | Dependente                   | Proporção de defeitos semeados detectados em relação ao total de defeitos                                      | M8                                 |
| Tempo de tarefa                   | Dependente                   | Tempo total gasto na tarefa, do início da leitura da user story ao término dos testes                           | M9                                 |
| Número de testes implementados    | Dependente                   | Quantidade de testes automatizados implementados pelo participante                                              | M10                                |
| Produtividade em testes           | Dependente                   | Número de testes automatizados por hora de tarefa                                                               | M11                                |
| Esforço percebido                 | Dependente (subjetiva)       | Percepção do esforço necessário para realizar a tarefa                                                          | M12                                |
| Confiança nos testes              | Dependente (subjetiva)       | Grau de confiança do participante nos testes que produziu                                                       | M13                                |
| Uso efetivo da IA                 | Dependente / mediadora       | Intensidade de uso da IA durante a tarefa, mensurada por interações ou sugestões aceitas                        | M14                                |
| Dependência percebida da IA       | Dependente (subjetiva)       | Percepção do quanto o estudante sente que precisa da IA para executar a tarefa                                  | M15                                |
| Utilidade percebida da IA         | Dependente (subjetiva)       | Percepção da utilidade da IA para entender user stories e gerar testes                                          | M16                                |
| Experiência prévia em programação | Controle / contexto          | Nível de experiência em programação, medido por questionário                                                    | Não se aplica diretamente         |
| Experiência prévia em testes      | Controle / contexto          | Nível de experiência em testes automatizados                                                                    | Não se aplica diretamente         |
| Experiência prévia com IA         | Controle / contexto          | Frequência de uso de IA em programação antes do experimento                                                     | Não se aplica diretamente         |

Essa tabela resume de forma clara quais são as variáveis centrais do experimento, quais são manipuladas, quais são respostas, e quais são contextuais ou de controle.

---

# 9. Desenho experimental

## 9.1 Tipo de desenho

O desenho experimental adotado pode ser caracterizado como um desenho em blocos aleatorizados com medidas repetidas no fator uso de IA. Cada participante atua como um bloco, pois executa duas tarefas relacionadas, uma com uso de IA e outra sem uso de IA, em ordem contrabalançada. O fator uso de IA é, portanto, manipulado de forma intra-sujeitos (dentro de cada participante), enquanto a tarefa e a ordem de execução são utilizadas para evitar que os resultados sejam influenciados de forma sistemática por aprendizagem ou fadiga.

Esse tipo de desenho é adequado ao contexto porque:

1. Reduz a variabilidade entre sujeitos, uma vez que cada estudante é comparado consigo mesmo entre as condições com e sem IA.
2. Aproveita de forma eficiente o tamanho de amostra, que é limitado em um TCC de graduação.
3. Permite isolar, em maior grau, o efeito do fator uso de IA, controlando parcialmente diferenças individuais de habilidade, experiência e estilo de trabalho.

Embora exista um arranjo conceitual de fatores que lembra um desenho fatorial dois por dois (uso de IA por tarefa), o foco principal está no contraste entre condições com e sem IA, com as tarefas atuando como contextos distintos, mas comparáveis.

---

## 9.2 Randomização e alocação

A randomização será aplicada em dois pontos principais.

Primeiro, na definição da ordem de execução das condições para cada participante. Haverá pelo menos duas sequências possíveis, por exemplo:

- **Sequência S1:** Tarefa A sem IA, seguida de Tarefa B com IA.
- **Sequência S2:** Tarefa A com IA, seguida de Tarefa B sem IA.

Adicionalmente, podem ser definidas sequências que iniciem pela Tarefa B, de forma a diversificar ainda mais a ordem, como:

- **Sequência S3:** Tarefa B sem IA, seguida de Tarefa A com IA.
- **Sequência S4:** Tarefa B com IA, seguida de Tarefa A sem IA.

Os participantes serão alocados aleatoriamente a uma das sequências, de maneira aproximadamente balanceada. A randomização poderá ser feita utilizando uma ferramenta simples, como uma planilha com funções de aleatoriedade ou um script básico que gere números aleatórios.

Segundo, na atribuição das tarefas aos horários ou sessões, para evitar que um determinado horário fique concentrado em uma única combinação de fatores. Isso ajuda a reduzir o risco de viés decorrente de fatores externos associados ao horário ou ao dia da semana.

---

## 9.3 Balanceamento e contrabalanço

O balanceamento refere-se a garantir que, no conjunto da amostra, haja números semelhantes de participantes em cada combinação relevante de fatores. Especificamente, o objetivo é que:

1. A quantidade de participantes que inicia sem IA e depois usa IA seja semelhante à quantidade de participantes que inicia com IA e depois atua sem IA.
2. A Tarefa A e a Tarefa B apareçam em proporções semelhantes nas condições com e sem IA.

O contrabalanço é a estratégia utilizada para mitigar efeitos de ordem e de aprendizagem. Ao alternar a ordem das condições (IA primeiro ou IA depois) e a ordem das tarefas (Tarefa A ou Tarefa B primeiro), busca-se evitar que a segunda tarefa seja sempre beneficiada por um efeito de aprendizagem ou prejudicada por cansaço. Com as sequências definidas (S1 a S4), o pesquisador buscará distribuir os participantes de forma que todas as sequências sejam preenchidas, dentro do possível.

Na análise de dados, será possível verificar se a ordem teve impacto relevante, comparando resultados agregados por sequência. Caso algum efeito de ordem seja identificado, ele será discutido como limitação e, quando possível, controlado estatisticamente.

---

## 9.4 Número de grupos e sessões

Com base no desenho definido, a estrutura de grupos e sessões será organizada da seguinte forma.

**Condições principais**

- **Condição controle:** tarefas executadas sem uso de IA.
- **Condição tratamento:** tarefas executadas com uso de IA.

**Grupos por sequência**

Os participantes não serão divididos em grupos fixos que fiquem em apenas uma condição. Em vez disso, cada participante comporá dois grupos lógicos: em uma sessão, integrará o conjunto de observações da condição sem IA; em outra sessão, integrará o conjunto de observações da condição com IA. A combinação de ordem e tarefa define as sequências S1 a S4.

**Sessões**

Cada participante participará de duas sessões de experimento, que podem ocorrer em um mesmo encontro estendido (por exemplo, duas horas consecutivas) ou em dois encontros próximos, a depender da organização logística. Em cada sessão, o estudante receberá uma user story e um módulo do sistema sob teste, executará a leitura, derivará casos de teste em linguagem natural, implementará testes automatizados, executará os testes e preencherá os questionários correspondentes.

**Número de participantes**

O número exato de participantes será definido de acordo com a disponibilidade, mas o planejamento considera um mínimo desejável de 24 estudantes, distribuídos de forma aproximadamente uniforme entre as sequências possíveis. Esse número permite que a análise estatística obtenha estimativas razoáveis de médias e variâncias, e que comparações entre as condições com e sem IA sejam realizadas com um mínimo de robustez.

Em síntese, o desenho experimental busca um equilíbrio entre rigor metodológico e viabilidade prática em contexto de TCC, aproveitando medidas repetidas para aumentar a sensibilidade às diferenças entre condições, utilizando randomização para minimizar viés, e aplicando balanceamento e contrabalanço para reduzir efeitos de ordem e efeitos específicos de tarefa.
## 10. População, sujeitos e amostragem

### 10.1 População-alvo

A população-alvo que este experimento busca representar é composta por estudantes de graduação em Engenharia de Software (e cursos diretamente relacionados à Computação) inseridos em instituições de ensino superior com perfil semelhante ao da PUC Minas. O foco são estudantes em períodos intermediários ou avançados, que já têm experiência básica com programação e contato inicial com testes de software, e que executam atividades práticas de desenvolvimento orientadas por user stories em disciplinas de laboratório, projetos integradores ou trabalhos práticos.

Em termos de generalização, os resultados pretendem ser transferíveis, principalmente, para:

1. Estudantes de Engenharia de Software, Sistemas de Informação, Ciência da Computação e áreas afins que realizam tarefas de leitura de user stories, derivação de casos de teste e implementação de testes automatizados em sistemas de pequeno e médio porte.
2. Contextos acadêmicos em que esses estudantes desempenham um papel análogo ao de desenvolvedores ou testadores júnior, com responsabilidades de entendimento de requisitos, escrita de testes e uso crescente de ferramentas de inteligência artificial como apoio.

Embora a coleta ocorra em um contexto específico (PUC Minas), a definição conceitual da população-alvo permite que o experimento dialogue com outras instituições que apresentam estrutura de curso, perfil de estudante e práticas pedagógicas semelhantes.

---

### 10.2 Critérios de inclusão de sujeitos

Para que o experimento produza resultados coerentes com seu objetivo e continue exequível no contexto de um TCC, são estabelecidos critérios claros de inclusão. Poderão participar estudantes que:

1. Estejam regularmente matriculados no curso de Engenharia de Software da PUC Minas (ou, eventualmente, em cursos correlatos de Computação, caso seja acordado com a coordenação e o orientador).
2. Estejam posicionados entre o terceiro e o sétimo período do curso, o que garante que já tenham cursado pelo menos uma disciplina de programação básica e, idealmente, alguma disciplina que introduza testes de software, ainda que de forma inicial.
3. Possuam capacidade de compreender textos técnicos em português, ler user stories e manipular projetos simples em um ambiente de desenvolvimento como Visual Studio Code.
4. Tenham disponibilidade para participar de duas sessões experimentais, conforme descrito no desenho experimental (uma tarefa com uso de IA e outra tarefa sem uso de IA).
5. Aceitem participar de forma voluntária, registrando ciência em termo de consentimento que descreve objetivos, procedimentos, riscos mínimos, confidencialidade e direito de desistência.

Esses critérios asseguram que os participantes tenham condições mínimas para realizar as tarefas previstas, sem exigir um nível de especialização que inviabilize o recrutamento no contexto da graduação.

---

### 10.3 Critérios de exclusão de sujeitos

Alguns sujeitos, mesmo pertencendo ao público-alvo em sentido amplo, podem introduzir viés ou encontrar dificuldades que comprometam a execução do experimento. Assim, serão excluídos:

1. Estudantes diretamente envolvidos no planejamento e implementação do experimento, do sistema sob teste ou dos instrumentos de coleta (por exemplo, colegas que ajudaram a semear defeitos, montar o repositório ou definir questionários), para evitar conflito de interesse e conhecimento prévio excessivo das tarefas.
2. Estudantes com experiência profissional muito avançada em testes automatizados ou uso intensivo de IA em desenvolvimento, quando essa experiência destoar fortemente do perfil médio da turma e puder distorcer a amostra, transformando-os em outliers sistemáticos.
3. Estudantes que, por agenda, saúde, questões técnicas ou outras limitações, não tenham condições de comparecer às duas sessões previstas ou de utilizar o ambiente de desenvolvimento e as ferramentas mínimas (editor, framework de teste, ferramenta de IA na condição correspondente).
4. Estudantes que não estejam autorizados, por políticas institucionais ou pessoais, a utilizar ferramentas de IA no contexto de atividades acadêmicas, quando isso inviabilizar sua participação na condição “com IA”.
5. Estudantes muito iniciantes que ainda não cursaram disciplinas básicas de programação e claramente não conseguiriam compreender o código do sistema sob teste, ainda que simplificado.

Esses critérios de exclusão reforçam a validade interna do estudo e preservam a ética, ao mesmo tempo em que mantêm o experimento viável para o pesquisador.

---

### 10.4 Tamanho da amostra planejado

O tamanho da amostra precisa equilibrar três aspectos: poder estatístico mínimo, recursos disponíveis e tempo de execução compatível com um TCC. Considerando isso, o plano prevê:

1. Um tamanho total desejável entre aproximadamente vinte e quarenta estudantes (por exemplo, entre 24 e 40 participantes), dependendo da adesão obtida no recrutamento.
2. Cada participante executa duas condições (uma tarefa com IA e outra tarefa sem IA), o que caracteriza um desenho com medidas repetidas. Assim, mesmo um número moderado de participantes aumenta a capacidade de detectar diferenças entre condições, pois cada estudante serve parcialmente como seu próprio controle.
3. As observações não são organizadas em grupos fixos independentes, mas sim em conjuntos de observações por condição: haverá um conjunto de medidas para a condição “Sem IA” e outro para a condição “Com IA”, ambos alimentados pelos mesmos sujeitos em momentos distintos.
4. O planejamento de análise (t-teste pareado ou testes não paramétricos equivalentes) é adequado para amostras nessa ordem de grandeza, permitindo investigar diferenças de magnitude moderada em métricas como entendimento (M1), cobertura (M4, M5), taxa de detecção de defeitos (M8), tempo (M9) e esforço percebido (M12).

Assim, o tamanho de amostra pensado é factível para um experimento conduzido por um único estudante de TCC e suficiente para produzir resultados analisáveis.

---

### 10.5 Método de seleção e recrutamento

O recrutamento dos sujeitos seguirá uma estratégia de amostragem por conveniência com convite aberto, que é comum em estudos empíricos conduzidos no contexto de disciplinas de graduação. O procedimento geral será:

1. Selecionar, em conjunto com docentes e coordenação, uma ou mais turmas de disciplinas práticas de programação, engenharia de requisitos, qualidade ou testes de software, nas quais haja estudantes que se encaixem nos critérios de inclusão.
2. Apresentar o experimento em sala (presencial ou virtual) de forma breve e clara, explicando objetivo, natureza acadêmica do estudo, atividades previstas, duração estimada das sessões e benefícios esperados para a aprendizagem.
3. Disponibilizar um formulário eletrônico de manifestação de interesse e caracterização básica, onde o estudante informa seus dados de contato, período, experiência prévia com programação, testes e IA, além de horários preferenciais.
4. Aplicar os critérios de inclusão e exclusão descritos anteriormente. Se o número de interessados elegíveis ultrapassar a capacidade de execução (por exemplo, mais de quarenta candidatos), utilizar uma seleção que priorize diversidade de períodos e de experiência, podendo recorrer a sorteio simples para completar a amostra de forma justa.
5. Uma vez selecionados, agendar as sessões, comunicando os participantes com antecedência, e esclarecer que a participação é voluntária, não vinculada diretamente à nota, podendo eventualmente ser reconhecida como atividade complementar, desde que isso seja acordado com a coordenação e não introduza pressão indevida.

Esse processo é simples o bastante para ser executado por um único pesquisador, ao mesmo tempo em que garante transparência e alinhamento com a realidade das turmas.

---

### 10.6 Treinamento e preparação dos sujeitos

Antes das tarefas experimentais, será realizada uma preparação breve e padronizada dos participantes, com o objetivo de reduzir desigualdades básicas de entendimento e evitar que o experimento meça somente quem já domina conceitos avançados de testes ou IA. Esse treinamento é compatível com o que já está descrito no desenho experimental e pode ser realizado em uma única sessão curta (Sessão 0).

Nessa sessão, o pesquisador retomará os conceitos essenciais: o que é uma user story, quais são seus elementos típicos e a importância dos critérios de aceitação como ponte entre requisitos e testes; o que se entende por casos de teste em linguagem natural e por testes automatizados de unidade ou integração em um projeto simples. Em seguida, apresentará o sistema sob teste de maneira pragmática, descrevendo o domínio funcional, a organização dos arquivos e o comando a ser utilizado para executar os testes e gerar relatórios de cobertura.

Os participantes receberão um pequeno guia escrito com instruções resumidas sobre abertura do projeto no editor de código, execução dos testes, preenchimento do template de casos de teste e regras sobre quando a IA pode ou não ser utilizada. Essa preparação é suficiente para nivelar o entendimento mínimo necessário, sem transformar o experimento em uma disciplina adicional, e mantém o protocolo exequível para o pesquisador dentro do cronograma de TCC.

---

## 11. Instrumentação e protocolo operacional

### 11.1 Instrumentos de coleta de dados

A instrumentação do experimento foi planejada para alinhar claramente cada instrumento às métricas definidas (M1 a M16) e às variáveis apresentadas nas seções anteriores. A ideia é que todo dado importante seja coletado com o mínimo de atrito para o participante e com esforço de consolidação compatível com o tempo de um TCC.

A tabela a seguir resume os principais instrumentos de coleta e sua relação com as métricas:

| Instrumento / Artefato                          | Papel no experimento                                                                                      | Principais métricas associadas      |
| ----------------------------------------------- | --------------------------------------------------------------------------------------------------------- | ----------------------------------- |
| Questionário de caracterização inicial          | Coletar dados de perfil, experiência prévia em programação, testes e uso de IA                            | Variáveis de controle (experiência) |
| Questionário de entendimento da user story      | Medir compreensão objetiva da user story e dos critérios de aceitação                                     | M1                                  |
| Template de casos de teste em linguagem natural | Registrar os casos de teste definidos pelos participantes a partir da user story                          | M2, M3                              |
| Código de testes automatizados produzidos       | Base principal para cálculo de cobertura, detecção de defeitos e produtividade em testes                  | M4, M5, M6, M7, M8, M10, M11        |
| Sistema sob teste com defeitos semeados         | Fornecer o ambiente controlado para execução dos testes e avaliação da detecção de defeitos               | Base conceitual para M7, M8         |
| Ferramenta de cobertura de código               | Gerar relatórios de cobertura por linha e por ramo em cada condição                                       | M4, M5                              |
| Registro de tempo (cronômetro, script ou log)   | Registrar horário de início e término de cada tarefa                                                      | M9                                  |
| Questionário pós-tarefa                         | Levantar percepção de esforço, confiança, utilidade e dependência em relação à IA após cada tarefa        | M12, M13, M15, M16                  |
| Registro estruturado de uso da IA               | Medir a frequência de interações relevantes com a ferramenta de IA na condição em que seu uso é permitido | M14                                 |
| Planilha de consolidação de dados               | Reunir, em um único local, todas as métricas M1–M16 por participante e por condição                       | Consolidação de todas as métricas   |

Esses instrumentos são tecnicamente simples (questionários online, planilhas, scripts de cobertura já integrados ao framework de teste) e podem ser facilmente operados por um único pesquisador.

---

### 11.2 Materiais de apoio e instruções

Além dos instrumentos de coleta, o experimento contará com materiais de apoio que visam tornar o protocolo repetível e reduzir dúvidas operacionais, tanto para os participantes quanto para o pesquisador. Serão preparados, por exemplo:

1. Um roteiro detalhado do experimentador, com o texto básico a ser utilizado na abertura das sessões, na apresentação do estudo, nos lembretes sobre uso adequado da IA e nas explicações sobre preenchimento dos questionários e templates. Esse roteiro ajuda a evitar variações indesejadas entre sessões.
2. Um guia do participante, em formato breve, disponibilizado em PDF ou impresso, contendo instruções passo a passo sobre como abrir o projeto no editor de código, como executar os testes automatizados, como preencher o template de casos de teste em linguagem natural e quais são as regras de uso ou não uso da ferramenta de IA em cada tarefa.
3. Uma pequena apresentação em slides para a Sessão 0, explicitando de maneira visual o papel das user stories, dos critérios de aceitação, dos testes automatizados e do experimento em si, reforçando que a IA é um fator a ser estudado e não uma obrigação.
4. O termo de consentimento, que descreve objetivos, procedimentos, riscos mínimos, sigilo e direitos dos participantes, garantindo transparência ética.

Esses materiais não apenas tornam a condução mais organizada, mas também reforçam a legitimidade do estudo como parte de um TCC sólido e bem planejado.

---

### 11.3 Procedimento experimental (protocolo operacional)

O protocolo operacional organiza o experimento em uma sequência clara de etapas, desde o recrutamento até a consolidação dos dados. A estrutura é compatível com o desenho descrito nas seções 8 e 9, em que cada participante realiza duas tarefas (uma com IA e outra sem IA) em sessões separadas, com contrabalanço entre ordem e tarefa.

Em termos narrativos, o procedimento ocorre da seguinte forma:

1. O pesquisador, após finalizar a preparação do sistema sob teste, dos questionários, templates e scripts de cobertura, realiza o recrutamento de participantes nas turmas selecionadas, aplica os critérios de inclusão e exclusão e organiza os horários de sessão.
2. Antes das tarefas principais, é realizada a Sessão 0, em que os participantes recebem explicações sobre o objetivo do estudo, os conceitos básicos necessários (user stories, critérios de aceitação, testes automatizados, papel da IA) e as instruções gerais. Nessa sessão, os participantes fornecem consentimento e, se ainda não o fizeram, preenchem o questionário de caracterização inicial.
3. Na Sessão 1, cada participante inicia sua primeira tarefa, que pode ser com IA ou sem IA e com a Tarefa A ou B, dependendo da sequência à qual foi aleatoriamente alocado. O pesquisador registra o horário de início, entrega a user story e os critérios de aceitação correspondentes, e o participante define casos de teste em linguagem natural utilizando o template fornecido. Em seguida, o participante implementa os testes automatizados no projeto, executa os testes, gera relatórios de cobertura e, ao finalizar, informa o término da tarefa, registrando o tempo total. Ao final, preenche o questionário pós-tarefa, incluindo esforço percebido, confiança e, na condição com IA, utilidade e dependência. O uso da IA (número de interações relevantes) é registrado para compor a métrica M14.
4. Na Sessão 2, o participante realiza a tarefa complementar, em condição espelho: se na primeira sessão trabalhou sem IA, agora trabalha com IA; se antes executou a Tarefa A, agora executa a Tarefa B, ou vice-versa. O protocolo é o mesmo: leitura da user story, definição de casos de teste, implementação de testes, execução, registro de tempo e preenchimento do questionário pós-tarefa.
5. Após concluídas as sessões de todos os participantes, o pesquisador consolida os dados coletados: importa os resultados dos questionários, extrai relatórios de cobertura, contabiliza defeitos semeados detectados, centraliza métricas M1 a M16 em uma planilha única e verifica consistência básica dos registros. Essa planilha alimentará diretamente o plano de análise de dados.

Esse fluxo é simples o suficiente para ser executado dentro do tempo de um semestre de TCC, especialmente se as sessões forem organizadas aproveitando horários de aula ou laboratórios previamente reservados.

#### 11.3.1 Fluxograma da operacionalização do experimento

Para sintetizar a visão operacional, o fluxograma abaixo apresenta o encadeamento das principais etapas, destacando instrumentos, variáveis, métricas e stakeholders envolvidos em cada fase.

```text
┌────────────────────────────────────────────────────────────────────────┐
│                     Planejamento e Preparação                         │
│ - Definição de objetivos, hipóteses e métricas (M1–M16)               │
│ - Preparação do sistema sob teste com defeitos semeados               │
│ - Criação de questionários, templates, scripts de cobertura           │
│ Stakeholders: pesquisador, orientador                                 │
└───────────────────────────┬────────────────────────────────────────────┘
                            │
                            ▼
┌────────────────────────────────────────────────────────────────────────┐
│                 Recrutamento e Seleção de Participantes               │
│ - Convite a estudantes elegíveis                                      │
│ - Aplicação de critérios de inclusão/exclusão                         │
│ - Alocação aleatória nas sequências (S1, S2, S3, S4)                  │
│ Stakeholders: estudantes, docentes, coordenação                        │
└───────────────────────────┬────────────────────────────────────────────┘
                            │
                            ▼
┌────────────────────────────────────────────────────────────────────────┐
│                 Sessão 0 – Treinamento e Consentimento                │
│ - Explicação do experimento e termo de consentimento                  │
│ - Nivelamento sobre user stories, testes automatizados e IA           │
│ - Demonstração do sistema sob teste                                   │
│ Instrumentos: slides, guia do participante, termo de consentimento    │
└───────────────────────────┬────────────────────────────────────────────┘
                            │
                            ▼
┌────────────────────────────────────────────────────────────────────────┐
│                   Sessão 1 – Tarefa 1 (Com ou Sem IA)                 │
│ - Registro de início (tempo M9)                                       │
│ - Entrega da user story (Tarefa A ou B)                               │
│ - Preenchimento de casos de teste em linguagem natural                │
│   (M2, M3; entendimento apoiado por M1)                               │
│ - Implementação de testes automatizados                               │
│   (M4, M5, M6, M7, M8, M10, M11)                                      │
│ - Execução de testes e coleta de cobertura                            │
│ - Registro de término (M9)                                            │
│ - Questionário pós-tarefa (M12, M13, M15, M16)                        │
│ - Registro de uso da IA (M14) se for condição com IA                  │
└───────────────────────────┬────────────────────────────────────────────┘
                            │
                            ▼
┌────────────────────────────────────────────────────────────────────────┐
│                  Sessão 2 – Tarefa 2 (Condição Espelho)               │
│ - Repetição do fluxo de Sessão 1                                      │
│ - Troca de condição (Sem IA ↔ Com IA) e de tarefa (A ↔ B)             │
│ - Coleta das mesmas métricas M1–M16                                   │
└───────────────────────────┬────────────────────────────────────────────┘
                            │
                            ▼
┌────────────────────────────────────────────────────────────────────────┐
│                     Consolidação e Checagem de Dados                  │
│ - Consolidação de M1–M16 em planilha                                  │
│ - Verificação de consistência e dados faltantes                       │
│ Stakeholders: pesquisador, orientador                                 │
└───────────────────────────┬────────────────────────────────────────────┘
                            │
                            ▼
┌────────────────────────────────────────────────────────────────────────┐
│                      Análise, Interpretação e Relato                  │
│ - Aplicação dos métodos estatísticos e qualitativos planejados        │
│ - Resposta às questões Q1.1–Q4.3                                      │
│ - Elaboração das seções de resultados, discussão e conclusões do TCC  │
│ Stakeholders: pesquisador, orientador, banca, comunidade acadêmica    │
└────────────────────────────────────────────────────────────────────────┘
```

Esse fluxograma reforça que o experimento está operacionalmente bem definido, com vínculos claros entre etapas, métricas e atores envolvidos.

---

### 11.4 Plano de piloto

Antes da execução completa, será conduzido um estudo piloto em escala reduzida, com um pequeno grupo de estudantes que tenham perfil semelhante ao da amostra principal. Esse piloto tem papel crucial para ajustar o desenho à realidade e manter o experimento executável dentro do contexto do TCC.

O piloto utilizará o mesmo sistema sob teste, os mesmos instrumentos e uma versão compacta do protocolo (Sessão 0, Sessão 1 e Sessão 2), aplicada a três a cinco participantes. O objetivo principal é verificar se o tempo estimado para cada tarefa é adequado, se as instruções são claras, se a complexidade da user story e dos defeitos semeados é compatível com o tempo de sessão e se os instrumentos (questionários, scripts de cobertura, registros de tempo, uso de IA) funcionam sem falhas.

Com base nas observações do piloto, poderão ser realizados ajustes pontuais, por exemplo: simplificar ligeiramente a user story ou reduzir o número de critérios de aceitação, aumentar ou reduzir o tempo disponível para cada tarefa, esclarecer trechos do guia do participante que tenham gerado dúvidas, ou corrigir problemas técnicos de execução de testes e geração de cobertura. Todos os ajustes serão documentados, mantendo a transparência metodológica e garantindo que a versão final do protocolo seja realista para o conjunto de participantes do estudo principal.

---

## 12. Plano de análise de dados (pré-execução)

### 12.1 Estratégia geral de análise

O plano de análise de dados foi definido de forma antecipada para alinhar diretamente as métricas (M1 a M16) às questões de pesquisa (Q1.1 a Q4.3) e aos objetivos específicos (O1 a O4). A estratégia combina análise quantitativa (dados numéricos) e análise qualitativa (comentários e respostas abertas), buscando não apenas verificar diferenças estatísticas, mas também entender como os participantes perceberam o uso de IA nas tarefas de entendimento de user stories e geração de testes.

A primeira etapa consiste em uma análise descritiva das métricas, separando os resultados por condição (“Com IA” e “Sem IA”). Serão calculadas medidas como média, mediana, desvio padrão, valores mínimos e máximos para métricas como M1 (entendimento), M4 e M5 (cobertura de código), M7 e M8 (defeitos detectados e taxa de detecção), M9 (tempo de tarefa), M10 e M11 (número de testes e produtividade), bem como M12, M13, M15 e M16 (percepções de esforço, confiança, dependência e utilidade). Isso fornecerá uma visão inicial do comportamento dos dados.

Em seguida, serão realizadas comparações entre as condições para cada métrica central, respeitando o desenho com medidas repetidas. Por exemplo, será comparado, para cada participante, o valor de M1 na tarefa sem IA com o valor de M1 na tarefa com IA; o mesmo será feito para M4, M5, M8, M9 e demais métricas de interesse. Com isso, pretende-se responder diretamente se o uso de IA está associado a aumento de entendimento, maior cobertura, melhor detecção de defeitos ou redução de tempo e esforço.

Finalmente, os resultados quantitativos serão interpretados à luz de informações qualitativas oriundas dos questionários pós-tarefa (por exemplo, comentários sobre como a IA ajudou ou atrapalhou) e das observações feitas durante o piloto e as sessões principais, buscando uma compreensão mais rica do fenômeno estudado.

---

### 12.2 Métodos estatísticos planejados

Os métodos estatísticos foram escolhidos considerando o tamanho de amostra esperado, o desenho com medidas repetidas e a natureza das métricas. Para cada métrica numérica relevante (como M1, M4, M5, M8, M9, M10, M11), será avaliada a distribuição das diferenças entre condições (valor na condição “Com IA” menos valor na condição “Sem IA”) por meio de testes de normalidade e inspeção gráfica.

Quando a distribuição dessas diferenças se mostrar razoavelmente próxima da normalidade, o método principal para comparação entre “Com IA” e “Sem IA” será o teste t pareado, que é adequado a dados emparelhados. Quando a normalidade não for atendida, serão utilizados testes não paramétricos equivalentes, como o teste de Wilcoxon para amostras pareadas, que não exigem pressupostos tão fortes sobre a forma da distribuição.

Para explorar a influência simultânea do fator uso de IA e da tarefa (A ou B), poderá ser utilizada, quando viável, uma análise de variância com medidas repetidas, em que o uso de IA é tratado como fator intra-sujeitos e a tarefa como fator adicional ou bloqueio. Caso o tamanho da amostra ou os pressupostos limitem esse tipo de análise, serão realizadas análises estratificadas por tarefa e inspeções gráficas das interações, mantendo a coerência com o nível de complexidade esperado em um TCC.

Além das comparações entre condições, podem ser investigadas correlações entre certas variáveis, como o uso efetivo da IA (M14) e o ganho em cobertura (M4, M5) ou taxa de detecção de defeitos (M8), usando coeficientes de correlação adequados (por exemplo, Spearman) quando os dados não forem estritamente normais ou envolverem escalas ordinais. Em todas as análises, além do p-valor, serão calculadas medidas de tamanho de efeito (como Cohen’s d para comparações pareadas ou estatísticas derivadas de testes não paramétricos), de forma a discutir não apenas se há diferença, mas também qual é a magnitude prática dessa diferença no contexto do experimento.

---

### 12.3 Tratamento de dados faltantes e outliers

O tratamento de dados faltantes e valores extremos será definido previamente para evitar decisões ad hoc após a observação dos resultados. No caso de participantes que não completarem uma das duas tarefas previstas (por exemplo, apenas a tarefa com IA ou apenas a tarefa sem IA), seus dados poderão ser utilizados em análises descritivas, mas não serão incluídos nas comparações pareadas que exigem medidas em ambas as condições para o mesmo sujeito.

Quando métricas específicas estiverem ausentes (como um questionário pós-tarefa não preenchido ou um relatório de cobertura não gerado), não serão realizadas imputações complexas; em vez disso, será adotada análise por caso disponível, deixando claro, para cada teste estatístico, quantas observações foram utilizadas.

Para identificação de outliers, serão examinadas distribuições de métricas como tempo (M9), número de testes (M10) e cobertura (M4, M5), por meio de gráficos (boxplots, histogramas) e critérios simples, como valores muito além do intervalo interquartil. Quando um valor extremo puder ser claramente atribuído a erro de registro (por exemplo, tempo igual a zero por esquecimento de registrar o início), será corrigido se houver informação confiável ou excluído daquela análise específica. Quando o valor extremo for plausível (por exemplo, um participante demorou muito mais por dificuldades reais), não será removido automaticamente; nesse caso, podem ser feitas análises de sensibilidade, com e sem o outlier, e qualquer influência importante será discutida na seção de ameaças à validade do TCC.

---

### 12.4 Plano de análise para dados qualitativos

Os dados qualitativos coletados por meio de respostas abertas nos questionários pós-tarefa e de comentários espontâneos durante o piloto e as sessões principais servirão para complementar a análise estatística e explicar padrões observados nas métricas numéricas.

Primeiro, todas as respostas abertas serão reunidas em um único documento ou planilha, com os dados devidamente anonimizados. Em seguida, será feita uma leitura exploratória, identificando temas recorrentes, como percepções de que a IA ajudou a lembrar casos de borda, sensações de dependência excessiva, relatos de confusão gerada por sugestões incorretas da IA ou de ganho de segurança na definição de testes. Esses trechos serão marcados com códigos curtos (por exemplo, “ganho de cobertura percebido”, “dependência”, “IA confusa”) em um processo de codificação inicial.

Na etapa seguinte, esses códigos serão agrupados em categorias mais amplas, como benefícios percebidos, riscos percebidos, estratégias de uso da IA e percepções sobre aprendizado. A partir dessas categorias, será realizada uma análise temática simples, buscando relacionar os temas qualitativos com os resultados quantitativos. Por exemplo, pode-se observar se participantes que relatam alta dependência da IA também apresentam valores elevados em M15 (dependência percebida) e se isso se reflete ou não em melhorias reais em cobertura (M4, M5) ou taxa de defeitos detectados (M8).

Por fim, na redação dos resultados e da discussão do TCC, serão utilizadas citações representativas (anonimizadas) para ilustrar e enriquecer a interpretação dos achados estatísticos, mostrando como os estudantes, na prática, vivenciaram o uso de IA nas tarefas de entendimento de user stories e geração de testes automatizados. Dessa forma, o plano de análise qualitativa reforça o caráter empírico do trabalho e aprofunda a compreensão sobre o fenômeno em estudo, mantendo-se plenamente exequível dentro do escopo de um TCC.

