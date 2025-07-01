# Beton

## Sterkte en stijfheid

<div style="max-height: 400px; overflow-y: auto;">
    <table style="width: 100%; border-collapse: collapse;">
        <thead style="position: sticky; top: 0; background-color: #f2f2f2;">
            <tr>
                <th style="width: 200px;">Materiaaleigenschap</th>
                <th></th>
                <th></th>
                <th colspan="6" style="text-align: center;">Sterkteklasse</th>
            </tr>
            <tr>
                <th></th>
                <th style="width: 150px;"></th>
                <th style="width: 150px;"></th>
                <th style="width: 150px;">C12/15</th>
                <th style="width: 150px;">C20/25</th>
                <th style="width: 150px;">C30/37</th>
                <th style="width: 150px;">C35/45</th>
                <th style="width: 150px;">C45/55</th>
                <th style="width: 150px;">C50/60</th>
            </tr>
        </thead>
        <tbody>
            <tr><td>volumieke massa</td><td>ρ<sub>rep</sub></td><td>[kg/m<sup>3</sup>]</td><td>2500</td><td>2500</td><td>2500</td><td>2500</td><td>2500</td><td>2500</td></tr>
            <tr><td>elasticiteitsmodulus</td><td>E<sub>cm</sub></td><td>[N/mm<sup>2</sup>]</td><td>27000</td><td>30000</td><td>33000</td><td>34000</td><td>36000</td><td>37000</td></tr>
            <tr><td>gemiddelde druksterkte</td><td>f<sub>cm</sub></td><td>[N/mm<sup>2</sup>]</td><td>20</td><td>28</td><td>38</td><td>43</td><td>53</td><td>58</td></tr>
            <tr><td>karakteristieke cilindersterkte</td><td>f<sub>ck</sub></td><td>[N/mm<sup>2</sup>]</td><td>12</td><td>20</td><td>30</td><td>35</td><td>45</td><td>50</td></tr>
            <tr><td>karakteristieke kubussterkte</td><td>f<sub>ck;cube</sub></td><td>[N/mm<sup>2</sup>]</td><td>15</td><td>25</td><td>37</td><td>45</td><td>55</td><td>60</td></tr>
            <tr><td>gemiddelde treksterkte</td><td>f<sub>ctm</sub></td><td>[N/mm<sup>2</sup>]</td><td>1,6</td><td>2,2</td><td>2,9</td><td>3,2</td><td>3,8</td><td>4,1</td></tr>
            <tr><td>karakteristieke treksterkte</td><td>f<sub>ctk;0,05</sub></td><td>[N/mm<sup>2</sup>]</td><td>1,1</td><td>1,5</td><td>2,0</td><td>2,2</td><td>2,7</td><td>2,9</td></tr>
        </tbody>
    </table>
</div>


## Sterkte

| Rekenwaarde | Formule | |
|---|---|---|
| Rekenwaarde druksterkte: |  $\mathsf{ f_{cd}=\frac{f_{ck}}{\gamma_C}}$ | $\mathsf{\gamma_C}$ is de partiele veiligheidsfactor voor beton. $\mathsf{\gamma_C}=1,5$ |
| Rekenwaarde afschuifsterkte: | $\mathsf{0,035\cdot k^{3/2}\cdot \sqrt{f_{ck}}}$ | Ondergrens, voor preciese waarde, zie NEN-EN1992. De afschuif weerstand van het beton kan als vergroot worden door wapening toe te passen. |
|  | $\mathsf{k=1+\sqrt{\frac{200}{d}}\leq 2}$ | d in mm |

<br>

## Spannings-rek diagram

| Diagram | | |
|---|---|---|
| <img src="Images/8gegevens_beton_spanning_rek.png" alt="Spannings-rek diagram" class="bg-primary" width="300px"> | $\mathsf{\sigma_c}$ <br> $\mathsf{\epsilon_c}$ <br> $\mathsf{f_{ck}}$ <br> $\mathsf{f_{cd}}$ <br> $\mathsf{\epsilon_{c3}}$ <br> $\mathsf{\epsilon'_{bu}}$ <br> $\mathsf{\epsilon_{c3}}$ <br> $\mathsf{\epsilon_{cu3}}$ | drukspanning van het beton <br> rek van het beton <br> karakteristieke waarde druksterkte <br> rekenwaarde druksterkte <br> betonstuik bij het begin van de plastische vervorming <br> grenswaarde van de betonstuik <br> 1,75 ‰ * <br> 3,50 ‰ * |

$^{*}$ Deze waardes zijn geldig voor de sterkteklassen in bovenstaande tabel, niet bij hogere sterkteklassen.
