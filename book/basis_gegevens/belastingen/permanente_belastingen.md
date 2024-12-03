# Permanente belastingen

De permanente belastingen van constructies bestaan uit het eigen gewicht van het desbetreffende constructie-element en de eigen gewichten van de erop rustende (afbouw)elementen. Door gebruik te maken van de tabellen zoals deze, kunnen de permanente belastingen worden bepaald voor ontwerp-/gewichtsberekeningen alsmede voor controle.

## Bouwmaterialen I


<div style="max-height: 400px; overflow-y: auto;">
    <table style="width: 100%; border-collapse: collapse;">
        <thead style="position: sticky; top: 0; background-color: #f2f2f2;">
            <tr>
                <th>Materiaal</th>
                <th>ρ [kg/m³]</th>
            </tr>
        </thead>
        <tbody>
            <tr><td colspan="2"><strong>Primaire bouwstoffen</strong></td></tr>
            <tr><td>Duinzand - droog</td><td>1550</td></tr>
            <tr><td>Duinzand - vochtig</td><td>1700</td></tr>
            <tr><td>Duinzand - verzadigd</td><td>1950</td></tr>
            <tr><td>Rivier- en grindzand - droog</td><td>1650</td></tr>
            <tr><td>Rivier- en grindzand - vochtig</td><td>1750</td></tr>
            <tr><td>Rivier- en grindzand - verzadigd</td><td>2000</td></tr>
            <tr><td>Grind - droog</td><td>1600</td></tr>
            <tr><td>Grind - vochtig</td><td>1700-2000</td></tr>
            <tr><td>Grind - verzadigd</td><td>1922</td></tr>
            <tr><td>Aarde en klei - droog</td><td>1600</td></tr>
            <tr><td>Aarde en klei - nat</td><td>2000</td></tr>
            <tr><td>Natuursteen - basalt, graniet</td><td>2850</td></tr>
            <tr><td>Natuursteen - kalksteen, marmer</td><td>2700</td></tr>
            <tr><td>Natuursteen - leisteen</td><td>2700</td></tr>
            <tr><td colspan="2"><strong>Secundaire bouwstoffen</strong></td></tr>
            <tr><td>As</td><td>1000</td></tr>
            <tr><td>Hoogovenslakken</td><td>1700</td></tr>
            <tr><td colspan="2"><strong>Metselwerk</strong></td></tr>
            <tr><td>Klinkers</td><td>2000</td></tr>
            <tr><td>Gewone gevelstenen - vol (0% perforatie)</td><td>1700</td></tr>
            <tr><td>Gewone gevelstenen - geperforeerd (20%)</td><td>1400</td></tr>
            <tr><td>Gewone gevelstenen - hol (35%)</td><td>1100</td></tr>
            <tr><td>Verblendsteen (20%)</td><td>1800</td></tr>
            <tr><td>Kalkzandsteen</td><td>1850</td></tr>
            <tr><td>Isolatiesteen - poriso, fomin</td><td>1300</td></tr>
            <tr><td>Isolatiesteen - poroton</td><td>800</td></tr>
            <tr><td colspan="2"><strong>Betonstenen</strong></td></tr>
            <tr><td>Betonstenen - licht</td><td>800-1500</td></tr>
            <tr><td>Betonstenen - normaal</td><td>1500-1900</td></tr>
            <tr><td>Betonstenen - zwaar</td><td>1900-2300</td></tr>
            <tr><td>Gasbetonblokken</td><td>500-800</td></tr>
            <tr><td>Gipsblokken</td><td>1100</td></tr>
            <tr><td>Tegels - poreus</td><td>1900</td></tr>
            <tr><td>Tegels - dicht</td><td>2300</td></tr>
            <tr><td colspan="2"><strong>Beton</strong></td></tr>
            <tr><td>Licht beton</td><td>&lt;2000</td></tr>
            <tr><td>Normaal grindbeton</td><td>2300-2450</td></tr>
            <tr><td>Zwaarbeton</td><td>&lt;2800</td></tr>
            <tr><td>Gewapend grindbeton</td><td>2400-2550</td></tr>
            <tr><td>Constructief lichtbeton</td><td>1200-2000</td></tr>
            <tr><td>Schuimbeton</td><td>300-1400</td></tr>
        </tbody>
    </table>
</div>

<br>

Let op: de bovengenomende waarden zijn volumieke massa's, $\mathsf{[kg/m^3]}$, deze moet je dus nog omrekenen naar $\mathsf{[kN/m^3]}!$

*Bron: NEN-EN 1991 Bijlage A*

## Volumieke massa's materialen

