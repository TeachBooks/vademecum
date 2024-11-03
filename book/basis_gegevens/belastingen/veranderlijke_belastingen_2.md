# Veranderlijke belastingen II, wind

De belastingen die worden veroorzaakt door wind zijn aanzienlijk en dienen dan ook met zorg te worden bestudeerd voor de berekeningen. In de Bachelor Bouwkunde mag echter met een vereenvoudigde windbelasting worden gerekend. Voor een meer gedetailleerde berekening of bij gebouwen met afwijkende vorm kan NEN-EN 1991-1-4 Algemene belastingen - Windbelasting geraadpleegd worden.

## Bepalen windbelasting (eenvoudige formule)

<br>

$$
F_i = c_sc_d \cdot c_f \cdot q_p(z_e) \cdot A_{ref}
$$

Zie NEN-EN 1991-1-4 sectie 5.3.

| Symbolen                  | Betekenis                                                      |
|---------------------------|---------------------------------------------------------------|
| $F_i$                   | Windkracht op een constructie of constructie-element          |
| $c_sc_d$                | Bouwwerkfactor¹                                              |
| $c_f$                   | Krachtcoëfficiënt voor de constructie of het constructie-element |
| $q_p(z_e)$              | Extreme stuwdruk op referentiehoogte \(z_e\)²                |
| $A_{ref}$               | Referentie-oppervlakte van de constructie of constructie-element |

*¹ Voor gebouwen met een hoogte kleiner dan 15 m mag voor $c_sc_d$ de waarde 1 zijn genomen. Voor meer informatie raadpleeg NEN-EN 1991-1-4.  
² Voor hoge gebouwen (h>b) mag aangenomen worden dat de stuwdruk afneemt naar de grond toe.*

## Krachtcoëfficiënt $C_f$ voor constructie of constructie-element: gevels en daken

De nettodruk op een wand, dak of element is het verschil tussen de druk op de vlakken aan weerszijden, rekening houdend met het teken van de druk. Overdruk, gericht naar het oppervlak, wordt positief gerekend en onderdruk, weg van het oppervlak, wordt negatief gerekend.

In deze paragraaf worden de krachtcoëfficiënten behandeld. De methode wordt hier uitgelegd aan de hand van een eenvoudig gebouw, gezien de Eurocode erg uitgebreid is. Gebruik NEN-EN 1991-1-4 voor meer gecompliceerde gebouwvormen.

Allereerst moeten de verschillende windbelastingen worden bepaald: de krachtcoëfficiënten die corresponderen met de verschillende windzones zijn afhankelijk van de geometrie van het gebouw. Krachtcoëfficiënten zijn gegeven voor bepaalde standaardwaarden, voor andere waarden is interpolatie toegestaan. In deze paragraaf zijn uitsluitend krachtcoëfficiënten gegeven die horen bij grote oppervlakken (>10m²). Zie NEN-EN-1999 1-1-4 voor kleinere oppervlakken.

| Positieve uitwendige druk | Positieve inwendige druk |
|---------------------------|---------------------------|
| <img src="Images/542_external.png" alt="Positieve uitwendige druk" class="bg-primary" width="200px"> | <img src="Images/542_internal.png" alt="Positieve inwendige druk" class="bg-primary" width="200px"> |

Beide krachten worden gecombineerd in een ongunstige situatie.

## Parameters constructie

- $h$ = referentiehoogte [m]
- $d$ = afmeting in windrichting [m]
- $b$ = afmeting loodrecht op de windrichting [m]
- $e$ = $b$ of $2h$, kleinste waarde is maatgevend

Let op dat voor beide windrichtingen verschillende parameters gelden.

```{figure} Images/543_parameters.png
---
scale: 25%
name: Parameters
---
```

## Windzones voor gevels

De verschillende windzones voor de gevels van een gebouw zijn hieronder weergegeven. Het aantal windzones op de gevel varieert van 1 tot 3, afhankelijk van de waardes van $e$ en $d$. Voor gebouwen met een zadeldak gelden dezelfde zones. De waarde van $h$ dient dan genomen te worden als de hoogte van de nok boven maaiveldniveau. De parameters $e$ en $d$jaa zijn hierboven gedefinieerd.

```{figure} Images/544_windzones_gevels.png
---
scale: 25%
---
```

