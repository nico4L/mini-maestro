# Mini Maestro

Appli web pour apprendre le piano aux enfants : 5 mondes, 31 leçons progressives (notes Do → Do aigu, chansons, tubes originaux, accords), accompagnement batterie-basse-accords en 7 styles, Studio pour ajouter ses propres chansons, partition qui défile, clavier à l'écran, étoiles, XP, série de jours et trophées.

- `index.html` : version autonome, à ouvrir dans Chrome, Edge ou Safari. Elle écoute un vrai piano au **micro** et accepte un clavier **MIDI/USB**.
- `app.html` : même contenu sans l'en-tête HTML (source de l'aperçu Artifact).

Pour héberger la version autonome : GitHub Pages ou n'importe quel hébergement statique en HTTPS. Le micro exige HTTPS ou `localhost`.
Exemple en local : `python3 -m http.server` dans ce dossier, puis ouvrir http://localhost:8000.
