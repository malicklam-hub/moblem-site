# Site public de Moblem

Ce dépôt ne contient qu'une page : la politique de confidentialité de
l'application Moblem. Les deux magasins en exigent une, à une adresse web
publique et stable.

Il est **séparé du dépôt de l'application**, qui est privé, parce que GitHub
Pages ne publie pas de dépôt privé sans abonnement payant.

## Publier la page

1. Créer sur GitHub un dépôt **public** nommé `moblem-site`.
2. Y pousser ce dossier.
3. Dans le dépôt, aller dans **Settings**, puis **Pages**, et choisir la
   branche `main` avec le dossier `/ (root)`.
4. Au bout d'une minute, la page est en ligne à l'adresse :
   `https://<utilisateur>.github.io/moblem-site/`

C'est cette adresse qu'il faut donner à App Store Connect et à Google Play.

## Avant de publier

Deux mentions restent à compléter dans `index.html`, marquées
`[À COMPLÉTER]` : l'adresse e-mail de support et le nom de l'éditeur. Les deux
seront visibles publiquement, d'où le choix de ne pas les remplir à votre
place.

## Tenir la page à jour

Le texte de référence vit dans le dépôt de l'application, au fichier
`POLITIQUE_CONFIDENTIALITE.md`. Si l'application se met un jour à collecter
quoi que ce soit, il faut changer les deux.