```{figure} Images/544_windzones_gevels_2.png
---
scale: 25%
---
```

**Gevels: Krachtcoëfficiënt $C_f$ voor zone**
| **$h/d$**        | **A** | **B** | **C** | **D** | **E** |
|------------------|-----|-------|-------|-------|-------|
| 5                | -1.2| -0.8  | -0.5  | +0.8  | -0.7  |
| 1                | -1.2| -0.8  | -0.5  | +0.8  | -0.5  |
| $\geq 0.25$      | -1.2| -0.8  | -0.5  | +0.7  | -0.3  |

## Windzones voor platte daken

```{figure} Images/545_windonzes_platte_daken.png
---
scale: 25%
name: Windzones platte daken
---
```

**Platte daken: Krachtcoëfficiënt $C_f$ voor zone**
| type              | F     | G     | H     | I     |
|-------------------|-------|-------|-------|-------|
| scherpe dakranden | -1.8  | -1.2  | -0.7  | +0.2/-0.2 |

Op andere randen zijn mogelijk lagere krachtcoëfficiënten van toepassing, zie NEN-EN-1991-1-4.

## Windzones voor zadeldaken

```{figure} Images/546_windzones_duopitched.png
---
scale: 25%
---
```

**Zadeldaken ($\theta = 0$): Krachtcoëfficiënt $C_f$ voor zone**
| hellingshoek $\alpha$     | F     | G     | H     | I     | J     |
|------------------------------|-------|-------|-------|-------|-------|
| 5°                           | -1.7  | -1.2  | -0.6  | -0.6  | +0.2  |
|                              | +0.0  | +0.0  | +0.0  | -0.6  | -0.6  |
| 15°                          | -0.9  | -0.8  | -0.3  | -0.4  | -1.0  |
|                              | +0.2  | +0.2  | +0.2  | 0.0   | 0.0   |
| 30°                          | -0.5  | -0.5  | -0.2  | -0.4  | -0.5  |
|                              | +0.7  | +0.7  | +0.4  | +0.0  | +0.0  |
| 45°                          | -0.0  | -0.0  | -0.0  | -0.2  | -0.3  |
|                              | +0.7  | +0.7  | +0.6  | +0.0  | +0.0  |
| 60°                          | +0.7  | +0.7  | +0.7  | -0.2  | -0.3  |
| 75°                          | +0.8  | +0.8  | +0.8  | -0.2  | -0.3  |


**Zadeldaken ($\theta = 90$): Krachtcoëfficiënt $C_f$ voor zone**
| hellingshoek $\alpha$         | F     | G     | H     | I     |
|-------------------------------|-------|-------|-------|-------|
| 5°                            | -1.6  | -2.2  | -0.7  | -0.6  |
| 15°                           | -1.3  | -2.0  | -0.6  | -0.5  |
| 30°                           | -1.1  | -1.5  | -0.8  | -0.5  |
| 45°                           | -1.1  | -1.5  | -0.9  | -0.5  |
| 60°                           | -1.1  | -1.5  | -0.8  | -0.5  |
| 75°                           | -1.1  | -1.5  | -0.8  | -0.5  |


## Windzones voor open overkappingen

Een open overkapping is een dak van een constructie die geen blijvende gevels heeft, zoals benzinestations en kapschuren. Een resultante kracht kan worden bepaald voor open overkappingen (zonder gebruik van windzones). Deze kracht vertegenwoordigt het effect van alle windzones op de totale constructie. De kracht werkt op de punten zoals hieronder weergegeven, en wordt berekend met dezelfde formule als voor andere windbelastingen. De plek waar de kracht op aangrijpt is afhankelijk van de geometrie en het teken van de gehele krachtcoëfficient.

![Windzones Canopies 1](Images/547_windzones_canopies_1.png)

Lokaal kan de winddruk of -zuiging op de overkapping natuurlijk groter zijn dan het gemiddelde. Voor het ontwerp van dakelementen en bevestigingen dienen deze lokale belastingen meegenomen te worden. Voor het rekenen aan lokale windkrachten wordt de overkapping onderverdeeld in verschillende windzones, zoals hieronder weergegeven.

```{figure} Images/547_windzones_canopies_2.png
---
scale: 25%
name: Windzones Canopies 2
---
```

