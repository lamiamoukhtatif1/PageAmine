# Amin Ordinaires — Code source complet

Landing page en darija, responsive et en lecture de droite à gauche.

## Fichiers
- index.html : totalité du HTML, des styles CSS et du JavaScript.
- README.md : instructions.

## Ouvrir le site
Double-cliquez sur index.html dans un navigateur. Aucune installation ou compilation nécessaire.
Pour utiliser un serveur local : python3 -m http.server 8000, puis ouvrez http://localhost:8000.

## Mettre en ligne
Déposez index.html à la racine de votre hébergement statique (Netlify, GitHub Pages ou hébergement classique).

## Personnaliser
Modifiez directement les textes et les couleurs dans index.html. Les couleurs principales se trouvent dans :root. Le contenu est une proposition : les détails de l’activité sont à compléter.

## Formulaire
Le formulaire est une démonstration côté navigateur. Il ne transmet ni ne conserve de données. Le script affiche explicitement ce statut après validation. Pour recevoir des messages, connectez un service de formulaire ou un backend et adaptez le gestionnaire submit. N’intégrez jamais de mot de passe SMTP ou de clé secrète dans le JavaScript public.

## Police
Noto Sans Arabic est chargée depuis Google Fonts et nécessite Internet. Sans connexion, le navigateur utilise Tahoma ou une police sans serif. Aucun autre service ou bibliothèque n’est nécessaire.
