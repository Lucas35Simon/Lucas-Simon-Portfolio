# 🎨 Portfolio Lucas Simon

Bienvenue dans mon portfolio personnel ! Ce site web présente mes compétences, mes projets et mon expérience professionnelle.

## 📋 Table des matières

- [À Propos](#à-propos)
- [Fonctionnalités](#fonctionnalités)
- [Structure du Projet](#structure-du-projet)
- [Déploiement](#déploiement)
- [Personnalisation](#personnalisation)
- [Contacter](#contacter)

## 🌟 À Propos

Ce portfolio a été créé pour showcaser mon travail en tant que développeur web. Il présente :

- **Accueil** : Une introduction profesionelle avec call-to-action
- **À Propos** : Informations personnelles et contexte professionnel
- **Compétences** : Les technologies et compétences maîtrisées
- **Projets** : Portfolio de projets réalisés
- **Expérience** : Timeline de l'expérience professionnelle
- **Formation** : Diplômes et certifications
- **Contact** : Formulaire de contact

## ✨ Fonctionnalités

✅ **Design Responsive** - Compatible mobile, tablette et desktop
✅ **Navigation Fluide** - Scroll smooth et menu mobile intégré
✅ **Animations Modernes** - Transitions et effets visuels élégants
✅ **Performance Optimisée** - Chargement rapide et léger
✅ **SEO Friendly** - Structure optimisée pour les moteurs de recherche
✅ **Formulaire de Contact** - Collecte les messages des visiteurs
✅ **Design Moderne** - Palette de couleurs attrayante et mise en page professionnelle

## 📁 Structure du Projet

```
Lucas-Simon-Portfolio/
├── index.html          # Page principale avec toutes les sections
├── style.css           # Feuille de styles (responsive)
├── script.js           # Logique JavaScript (animations, interactivité)
└── README.md           # Ce fichier
```

## 🚀 Déploiement avec GitHub Pages

Ce portfolio est hébergé sur **GitHub Pages**. Pour le déployer :

1. **Accédez aux paramètres du repository**
   - Allez dans `Settings` → `Pages`

2. **Configurez GitHub Pages**
   - Branch: `main` (ou `master`)
   - Folder: `/ (root)`
   - Cliquez sur `Save`

3. **Accédez à votre site**
   - Votre portfolio sera disponible à : `https://lucas35simon.github.io/Lucas-Simon-Portfolio/`

## 🎨 Personnalisation

### Modifier les Informations Personnelles

Ouvrez `index.html` et cherchez les sections suivantes :

```html
<!-- À modifier dans la section À Propos -->
<p>Bonjour ! Je m'appelle <strong>Lucas Simon</strong>...</p>

<!-- À modifier dans les informations de contact -->
<p><strong>Email:</strong> lucas@example.com</p>
<p><strong>Téléphone:</strong> +33 6 XX XX XX XX</p>
```

### Ajouter des Projets

Dupliquez un `.project-card` dans la section `projets` :

```html
<div class="project-card">
    <div class="project-image">
        <div class="placeholder">Votre Projet</div>
    </div>
    <div class="project-content">
        <h3>Titre de votre Projet</h3>
        <p>Description du projet...</p>
        <div class="project-tags">
            <span class="tag">Technologie 1</span>
            <span class="tag">Technologie 2</span>
        </div>
        <div class="project-links">
            <a href="#" class="btn-small">Voir le projet</a>
            <a href="#" class="btn-small">Code</a>
        </div>
    </div>
</div>
```

### Modifier les Couleurs

Ouvrez `style.css` et modifiez les variables CSS :

```css
:root {
    --primary-color: #6366f1;        /* Couleur primaire */
    --secondary-color: #ec4899;      /* Couleur secondaire */
    --dark-bg: #0f172a;              /* Fond sombre */
    --light-bg: #f8fafc;             /* Fond clair */
    --text-dark: #1e293b;            /* Texte foncé */
    --text-light: #64748b;           /* Texte clair */
}
```

### Ajouter une Image de Profil

Remplacez la section `.avatar` par une image :

```html
<img src="votre-image.jpg" alt="Photo de profil" class="avatar">
```

Puis modifiez le CSS :

```css
.avatar {
    width: 250px;
    height: 250px;
    border-radius: 50%;
    object-fit: cover;
}
```

## 💡 Suggestions d'Améliorations

- [ ] Ajouter un mode sombre
- [ ] Intégrer un blog
- [ ] Ajouter des statistiques (nombre de projets, etc.)
- [ ] Créer une page dédiée par projet
- [ ] Ajouter un système de filtrage des projets
- [ ] Intégrer les réseaux sociaux
- [ ] Ajouter un CV téléchargeable

## 📞 Contacter

Pour toute question ou proposition de collaboration :

- **Email** : lucas@example.com
- **GitHub** : [github.com/lucas35simon](https://github.com/lucas35simon)
- **LinkedIn** : [linkedin.com/in/lucas-simon](https://linkedin.com/in/lucas-simon)

## 📝 Licence

Ce project est libre d'utilisation. Vous pouvez le modifier et l'utiliser comme base pour votre propre portfolio !

---

⭐ N'hésitez pas à forker ce repository et à ajouter vos propres modifications !

**Dernière mise à jour** : Juin 2024
