# Belastingcombinaties en grenstoestandens

Elke constructie moet voldoen aan de twee hoofdgrenstoestanden die direct te maken hebben met de betrouwbaarheid (sterkte) en bruikbaarheid (stijfheid). De uiterste grenstoestand (**UGT**) wordt benut bij de toetsing van de constructieve veiligheid. De bruikbaarheidsgrenstoestand (**BGT**) wordt benut bij de toetsing van de eisen voor de bruikbaarheid.

Belastingcombinaties bestaan uit de combinaties van de rekenwaarden van de permanente en veranderlijke belastingen. Daarbij worden zowel de representatieve als de momentane waarden van de belastingen gecombineerd voor de **UGT** of de **BGT**. Zelf zul je de maatgevende belastingcombinatie van de draagconstructie of het constructie-element moeten bepalen. Bedenk hierbij om welk constructie-element het gaat, bijv. een vloerligger, een kolom of een stabiliteitsconstructie.

Bouwconstructies en onderdelen van bouwconstructies, en hun ondersteuningen of bevestigingen moeten met voldoende betrouwbaarheid bestand zijn tegen de ongunstigste combinaties van belastingen die gelijktijdig kunnen optreden, met dien verstande dat:

- de extreme waarde van een veranderlijke belasting niet gecombineerd hoeft te zijn met extreme waarden van andere veranderlijke belastingen of met bijzondere belastingen.
- een bijzondere belasting niet gecombineerd hoeft te zijn met extreme waarden van veranderlijke belastingen of met andere bijzondere belastingen.
- in een aantal gevallen uitgesloten is dat op verschillende delen van de constructie de extreme en momentane of nulwaarde van hetzelfde belastingsgeval gelijktijdig voorkomt (o.a. de wind- en sneeuwbelasting).


## Uiterste grenstoestand (UGT), fundamentele combinaties

Een belastingscombinatie bestaat over het algemeen uit het eigen gewicht, een overheersende veranderlijke belasting en eventuele overige veranderlijke belastingen. 

<br>

$$
\gamma_{G,j} \cdot G_{k,j} + \gamma_{Q,1} \cdot Q_{k,1} + \sum \gamma_{Q,i} \cdot \Psi_{0,i} \cdot Q_{k,i}
$$

*Bron: NEN-EN 1990 artikel 6.4.3.2* 

| Symbool        | Betekenis                                       |
|----------------|-------------------------------------------------|
| $\gamma_{G,j}$ | veiligheidsfactor permanente belasting   |
| $G_{k,j}$     | totale permanente belasting               |
| $\gamma_{Q,1}$ | veiligheidsfactor veranderlijke belasting  |
| $Q_{k,1}$     | overheersende veranderlijke belasting      |
| $\Psi_{0,1}$  | combinatiefactor behorende bij veranderlijke belasting $Q_{k,i}$ |
| $Q_{k,i}$     | eventuele overige veranderlijke belastingen |
| $+$                  | betekent "te combineren met"               |
| $\sum$      | betekent "de gecombineerde uitkomst van"   |


## Bruikbaarheidsgrenstoestanden (BGT)

De in aanmerking te nemen vervormingen met betrekking tot de bruikbaarheidseisen behoren die te zijn als omschreven in sectie \ref{sec:bgt-crit}-Bruikbaarheidscriteria al naargelang de aard van de bouwwerken, of zoals overeengekomen met de opdrachtgever of de nationale overheid.

**Karakteristieke combinatie**  
De karakteristieke combinatie wordt gebruikt voor onomkeerbare grenstoestanden (plastische vervorming). Hiermee wordt bedoeld dat ergens in de constructie vloeien (staal) of scheurvorming optreedt (beton/metselwerk) door het vervormen van het constructiedeel. Dit kan bijvoorbeeld gaan om het scheuren van een metselwerk scheidingswand ten gevolge van doorbuiging van de vloer. 

<br>

$$
G_{k,j} + Q_{k,1} + \sum \Psi_{2,i} \cdot Q_{k;i}
$$

*Bron: NEN-EN 1990 artikel 6.5.3*

| Symbool        | Betekenis                                       |
|----------------|-------------------------------------------------|
| $G_{k,j}$ | totale permanente belasting                   |
| $Q_{k,1}$ | overheersende veranderlijke belasting          |
| $\Psi_{0,i}$ | combinatiefactor voor veranderlijke belasting $\mathsf{Q_{k,i}}$ |
| $Q_{k,i}$ | eventuele overige veranderlijke belastingen     |
| $+$                  | betekent "te combineren met"               |
| $\sum$      | betekent "de gecombineerde uitkomst van"   |


**Frequentie combinatie**

De frequente combinatie wordt gebruikt voor omkeerbare grenstoestanden (elastische vervorming). Er is sprake van een omkeerbare bruikbaarheidsgrenstoestand wanneer nergens in de constructie vloeien (staal) of scheuren (beton/metselwerk) optreedt door de doorbuiging en de constructie elastisch terugveert naar de oorspronkelijke vorm wanneer de belasting wordt weggenomen.

<br>

$$
G_{k,j} + \Psi_{1,1} \cdot Q_{k,1} + \sum \Psi_{2,i} \cdot Q_{k;i}
$$

*Bron: NEN-EN 1990 artikel 6.5.3*

| Symbool        | Betekenis                                       |
|----------------|-------------------------------------------------|
| $G_{k,j}$ | totale permanente belasting                   |
| $\Psi_{1,1}$ | factor i.v.m. frequente waarde belasting    |
| $Q_{k,1}$ | overheersende veranderlijke belasting          |
| $\Psi_{2,i}$ | factor i.v.m. quasi-blijvende waarde belasting |
| $Q_{k,i}$ | eventuele overige veranderlijke belastingen     |
| $+$                  | betekent "te combineren met"               |
| $\sum$      | betekent "de gecombineerde uitkomst van"   |


**Quasi-blijvende combinatie**  
De quasi-blijvende combinatie wordt gebruikt voor langetermijneffecten (krimp en kruip) en voor het uiterlijk van de constructie. 

<br>

$$
G_{k,j} + \sum \Psi_{2,i} \cdot Q_{k;i}
$$

*Bron: NEN-EN 1990 artikel 6.5.3*

| Symbool        | Betekenis                                       |
|----------------|-------------------------------------------------|
| $G_{k,j}$ | totale permanente belasting                   |
| $\Psi_{2,i}$ | factor i.v.m. quasi-blijvende waarde belasting |
| $Q_{k,i}$ | veranderlijke belastingen                      |
| $+$                  | betekent "te combineren met"               |
| $\sum$      | betekent "de gecombineerde uitkomst van"   |


