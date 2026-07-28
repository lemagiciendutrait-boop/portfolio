# Portfolio - Digital Sénégal

Site portfolio professionnel pour un développeur web sénégalais spécialisé dans les bots WhatsApp, tunnels de vente et sites e-commerce.

## Installation

1. Ouvrez le fichier `index.html` dans votre navigateur
2. Ou utilisez un serveur local :

```bash
# Avec Python
python -m http.server 8000

# Avec Node.js
npx serve .

# Avec PHP
php -S localhost:8000
```

## Personnalisation

### Changer les couleurs
Modifiez les couleurs dans `tailwind.config` dans `index.html` :
```javascript
colors: {
    primary: '#667eea',    // Bleu principal
    secondary: '#f5576c',  // Rose/coral
    whatsapp: '#25D366',   // Vert WhatsApp
}
```

### Modifier le numéro WhatsApp
Remplacez toutes les occurrences de `221XXXXXXXXX` par votre vrai numéro :
- Dans le bouton WhatsApp flottant
- Dans le lien "Discuter sur WhatsApp" du hero
- Dans le formulaire de contact
- Dans le footer

### Modifier les tarifs
Les prix sont directement dans `index.html`. Cherchez les textes contenant "FCFA" et modifiez-les.

### Ajouter de vraies photos
Remplacez les icônes Font Awesome par vos images réelles dans la section Portfolio et À propos.

## Déploiement

### Netlify (gratuit)
1. Créez un compte sur [netlify.com](https://netlify.com)
2. Glissez-déposez le dossier `portfolio` sur Netlify
3. Votre site est en ligne !

### Render (gratuit)
1. Créez un compte sur [render.com](https://render.com)
2. Créez un nouveau "Static Site"
3. Connectez votre dépôt GitHub
4. Build command : (laisser vide)
5. Publish directory : `.`

### GitHub Pages
1. Poussez le code sur GitHub
2. Allez dans Settings > Pages
3. Sélectionnez la branche `main`
4. Votre site sera à l'adresse `https://votre-user.github.io/nom-repo/`

## Structure des fichiers

```
portfolio/
├── index.html          # Page principale
├── css/
│   └── style.css       # Styles personnalisés
├── js/
│   └── main.js         # Animations et interactions
├── images/             # Vos images
└── README.md           # Ce fichier
```

## Technologies utilisées

- HTML5
- CSS3
- JavaScript vanilla
- Tailwind CSS (CDN)
- Font Awesome (CDN)
- Google Fonts (Poppins + Inter)
- AOS - Animate On Scroll (CDN)

## Checklist avant déploiement

- [ ] Remplacer `221XXXXXXXXX` par votre vrai numéro WhatsApp
- [ ] Remplacer `ton@email.com` par votre vrai email
- [ ] Ajouter vos vraies photos/screenshots
- [ ] Tester le formulaire WhatsApp
- [ ] Tester sur mobile
- [ ] Vérifier les liens vers démos
- [ ] Ajouter vos vrais témoignages clients
- [ ] Modifier le nom "Digital Sénégal" si nécessaire
- [ ] Vérifier les tarifs affichés