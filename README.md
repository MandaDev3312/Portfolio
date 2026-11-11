# Portfolio — Miarimanda Rakotomandimby

Portfolio professionnel en français, réalisé en HTML, CSS et JavaScript. Aucun framework, service externe ou étape de compilation n’est nécessaire. Tous les chemins sont relatifs pour fonctionner sur GitHub Pages, y compris dans un dépôt de projet.

## Consulter en local

Ouvrir `index.html` dans un navigateur. Le site fonctionne directement depuis le disque. Pour utiliser un serveur local, si Python est installé : `python -m http.server 8000`, puis ouvrir `http://localhost:8000`.

## Déployer sur GitHub Pages

1. Créer un dépôt GitHub, par exemple `portfolio`.
2. Y ajouter `index.html`, `styles.css`, `script.js`, `.nojekyll` et le dossier `assets` complet. Le dossier `assets` contient notamment le CV téléchargeable et la photo.
3. Dans le dépôt, ouvrir **Settings → Pages**.
4. Sélectionner **Deploy from a branch**, puis la branche **main** et le dossier **/ (root)**. Enregistrer.
5. Une fois le déploiement terminé, GitHub affiche l’adresse du site dans cette même page. Pour le compte indiqué dans le CV et un dépôt `portfolio`, l’adresse sera `https://mandadev123.github.io/portfolio/`.

Pour publier à la racine du compte, nommer le dépôt `MandaDev123.github.io`.

## Personnalisation

- Contenu, coordonnées, liens et projets : `index.html`.
- Couleurs, espacements et affichage mobile : `styles.css` (variables dans `:root`).
- Menu mobile et navigation active : `script.js`.
- Photo : `assets/portrait.jpg`.
- CV à télécharger : `assets/CV-Miarimanda-Rakotomandimby.pdf`.

Le contenu est fondé sur le CV « CV — Miarimanda RAKOTOMANDIMBY.pdf ». `CVmanda.pdf` ne comporte pas de texte extractible avec l’outil utilisé ; aucune information supplémentaire de ce document n’a été supposée. La photo provient du CV principal. Les illustrations des projets sont des compositions CSS conceptuelles, et non des captures des applications. Les projets ne renvoient pas vers des dépôts individuels, leurs adresses n’étant pas fournies. Le contact utilise les applications email et téléphone du visiteur, sans formulaire serveur.

## Vérification avant publication

Ouvrir le site sur ordinateur et mobile, vérifier le téléchargement du CV ainsi que les coordonnées. Le site propose un menu accessible au clavier, des liens de navigation, des détails de projets et un mode respectant la préférence de réduction des animations.
