# Site du mariage laïque, Lucie & Marion

Deux pages statiques, sans rien à installer :

- `index.html` : la page d'accueil (sceau, programme, voyage, banquet, cagnotte, couleurs)
- `hebergements.html` : la page "Où dormir"

## Mettre le site en ligne avec GitHub Pages

1. Sur github.com, crée un dépôt (par exemple `mariage-laique`). Un compte gratuit demande un dépôt public.
2. Clique sur "Add file" puis "Upload files" et dépose `index.html`, `hebergements.html` et `.nojekyll`.
3. Valide avec "Commit changes".
4. Dans "Settings", puis "Pages", choisis "Deploy from a branch", la branche `main` et le dossier `/ (root)`, puis "Save".
5. Après une à deux minutes, le site est disponible sur `https://TON-PSEUDO.github.io/mariage-laique/`.

Astuce : si le site du mariage civil est déjà dans un dépôt, tu peux mettre ces fichiers dans un sous-dossier `laique/`. Les liens entre les pages sont relatifs, donc tout fonctionne.

## À personnaliser avant de partager

Dans `index.html`, cherche les crochets `[...]` et les liens `#` :

- `[date à confirmer]`, `[lieu]`, `[heure]` (5 horaires du programme), `[date limite]`
- `[Infos train et voiture à compléter.]` et `[contact]`
- Bouton "Répondre au sondage" : remplace `href="#"` par le lien du formulaire
- Bouton "Ouvrir la cagnotte" : remplace `href="#"` par le lien de la cagnotte

Pour modifier un fichier sur GitHub : ouvre-le, clique sur le crayon, modifie, puis "Commit changes". Le site se met à jour en une minute environ.

Attention : un dépôt public est lisible par tout le monde. Évite d'y mettre des informations privées (numéros de téléphone, adresses personnelles).
