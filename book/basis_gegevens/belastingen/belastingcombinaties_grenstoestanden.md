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


## Belastingsfactoren uiterste grenstoestand

De belastingsfactoren worden in de Eurocode partiële factoren genoemd. In sommige andere literatuur worden ze veiligheidsfactoren genoemd. Bij de toepassing van de belastingsfactoren moet er onderscheid gemaakt worden tussen gunstig en ongunstig werkende belastingen. Dit is afhankelijk van de toets die uitgevoerd wordt. Toets je bijvoorbeeld het moment in een ligger op twee steunpunten waarop een neerwaartse belasting (eigengewicht) en een opwaartse belasting (windzuiging) werken, dan zal het moment in de ligger minder kritisch zijn als beide belastingen gelijktijdig optreden. Een van de belastingen werkt dus gunstig.


| Gevolgklasse (CC) | $\mathsf{\gamma_{f;g}}$ (permanente belasting) | $\mathsf{\gamma_{f;q}}$ (veranderlijke belasting) |
|-------------------|--------------------------------------------------|---------------------------------------------------|
|                   | ongunstig     | gunstig      | ongunstig      | gunstig       |
| 1                 | 1,1           | 0,9          | 1,35           | 0             |
| 2                 | 1,2           | 0,9          | 1,5            | 0             |
| 3                 | 1,3           | 0,9          | 1,65           | 0             |

*Bron: NEN-EN 1990 Nationale Bijlage, tabel NB.4 en NB.5*


## Gevolgklasse (CC)

| **Gevolgklasse** | **Omschrijving**                                                                                   |
|------------------|---------------------------------------------------------------------------------------------------|
| CC3              | Grote gevolgen ten aanzien van het verlies van mensenlevens**, of zeer grote economische of sociale gevolgen of gevolgen voor de omgeving  |
| CC2              | Middelmatige gevolgen ten aanzien van het verlies van mensenlevens, of aanzienlijke economische of sociale gevolgen of gevolgen voor de omgeving  |
| CC1b             | Geringe gevolgen ten aanzien van het verlies van mensenlevens en kleine of verwaarloosbare economische of sociale gevolgen of gevolgen voor de omgeving |
| CC1a             | Verwaarloosbare gevolgen ten aanzien van het verlies van mensenlevens, en geen economische of sociale gevolgen of gevolgen voor de omgeving        |

*Bron: NEN-EN 1990 Nationale Bijlage, tabel NB.1*


## Voorbeelden van toepassing gevolgklasse voor bouwwerken

| **Gevolgklasse** | **Voorbeelden van toepassingen voor gebouwen en bouwwerken m.u.v. bruggen en maritieme constructies**  |
|------------------|---------------------------------------------------------------------------------------------------|
| **CC3**          | **-** Hoge gebouwen, waarvan de hoogste vloer van een gebruiksgebied, zoals gedefinieerd in het Bouwbesluit 2012, meer dan 70 m boven het maaiveld ligt ter plaatse van de toegang  <br> **-** Bouwwerken, waarvan de overspanning van de constructie in een draagrichting groter is dan 50 m en waarbij in geval van bezwijken van die overspanning meer dan 500 personen gelijktijdig gevaar lopen (zoals bij grote tentoonstellings- en stationshallen) <br> **-** Bouwwerken met de bestemming publieksfunctie (bijv. onderwijsgebouwen, stadions, concerthallen, tribunes), waarbij in geval van bezwijken meer dan 500 personen gelijktijdig gevaar lopen <br> **-** Gebouwen bedoeld voor een groep verminderd zelfredzame personen zoals ziekenhuizen, celgebouwen, verpleegtehuizen, met 4 of meer bouwlagen <br> **-** Gebouwen waar zeer vitale processen worden bestuurd, bijv. verkeerstoren Schiphol, verkeersleidingsgebouw <br> **-** Industriegebouwen voor gevaarlijke stoffen en/of processen zijnde onderdeel van een inrichting waarvoor een omgevingsvergunning voor het milieu noodzakelijk is en waarvan het bezwijken van het gebouw kan leiden tot het betreffende ongewenste milieueffect |
| **CC2**          | **-** Voor zover niet opgenomen in CC1 of CC3: <br> **-** Eengezinswoningen met 4 of meer bouwlagen <br> **-** Woongebouwen, hotels, en kantoorgebouwen <br> **-** Onderwijsgebouwen <br> **-** Winkels <br> **-** Gebouwen bedoeld voor een groep verminderd zelfredzame personen zoals ziekenhuizen, celgebouwen, verpleegtehuizen, met maximaal 3 bouwlagen <br> **-** Openbare gebouwen/industriegebouwen waarbij het aantal personen binnen niet beperkt is, of met 3 of meer bouwlagen <br> **-** Parkeergarages |
| **CC1b**         | **-** Eengezinswoningen* met 1, 2 of 3 bouwlagen <br> **-** Landbouwbedrijfsgebouwen uitsluitend voor productiedoeleinden, waarbij het aantal personen binnen beperkt is <br> **-** Tuinbouwkassen uitsluitend voor productiedoeleinden, waarbij het aantal personen binnen beperkt is <br> **-** Industriegebouwen met 1 of 2 bouwlagen uitsluitend voor productiedoeleinden, waarbij het aantal personen binnen beperkt is |
| **CC1a**         | **-** Landbouwbedrijfsgebouwen voor opslagdoeleinden en waarbij potentieel levensgevaar nagenoeg uitgesloten is <br> **-** Reclameborden bij een bouwactiviteit <br> **-** Reclamedragers rond lantaarnpalen <br> **-** Waslijnpaal <br> **-** Afscheiding tussen twee balkons <br> **-** Erfafscheiding |

