# Portfolio Clovis Langlois — Reproduction de l'ancien site Hostinger

Ce projet reproduit en HTML/CSS/JavaScript les quatre pages publiques d'origine, en utilisant les données de mise en page et les textes contenus dans les fichiers HTML exportés depuis Hostinger AI Builder le 8 novembre 2026.

## Pages
- `index.html` (Accueil)
- `situations-professionnelles-portfolio.html`
- `projet-portfolio.html`
- `contact-portfolio.html`

## Déploiement sur GitHub Pages
Créer un dépôt public, importer les fichiers HTML à la racine et activer **Settings → Pages → Deploy from a branch → main / root**. Garder le domaine actuel chez Hostinger le temps des tests.

## Limitations importantes
- **Images et PDF** : des URLs publiques `assets.zyrosite.com` sont temporairement utilisées pour reprendre les images d'origine. Pour un site autonome, téléchargez ces fichiers depuis la copie HTTrack puis placez-les dans un dossier `assets/` et mettez à jour les URLs.
- **Police** : Montserrat est chargée via Google Fonts, fallback Arial.
- **Formulaire** : l'ancien envoi via Hostinger ne peut pas être migré tel quel. Le bouton prépare un email via `mailto:` au lieu de transmettre automatiquement le message.
- **Vidéo d'arrière-plan** : la page Situations professionnelles utilise temporairement une vidéo Pexels distante présente dans la configuration originale.
- **Animations** : les effets `slide` sont réinterprétés en CSS.
- **Original** : les éléments sont positionnés selon les coordonnées de la configuration Hostinger récupérée; il peut subsister des écarts de rendu selon la taille d'écran et la disponibilité des ressources externes.
