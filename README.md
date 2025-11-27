# Portfolio - Hamidou Souley Imrane

Portfolio professionnel de développeur web et mobile full stack.

## 🚀 Technologies utilisées

- **HTML5** - Structure sémantique
- **Tailwind CSS** - Framework CSS via CDN
- **JavaScript Vanilla** - Interactivité et animations
- **Responsive Design** - Compatible mobile, tablette et desktop
- **Dark Mode** - Mode sombre/clair avec sauvegarde des préférences

## 📁 Structure du projet

```
portfolio/
├── index.html          # Page principale
├── images/             # Dossier pour les images
│   ├── profile.jpg     # Photo de profil
│   ├── project-1.jpg  # Image projet 1
│   ├── project-2.jpg  # Image projet 2
│   └── ...
└── README.md          # Ce fichier
```

## 🖼️ Ajout des images

1. **Photo de profil** : Placez votre photo dans `images/profile.jpg` (ou `.png`)
2. **Images des projets** : Nommez-les `project-1.jpg`, `project-2.jpg`, etc.

Voir le fichier `images/README.md` pour plus de détails.

## 🌐 Déploiement sur GitHub Pages

### Étapes pour publier :

1. **Créer un nouveau repository sur GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Portfolio"
   git branch -M main
   git remote add origin https://github.com/VOTRE-USERNAME/VOTRE-REPO.git
   git push -u origin main
   ```

2. **Activer GitHub Pages**
   - Allez dans les **Settings** de votre repository
   - Cliquez sur **Pages** dans le menu de gauche
   - Sous **Source**, sélectionnez la branche `main` et le dossier `/ (root)`
   - Cliquez sur **Save**
   - Votre site sera disponible à : `https://VOTRE-USERNAME.github.io/VOTRE-REPO`

### Alternative : Repository nommé `username.github.io`

Si vous créez un repository nommé exactement `VOTRE-USERNAME.github.io`, votre site sera directement accessible à :
- `https://VOTRE-USERNAME.github.io`

## ✨ Fonctionnalités

- ✅ Design moderne et responsive
- ✅ Mode sombre/clair avec sauvegarde des préférences
- ✅ Animations fluides au scroll
- ✅ Navigation smooth scroll
- ✅ Formulaire de contact (mailto)
- ✅ Section projets avec images
- ✅ Timeline d'expérience professionnelle
- ✅ Section compétences techniques
- ✅ Liens vers réseaux sociaux

## 🎨 Personnalisation

### Couleurs principales
Les couleurs peuvent être modifiées dans la section `<script>` de Tailwind :
```javascript
colors: {
    primary: '#2563EB',  // Bleu principal
    dark: '#0F172A',     // Fond mode sombre
}
```

### Contenu
Modifiez directement le contenu dans `index.html` :
- Sections À propos
- Projets
- Expériences
- Coordonnées de contact

## 📱 Compatibilité

- ✅ Chrome/Edge (dernières versions)
- ✅ Firefox (dernières versions)
- ✅ Safari (dernières versions)
- ✅ Mobile (iOS Safari, Chrome Mobile)

## 📝 Notes

- Le portfolio est entièrement frontend, aucune dépendance backend requise
- Les images utilisent un fallback automatique (emoji) si elles ne sont pas trouvées
- Le formulaire de contact utilise `mailto:` pour ouvrir le client email

## 📧 Contact

**Hamidou Souley Imrane**
- Email : hamidousouleyimrane@gmail.com
- Téléphone : +227 86 42 09 43 / +227 85 14 74 13
- Localisation : Niamey, Niger

---

Développé avec ❤️ à Niamey, Niger