$^{*}$ Grondgebonden woning niet gelegen in een woongebouw.
*Zie NEN-EN 1990 Nationale Bijlage tabel NB.24*


## Aanbevolen waarden van $\psi$-factoren voor gebouwen

Voor de veranderlijke belasting worden naast de (extreme) karakteristieke waarde voor de belasting \(Q\), met behulp van de $\psi$ factoren nog drie andere waarden onderscheiden:

- $Q_k$ = (extreme) karakteristieke waarde van de veranderlijke belasting
- $\psi_0 Q_k$ = combinatiewaarde van de veranderlijke belasting
- $\psi_1 Q_k$ = frequente waarde van de veranderlijke belasting
- $\psi_2 Q_k$ = quasi-blijvende waarde van de veranderlijke belasting

De volgende figuur geeft een voorbeeld van een veranderlijke belasting, uitgezet in de tijd.

```{figure} Images/416_aanbevolen_waarden_van_ψ_factoren_voor_gebouwen.png
---
scale: 30%
name: Voorbeeld van een veranderlijke belasting
---
```

**Belasting** 
| Voorgeschreven belastingen in gebouwen (categorie) | **$\psi_0$** | **$\psi_1$** | **$\psi_2$** |
|-----------------------------------------------------------------------------------------------------|---------------|---------------|---------------|
| **Categorie A**: woon- en verblijfsruimtes                                                             | 0,4           | 0,5           | 0,3           |
| **Categorie B**: kantoorruimtes                                                                         | 0,5           | 0,5           | 0,3           |
| **Categorie C**: bijeenkomstruimtes                                                                     | 0,6/0,4^*    | 0,7           | 0,6           |
| C1: Ruimten met tafels enz. bijv. ruimten in scholen, cafés, restaurants, eetzalen, leeszalen, ontvangstruimten. |               |               |               |
| C2: Ruimten met vaste zitplaatsen, bijv. ruimten in kerken, theaters of bioscopen, conferentiezalen, collegezalen, vergaderzalen, wachtkamers, wachtkamers/-lokalen in stations. |               |               |               |
| C3: Ruimten zonder obstakels voor rondlopende mensen, bijv. ruimten in musea, tentoonstellingsruimten enz. en toegangsruimten in openbare gebouwen en kantoren, hotels, ziekenhuizen, stationshallen. |               |               |               |
| C4: Ruimten ten behoeve van o.a. lichaamsbeweging, bijv. danszalen, gymnastiekzalen, toneel-/balletpodia enz. |               |               |               |
| C5: Ruimten waar zich grote mensenmassa’s kunnen bevinden, bijv. in gebouwen voor openbare evenementen, zoals concertzalen, sporthallen met inbegrip van tribunes, bordessen en toegangsruimten, stationsperrons. |               |               |               |
| **Categorie D**: winkelruimtes                                                                          | 0,4           | 0,7           | 0,6           |
| D1: Ruimten in gewone kleinhandelszaken.                                                           |               |               |               |
| D2: Ruimten in grootwarenhuizen/supermarkten.                                                      |               |               |               |
| **Categorie E**: opslagruimtes                                                                          | 1,0           | 0,9           | 0,8           |
| E1: Ruimten die gevoelig zijn voor opeenhoping van goederen, inclusief toegangsruimten             |               |               |               |
| E2: Industrieel gebruik                                                                              |               |               |               |
| **Categorie F**: verkeersruimte, voertuiggewicht $\geq$ 25 kN                                          | 0,7           | 0,7           | 0,6           |
| **Categorie G**: verkeersruimte$^{**}$, 25 kN < voertuiggewicht $\geq$ 160 kN                        | 0,7           | 0,5           | 0,3           |
| **Categorie H**: daken                                                                                    | 0             | 0             | 0             |
| **Andere soorten belasting (van buitenaf)** |   |   |   |
| Industrieel gebruik waarbij de veranderlijke belasting: |     |     |     |
| — niet langdurig aanwezig is | 0,5           | 0,5           | 0,3           |
| — langdurig aanwezig is | 1,0           | 0,9           | 0,8           |
| Sneeuwbelasting | 0             | 0,2           | 0             |
| Belasting door regenwater | 0             | 0             | 0             |
| Windbelasting | 0             | 0,2           | 0             |
| Temperatuur (geen brand) | 0             | 0,5           | 0             |

$^{*}$ De waarde 0,6 geldt voor delen van het gebouw die in geval van een calamiteit zwaar kunnen worden belast door een mensenmenigte (vluchtroutes, trappen enz.); de waarde 0,4 geldt in overige gevallen.

$^{**}$ Met verkeersruimte wordt in dit geval een ruimte bedoeld waar voertuigen kunnen rijden, bijvoorbeeld parkeergarages.

*Zie: NEN-EN 1990 Nationale bijlage. tabel NB.2 A1.1*
