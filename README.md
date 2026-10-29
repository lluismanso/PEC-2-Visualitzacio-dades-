# PEC 2: Visualització de dades
**Autor**: Lluís Manso Matachana

**Assignatura**: Visualització de dades — Màster en Data Science (UOC)

**Visualitzacions**: Cartogram, Linear dendrogram, UpSet: Visualizing  Intersecting Sets

# Visualitzacions publicades
Les tres visualitzacions elaborades per a aquesta pràctica es poden consultar en cadascun dels apartats de visualització del següent enllaç en: https://lluismanso.github.io/PEC-2-Visualitzacio-dades-/

# Descripció
En aquesta pràctica s’ha creat tres visualitzacions, usant les següents tècniques assignades: Cartograms, Linear dendrogram i UpSet: Visualizing. 

Per elaborar-les, s’han seleccionat conjunts de dades obertes adequats a les característiques de cada tècnica.

- **Cartogram**, s´ha treballat amb dades obertes d’Our World in Data sobre les emissions totals de CO2 per país l’any 2024, amb l’objectiu de representar visualment les diferències entre els principals emissors mundials.

- **Linear dendogram**, s’han utilitzat dades obertes de Kaggle sobre els partits de la temporada 2025-2026 de la UEFA Champions League, amb l’objectiu d’identificar similituds entre els partits a partir de les seves estadístiques numèriques.

- **Upset:visualizing**, s’han utilitzat dades d’Our World in Data sobre el consum d’energia per capita segons la font energètica als països de la Unió Europea l’any 2025, amb l’objectiu d’identificar patrons i interseccions entre les diferents fonts d’energia

# Contingut del repositori

| Fitxer | Descripció |
|---|---|
| PAC2_Visualitzacio_dades_Lluis_Manso.rmd | Codi font R Markdown amb tot el procés de creacions de les visualitzacions | 
| PAC2_Visualitzacio_dades_Lluis_Manso.html | Informe exportat amb els codi i visualitzacions | 
| annual_co2_emissions.csv | Dataset amb les emissions totals anuals de CO2 per país del any 2024 | 
| champions_league_matches.csv | Dataset dels partits UEFA Champions League de la temporada 2025 2026 | 
| per_capita_energy_source.csv | Dataset del consum energètic per capita de la UE 27 | 

# Requisits 
El codi R requereix els paquets següents:

install.packages(c("sf", "ggplot2", "dplyr", "cartogram", "rnaturalearth", "tidyr", "stringr", "dendextend", "ComplexUpset"))

# Reproducció 
1) Descarregar o clonar aquest repositori.

2) Obrir el fitxer PAC2_Visualitzacio_dades_Lluis_Manso.rmd amb RStudio.

3) Comprovar que els fitxers CSV es troben a la ubicació esperada pel codi.

4) Instal·lar els requisits

5) Executar el document R Markdown per reproduir les visualitzacions
   
# Font de dades
1. **Cartograma**: (https://ourworldindata.org/co2-emissions)
2. **Linear Dendrogram**:(https://www.kaggle.com/datasets/johntocci/champions-league-matches-2025-2026)
3. **Upset:visualizing**: (https://ourworldindata.org/energy-mix)
