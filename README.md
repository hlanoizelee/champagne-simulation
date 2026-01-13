# Champagne Simulation - Application de Gestion

Application de gestion pour l'association Champagne Simulation.

## 🚀 Déploiement sur Vercel (Gratuit)

### Méthode 1 : Via GitHub (Recommandé)

1. **Créer un compte GitHub** (si pas déjà fait)
   - Aller sur https://github.com
   - Cliquer sur "Sign up"

2. **Créer un nouveau repository**
   - Cliquer sur "New repository"
   - Nom : `champagne-simulation`
   - Laisser en "Public"
   - Cliquer sur "Create repository"

3. **Uploader les fichiers**
   - Sur la page du repository, cliquer sur "uploading an existing file"
   - Glisser-déposer TOUS les fichiers du dossier `champagne-simulation`
   - Cliquer sur "Commit changes"

4. **Déployer sur Vercel**
   - Aller sur https://vercel.com
   - Cliquer sur "Sign up" → "Continue with GitHub"
   - Cliquer sur "Add New Project"
   - Sélectionner votre repository `champagne-simulation`
   - Cliquer sur "Deploy"
   - Attendre 1-2 minutes... C'est en ligne ! 🎉

### Méthode 2 : Upload direct sur Vercel

1. Aller sur https://vercel.com
2. Créer un compte (gratuit)
3. Cliquer sur "Add New Project"
4. Choisir "Upload" et glisser le dossier complet

## 📁 Structure du projet

```
champagne-simulation/
├── index.html
├── package.json
├── vite.config.js
├── public/
│   └── logo.png
└── src/
    ├── main.jsx
    └── App.jsx
```

## ⚠️ Important

Cette version stocke les données en mémoire (elles sont perdues au rechargement de la page).
Pour une utilisation en production, il faudra ajouter une base de données.

## 🔐 Comptes de test

- Admin : jean@csrp.fr / admin123
- Lecteur : marie@csrp.fr / marie123
- Lecteur : pierre@csrp.fr / pierre123
