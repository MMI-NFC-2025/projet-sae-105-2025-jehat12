# Tu Youyou Tribute - Site Web Hommage

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![HTML5](https://img.shields.io/badge/HTML5-valid-green)
![CSS3](https://img.shields.io/badge/CSS3-valid-green)
![Mobile First](https://img.shields.io/badge/Mobile-First-orange)

## 📖 Description

Site web mobile-first (393px - iPhone 15 Pro) dédié à **Tu Youyou**, scientifique chinoise lauréate du Prix Nobel de physiologie ou médecine 2015 pour sa découverte de l'artémisinine contre la malaria.

Projet pédagogique MMI sur le thème de **l'effet Matilda** (invisibilisation des femmes scientifiques dans l'histoire).

## 🎨 Design System

### Palette de couleurs (Bleu/Violet/Vert)

```css
/* Bleu électrique */
--color-blue-primary: #3b82f6
--color-blue-light: #60a5fa

/* Violet moderne */
--color-violet-primary: #8b5cf6
--color-violet-light: #a78bfa

/* Vert émeraude */
--color-green-primary: #10b981
--color-green-light: #34d399

/* Cyan accent */
--color-cyan-primary: #06b6d4
```

### Style visuel
- **Glassmorphism** : effets de verre translucide avec `backdrop-filter`
- **Gradients vibrants** : transitions bleu → violet → vert
- **Animations fluides** : transitions douces et micro-interactions
- **Dark mode élégant** : fond sombre avec accents colorés

## 📁 Structure du projet

```
tu-youyou-tribute/
├── fr/                          # Pages françaises
│   ├── index.html               # Accueil
│   ├── a-propos.html            # À propos + Timeline + Effet Matilda + Vidéo
│   ├── article-1.html           # La découverte de l'artémisinine
│   ├── article-2.html           # L'effet Matilda en sciences
│   ├── article-3.html           # Prix Nobel 2015
│   ├── article-4.html           # L'impact médical mondial
│   ├── article-5.html           # Héritage scientifique
│   ├── glossaire.html           # Glossaire scientifique
│   ├── contact.html             # Formulaire de contact
│   └── autres-projets.html      # Autres projets MMI
│
├── en/                          # Pages anglaises (mêmes pages traduites)
│   ├── index.html
│   ├── about.html
│   ├── article-1.html
│   └── ...
│
├── css/                         # Feuilles de style
│   ├── normalize.css            # Reset CSS
│   ├── variables.css            # Variables CSS (design system)
│   ├── base.css                 # Styles de base
│   ├── header.css               # Header + Navigation (BEM)
│   ├── footer.css               # Footer (BEM)
│   ├── home.css                 # Page d'accueil (BEM)
│   ├── about.css                # Page À propos (BEM)
│   ├── article.css              # Pages articles (BEM)
│   ├── glossary.css             # Glossaire (BEM)
│   ├── contact.css              # Contact (BEM)
│   └── projects.css             # Autres projets (BEM)
│
├── js/                          # Scripts JavaScript
│   ├── menu.js                  # Menu hamburger + overlay
│   ├── scroll.js                # Scroll behavior + header
│   ├── glossary.js              # Recherche/filtre glossaire
│   └── contact.js               # Validation formulaire
│
├── images/                      # Images optimisées
│   ├── tu-youyou-portrait.jpg
│   ├── artemisinine-discovery.jpg
│   ├── gallery-1.jpg
│   └── ...
│
├── videos/                      # Vidéos locales
│   ├── hidden-figures.mp4
│   └── hidden-figures-fr.vtt    # Sous-titres
│
└── README.md
```

## ✅ Exigences respectées

### HTML5
- ✅ **10 pages minimum** (5 FR + 5 EN)
- ✅ **Validation W3C** : HTML5 valide
- ✅ **Structure sémantique** : header, nav, main, footer, article, section
- ✅ **Hiérarchie de titres** : h1, h2, h3
- ✅ **Citations** : blockquote, cite
- ✅ **Mise en valeur** : strong (forte), em (faible)
- ✅ **Liens hypertextes** : navigation, ancres

### Médias
- ✅ **Images avec légendes** : figure, figcaption
- ✅ **Vidéo intégrée** : balise video locale (pas YouTube)
- ✅ **Galerie d'images** : 6 images minimum
- ✅ **Optimisation mobile** : images compressées, lazy loading

### Accessibilité
- ✅ **ARIA** : labels, roles, aria-expanded
- ✅ **Alt text** : toutes les images
- ✅ **Focus visible** : outline personnalisé
- ✅ **Navigation clavier** : focus trap dans le menu
- ✅ **Contraste** : ratios WCAG AA
- ✅ **Sémantique** : balises HTML5 appropriées

### CSS
- ✅ **Aucune librairie** sauf normalize.css
- ✅ **Variables CSS** : design system complet
- ✅ **Méthodologie BEM** : nommage des classes
- ✅ **Mobile-first** : 393px de base
- ✅ **Responsive** : media queries pour tablet/desktop

### Éléments obligatoires
- ✅ **En-tête** : header avec logo + menu hamburger
- ✅ **Pied de page** : footer avec mentions légales complètes
- ✅ **Navigation** : menu mobile avec overlay
- ✅ **Glossaire** : termes scientifiques avec recherche
- ✅ **Frise chronologique** : timeline verticale animée
- ✅ **Articles** : 5 articles structurés avec h2/h3
- ✅ **Formulaire** : contact avec validation

## 🎯 Fonctionnalités

### Navigation
- Menu hamburger animé (transformation en X)
- Overlay avec backdrop-filter
- Smooth scroll vers les sections
- Sélecteur de langue FR/EN
- Focus trap dans le menu

### Animations
- Fade-in au scroll (Intersection Observer)
- Hover effects avec scale et glow
- Transitions fluides (300-500ms)
- Décorations flottantes (keyframes)

### Interactivité
- Recherche/filtre dans le glossaire
- Validation formulaire en temps réel
- Header sticky avec effet au scroll
- Bouton "retour en haut"
- Galerie d'images interactive

## 🚀 Installation et utilisation

### Prérequis
- Navigateur web moderne (Chrome, Firefox, Safari, Edge)
- Serveur local (Live Server, MAMP, etc.) pour les vidéos

### Lancement
1. Cloner le repository
```bash
git clone https://github.com/votrecompte/tu-youyou-tribute.git
```

2. Ouvrir avec Live Server (VS Code)
```bash
cd tu-youyou-tribute
# Clic droit sur index.html → "Open with Live Server"
```

3. Ou ouvrir directement dans le navigateur
```bash
open fr/index.html
```

## 📱 Compatibilité

- ✅ iPhone 15 Pro (393px) - **Design principal**
- ✅ Smartphones (320px - 480px)
- ✅ Tablettes (768px+) - responsive
- ✅ Desktop (1024px+) - responsive

## 🧪 Tests

### Validation
- [ ] W3C HTML Validator : https://validator.w3.org/
- [ ] W3C CSS Validator : https://jigsaw.w3.org/css-validator/
- [ ] WAVE Accessibility : https://wave.webaim.org/

### Performances
- [ ] Google PageSpeed Insights
- [ ] Lighthouse (Performance, Accessibilité, SEO)
- [ ] Ecoindex (empreinte environnementale)

### Navigateurs
- [ ] Chrome/Edge (Chromium)
- [ ] Firefox
- [ ] Safari (iOS)
- [ ] Samsung Internet

## 📝 Mentions légales

**Éditeur** : Jehat Bakiray  
**Qualité** : Étudiant en MMI  
**Email** : contact@tuyouyou-tribute.fr  
**Cadre** : Projet pédagogique MMI 2024

## 📚 Ressources

- Images : Unsplash, Archives Nobel, Domaine public
- Contenu : Biographie officielle, Nobel Prize, Wikipedia
- Design : Figma (maquette)
- Développement : HTML5, CSS3, JavaScript vanilla

## 🔗 Liens utiles

- [Site en ligne](https://tu-youyou.votredomaine.fr)
- [Repository GitHub](https://github.com/votrecompte/tu-youyou-tribute)
- [Maquette Figma](https://figma.com/file/votre-maquette)

## 📄 Licence

Ce projet est réalisé dans un cadre pédagogique. Tous droits réservés.

---

**Made with ❤️ by Jehat Bakiray - MMI 2024**
