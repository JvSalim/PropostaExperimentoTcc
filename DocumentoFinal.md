# 1. Identificação básica

## 1.1 Título do experimento

Avaliação experimental do uso de ferramentas de inteligência artificial no entendimento de user stories e na geração de testes automatizados.

## 1.2 ID / código

EXP-IA-US-TESTES-2025

## 1.3 Versão do documento e histórico de revisão

Versão atual do documento: v1.0.  
Histórico de revisão: v1.0 – elaboração inicial do plano de experimento para o TCC.

## 1.4 Datas (criação, última atualização)

Data de criação do plano de experimento: 23/11/2025.  
Data da última atualização desta versão: 23/11/2025.

## 1.5 Autores (nome, área, contato)

Autor: João Victor Salim Ribeiro Guimarães Trad (João Victor Salim).  
Área: Engenharia de Software.  
Vínculo: Estudante do sexto período de Engenharia de Software na Pontifícia Universidade Católica de Minas Gerais (PUC Minas).  
Contato: joao.trad@sga.pucminas.br

## 1.6 Responsável principal (PI / dono do experimento)

Responsável principal (PI) pelo experimento: João Victor Salim Ribeiro Guimarães Trad, estudante do sexto período de Engenharia de Software na Pontifícia Universidade Católica de Minas Gerais, responsável por todas as decisões científicas e operacionais do estudo.

## 1.7 Projeto / produto / iniciativa relacionada

Este experimento está diretamente relacionado ao Trabalho de Conclusão de Curso em Engenharia de Software, cujo tema versa sobre o uso de ferramentas de inteligência artificial para apoiar o entendimento de requisitos expressos como user stories e a geração de testes automatizados. O estudo está inserido em uma iniciativa acadêmica maior de investigação sobre o impacto de ferramentas de IA no processo de desenvolvimento e qualidade de software, tema de alta relevância na indústria de tecnologia e na formação de engenheiros de software contemporâneos.

Do ponto de vista de produto, o experimento estará associado a um ou mais sistemas de pequeno e médio porte utilizados como base de testes, tais como uma API de serviços, um módulo de aplicação web ou um conjunto de katas de programação, que servirão de sistema sob teste para os participantes gerarem testes automatizados. Esses sistemas serão organizados em repositórios controlados (por exemplo, em uma plataforma de versionamento como GitHub ou GitLab), vinculados explicitamente ao código do experimento EXP-IA-US-TST-2025, de forma a permitir replicação e reutilização em estudos futuros.

# 2. Contexto e problema

## 2.1 Descrição do problema / oportunidade

O desenvolvimento de software em ambientes ágeis costuma ser guiado por user stories, que descrevem o que o sistema deve fazer do ponto de vista do usuário, acompanhadas ou não de critérios de aceitação. Na prática, muitos estudantes e desenvolvedores iniciantes têm dificuldade em transformar essas histórias em casos de teste bem estruturados e em testes automatizados que realmente cubram os cenários importantes do negócio. Ao mesmo tempo, ferramentas de inteligência artificial que apoiam programação e testes, como assistentes de código e modelos de linguagem acessados via navegador, começaram a ser utilizadas espontaneamente por estudantes sem que exista clareza sobre o impacto real desse uso na compreensão das user stories e na qualidade dos testes gerados.

O problema central é que ainda não está claro se o uso dessas ferramentas de inteligência artificial ajuda os estudantes a entender melhor as user stories e a elaborar testes mais completos, ou se apenas acelera a escrita de código e de testes de forma superficial, deixando buracos na cobertura de cenários. Sinais observados em atividades práticas são, por exemplo, testes copiados e adaptados da ferramenta de IA sem relação precisa com os critérios de aceitação, repetição de cenários simples e ausência de testes para casos de erro e bordas, além de estudantes que relatam dificuldade em explicar o que os testes gerados realmente verificam.

Por outro lado, existe uma oportunidade clara de transformar essa prática em objeto de estudo estruturado. Ao planejar um experimento simples, conduzido por um estudante de Engenharia de Software, é possível comparar situações em que os participantes usam um assistente de IA na leitura da user story e na elaboração de testes, com situações em que isso não ocorre. Dessa forma, o trabalho pode produzir evidências concretas sobre os efeitos desse uso na compreensão dos requisitos e na qualidade dos testes, ajudando professores, estudantes e profissionais a tomar decisões mais embasadas sobre como e quando utilizar essas ferramentas em atividades de teste orientadas por user stories.

## 2.2 Contexto organizacional e técnico

O experimento será realizado em contexto acadêmico, no curso de Engenharia de Software da Pontifícia Universidade Católica de Minas Gerais. Os participantes serão estudantes de períodos intermediários ou avançados que já tiveram contato com programação e com noções básicas de testes de software. Esses participantes poderão ser recrutados em disciplinas práticas ou por convite direto, de forma voluntária. O ambiente não é uma empresa de software, mas busca simular de maneira simples uma situação real de desenvolvimento em que user stories são entregues a desenvolvedores para implementação e teste.

Do ponto de vista técnico, o experimento utilizará um cenário único e padronizado para todos os participantes, por exemplo uma pequena aplicação web ou uma API simples escrita em JavaScript com Node e testes em Jest, já implementada previamente. Esse sistema sob teste conterá funcionalidades claras e um conjunto de user stories curtas, além de defeitos semeados de forma controlada no código. Os participantes não precisarão criar a aplicação do zero. A tarefa principal será ler a user story, refinar e esclarecer o entendimento dessas histórias, definir casos de teste em linguagem natural e implementar testes automatizados utilizando o framework escolhido.

