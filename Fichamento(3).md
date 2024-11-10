# CENTRIS: A Precise and Scalable Approach for Identifying Modified Open-Source Software Reuse

Woo, Seunghoon; Park, Sunghan; Kim, Seulbae; Lee, Heejo; Oh, Hakjoo (2021). "CENTRIS: A Precise and Scalable Approach for Identifying Modified Open-Source Software Reuse," 2021 IEEE/ACM 43rd International Conference on Software Engineering (ICSE), pp. 860-871, doi:  [10.1109/ICSE43902.2021.00083](https://ieeexplore.ieee.org/document/9402128).

## 1. Fichamento de Conteúdo

Este artigo apresenta o CENTRIS, uma ferramenta projetada para identificar com precisão e escalabilidade o reuso modificado de software de código aberto (OSS). A técnica é especialmente útil no contexto de grandes projetos de software que reutilizam OSS de maneira modificada e frequentemente aninhada. CENTRIS emprega duas estratégias principais: a eliminação de redundância, para reduzir o espaço de comparação, e a segmentação de código, para focar na parte reutilizada do OSS. Em testes com um banco de dados de 10.241 repositórios, CENTRIS alcançou 91% de precisão e 94% de recall, detectando reutilizações modificadas com rapidez e reduzindo alarmes falsos em comparação com técnicas anteriores, como o DejaVu.
O estudo mostra que 95% dos componentes OSS são reutilizados com modificações, seja parcialmente, com mudanças de estrutura, ou com alterações de código. O artigo contribui com um método preciso para identificar o reuso modificado, auxiliando desenvolvedores a gerenciar componentes de OSS e reduzir riscos de segurança.

## 2. Fichamento Bibliográfico
* _Eliminação de Redundância:_ Técnica para evitar comparações redundantes no banco de dados de componentes, aumentando a eficiência do CENTRIS (página 862).
* _Segmentação de Código:_ Processo de separar o código do aplicativo do código de terceiros, minimizando alarmes falsos e facilitando a identificação de componentes modificados (página 864).
* _OSS Reutilizado Modificado:_ Reuso de um componente OSS em que parte do código original é alterada ou apenas uma porção do código é reutilizada (página 866).
* 
## 3. Fichamento de Citações
* _"We propose CENTRIS, the first approach capable of precisely and scalably identifying modified OSS reuse in the presence of nested OSS components."_ (página 861)
* _"Our observation results suggest the need to detect heavily modified components [...] CENTRIS would be a better solution for the efficient SCA process."_  (página 868)
* _"CENTRIS successfully identified the reused components with 91% precision and 94% recall."_ (página 867)
