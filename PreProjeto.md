# Reutilização de software e design de frameworks

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

1. O conceito/teoria principal, Reutilização de Software, é definido como o processo de desenvolver componentes que possam ser aplicados em múltiplos projetos para aumentar a eficiência, consistência e reduzir custos no desenvolvimento. Jacobson et al. (1997) enfatizam que a reutilização sistemática requer uma arquitetura sólida e estratégias que promovam a fácil integração de componentes reutilizáveis. Mais recentemente, o artigo [A3-CodGen: A Repository-Level Code Generation Framework for Code Reuse (2024)](https://ieeexplore.ieee.org/document/10734067) amplia essa definição ao demonstrar frameworks de geração de código que maximizam a taxa de reutilização e otimizam a utilização de bibliotecas locais e globais

2. O conceito/teoria secundário, Design de Frameworks, refere-se a estruturas que oferecem uma base reutilizável para o desenvolvimento de software. Fayad e Schmidt (1997) destacam que frameworks bem projetados devem ser extensíveis e promover a reutilização sem comprometer a flexibilidade. Artigos recentes, como [Standard-Driven Software Component Reuse and Agile Testing (2023)](https://ieeexplore.ieee.org/abstract/document/10633676), ressaltam a importância de integrar frameworks com práticas ágeis para garantir a qualidade e eficiência do software desenvolvido, evidenciando como a conformidade com padrões acelera o processo de desenvolvimento e reduz o retrabalho​.

3. O conceito/teoria terciário, Facilidade de Uso e Adaptabilidade, é essencial para o sucesso dos frameworks. Jakob Nielsen (1993), em ["Usability Engineering"]({https://books.google.com.br/books?id=95As2OF67f0C), define a facilidade de uso em termos de eficiência e satisfação do usuário, enquanto a adaptabilidade refere-se à capacidade do software de ser modificado facilmente para atender a novos requisitos. Esses princípios são explorados em frameworks modernos que visam melhorar a experiência do desenvolvedor e simplificar a personalização para diferentes contextos de aplicação​

## Trabalhos Relacionados

O campo de estudo sobre frameworks e reutilização de software é vasto e conta com diversas contribuições relevantes. Gamma et al. (1995) introduziram o conceito de padrões de design no contexto do desenvolvimento de frameworks, destacando como certos padrões podem promover a reutilização e a flexibilidade. Outros estudos, como os de Johnson e Foote (1988), exploram a arquitetura de frameworks orientados a objetos, propondo a importância da generalização para facilitar a adaptação.

Mais recentemente, pesquisas empíricas investigaram como as decisões de design impactam a usabilidade de frameworks. Por exemplo, Nguyen et al. (2016) realizaram um estudo comparativo de frameworks Java e JavaScript, demonstrando que práticas como a modularização e a documentação amigável influenciam positivamente a aceitação do framework. Já Garcia et al. (2020) analisaram as dificuldades enfrentadas por desenvolvedores ao adaptar frameworks complexos e recomendaram melhorias de design focadas na redução da complexidade.

Este projeto de pesquisa busca avançar o conhecimento existente ao propor estratégias de design que possam ser empiricamente validadas, com foco na facilidade de extensão, na adaptabilidade e na aceitação do framework.

## Materiais e Métodos

1. O tipo de pesquisa adotado neste trabalho é "exploratória e experimental", porque _busca investigar estratégias de design de frameworks, explorando práticas existentes e testando novas abordagens para avaliar sua eficácia na reutilização e adaptabilidade_.

2. Os materiais utilizados neste trabalho são: ambientes de desenvolvimento de software (IDEs) como Visual Studio Code e Eclipse; frameworks de código aberto como Spring, Django e .NET para análise comparativa; documentação técnica e repositórios de código em plataformas como [GitHub](https://github.com/) e dados qualitativos coletados por meio de entrevistas com desenvolvedores.

3. Os métodos empregados neste trabalho são: análise comparativa de frameworks, estudo de caso para testar diferentes abordagens de design, e pesquisa qualitativa para coleta de feedback dos desenvolvedores sobre usabilidade e adaptabilidade.

4. As métricas de avaliação são: Facilidade de aprendizado (medida pelo tempo necessário para entender e utilizar o framework), _baseada em Nielsen, J. (1993), _["Usability Engineering"]({https://books.google.com.br/books?id=95As2OF67f0C)_, adaptabilidade (avaliação da facilidade de modificar o framework para novos requisitos), conforme descrito por Fayad, M., Schmidt, D., & Johnson, R. (2000), _[“Building Application Frameworks: Object-Oriented Foundations of Framework Design”](https://dl.acm.org/doi/book/10.5555/326112)_, taxa de reutilização (proporção de componentes reutilizados em diferentes projetos), fundamentada nos princípios de reutilização descritos por Gamma, E., Helm, R., Johnson, R., & Vlissides, J. (1994), _[“Design Patterns: Elements of Reusable Object-Oriented Software”](https://books.google.com.br/books?id=iyIvGGp2550C)_.

5. As etapas de execução do trabalho são: (1) realizar uma revisão da literatura sobre estratégias de design de frameworks; (2) selecionar e documentar casos de sucesso e falha no uso de frameworks; (3) desenvolver ou modificar protótipos de frameworks baseados em diferentes estratégias de design; (4) Realizar testes experimentais com os protótipos desenvolvidos para avaliar a facilidade de aprendizado, adaptabilidade, e taxa de reutilização; (5) analisar os resultados obtidos e propor diretrizes de design para otimizar a reutilização e flexibilidade em frameworks de software.
