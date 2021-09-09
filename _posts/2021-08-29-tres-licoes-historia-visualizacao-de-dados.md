---
layout: post
title: "3 lições aprendidas sobre a história da visualização de dados"
featured-img: tres-licoes-historia-visualizacao-de-dados-cover
categories: [history, data, vizualization]
---


A visualização de dados é responsável por traduzir de forma gráfica as abstrações contidas nos dados que nós, cientistas, precisamos analisar. Além disso, este recurso visual possibilita _insights_ que outrora não estavam claros. 

Ao analisar ao longo dos séculos sua história<sup>1</sup>, é possível extrair 3 princípios importantes e que podem auxiliar nossas análises.

## 1) A visualização precisa ser uma resposta à um problema

Atualmente é comum montar uma visualização e despender a maior parte do tempo preocupado com a estética e a disposição dos elementos visuais. Este é um fator essencial, não tenha dúvidas. Porém, ele é de longe o mais essencial.

**Por que?**

Pois o cerne da visualização de dados não é sua harmonia estética, mas sim sua **funcionalidade** para evidenciar de forma **clara** a mensagem que você procura passar.

Podemos listar o exemplo de Minard<sup>2</sup>(1861).

![]({{ "assets/img/posts/history-data-visualization/minard-napoleon-chart.png" | absolute_url }})

A ideia deste gráfico é demonstrar a baixa que o exército de Napoleão teve durante sua incursão à Moscou e seu retorno. A grande faixa bege indica o volume de soldados que foram até a metrópole na Rússia. Já a faixa preta indica o volume de soldados que voltou.  Vale ressaltar que Minard não faz menção a Napoleão.
Qual a **primeira** impressão que a visualização passa?
O fato do exército ter tido uma gigantesca baixa, demonstrando que seu interesse estava nas **angústias e sacrifícios dos soldados**<sup>3</sup>. 

E este tipo de visualização não é pontual na história da visualização de dados. Como menção honrosa, destaco as visualizações criadas por Playfair<sup>4</sup>(1821), por exemplo, a comparação de população e impostos em várias nações, ou a visualização do número de pessoas doentes no campo de batalha nas guerras criada por Nightingale<sup>5</sup>(1857) evidenciando que muitos soldados morreram por conta das péssimas condições sanitárias. 

Portanto a visualização deve ser comprometida, a priori, com **qual** informação você quer disponibilizar do que **como** você deve visualizar.

## 2) Sua visualização pode conter pré-requisito para interpretação.

Esta afirmação pode soar um pouco polêmica, eu sei. Mas como vimos no primeiro princípio, nosso ponto de partida é o **propósito**. Existe um diagrama que ilustra bem isso, feito por Nobre(2021)<sup>6</sup> de uma leitura de Berinato(2016)<sup>7</sup>:


![]({{ "assets/img/posts/history-data-visualization/chart-declarativo-orientada-a-dados-1.png" | absolute_url }})

COLOCAR CONTEÚDO EXPLICANDO O DIAGRAMA

![]({{ "assets/img/posts/history-data-visualization/chart-declarativo-orientada-a-dados-2.png" | absolute_url }})

COLOCAR CONTEÚDO EXPLICANDO O DIAGRAMA 2 EVIDENCIANDO OS FOCOS


![]({{ "assets/img/posts/history-data-visualization/chart-declarativo-orientada-a-dados-3.png" | absolute_url }})

COLOCAR DIAGRAMA FINAL.

Portanto, existem visualizações que para fomentar _insights_ necessitam de um conhecimento prévio e/ou matemático. Um clássico exemplo disto é o desenvolvimento e a contribuição de Gauss para a visualização de dados. 

[Texto sobre Gauss.]


Dessa forma, não se sinta mal se sua visualização necessita de pré-requisitos. Isto é comum e é bom para construção de idéias.

## 3) Sua visualização nunca será perfeita.
## A tecnologia muda
## A abstração muda

[Exemplo do texto final]


# Conclusão
    
Foram desenvolvidos 8 marcos históricos, a saber: (**Pre-17th Century: Early maps and diagrams, 1600-1699: Measurement and theory, 1700-1799: New graphic forms, 1800-1850: Beginnings of modern graphics, 1850-1900: The Golden Age of statistical graphics, 1900-1950: The modern dark ages, 1950–1975: Re-birth of data visualization e 1975–present: High-D, interactive, and dynamic data visualization).** Em cada *milestone* ele se preocupou em contextualizar o desenvolvimento da técnica de visualização, e algo que ficou claro durante o artigo é como que as visualizações sempre procuraram **responder** aos problemas e análises científicos/sociais. Ou seja, no seu início ela sempre esteve marcada pela praticidade. Porém, com o desenvolvimento da estatística, a visualização de dados ganhou mais robustez teórica, facilitando algumas de suas compreensões que outrora seria mais díficil sem ela. Nomes como **Minard** e **Galton** tiveram grandes contribuições neste quesito.

Entretanto, a sofisticação de desenhar e manter a visualização dos dados que só cresciam com o tempo, tornou custoso a utilização da visualização de dados. E, quando os primeiros computadores foram criados, o processamento e computação de dados já estruturados, facilitou o desenvolvimento das visualizações (agora em contexto computadorizado). Ademais, como advento gráfico dos computadores, a visualização ganhou um novo paradigma, a saber, a movimentação. Desta forma, novos conceitos de visualização puderam ser inventados e a visualização, expandida.

Na segunda parte do artigo, o autor procurou construir uma histografia da estatística, mostrando um pouco de como os dados temporais surgiram e foram consolidados ao longo dos anos. Além disso, o autor mostra de forma agrupada, uma análise geral dos assuntos que a visualização abordou ao longo do tempo, bem como qual foi seu *approach.* Por fim, o autor mostra que os principais desenvolvimentos que foram feitos pelos principais nomes históricos da visualização não desenvolveram a "melhor visualização" possível, mas afirmar isso seria **anacrônico**.

### Referências

[1] Friendly, Michael. (2008). A brief history of data visualization. In: Handbook of data visualization. Springer, Berlin, Heidelberg. p. 15-56.

[2] Minard, Charles-Joseph. (1781-1870). “Tableaux graphiques et cartes figuratives,” Bibliothèque numérique patrimoniale des ponts et chaussées, accessed September 9, 2021, Disponível em: https://patrimoine.enpc.fr/document/ENPC01_Fol_10975

[3] Corbett, John. (2017). "Charles Joseph Minard: Mapping Napoleon's March, 1861". Centro de Ciências Sociais Espacialmente Integradas.

[4]Playfair, William. (1821). Letter on our agricultural distresses, their causes and remedies; accompanied with tables and copperplate charts shewing and comparing the prices of wheat, bread and labour, from 1565 to 1821. BL: 8275.c.64.

[5] Nightingale, Florence. (1857). Mortality of the British Army. London: Harrison and Sons.

[6] Nobre, Cristiane. (2021). Visualização de dados. p. 14-18.

[7] Berinato, S. (2016). Good charts: The HBR guide to making smarter, more persuasive data visualizations. Harvard Business Review Press.