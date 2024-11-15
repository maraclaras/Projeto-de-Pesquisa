# Avaliação do engajamento de longo prazo de programadores em projetos de código aberto

1. Giovanna Lima Torres Guasch
2. Maria Clara de Oliveira Silva
* Lesandro Ponciano dos Santos - Introdução à Pesquisa em Informática

## Introdução

A área da Engenharia de Software tratada neste trabalho é Fatores Humanos na Engenharia de Software e Desenvolvimento de Software de Código Aberto. O foco dessa pesquisa está em investigar o comportamento de engajamento de programadores em projetos de software de código aberto, um campo cada vez mais relevante dado o crescimento e a influência dessas iniciativas no desenvolvimento tecnológico global.

O problema que este trabalho busca resolver envolve a compreensão de questões-chave relacionadas ao engajamento dos programadores nesses projetos, conforme delineado pelas seguintes questões de pesquisa (RQ, do inglês Research Questions):

1. _(RQ1) Qual é a duração do engajamento de programadores em projetos de código aberto?_
2. _(RQ2) Os programadores se engajam fazendo commit nos projetos de código aberto de forma transiente, ou seja, contribuem uma única vez e não retornam mais, ou permanecem engajados ao longo do tempo?_
3. _(RQ3) A popularidade do projeto influencia a duração do engajamento?_

Resolver este problema é relevante porque a avaliação do engajamento em projetos de código aberto permite analisar a sustentabilidade dessas iniciativas ao longo do tempo. Se muitos programadores apresentarem comportamentos transientes, os projetos podem estar sujeitos a riscos de qualidade e continuidade. Além disso, entender se a popularidade de um projeto influencia o engajamento prolongado dos programadores é essencial para criar estratégias de incentivo à colaboração contínua, garantindo que as comunidades em torno desses projetos permaneçam vibrantes e produtivas.

## Fundamentação Teórica

A reutilização de software é um conceito fundamental na engenharia de software moderna, referindo-se ao uso de artefatos já desenvolvidos em novos projetos. Esta prática não apenas economiza tempo e recursos, mas também contribui para a manutenção de consistência e qualidade no desenvolvimento de sistemas complexos. Um framework de software se destaca como um exemplo clássico de artefato reutilizável, oferecendo uma infraestrutura que pode ser customizada para diferentes aplicações.

O design de frameworks eficazes implica abordar questões de extensibilidade, modularidade e acoplamento. Extensibilidade refere-se à capacidade do framework de ser ampliado sem modificar sua estrutura principal. A modularidade está relacionada à organização do código em componentes independentes, enquanto o acoplamento trata da interação entre esses componentes. As estratégias de design que equilibram essas características têm se mostrado cruciais para a aceitação de frameworks na prática.

Pesquisas anteriores indicam que frameworks bem-sucedidos, como Spring, Django e Angular, compartilham práticas comuns, como o uso de padrões de design (por exemplo, injeção de dependência, estratégia de modelo-vista-controlador) e a disponibilização de documentações abrangentes. Além disso, frameworks que promovem a reutilização eficaz geralmente são acompanhados por uma comunidade ativa que fornece suporte contínuo aos desenvolvedores.

## Trabalhos Relacionados

O campo de estudo sobre frameworks e reutilização de software é vasto e conta com diversas contribuições relevantes. Gamma et al. (1995) introduziram o conceito de padrões de design no contexto do desenvolvimento de frameworks, destacando como certos padrões podem promover a reutilização e a flexibilidade. Outros estudos, como os de Johnson e Foote (1988), exploram a arquitetura de frameworks orientados a objetos, propondo a importância da generalização para facilitar a adaptação.

Mais recentemente, pesquisas empíricas investigaram como as decisões de design impactam a usabilidade de frameworks. Por exemplo, Nguyen et al. (2016) realizaram um estudo comparativo de frameworks Java e JavaScript, demonstrando que práticas como a modularização e a documentação amigável influenciam positivamente a aceitação do framework. Já Garcia et al. (2020) analisaram as dificuldades enfrentadas por desenvolvedores ao adaptar frameworks complexos e recomendaram melhorias de design focadas na redução da complexidade.

Este projeto de pesquisa busca avançar o conhecimento existente ao propor estratégias de design que possam ser empiricamente validadas, com foco na facilidade de extensão, na adaptabilidade e na aceitação do framework.

## Materiais e Métodos

** 1.1. Seleção de Frameworks Populares **
* Serão analisados 20 frameworks amplamente utilizados, incluindo exemplos de diferentes linguagens de programação, como Spring (Java), Django (Python) e Angular (JavaScript).
* A escolha desses frameworks visa garantir uma análise diversificada, cobrindo aplicações web, mobile e desktop.

** 1.2. Estudos de Caso **
* Serão realizados estudos de caso comparativos para identificar práticas de design que promovem a reutilização eficaz. Frameworks com diferentes níveis de sucesso em termos de adaptação e aceitação serão comparados.
* Exemplos de domínios de aplicação incluem desenvolvimento web (Django, Angular) e aplicações empresariais (Spring).

** 1.3. Coleta de Dados **
* A coleta de dados envolverá a análise de documentação oficial, inspeção de código-fonte, e consulta a repositórios GitHub associados aos frameworks.
* Serão utilizados scripts para extrair métricas de reutilização de código, como a porcentagem de classes reutilizáveis e o tempo médio necessário para modificar o framework.
  
** 1.4. Métricas de Usabilidade **
* A usabilidade dos frameworks será avaliada com base em:
* Facilidade de extensão (tempo médio de modificação)
* Número de linhas de código reutilizáveis
* Tempo médio necessário para implementar um novo projeto utilizando o framework

** 1.5. Análise Estatística **
* A análise estatística será conduzida usando métodos como análise de variância (ANOVA) para comparar a eficácia das estratégias de design propostas.
* A correlação de Spearman será aplicada para investigar a relação entre a extensibilidade do framework e sua aceitação pelos desenvolvedores.
  
** 1.6. Validação **
* A eficácia das estratégias propostas será mensurada por meio de estudos empíricos com desenvolvedores, envolvendo experimentos controlados e questionários qualitativos.
