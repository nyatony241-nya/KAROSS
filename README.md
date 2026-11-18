# KAROSS — pièces de carrosserie Chine → Gabon

Site vitrine statique : catalogue de 2 685 pièces, demande de prix envoyée sur WhatsApp.

## Contenu
- `index.html` : le site (une seule page, mobile d'abord).
- `catalogue.json` : toutes les pièces. Une ligne par pièce :
  `[réf, code fournisseur, catégorie, marque, modèle, année début, année fin, titre, description, côté, options, n° photo]`.
- `s/` : photos des pièces, regroupées par planches de 12.
- `vercel.json` : réglages d'hébergement (cache des photos).

## Modifier le numéro WhatsApp
Dans `index.html`, bloc `CONFIG` en haut du script : `whatsapp` (format international sans +) et `telephoneAffiche`.

## Mise en ligne
Le dépôt GitHub est relié à Vercel : chaque modification envoyée sur la branche `main` est publiée automatiquement.
