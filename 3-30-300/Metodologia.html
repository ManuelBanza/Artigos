# Análise 3-30-300 Lisboa
## Metodologia


### Fontes de dados usadas:
- Edifícios de Lisboa (Open Street Map)
- Árvores em Lisboa (Câmara Municipal Lisboa)
- Espaços verdes de Lisboa (Discord Lisboa Para Pessoas)
- Tree Cover Density 2018 (Copernicus)
- Street Tree Layer (STL) 2018 (Copernicus)

### Tratamento de dados
Para o tratamento dos dados e cálculo da regra procedemos aos seguintes passos:

**Edifícios:**
- Importar todos os edifícios de Lisboa através do Open Street Map 
- Criar o centroid (ponto mais central do edifício) para cada polígono que representa cada edifício. Este ponto será a base para calcular as 3 regras (3, 30, 300).

**Regra 3:**
- Usar os dataset [Árvores em Lisboa](https://geodados-cml.hub.arcgis.com/datasets/arvoredo/explore). A atualização dos mesmos é da CML, caso encontres alguma incongruência nos dados por favor ajuda a câmara e a cidade a ter o dataset o mais atualizado possível enviando um e-mail para: geodados@cm-lisboa.pt
- Calculou-se um raio de 50 metros desde cada centroid (ponto mais central do edifício)
- Calculou-se o número de árvores que estão dentro do raio descrito no ponto acima

**Regra 30:**
- Importar dados da provenientes de imagens satélites da Copernico [Tree Cover Density 2018](https://land.copernicus.eu/pan-european/high-resolution-layers/forests/tree-cover-density/status-maps/tree-cover-density-2018) [Street Tree Layer](https://land.copernicus.eu/local/urban-atlas/street-tree-layer-stl-2018)
- Não cruzou-se os dados referidos acima, bem como os pontos do árvores de Lisboa utilizadas para a regra 3, de forma a verificar se existem árvores que não foram contabilizadas nas imagens satélite. Nos casos em que se verificou isso, decidiu-se atribuir um raio de 1.5 metros a cada árvores, de forma a simular uma copa da árvore. O valor 1.5 metros é bastante conservador mas foi optado por se tratar de algo bastante difícil de prever segundo vários estudos consultados. Apontou-se para o valor médio das árvores mais recentes, até porque serão as árvores implementadas após 2018 que não constam nas imagens satélite.
- Calculou-se para cada secção estatística fornecida pelo INE, a área de cobertura verde, usando os dados dos pontos acima

**Regra 300:**
- Usar os dataset [Espaços verdes de Lisboa](https://www.google.com/maps/d/u/0/viewer?ll=38.73506809596677%2C-9.13856244522261&z=14&mid=1WoxC-scPwblyYQftO9qmdM_e4PZFi_A). A atualização dos mesmos é realizada pela comunidade do Discord do Lisboa Para Pessoas. Verificando-se que tinham parque mais recentes que não constavam nos dados da CML.
- Foram usadas as camadas que se enquadram apenas em jardins e parques
- Calculou-se um raio de 300 metros desde cada centroid (ponto mais central do edifício)
- Identificou-se se esse raio intersectava algum dos jardins ou parques