De blokkeringsgraad onder een open overkapping is weergegeven in onderstaande figuur. Deze is afhankelijk van de blokkering $\varphi$, wat de verhouding beschrijft tussen de oppervlakte van werkelijk aannemelijke obstakels onder de overkapping en de oppervlakte onder de overkapping, dwars op de wind. Beide oppervlakten staan loodrecht op de windrichting. $\mathsf{\varphi=0}$ betekent een lege overkapping, $\mathsf{\varphi=1}$ betekent een overkapping volledig gevuld aan lijzijde van het dak (dit is geen gesloten gebouw).

![Windzones Canopies 3](Images/547_windzones_canopies_3.png)

| **Lessenaarsdaken**  |  | **Krachtcoëfficiënt C$\mathsf{_f}$ voor zone** | | | |
|----------------------|--|------------------------------------------------|-|-|-|
| Dakhelling $\alpha$  | blokkering $\varphi$ | globale krachtcoëfficient $\mathsf{c_f}$ | A | B | C |
| 0°                   | Maximaal voor alle $\varphi$ | +0,2 | +0,5 | +1,8 + | +1,1 |
|                      | Minimaal voor $\mathsf{\varphi=0}$ | -0,5 | -0,6 | -1,3 | -1,4 |
|                      | Minimaal voor $\mathsf{\varphi=1}$ | -1,3 | -1,5 | -1,8 | -2,2 |
| 5°                   | Maximaal voor alle $\varphi$ | +0,4 | +0,8 | +2,1 | +1,3 |
|                      | Minimaal voor $\mathsf{\varphi=0}$ | -0,7 | -1,1 | -1,7 | -1,8 |
|                      | Minimaal voor $\mathsf{\varphi=1}$ | -1,4 | -1,6 | -2,2 | -2,5 |
| 10°                  | Maximaal voor alle $\varphi$ | +0,5 | +1,2 | +2,4 | +1,6 |
|                      | Minimaal voor $\mathsf{\varphi=0}$ | -0,9 | -1,5 | -2,0 | -2,1 |
|                      | Minimaal voor $\mathsf{\varphi=1}$ | -1,4 | -2,1 | -2,6 | -2,7 |
| 15°                  | Maximaal voor alle $\varphi$ | +0,7 | +1,4 | +2,7 | +1,8 |
|                      | Minimaal voor $\mathsf{\varphi=0}$ | -1,1 | -1,8 | -2,4 | -2,5 |
|                      | Minimaal voor $\mathsf{\varphi=1}$ | +1,4 | -1,6 | -2,9 | -3,0 |
| 20°                  | Maximaal voor alle $\varphi$ | +0,8 | +1,7 | +2,9 | +2,1 |
|                      | Minimaal voor $\mathsf{\varphi=0}$ | -1,3 | -2,2 | -2,8 | -2,9 |
|                      | Minimaal voor $\mathsf{\varphi=1}$ | -1,4 | -1,6 | -2,29 | -3,0 |
| 25°                  | Maximaal voor alle $\varphi$ | +1,0 | +2,0 | +3,1 | +2,3 |
|                      | Minimaal voor $\mathsf{\varphi=0}$ | -1,6 | -2,6 | -3,2 | -3,2 |
|                      | Minimaal voor $\mathsf{\varphi=1}$ | -1,4 | -1,5 | -2,5 | -2,8 |
| 30°                  | Maximaal voor alle $\varphi$ | +1,2 | +2,2 | +3,2 | +2,4 |
|                      | Minimaal voor $\mathsf{\varphi=0}$ | -1,8 | -3,0 | -3,8 | -3,6 |
|                      | Minimaal voor $\mathsf{\varphi=1}$ | -1,4 | -1,5 | -2,2 | -2,7 |

Voor $\mathsf{\theta=0}$, tussen $\mathsf{\alpha=0°}$ en $\mathsf{\alpha=45°}$ varieert de winddruk snel tussen positieve en negatieve waarden. Voor deze daken dienen vier gevallen te worden beschouwd, waar de grootste of kleinste waarden van alle zones F, G en H worden gecombineerd met de grootste of kleinste waarden in gebieden I en J. Het is niet toegestaan om positieve en negatieve waarden te combineren op hetzelfde vlak.

### Krachtcoëfficienten C$\mathsf{_{fr}}$ voor wrijving

