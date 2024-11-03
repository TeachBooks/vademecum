# Veranderlijke belastingen III, regenwater en sneeuw

## Regenbelasting

Belastingen door regenwater zijn een gevolg van accumulerend water, bijvoorbeeld door het doorbuigen van aanliggende dakelementen of het verstoppen van afvoersystemen. De meest praktische manier om deze belasting te beschouwen, is door sneeuwbelasting om te zetten in een laag water (e.g.: $\mathsf{0,56 \, kN/m^2}$ is gelijk aan 56 mm water op het dak), en te voorkomen dat water boven dit peil uitkomt door het ontwerpen van noodoverstorten. Ontwerp daarnaast een plat dak altijd met een kleine hellingshoek (zie sectie [Bruikbaarheidscriteria](#) voor meer informatie over de hellingshoek en wateraccumulatie).

<img src="Images/noodafvoer_4_brievenbus_www_adviesbureau_hageman_nl.jpg" alt="Noodoverstort 1" class="bg-primary" width="240px"> <img src="Images/noodafvoer_6_plaatselijk_sterk_verlaagde_borstwering_www_adviesbureau_hageman_nl.jpg" alt="Noodoverstort 2" class="bg-primary" width="300px">

Een brievenbusvormige noodoverstort en een verlaagde borstwering als noodoverstort.

## Sneeuwbelasting

Sneeuw kan resulteren in aanzienlijke belastingen, aangezien het niet wegloopt zoals regenwater. Het is daarom van belang om te toetsen of een belastingcombinatie met sneeuwbelasting maatgevend is. De waarde van sneeuwbelasting kan binnen Europa sterk variëren (e.g. vergelijk de Mediterraanse kust met de Alpen). In de Nederlandse Nationale Bijlage van NEN-EN-1991-1-3 worden de complexe berekeningen vervangen door één waarde voor het hele land ($\mathsf{s_k=0,7 \, kN/m^2}$). Voor andere gebieden dient NEN-EN 1991-1-3 geraadpleegd te worden. De volgende formule kan worden gebruikt om de sneeuwbelasting te bepalen:

<br>

$$
\mathsf{s = \mu_i \cdot c_e \cdot c_t \cdot s_k}
$$

Zie NEN-EN 1991-1-3 sectie 5.2.

| Symbool         | Betekenis                                                      |
|-----------------|---------------------------------------------------------------|
| $\mathsf{s_k}$ | karakteristieke waarde van de sneeuwbelasting op de grond ($\mathsf{=0,7 \, kN/m^2}$ in Nederland) |
| $\mathsf{\mu_i}$ | vormcoëfficiënt, afhankelijk van de hoek van het dak         |
| $\mathsf{c_e}$   | blootstellingscoëfficiënt (meestal 1.0)                      |
| $\mathsf{C_t}$   | warmtecoëfficiënt (meestal 1.0)                             |
