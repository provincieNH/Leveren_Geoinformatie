# Algemeen

In dit hoofdstuk worden de algemene objecten beschreven: enerzijds objecten die niet over een specifiek areaal gaan, maar 
areaal oversteigende informatie vastleggen. Anderzijds objecten die relaties hebben net objecten in verschillende thema's.

Bovendien bevat dit hoofstuk de regels voor een aantal berekende velden: velden die niet ingevuld worden, maar berekend 
door een script op basis van een formule en waardes uit andere velden.

### Relatiediagrammen

In elk hoofdstuk worden de relaties binnen en buiten het thema geïllustreerd met een relatiediagram. Hierbij hoort onderstaande legenda:

![Legenda](D:\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.2d3\Objectbladen\01_Algemeen\legenda_relaties.png)

Het diagram voor de algemene objecten is:

![Algemeen_relaties](D:\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.2d3\Objectbladen\01_Algemeen\algemeen_relaties.png)



### Berekende velden

De volgende velden in Areaaldata worden berekend:

|__ATRRIBUUT__                       |__FORMULE__          	       | __HOE VAAK PER ETMAAL__ |
|---                             |---                      |---         |
|*.LENGTE                        | *.SHAPE.LEN                        | 1           |
|*.OMTREK                        | *.SHAPE.LEN                        | 1           |
|*.OPPERVLAKTE                   | *.SHAPE.AREA                       | 1           |
|KastVri_p.TOTAALSCORE           | (IMPACT_VEILIGHEID+IMPACT_VERTRAGING_MIN+OVERSTEEKBAARHEID+HINDER_LANGZAAM_VERKEER)+((PRIO_NETWERKVISIE+VM_KWALITEITSNIVEAU)/2)| 1           |
|KastVri_p.TOTAALPRIO            | ALS(14,5<TOTAALSCORE;1;ALS(11<TOTAALSCORE;2;ALS(0<TOTAALSCORE;3;4)))| 1           |
|oevervak_v.RISICO_TOTAAL        | RISICO_AFSTAND_WEG + RISICO_STEILTE_TALUD + RISICO_WATERKERING     | 1           |
|