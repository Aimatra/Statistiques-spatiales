# Statistiques spatiales — manipulation de données géographiques

TP de statistique spatiale, ENSAI. Manipulation de données géographiques avec `sf` : import du découpage communal de la France métropolitaine, filtrage sur la Bretagne, calcul de surfaces et agrégation par département.

## Contenu

- `upload_fond.R` — télécharge le fond de carte des communes de France métropolitaine (format `.gpkg`)
- `code.R` — lecture du fond de carte avec `sf`, filtrage des communes bretonnes (22, 56, 35, 29), calcul de surface (`st_area`), agrégation par département (`group_by` + `st_union`) et visualisation
- `TP3/` — travaux pratiques complémentaires

## Outils

`R` · `sf` · `dplyr` · `units`

## Reproduire

```r
source("upload_fond.R")  # télécharge le fond de carte dans fonds/
source("code.R")         # analyse et cartes
```
