# Análise Exploratória de Dados sobre <span style="color:green">Jogos na Steam</span>
## Por: Vinícius Leôncio 
### Módulo: Estatística I
---
O objetivo deste projeto é proporcionar a oportunidade de aplicar os conhecimentos adquiridos ao longo da disciplina de Estatística I em um contexto prático, relevante e data-driven. Com uma análise exploratória e levantando uma hipótese, utilizando uma base de dados sobre os jogos na Steam, maior plataforma de distribuição digital de jogos digitais, utilizando um conjunto de dados real, a fim de extrair insights e entender melhor a base de dados.

Base de dados usada: https://www.kaggle.com/datasets/nikdavis/steam-store-games

Foi explorado o seguinte dataset nesse arquivo: 
- steam.csv

---
## Introdução
**Motivação:** Entender se comparar o tempo de jogo mediano com as avaliações positivas para ver se jogos com maior tempo de gameplay têm melhor recepção dos usuários. Vamos usar o valor **mediano** de tempo de jogo em vez da **média**, pois a mediana fornece uma medida de tendência central que não é afetada por valores extremos.

**Hipótese:** Jogos com tempo de jogo mediano(median_playtime) mais alto tendem a ter avaliações mais positivas.

- **H0 (hipótese nula):**  Não há correlação entre o tempo de jogo mediano e as avaliações dos usuários
- **H1 (hipótese alternativa):** Existe uma correlação entre o tempo de jogo mediano e as avaliações dos usuários
