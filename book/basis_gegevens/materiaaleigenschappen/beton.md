# Beton

## Sterkte en stijfheid

| **Materiaaleigenschap** | | | **Sterkteklasse** | | | | | |
|---|---|---|---|---|---|---|---|---|
| | | | C12/15 | C20/25 | C30/37 | C35/45 | C45/55 | C50/60 |
| volumieke massa | $\mathsf{\rho_{rep}}$ | $\mathsf{[kg/m^3]}$ | 2500 | 2500 | 2500 | 2500 | 2500 | 2500 |
| elasticiteitsmodulus | $\mathsf{E_{cm}}$ | $\mathsf{[N/mm^2]}$ | 27000 | 30000 | 33000 | 34000 | 36000 | 37000 |
| gemiddelde druksterkte | $\mathsf{f_{cm}}$ | $\mathsf{[N/mm^2]}$ | 20 | 28 | 38 | 43 | 53 | 58 |
| karakteristieke cilindersterkte | $\mathsf{f_{ck}}$ | $\mathsf{[N/mm^2]}$ | 12 | 20 | 30 | 35 | 45 | 50 |
| karakteristieke kubussterkte | $\mathsf{f_{ck;cube}}$ | $\mathsf{[N/mm^2]}$ | 15 | 25 | 37 | 45 | 55 | 60 |
| gemiddelde treksterkte | $\mathsf{f_{ctm}}$ | $\mathsf{[N/mm^2]}$ | 1,6 | 2,2 | 2,9 | 3,2 | 3,8 | 4,1 |
| karakteristieke treksterkte | $\mathsf{f_{ctk;0,05}}$ | $\mathsf{[N/mm^2]}$ | 1,1 | 1,5 | 2,0 | 2,2 | 2,7 | 2,9 |


## Sterkte

| Rekenwaarde | Formule | |
|---|---|---|
| Rekenwaarde druksterkte: |  $$\mathsf{ f_{cd}=\frac{f_{ck}}{\gamma_C}}$$ | $\mathsf{\gamma_C}$ is de partiele veiligheidsfactor voor beton. $\mathsf{\gamma_C}=1,5$ |
| Rekenwaarde afschuifsterkte: | $$\mathsf{0,035\cdot k^{3/2}\cdot \sqrt{f_{ck}}}$$ | Ondergrens, voor preciese waarde, zie NEN-EN1992. De afschuif weerstand van het beton kan als vergroot worden door wapening toe te passen. |
|  | $$\mathsf{k=1+\sqrt{\frac{200}{d}}\leq 2}$$ | d in mm |

<br>

## Spannings-rek diagram

| Diagram | | |
|---|---|---|
| ![Spannings-rek diagram](Images/8gegevens_beton_spanning_rek.png) | $\mathsf{\sigma_c}$ <br> $\mathsf{\epsilon_c}$ <br> $\mathsf{f_{ck}}$ <br> $\mathsf{f_{cd}}$ <br> $\mathsf{\epsilon_{c3}}$ <br> $\mathsf{\epsilon'_{bu}}$ <br> $\mathsf{\epsilon_{c3}}$ <br> $\mathsf{\epsilon_{cu3}}$ | : drukspanning van het beton <br> : rek van het beton <br> : karakteristieke waarde druksterkte <br> : rekenwaarde druksterkte <br> : betonstuik bij het begin van de plastische vervorming <br> : grenswaarde van de betonstuik <br> : 1,75 ‰ * <br> : 3,50 ‰ * |

$^{*}$ Deze waardes zijn geldig voor de sterkteklassen in bovenstaande tabel, niet bij hogere sterkteklassen.
