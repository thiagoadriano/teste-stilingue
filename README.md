# Introdução

Este é o primeiro teste de avaliação do Stilingue. 

Pode parecer difícil a primeira vista, mas tenho certeza que irá pensar em alguma alternativa. Afinal de contas, TODOS os problemas possuem uma solução trivial.


# Data

72h para uma solução trivial ONLINE


# Problema

Lidar com:

- tempo / prioridade;
- interpretação de um problema proveniente da linguagem humana;
- desenvolver e descrever planejamento + execução da solução;
- desenvolvimento de um sistema mínimo de coleta e visualização (Web Dev).


## Briefing

A palavra é uma unidade da linguagem humana. Uma de suas funções é representar o que pensamos.

É conhecido que uma palavra possui diferentes tipos de relações com outras palavras. E que uma palavra pode ser “definida” pelo contexto em que habita. Mas como explorar esse universo de palavras? Como visualiza-lo, resumi-lo em uma imagem? 

Em termos práticos, o desafio proposto é coletar informações sobre palavras e implementar uma visualização que resuma o universo em questão. Na visualização deve ser possível procurar por palavras e encontrar suas relações com outras palavras. 


## Detalhamento 

Dividindo o problema em etapas: (1) entendimento / exploração do problema, (2) modelagem da solução e (3) desenvolvimento da coleta +  view que apresente as funcionalidades desejadas.


#1) Num briefing “real”, nem tudo reportado pode estar 100% claro (o cliente as vezes nem sabe o que quer).
Portanto, aproveite os primeiros momentos para fazer várias perguntas e ter o objetivo em mente, com muita clareza.


#2) Desenhe sua solução, como planeja resolver o problema. Faça anotações das decisões que tomou. Nesse passo, você já deve ter listado algumas formas práticas de como modelar um “resumo visual”. Você pode "colar" / perguntar para outras pessoas sobre o problema (mas não fale do desafio).


#3.1) Coleta: você precisa encontrar uma base de conhecimento de palavras e coletar as informações. Exemplo: baixar as informações das palavras do site dicionariocriativo.com.br e ir navegando pelas palavras sinônimos / análogas (assim o coletor iria fazer download de praticamente toda a base de palavras).

#3.2) Modelagem de Dados: interprete as informações que tem de cada palavra e modele de uma forma simples e objetiva. Se você vai visualizar por um gráfico, seus dados terão “cara de tabela”. Se for modelar um grafo (palavras e suas relações), você irá modelar de forma que uma palavra saiba quais são todas suas ligações.

#3.3) View, foco do desafio: Aqui é onde deve focar maior parte do seu tempo. Confira as dicas, existem vários exemplos para você testar. Uma rede de relacionamentos (modelado num grafo), pode ser uma boa. Mas, no final, você é quem deve decidir qual a melhor forma de visualização!


## Dicas

- Ferramentas de coleta? https://import.io (faça o tutorial e em 15 minutos você coleta um site!), quer ir por código? jSoup (https://www.youtube.com/watch?v=Da_DczRGFa8)

- Hosting da solução? Google Cloud (AppEngine), ou uma máquina mínima da Digital Ocean (só pedir). Quanto menos problemas, melhor. Não perca tempo com isso mas faça ficar online. 

- Libs JavaScript? Vis.js, cytoscape.js, HighCharts, sigma.js, d3.js (aconselho cytoscape.js)

- Modelo de inspiração? https://sites.google.com/site/sergeymelderis/word.png

- Converse, pergunte, valide a todo tempo. Seja rápida para pivotar nas ideias e encontrará a saída.

- Não perca tempo com documentações formais. Vale muito mais você explicar numa conversa e mostrar seus esboços / planos.


# Considerações finais

São 3 dias em que cada hora de dedicação conta para surpreender. Você não terá tempo para ficar pensando nas coisas, então saiba explorar o máximo de ideias de uma vez só, e escolher as que vai tirar do papel.