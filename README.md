# PrédiQual, site vitrine

Site statique publié par GitHub Pages : https://marius-blanchet2004.github.io/PrediQual/

- `index.html` : la couverture (vidéo, accroche, bouton « Démonstration avec des données d'usine »).
- `donnees.html` : « Bravo », puis un exemple de 20 lots avec leur prix de vente (moyenne 146 €).
- `analyse.html` : l'étude simulée (environ 13 s), qui ouvre ensuite `demo.html?prix=146`.
- `site.css` : les styles communs à ces trois pages.
- `img/usine/fond.mp4` : vidéo de la couverture (Mixkit, licence libre).
- `demo.html` : la page de résultats (les 3 graphiques 3D puis les plages de réglages), copie telle quelle de `ml/nuage_3d.html` du dépôt privé du MVP. Le design du site et le lien de retour sont dans le gabarit de `nuage.py`.
- `img/apercu_cube.png` : capture du cube, affichée sur l'accueil.
- `img/marius.jpg`, `img/matthieu.jpg` : portraits des fondateurs, dans le bandeau de contact de la démo.
- `img/usine/` : photos d'usine (licence Unsplash, photographes crédités en pied de page).

Ce dépôt est public. Il ne contient que le site : ni code du moteur, ni donnée client. La démo tourne sur le jeu public AI4I 2020 (UCI, licence CC BY 4.0).

## Mettre la démo à jour

1. Dans le dépôt du MVP : `cd ml` puis `py nuage.py` (environ une minute), qui écrit `nuage_3d.html`.
2. Recopier ce fichier ici sous le nom `demo.html`, puis commit et push : GitHub Pages republie tout seul en une ou deux minutes.