Op vlakken parallel aan de windrichting werkt windwrijving. Voor ontwerpdoeleinden mag het worden aangenomen dat deze kracht werkt langs alle vlakken parallel aan de windrichting. Volgens NEN-EN-1991-1-4 kan dit afhankelijk van de geometrie worden gereduceerd.

| oppervlakten        | wrijvingscoëfficiënt $\mathsf{c_{fr}}$ |
|---------------------|-------------------------------------|
| glad (bijvoorbeeld staal, glad beton) | 0,01 |
| ruw (bijvoorbeeld ruwe beton, beteerde boorden) | 0,02 |
| zeer ruw (bijvoorbeeld rimpels, rubben, kronkelingen) | 0,04 |

### Krachtcoëfficienten C$\mathsf{_f}$ voor inwendige druk

De krachtcoefficiënten voor inwendige druk zijn afhankelijk van het aantal openingen in de gevel en de geometrie van het gebouw. Om overgecompliceerde berekeningen tijdens het ontwerpen te vermijden, wordt in NEN-EN-1991-1-4 vermeld: *"Wanneer in ten minste twee zijden van het gebouw (gevels of dak) de totale oppervlakte van de openingen per zijde meer is dan 30% van de oppervlakte van deze zijde, behoren de belastingen op de constructie niet te zijn berekend volgens de regels gegeven in deze paragraaf, maar behoren in plaats daarvan de regels van 7.3 en 7.4 (open overkappingen) te zijn gebruikt."*

### Windregio's in Nederland

De grootte van de extreme stuwdruk wordt bepaald door de gebouwhoogte, de plaats waar het gebouw staat en of rond het bouwwerk al of niet is gebouwd. Nederland is opgedeeld in drie regio’s, waarvan de windstuwdruk varieert. In de kustprovincies waait het harder dan in de landprovincies. Voor een gebouw direct langs de kust geldt een nog grotere windbelasting. Hieronder is de kaart opgenomen waarin de verschillende windregio's zijn aangegeven.

