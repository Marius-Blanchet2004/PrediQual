# PrédiQual, site vitrine

Site statique publié par GitHub Pages : https://marius-blanchet2004.github.io/PrediQual/

- `index.html` : la couverture (vidéo, accroche, bouton « Démonstration avec des données d'usine »).
- `donnees.html` : « Bravo », puis un exemple de 20 lots avec leur prix de vente (moyenne 146 €).
- `analyse.html` : l'étude simulée (environ 13 s), qui ouvre ensuite `demo.html`. Le prix moyen d'un lot (146 €) est écrit en dur dans `demo.html`.
- `site.css` : les styles communs à ces trois pages.
- `img/usine/flacons.mp4` : vidéo de la couverture, flacons sur une ligne de conditionnement (Mixkit 33003, licence libre) ; `img/usine/flacons.jpg` est son image d'attente.
- `demo.html` : la page de résultats (les plages de réglages, le gain estimé, puis « En savoir plus » avec les 2 graphiques 3D et la méthode). Générée au départ par `ml/nuage.py` du dépôt privé du MVP, puis retouchée à la main (ordre des sections, textes) : ce n'est plus une copie telle quelle de `nuage_3d.html`.
- `img/apercu_cube.png` : capture du cube, affichée sur l'accueil.
- `img/marius.jpg`, `img/matthieu.jpg` : portraits des fondateurs, dans le bandeau de contact de la démo.
- `img/usine/` : photos d'usine (licence Unsplash, photographes crédités en pied de page).

Ce dépôt est public. Il ne contient que le site : ni code du moteur, ni donnée client. La démo tourne sur le jeu public AI4I 2020 (UCI, licence CC BY 4.0).

## Mettre la démo à jour

1. Dans le dépôt du MVP : `cd ml` puis `py nuage.py` (environ une minute), qui écrit `nuage_3d.html`.
2. Recopier ce fichier ici sous le nom `demo.html`, puis commit et push : GitHub Pages republie tout seul en une ou deux minutes.

Attention : recopier `nuage_3d.html` écrase les retouches faites à la main dans `demo.html`. Tant que `nuage.py` n'est pas refait, modifier `demo.html` directement.
