# Reutilização de software e design de frameworks

1. Giovanna Lima Torres Guasch
2. Maria Clara de Oliveira Silva
* Lesandro Ponciano dos Santos - Introdução à Pesquisa em Informática

## Introdução

Este trabalho aborda a área da Engenharia de Software focada no design de frameworks, com ênfase em sua reutilização, adaptabilidade e eficiência no desenvolvimento de software.

O problema explorado neste estudo é: Quais estratégias de design de frameworks garantem uma utilização eficaz do software em diferentes cenários? De que forma essas estratégias impactam a usabilidade e a capacidade de adaptação dos frameworks pelos desenvolvedores?

A relevância de resolver este problema está no fato de que frameworks são ferramentas essenciais para o desenvolvimento de software, permitindo maior agilidade e qualidade nos projetos. No entanto, frameworks que não são bem projetados podem dificultar seu uso e personalização, além de causar perdas de tempo e recursos. Identificar soluções eficazes contribui para aprimorar o processo de desenvolvimento e a experiência dos desenvolvedores, bem como para maximizar o potencial dessas ferramentas.

O objetivo geral deste estudo é investigar e propor estratégias de design que favoreçam a eficiência, a adaptabilidade e a usabilidade dos frameworks no contexto do desenvolvimento de software.

Os objetivos específicos do trabalho são:
1. Estudar frameworks já existentes para identificar práticas de design que favoreçam a eficiência e o uso adequado.

2. Avaliar como diferentes abordagens de design afetam a usabilidade e a adaptabilidade dos frameworks em diferentes contextos.

3. Desenvolver diretrizes práticas para o design de frameworks que possam ser utilizados de forma eficaz em diversos cenários.

## Fundamentação Teórica