As ferramentas necessárias serão limitadas a um editor de código, como Visual Studio Code, um repositório preparado com o projeto base e, no grupo em que houver uso de inteligência artificial, o acesso a um assistente de IA, por exemplo um modelo de linguagem acessível via navegador, desde que autorizado pela instituição e conforme combinado no plano de pesquisa. O processo de desenvolvimento adotado no experimento será propositalmente simples. Cada participante realizará individualmente uma ou duas tarefas curtas, com tempo limitado, em uma sessão que poderá ocorrer em laboratório ou de forma remota com instruções claras. Isso torna o experimento exequível por um único estudante responsável, tanto em termos de preparação quanto de acompanhamento da execução e análise dos dados coletados.

## 2.3 Trabalhos e evidências prévias (internos e externos)

Na literatura de Engenharia de Software existem estudos que analisam a influência de user stories e de critérios de aceitação na qualidade do software, mostrando que requisitos mal escritos ou mal compreendidos tendem a gerar funcionalidades inconsistentes e conjuntos de testes incompletos. Há também trabalhos recentes que investigam o uso de assistentes de código baseados em inteligência artificial, avaliando produtividade, qualidade do código gerado e percepção dos desenvolvedores. Esses estudos costumam apontar ganhos de velocidade e sensação de apoio na programação, mas também alertam para o risco de aceitação acrítica de sugestões, introdução de defeitos e redução do entendimento profundo do código.

Em paralelo, estudos empíricos realizados em cursos de Engenharia de Software, mostram que estudantes frequentemente têm dificuldades em derivar casos de teste a partir de requisitos textuais. É comum observar testes que cobrem apenas o fluxo principal, ausência de casos de erro e fraca ligação entre o que está descrito na user story e o que é efetivamente verificado pelos testes automatizados. Em atividades práticas e projetos de disciplinas, muitos estudantes já utilizam ferramentas de IA para pedir exemplos de testes ou para pedir explicações sobre requisitos, mas esse uso raramente é medido de forma sistemática.

Esse conjunto de evidências sugere que o problema abordado pelo experimento é relevante e atual. Por um lado, já existem indícios de que a qualidade da ligação entre requisitos e testes é um ponto frágil. Por outro lado, o uso crescente de ferramentas de IA abre uma oportunidade para melhorar esse cenário, mas também traz novas incertezas. Ainda são raros os estudos simples, aplicáveis em contexto de graduação, que comparam diretamente tarefas de entendimento de user stories e elaboração de testes com e sem uso de IA, usando métricas objetivas e questionários para capturar a percepção dos participantes. O experimento proposto busca contribuir justamente nesse espaço, com um desenho enxuto e realizável por um estudante, mas com potencial para gerar resultados analisáveis e úteis.

## 2.4 Referencial teórico e empírico essencial

O referencial teórico que fundamenta o experimento combina quatro eixos principais. O primeiro eixo é a engenharia de requisitos, especialmente o uso de user stories em métodos ágeis. User stories podem ser vistas como uma forma de especificação leve que descreve uma necessidade do usuário, geralmente com uma estrutura padrão e com apoio de critérios de aceitação. A teoria destaca que a clareza, a completude e a ausência de ambiguidades nessas histórias influenciam diretamente a capacidade da equipe de implementar e testar corretamente as funcionalidades.

O segundo eixo é a teoria de testes de software. Testes de unidade e testes de integração simples, quando derivam de requisitos de forma sistemática, devem cobrir cenários típicos de uso, casos de erro e situações de fronteira. Métricas como número de casos de teste, cobertura de código e quantidade de defeitos descobertos em um código com falhas semeadas são formas práticas de avaliar a qualidade do conjunto de testes. Em um experimento simples, basta comparar essas métricas entre tarefas realizadas com e sem uso de inteligência artificial, mantendo o mesmo sistema sob teste e user stories equivalentes.

O terceiro eixo é o uso de inteligência artificial aplicada ao desenvolvimento de software. Assistentes de código e modelos de linguagem podem apoiar o desenvolvedor na interpretação de textos, na sugestão de casos de teste em linguagem natural e na geração de trechos de código de teste. Do ponto de vista teórico, essas ferramentas podem atuar como apoio cognitivo na leitura da user story ou como gerador automático de exemplos. Ao mesmo tempo, a teoria alerta que apoio não é garantia de entendimento. Se o estudante aceita as sugestões sem análise crítica, a ferramenta pode reforçar lacunas de compreensão ou esconder defeitos sutis.

O quarto eixo é a engenharia de software empírica, que traz princípios para planejar experimentos controlados em desenvolvimento de software. Um desenho simples, adequado ao nível de TCC, pode consistir em tarefas individuais em que cada participante realiza uma atividade sem uso de IA e outra com uso de IA, em ordem alternada entre os participantes, de modo que cada pessoa funcione parcialmente como seu próprio controle. Em cada tarefa, o participante recebe uma user story, define casos de teste em texto e implementa testes automatizados. O pesquisador mede, por exemplo, quantos casos de teste foram criados, se eles cobrem os critérios de aceitação, qual a cobertura de código obtida e quantos defeitos semeados foram encontrados. Questionários curtos permitem capturar a percepção de entendimento e de esforço.

Esse conjunto de conceitos e resultados empíricos oferece base suficiente para justificar o experimento proposto. Ele mostra que há teoria consolidada sobre user stories, testes e experimentação em engenharia de software, ao mesmo tempo em que aponta lacunas específicas relacionadas ao uso de inteligência artificial em tarefas de entendimento de requisitos e geração de testes. O desenho escolhido é intencionalmente mais simples, para ser exequível por um estudante de graduação, mas ainda assim capaz de produzir dados que permitam testar hipóteses claras e gerar conclusões úteis para a prática e para o ensino.
