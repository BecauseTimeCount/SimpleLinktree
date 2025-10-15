# Simple Linktree - Julien Wanecque

## 📋 Description du projet

Site Linktree personnel minimaliste créé avec HTML, CSS et JavaScript vanilla. Permet de centraliser tous les liens professionnels en un seul endroit avec un design moderne et responsive.

## 🎯 Fonctionnalités

- Design Bento moderne avec effet glassmorphism
- Fond de carte Google Maps (région de Guérande)
- Cartes interactives pour :
  - Citation inspirante (Satoshi Nakamoto)
  - LinkedIn
  - GitHub avec graphique de contributions
  - Portfolio personnel
  - Agence web (Because Time Counts)
- Fully responsive (mobile & desktop)
- Animations fluides
- Bouton scroll-to-top

## 🛠️ Technologies utilisées

- **HTML5** : Structure sémantique
- **CSS3** : Animations, gradients, flexbox, grid
- **JavaScript Vanilla** : Interactivité (scroll button)
- **Font Awesome 6.4.2** : Icônes

## 📁 Structure du projet

```
/
├── index.html          # Page principale
├── style.css          # Tous les styles et responsive
├── picture.png        # Photo de profil
├── CLAUDE.md          # Documentation
└── README.md          # (à créer)
```

## 🚀 Déploiement

### Repository GitHub
- **URL** : https://github.com/BecauseTimeCount/SimpleLinktree
- **Branche principale** : `main`
- **Visibilité** : Public

### Hébergement Vercel
- **Domaine cible** : `linktree.julienwanecque.com`
- **Type** : Site statique (HTML/CSS/JS)
- **Build** : Aucun build nécessaire
- **Output Directory** : `./` (racine)

## ⚙️ Configuration DNS (Hostinger)

Pour le sous-domaine `linktree.julienwanecque.com` :

```
Type: CNAME
Name: linktree
Target: cname.vercel-dns.com.
TTL: 3600
```

## 🎨 Personnalisation

### Modifier les liens
Éditer les balises `<a>` dans `index.html` (lignes 39-125)

### Modifier les couleurs
Ajuster les gradients dans `style.css` :
- LinkedIn : lignes 234-237
- GitHub : lignes 244-247
- Portfolio : lignes 314-317
- Agency : lignes 336-339

### Modifier la carte Google Maps
Remplacer l'URL de l'iframe (ligne 14 de `index.html`)

## 📱 Responsive

- **Mobile** (< 768px) : Une seule colonne, tout en vertical
- **Tablet** (768px - 1023px) : Grille 2 colonnes
- **Desktop** (> 1024px) : Citation fixée en bas à droite, header fixé en haut à gauche

## ⚠️ Points importants

1. **UNIQUEMENT ce dossier Linktree** doit être publié sur GitHub
2. **Ne jamais publier** sur d'autres branches que `main`
3. **Ne pas inclure** les dossiers parents ou autres projets
4. Le fichier `picture.png` doit être présent à la racine

## 🔄 Mises à jour

Pour toute modification future :

```bash
git add .
git commit -m "Description des changements"
git push origin main
```

Vercel redéploiera automatiquement en 30 secondes.

## 📊 Historique des modifications

### 2025-10-15 - Version initiale
- ✅ Création du design Bento
- ✅ Intégration des cartes LinkedIn, GitHub, Portfolio, Agency
- ✅ Optimisation mobile (toutes cartes en une colonne)
- ✅ Réduction taille cartes LinkedIn/GitHub pour harmonisation
- ✅ Graphique GitHub compact (carré au lieu de rectangle)
- ✅ Préparation pour déploiement Vercel

## 👤 Auteur

**Julien Wanecque**
- Portfolio : https://www.julienwanecque.com/
- LinkedIn : https://www.linkedin.com/in/julien-w-a8579329/
- GitHub : https://github.com/BecauseTimeCount
- Agence : https://becausetimecounts.fr/

---

💡 *Projet créé avec l'assistance de Claude (Anthropic)*
