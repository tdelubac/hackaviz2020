# Aggrégation

Données aggrégées par mois et par département.

# Critères

- Pluvieux / Ensoleillé (météo)
- Chaud / Froid (temp)
- Touristique / Authentique (volume / pop)
- Animé / calme (evenmt)
- Ville / Nature (pop / km2)
- Facilité d'hebergement (volume / nb place)
- Tourisme international / national (Nb Internationaux / Nb total touristes)


# To do list

- Page 3:
  - Add 42
  - (Remove volume_sur_hbgt)

- Page 4:
  - Add dpt title when selected - O
  - Change plot color - T
  - Babel fish - O
  - Fix click outside of map - OT
  - Fix 1200 jump - O
  - When resize put buttons on one / two line - O

- Page 5 footer:
  - Dans le cadre du Hackaton
  - Bref description des données
  - ©
  - (Thank you for the fish)


- Clean template


# plotXY

- Par défaut: Plot XY Volume

- geojson en entrée
  - fonction pour récupérer X axis (mois)
  - fonction pour récupérer n'importe quelle feature pour chaque département

- updatePlot pour updater avec n'importe quelle autre feature
- highlightCurve pour mettre en avant n'importe quelle courbe