1. O conceito/teoria principal, Reutilização de Software, é definido como o processo de desenvolver componentes que possam ser aplicados em múltiplos projetos para aumentar a eficiência, consistência e reduzir custos no desenvolvimento. Jacobson et al. (1997) enfatizam que a reutilização sistemática requer uma arquitetura sólida e estratégias que promovam a fácil integração de componentes reutilizáveis. Mais recentemente, o artigo [A3-CodGen: A Repository-Level Code Generation Framework for Code Reuse (2024)](https://ieeexplore.ieee.org/document/10734067) amplia essa definição ao demonstrar frameworks de geração de código que maximizam a taxa de reutilização e otimizam a utilização de bibliotecas locais e globais

2. O conceito/teoria secundário, Design de Frameworks, refere-se a estruturas que oferecem uma base reutilizável para o desenvolvimento de software. Fayad e Schmidt (1997) destacam que frameworks bem projetados devem ser extensíveis e promover a reutilização sem comprometer a flexibilidade. Artigos recentes, como [Standard-Driven Software Component Reuse and Agile Testing (2023)](https://ieeexplore.ieee.org/abstract/document/10633676), ressaltam a importância de integrar frameworks com práticas ágeis para garantir a qualidade e eficiência do software desenvolvido, evidenciando como a conformidade com padrões acelera o processo de desenvolvimento e reduz o retrabalho​.

3. O conceito/teoria terciário, Facilidade de Uso e Adaptabilidade, é essencial para o sucesso dos frameworks. Jakob Nielsen (1993), em ["Usability Engineering"](https://books.google.com.br/books?id=95As2OF67f0C), define a facilidade de uso em termos de eficiência e satisfação do usuário, enquanto a adaptabilidade refere-se à capacidade do software de ser modificado facilmente para atender a novos requisitos. Esses princípios são explorados em frameworks modernos que visam melhorar a experiência do desenvolvedor e simplificar a personalização para diferentes contextos de aplicação​

## Trabalhos Relacionados

1. O trabalho mais relacionado é ["FeaMod: Enhancing Modularity, Adaptability, and Code Reuse in Embedded Software Development"](https://ieeexplore.ieee.org/abstract/document/10703738/references#references), publicado em 2024, pois propõe um framework inovador para modularização e reutilização de código em sistemas embarcados, utilizando técnicas avançadas de análise de código e aprendizado de máquina. O FeaMod se destaca por integrar modularidade baseada em funcionalidades com um modelo adaptativo de recursos, permitindo configuração dinâmica e integração de sistemas de acordo com requisitos evolutivos. A abordagem incorpora o modelo BERT para extração automática de funcionalidades de bases de código, o que otimiza a identificação de requisitos computacionais e promove a eficiência no ciclo de desenvolvimento. Os resultados experimentais destacam sua eficácia na identificação de funcionalidades e configuração adaptativa em um estudo de caso envolvendo reconhecimento facial.

2. O trabalho mais relacionado é ["Research on the Application of Software Development Mode on Reusable Framework based on Neural Network Algorithm"](https://ieeexplore.ieee.org/document/9760797), publicado em 2022, pois explora um modelo de desenvolvimento de software baseado em frameworks reutilizáveis, aplicando algoritmos de redes neurais para melhorar a eficiência e a qualidade do desenvolvimento. A pesquisa apresenta a criação de estruturas reutilizáveis que integram algoritmos como redes neurais convolucionais e redes feedforward multicamadas. Este modelo oferece benefícios como redução de custos, tempo de desenvolvimento e maior adaptabilidade a diferentes domínios. Além disso, o trabalho avalia algoritmos como MIML-BOOST e M3MIML em problemas de classificação, destacando sua capacidade de lidar com tarefas complexas em sistemas baseados em inteligência artificial e computação distribuída.

3. O trabalho mais relacionado é ["Towards Integrated Framework for Efficient Educational Software Development"](https://ieeexplore.ieee.org/document/10197734), publicado em 2023, pois apresenta um framework híbrido que integra métodos ágeis (Scrum e DSDM) com modelos de design instrucional (ADDIE e ASSURE), com o objetivo de melhorar a eficiência, reduzir custos e adaptar softwares às necessidades de professores e alunos. O estudo propõe o modelo IIADPIE, com sete fases iterativas (inicial, orientação instrucional, análise, design, produção, integração/implementação e avaliação), destacando-se pela integração de estratégias pedagógicas, como análise de perfis de alunos e inventários de conceitos, para personalizar o ensino e aprendizagem. Embora voltado para software educacional, compartilha objetivos com trabalhos que aplicam frameworks reutilizáveis, buscando eficiência e qualidade no desenvolvimento, mas com foco específico em atender às demandas pedagógicas.

   
## Materiais e Métodos

1. O tipo de pesquisa adotado neste trabalho é quantitativa e descritiva, porque visa medir e descrever características de frameworks de software, como a reutilização de código, a adaptabilidade e a usabilidade, sem interferir diretamente nas variáveis envolvidas. A pesquisa é quantitativa, pois se concentra na coleta e análise de dados objetivos, como o número de forks, contribuições em repositórios, tempo de desenvolvimento e outras métricas relacionadas ao uso dos frameworks. Além disso, é descritiva, já que busca caracterizar as propriedades de frameworks amplamente utilizados, sem manipulação de variáveis.

2. Os materiais utilizados neste trabalho são frameworks de software (Spring Boot, Django, React, Angular), dados coletados de repositórios de código aberto no GitHub, ferramentas de coleta de dados como a API do GitHub para extração de informações sobre commits, número de colaboradores e evolução de projetos, além de computadores para análise e implementação de experimentos práticos.

3. Os métodos empregados neste trabalho são análise de tendência central e dispersão, regressão linear e testes de correlação (Spearman e Kendall) para investigar relações entre métricas de popularidade e desempenho dos frameworks, e análise de agrupamento k-means para segmentação dos frameworks com base em características comuns.

4. As métricas de avaliação são reutilização de código (número de bibliotecas e componentes reutilizáveis), adaptabilidade (facilidade de personalização sem modificar o núcleo do framework), usabilidade (tempo necessário para configurar um ambiente de desenvolvimento básico e a curva de aprendizado) e popularidade (número de forks, contribuições e estrelas nos repositórios do GitHub).

5. As etapas de execução do trabalho são:

* Coleta de dados dos repositórios no GitHub, utilizando a API para extrair informações sobre forks, contribuições, commits e estrelas.
* Implementação de tarefas práticas, desenvolvendo pequenas aplicações em cada framework para avaliar sua usabilidade e adaptabilidade.
* Cálculo das métricas, obtendo dados sobre bibliotecas reutilizáveis, tempo de implementação e facilidade de personalização.
* Análise estatística dos dados, aplicando regressão, correlação e análise de agrupamento para identificar padrões e relações entre as métricas.
* Documentação e comparação dos resultados, com conclusões sobre quais frameworks se destacam em termos de reutilização de código, adaptabilidade e usabilidade, e proposição de diretrizes para futuros designers de frameworks.
