# RAZE ESPORT — Portail interactif

Version de démonstration du portail RAZE ESPORT, avec le visuel d'accueil validé et des espaces interactifs pour RAZE CHAMPIONSHIP, RAZE CARDS, PRIVATE MATCH, Avis & Idées et les menus communautaires.

## Publication sur GitHub Pages

1. Créer un **nouveau dépôt public** sur GitHub, par exemple `raze-esport-hub` (ne pas remplacer les dépôts des sites existants).
2. Ajouter **`index.html`** à la racine du dépôt.
3. Créer le dossier **`assets`** et y ajouter **`accueil-raze-esport.png`**. Conserver exactement cette arborescence :

   ```text
   raze-esport-hub/
   ├── index.html
   ├── assets/
   │   └── accueil-raze-esport.png
   └── README.md
   ```

4. Dans **Settings → Pages**, sélectionner **Deploy from a branch**, puis la branche **main** et le dossier **/(root)** ; enregistrer.
5. Attendre la publication : l'adresse s'affiche dans la section **Pages**. Elle ressemble généralement à `https://NOM-UTILISATEUR.github.io/raze-esport-hub/`.

## Limites importantes

- Les trois espaces sont des **démonstrations**, pas des intégrations des sites réels.
- Les données (boosters, idées, votes, pseudo, etc.) sont **locales au navigateur** via `localStorage` : elles ne sont **pas partagées** entre les visiteurs.
- Aucune connexion réelle à Discord, Supabase ou aux sites existants n'est configurée.
- Le mode administrateur est une **simulation** et ne doit pas être considéré comme un contrôle d'accès sécurisé.
- GitHub Pages héberge des fichiers statiques. Pour synchroniser les comptes, les avis et les matchs, il faudra un backend et une authentification appropriée.

## Vérifier en local

Ouvrir `index.html` dans un navigateur avec le dossier `assets` présent à côté.