![Windregio's in Nederland](Images/5410_windregios_in_nederland.png)

### Extreme stuwdruk $q_p$ $(Z_e)$

De grootte van de windbelasting wordt bepaald door de windstuwdruk. Voor de basisstuwdruk geldt de formule 

$q_p = 0,5 \cdot \rho \cdot v^2$

Hierin is $\rho$ de dichtheid van de lucht en $v$ de windsnelheid. De luchtdichtheid is afhankelijk van de hoogte, de temperatuur en de luchtdruk. In de Nationale Bijlage bij de NEN-EN 1991 deel 1-4 wordt voor de luchtdichtheid van 1,25 kg/m^3 aangehouden. Bij het bepalen van de windbelasting moet worden gerekend met de extreme stuwdruk op de referentiehoogte z:

$q_p(z) = C_e(z) \cdot q_b$  
(*waarbij $C_e$ de blootstellingsfactor is*)

Onderstaand is een tabel opgenomen waarin de verschillende waarden voor de extreme stuwdruk zijn weergegeven.

| | $z_e$ [m] | | | $q_p(z_e)$ [kN/m^2] | | | | |
|---|---|---|---|---|---|---|---|---|
|   | regio 1 |   |   | regio 2 |   |   | regio 3 |   |
|   | kust | onbebouwd | bebouwd | kust | onbebouwd | bebouwd | onbebouwd | bebouwd |
| 1 | 0,93 | 0,71 | 0,69 | 0,78 | 0,60 | 0,58 | 0,49 | 0,48 |
| 2 | 1,11 | 0,71 | 0,69 | 0,93 | 0,60 | 0,58 | 0,49 | 0,48 |
| 3 | 1,22 | 0,71 | 0,69 | 1,02 | 0,60 | 0,58 | 0,49 | 0,48 |
| 4 | 1,30 | 0,71 | 0,69 | 1,09 | 0,60 | 0,58 | 0,49 | 0,48 |
| 5 | 1,37 | 0,78 | 0,69 | 1,14 | 0,66 | 0,58 | 0,54 | 0,48 |
| 6 | 1,42 | 0,84 | 0,69 | 1,19 | 0,71 | 0,58 | 0,58 | 0,48 |
| 7 | 1,47 | 0,89 | 0,69 | 1,23 | 0,75 | 0,58 | 0,62 | 0,48 |
| 8 | 1,51 | 0,94 | 0,73 | 1,26 | 0,79 | 0,62 | 0,65 | 0,51 |
| 9 | 1,55 | 0,98 | 0,77 | 1,29 | 0,82 | 0,65 | 0,68 | 0,53 |
| 10 | 1,58 | 1,02 | 0,81 | 1,32 | 0,85 | 0,68 | 0,70 | 0,56 |
| 15 | 1,71 | 1,16 | 0,96 | 1,43 | 0,98 | 0,80 | 0,80 | 0,66 |
| 20 | 1,80 | 1,27 | 1,07 | 1,51 | 1,07 | 0,90 | 0,88 | 0,74 |
| 25 | 1,88 | 1,36 | 1,16 | 1,57 | 1,14 | 0,97 | 0,94 | 0,80 |
| 30 | 1,94 | 1,43 | 1,23 | 1,63 | 1,20 | 1,03 | 0,99 | 0,85 |
| 35 | 2,00 | 1,50 | 1,30 | 1,67 | 1,25 | 1,09 | 1,03 | 0,89 |
| 40 | 2,04 | 1,55 | 1,35 | 1,71 | 1,30 | 1,13 | 1,07 | 0,93 |
| 45 | 2,09 | 1,60 | 1,40 | 1,75 | 1,34 | 1,17 | 1,11 | 0,97 |
| 50 | 2,21 | 1,65 | 1,45 | 1,78 | 1,38 | 1,21 | 1,14 | 1,00 |
| 55 | 2,16 | 1,69 | 1,49 | 1,81 | 1,42 | 1,25 | 1,17 | 1,03 |
| 60 | 2,19 | 1,73 | 1,53 | 1,83 | 1,45 | 1,28 | 1,19 | 1,05 |
| 65 | 2,22 | 1,76 | 1,57 | 1,86 | 1,48 | 1,31 | 1,22 | 1,08 |
| 70 | 2,25 | 1,80 | 1,60 | 1,88 | 1,50 | 1,34 | 1,24 | 1,10 |
| 75 | 2,27 | 1,83 | 1,63 | 1,90 | 1,53 | 1,37 | 1,26 | 1,13 |
| 80 | 2,30 | 1,86 | 1,66 | 1,92 | 1,55 | 1,39 | 1,28 | 1,15 |
| 85 | 2,32 | 1,88 | 1,69 | 1,94 | 1,58 | 1,42 | 1,30 | 1,17 |
| 90 | 2,34 | 1,91 | 1,72 | 1,96 | 1,60 | 1,44 | 1,32 | 1,18 |
| 95 | 2,36 | 1,93 | 1,74 | 1,98 | 1,62 | 1,46 | 1,33 | 1,20 |
| 100 | 2,38 | 1,96 | 1,77 | 1,99 | 1,64 | 1,48 | 1,35 | 1,22 |
| 110 | 2,42 | 2,00 | 1,81 | 2,03 | 1,68 | 1,52 | 1,38 | 1,25 |
| 120 | 2,45 | 2,04 | 1,85 | 2,05 | 1,71 | 1,55 | 1,41 | 1,28 |
| 130 | 2,48 | 2,08 | 1,89 | 2,08 | 1,74 | 1,59 | 1,44 | 1,31 |
| 140 | 2,51 | 2,12 | 1,93 | 2,10 | 1,77 | 1,62 | 1,46 | 1,33 |
| 150 | 2,54 | 2,15 | 1,96 | 2,13 | 1,80 | 1,65 | 1,48 | 1,35 |
| 160 | 2,56 | 2,18 | 2,00 | 2,15 | 1,83 | 1,67 | 1,50 | 1,38 |
| 170 | 2,59 | 2,21 | 2,03 | 2,17 | 1,85 | 1,70 | 1,52 | 1,40 |
| 180 | 2,61 | 2,24 | 2,06 | 2,19 | 1,88 | 1,72 | 1,54 | 1,42 |
| 190 | 2,63 | 2,27 | 2,08 | 2,20 | 1,90 | 1,75 | 1,56 | 1,44 |
| 200 | 2,65 | 2,29 | 2,11 | 2,22 | 1,92 | 1,77 | 1,58 | 1,46 |