<div style="max-height: 400px; overflow-y: auto;">
    <table style="width: 100%; border-collapse: collapse;">
        <thead style="position: sticky; top: 0; background-color: #f2f2f2;">
            <tr>
                <th>Materiaal</th>
                <th>ρ [kg/m³]</th>
            </tr>
        </thead>
        <tbody>
            <tr><td colspan="2"><strong>Primaire bouwstoffen</strong></td></tr>
            <tr><td>Duinzand - droog</td><td>1550</td></tr>
            <tr><td>Duinzand - vochtig</td><td>1700</td></tr>
            <tr><td>Duinzand - verzadigd</td><td>1950</td></tr>
            <tr><td>Rivier- en grindzand - droog</td><td>1650</td></tr>
            <tr><td>Rivier- en grindzand - vochtig</td><td>1750</td></tr>
            <tr><td>Rivier- en grindzand - verzadigd</td><td>2000</td></tr>
            <tr><td>Grind - droog</td><td>1600</td></tr>
            <tr><td>Grind - vochtig</td><td>1700-2000</td></tr>
            <tr><td>Grind - verzadigd</td><td>1922</td></tr>
            <tr><td>Aarde en klei - droog</td><td>1600</td></tr>
            <tr><td>Aarde en klei - nat</td><td>2000</td></tr>
            <tr><td>Natuursteen - basalt, graniet</td><td>2850</td></tr>
            <tr><td>Natuursteen - kalksteen, marmer</td><td>2700</td></tr>
            <tr><td>Natuursteen - leisteen</td><td>2700</td></tr>
            <tr><td colspan="2"><strong>Secundaire bouwstoffen</strong></td></tr>
            <tr><td>As</td><td>1000</td></tr>
            <tr><td>Hoogovenslakken</td><td>1700</td></tr>
            <tr><td colspan="2"><strong>Metselwerk</strong></td></tr>
            <tr><td>Klinkers</td><td>2000</td></tr>
            <tr><td>Gewone gevelstenen - vol (0% perforatie)</td><td>1700</td></tr>
            <tr><td>Gewone gevelstenen - geperforeerd (20%)</td><td>1400</td></tr>
            <tr><td>Gewone gevelstenen - hol (35%)</td><td>1100</td></tr>
            <tr><td>Verblendsteen (20%)</td><td>1800</td></tr>
            <tr><td>Kalkzandsteen</td><td>1850</td></tr>
            <tr><td>Isolatiesteen - poriso, fomin</td><td>1300</td></tr>
            <tr><td>Isolatiesteen - poroton</td><td>800</td></tr>
            <tr><td colspan="2"><strong>Betonstenen</strong></td></tr>
            <tr><td>Betonstenen - licht</td><td>800-1500</td></tr>
            <tr><td>Betonstenen - normaal</td><td>1500-1900</td></tr>
            <tr><td>Betonstenen - zwaar</td><td>1900-2300</td></tr>
            <tr><td>Gasbetonblokken</td><td>500-800</td></tr>
            <tr><td>Gipsblokken</td><td>1100</td></tr>
            <tr><td>Tegels - poreus</td><td>1900</td></tr>
            <tr><td>Tegels - dicht</td><td>2300</td></tr>
            <tr><td colspan="2"><strong>Beton</strong></td></tr>
            <tr><td>Licht beton</td><td>&lt;2000</td></tr>
            <tr><td>Normaal grindbeton</td><td>2300-2450</td></tr>
            <tr><td>Zwaarbeton</td><td>&lt;2800</td></tr>
            <tr><td>Gewapend grindbeton</td><td>2400-2550</td></tr>
            <tr><td>Constructief lichtbeton</td><td>1200-2000</td></tr>
            <tr><td>Schuimbeton</td><td>300-1400</td></tr>
            <tr><td colspan="2"><strong>Overige materialen</strong></td></tr>
            <tr><td>Aluminium, gegoten</td><td>2768</td></tr>
            <tr><td>Kunststeen</td><td>2304</td></tr>
            <tr><td>As, steenkool</td><td>719</td></tr>
            <tr><td>Asfalt, bestrating</td><td>2308</td></tr>
            <tr><td>Ballast, baksteen, grind</td><td>1788</td></tr>
            <tr><td>Gerst, in zakken</td><td>576</td></tr>
            <tr><td>Gerst, in bulk</td><td>640</td></tr>
            <tr><td>Bleek, in vaten</td><td>512</td></tr>
            <tr><td>Bouwblokken</td><td>1305-2202</td></tr>
            <tr><td>Messing, gegoten</td><td>8431</td></tr>
            <tr><td>Messing, gewalst</td><td>8546</td></tr>
            <tr><td>Metselwerk</td><td>1549-2365</td></tr>
            <tr><td>Brons</td><td>8386</td></tr>
            <tr><td>Cement, in zakken</td><td>1345</td></tr>
            <tr><td>Cement, in vaten</td><td>1168</td></tr>
            <tr><td>Cement, mortel</td><td>1678</td></tr>
            <tr><td>Portlandcement, los</td><td>1438</td></tr>
            <tr><td>Porseleinaarde</td><td>2209</td></tr>
            <tr><td>Klei, vochtig, plastic</td><td>1788</td></tr>
            <tr><td>Klei, droog</td><td>1920</td></tr>
            <tr><td>Cokes, los</td><td>480</td></tr>
            <tr><td>Beton, breeze</td><td>1538</td></tr>
            <tr><td>Beton, baksteen</td><td>1918</td></tr>
            <tr><td>Beton, steen</td><td>2308</td></tr>
            <tr><td>Koper, gegoten</td><td>8801</td></tr>
            <tr><td>Koper, gewalst</td><td>8930</td></tr>
            <tr><td>Aardewerk, in kratten</td><td>640</td></tr>
            <tr><td>Aarde, droog, los</td><td>1152</td></tr>
            <tr><td>Aarde, droog, gestampt (stampleem)</td><td>1788</td></tr>
            <tr><td>Aarde, vochtig, verpakt</td><td>1638</td></tr>
            <tr><td>Keisteen</td><td>2640</td></tr>
            <tr><td>Bloem, in zakken</td><td>721</td></tr>
            <tr><td>Hardsteen, gepolijst</td><td>2398</td></tr>
            <tr><td>Keisteen, steenslag</td><td>2238</td></tr>
            <tr><td>Glas, in kratten</td><td>960</td></tr>
            <tr><td>Glas, plaat</td><td>2787</td></tr>
            <tr><td>Glas, dunne plaat</td><td>2497</td></tr>
            <tr><td>Glycerine, verpakt</td><td>832</td></tr>
            <tr><td>Graniet</td><td>2722</td></tr>
            <tr><td>Graniet, gepolijst</td><td>2642</td></tr>
            <tr><td>Graniet, steenslag</td><td>2477</td></tr>
            <tr><td>Grind</td><td>1918</td></tr>
            <tr><td>Hooi, in balen, samengeperst</td><td>384</td></tr>
            <tr><td>Hooi, niet samengeperst</td><td>224</td></tr>
            <tr><td>Ijzer, gegoten</td><td>7203</td></tr>
            <tr><td>Ijzer, gesmeed</td><td>7682</td></tr>
            <tr><td>Ijzerwaren, in verpakking</td><td>896</td></tr>
            <tr><td>Lood, gegoten</td><td>11328</td></tr>
            <tr><td>Lood, plaat</td><td>11358</td></tr>
            <tr><td>Leder, huiden, samengeperst</td><td>368</td></tr>
            <tr><td>Leder, in bundels</td><td>256</td></tr>
            <tr><td>Kalkmortel</td><td>1648</td></tr>
            <tr><td>Kalk, in vaten</td><td>800</td></tr>
            <tr><td>Kalksteen</td><td>2562</td></tr>
            <tr><td>Macadam</td><td>2403</td></tr>
            <tr><td>Marmer</td><td>2642</td></tr>
            <tr><td>Nikkel, monel, metaal</td><td>8896</td></tr>
            <tr><td>Haver, in zakken</td><td>432</td></tr>
            <tr><td>Haver, in bulk</td><td>512</td></tr>
            <tr><td>Olie, in vaten</td><td>576</td></tr>
            <tr><td>Olie, in bulk</td><td>896</td></tr>
            <tr><td>Olie, in vaten</td><td>721</td></tr>
            <tr><td>Papier, print</td><td>640</td></tr>
            <tr><td>Papier, schrijven</td><td>960</td></tr>
            <tr><td>Benzine</td><td>672</td></tr>
            <tr><td>Bitumen</td><td>1119</td></tr>
            <tr><td>Pleister</td><td>1538</td></tr>
            <tr><td>Gips</td><td>1278</td></tr>
            <tr><td>Pleister, in vaten</td><td>848</td></tr>
            <tr><td>Potas</td><td>3276</td></tr>
            <tr><td>Aardappelen, gestapeld</td><td>721</td></tr>
            <tr><td>Loodmenie, droog</td><td>2112</td></tr>
            <tr><td>Gewapend beton 2%</td><td>2401</td></tr>
            <tr><td>Gewapend beton 3%</td><td>2503</td></tr>
            <tr><td>Hars, in vaten</td><td>769</td></tr>
            <tr><td>Rubber</td><td>960</td></tr>
            <tr><td>Salpeter</td><td>1072</td></tr>
            <tr><td>Zand, droog</td><td>1598</td></tr>
            <tr><td>Zand, nat</td><td>1998</td></tr>
            <tr><td>Zandsteen</td><td>2403</td></tr>
            <tr><td>Schroeven, spijkers, in verpakking</td><td>1600</td></tr>
            <tr><td>Leisteen</td><td>2877</td></tr>
            <tr><td>Sneeuw, vers gevallen</td><td>96</td></tr>
            <tr><td>Sneeuw, nat, compact</td><td>320</td></tr>
            <tr><td>Natriumcarbonaat, in vaten</td><td>992</td></tr>
            <tr><td>Natriumhydroxide, in tonnen</td><td>1409</td></tr>
            <tr><td>Zetmeel, in vaten</td><td>401</td></tr>
            <tr><td>Staal, gegoten</td><td>8002</td></tr>
            <tr><td>Staal, gewalst</td><td>8002</td></tr>
            <tr><td>Stro, in balen, samengeperst</td><td>304</td></tr>
            <tr><td>Zwavelzuur</td><td>960</td></tr>
            <tr><td>Steenkool, los</td><td>896</td></tr>
            <tr><td>Terracotta</td><td>1794</td></tr>
            <tr><td>Hout, pijnboom, spar</td><td>481</td></tr>
            <tr><td>Hout, (Amerikaans) grenehout</td><td>673</td></tr>
            <tr><td>Hout, mahonie</td><td>561</td></tr>
            <tr><td>Hout, teak, eiken</td><td>721</td></tr>
            <tr><td>Tin, gegoten</td><td>7282</td></tr>
            <tr><td>Tin, gewalst</td><td>7392</td></tr>
            <tr><td>Tin, plaat, in dozen</td><td>4450</td></tr>
            <tr><td>Water, zoet</td><td>1000</td></tr>
            <tr><td>Water, zee</td><td>1024</td></tr>
            <tr><td>Tarwe, in zakken</td><td>624</td></tr>
            <tr><td>Tarwe, in bulk</td><td>721</td></tr>
            <tr><td>Loodwit, pasta</td><td>2785</td></tr>
            <tr><td>Loodwit, droog</td><td>138</td></tr>
            <tr><td>Draad, in spoelen</td><td>1185</td></tr>
            <tr><td>Zink</td><td>6993</td></tr>
        </tbody>
    </table>
