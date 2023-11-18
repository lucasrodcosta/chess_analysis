[🇺🇸](/README.md "English")

# Análises de xadrez

Alguns notebooks Jupyter para extração de métricas sobre os jogadores ao longo dos anos.

## Resumo e achados

### Uma visão geral sobre os ratings ao longo do tempo

![Ratings de 2000 a 2023](/img/ratings_all_time.png "Ratings de 2000 a 2023")

Houve uma inflação considerável no rating dos jogadores até os últimos meses de 2011.

O momento em que os ratings ficaram mais estáveis coincide com o momento em que Magnus Carlsen iniciou sua dinastia no top 1.

### A Era de Magnus Carlsen (2011 - agora)

![Ratings na era Carlsen](/img/ratings_carlsen_era.png "Ratings na era Carlsen")

Se dermos um zoom para olharmos detalhadamente o que vem ocorrendo desde o início da dinastia do Carlsen (maio de 2011), observamos algumas coisas interessantes:
  - de fato, os ratings parecem mais estáveis;
  - mas parece que os percentis e média geral dos ratings dos top-100 jogadores caiu um pouco.

Pra confirmar (ou refutar) a segunda hipótese, vamos dar uma olhada em alguns gráficos:

![p50 dos top-100 jogadores](/img/p50.png "p50 dos top-100 jogadores")

![p75 dos top-100 jogadores](/img/p75.png "p75 dos top-100 jogadores")

![p95 dos top-100 jogadores](/img/p95.png "p95 dos top-100 jogadores")

![média dos top-100 jogadores](/img/avg.png "média dos top-100 jogadores")

Observe que todos os percentis e a média geral de rating dos top-100 estão menores hoje em dia do que suas médias históricas.
Isso pode indicar que, de fato, está ocorrendo uma leve deflação no rating dos jogadores.

Mas essas métricas podem estar afetadas pelo rating do Magnus Carlsen, que é um outlier.
Por isso, vamos analisar novamente essas métricas, mas desconsiderando o rating do Carlsen:

![p50 dos top-99 jogadores (desconsiderando Carlsen)](/img/p50_without_carlsen.png "p50 dos top-99 jogadores (desconsiderando Carlsen)")

![p75 dos top-99 jogadores (desconsiderando Carlsen)](/img/p75_without_carlsen.png "p75 dos top-99 jogadores (desconsiderando Carlsen)")

![p95 dos top-99 jogadores (desconsiderando Carlsen)](/img/p95_without_carlsen.png "p95 dos top-99 jogadores (desconsiderando Carlsen)")

![média dos top-99 jogadores (desconsiderando Carlsen)](/img/avg_without_carlsen.png "média dos top-99 jogadores (desconsiderando Carlsen)")

Agora sim parece que podemos dizer com um bom nível de confiança que, de fato, houve uma leve deflação nos ratings dos jogadores do top-100.

### É justo dizer que "Magnus Carlsen não é mais o mesmo?"

É tentador falar isso sempre que o vemos empatar uma partida contra um jogador de 2500~2600 de rating.

Nossa primeira reação é pensar que ele não é mais o mesmo, que seu nível de jogo está caindo e que logo logo ele perderá o posto de melhor jogador do mundo.

Mas olhando pra alguns números frios, não parece ser o caso.

![Diferença entre o top 1 e top 2](/img/distance_top_1_2.png "Diferença entre o top 1 e top 2")

O gráfico acima mostra a diferença de rating entre Carlsen e o 2º melhor jogador do mundo.

Houveram momentos nesses últimos anos que a diferença ficou muito pequena (especialmente em 2011 e em julho/agosto de 2018).
Mas em novembro de 2023, essa diferença parece estar num patamar bastante seguro (para o Carlsen, claro).