</div>

<br>

Let op: de bovengenomende waarden zijn volumieke massa's, $[kg/m^3]$, deze moet je dus nog omrekenen naar $[kN/m^3]!$

*Bron: NEN-EN 1991 Bijlage A*

## Belasting per oppervlakte-eenheid voor samengestelde constructies

<div style="max-height: 400px; overflow-y: auto;">
    <table style="width: 100%; border-collapse: collapse;">
        <thead style="position: sticky; top: 0; background-color: #f2f2f2;">
            <tr>
                <th>Materiaal</th>
                <th>ρ [kN/m²]</th>
            </tr>
        </thead>
        <tbody>
            <tr><td colspan="2"><strong>Gevel- en dakmaterialen</strong></td></tr>
            <tr><td>Stalen gevelplaten</td><td>0,05 - 0,13</td></tr>
            <tr><td>Isolatiemateriaal gevel</td><td>0,015 - 0,05</td></tr>
            <tr><td>Houten vloer + balken</td><td>0,3</td></tr>
            <tr><td>Stalen dakplaten</td><td>0,05 - 0,18</td></tr>
            <tr><td>Stalen dakplaten (dikte 0,75 mm)</td><td>0,11</td></tr>
            <tr><td>Isolatie en dakbedekking</td><td>0,10 - 0,20</td></tr>
            <tr><td>Bitumenlagen</td><td></td></tr>
            <tr><td>Glasvlies 2 lagen</td><td>0,07</td></tr>
            <tr><td>Glasvlies 3 lagen</td><td>0,1</td></tr>
            <tr><td>Dakspanen</td><td>0,07</td></tr>
            <tr><td>Kunststoffolie</td><td>0,02</td></tr>
            <tr><td>Golfplaten vezel versterkt cement</td><td></td></tr>
            <tr><td>Plaat alleen</td><td>0,15</td></tr>
            <tr><td>Met bevestiging en gordingen</td><td>0,25</td></tr>
            <tr><td>Golfplaten kunststof</td><td>0,02</td></tr>
            <tr><td>Golfplaten gegalvaniseerd</td><td></td></tr>
            <tr><td>Met bevestiging en gordingen</td><td>0,15</td></tr>
            <tr><td>Pannendak, dakbeschot, gordingen</td><td>0,65</td></tr>
            <tr><td>Plat dak, balken, beschot geen grind</td><td>0,36</td></tr>
        </tbody>
    </table>
</div>

<br>

*Bron: NEN-EN 1991 Bijlage A*
