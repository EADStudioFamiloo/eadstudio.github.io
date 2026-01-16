# 🏠 Site Familoo - Multilingue (FR/EN)

Site web statique bilingue pour Familoo avec détection automatique de la langue.

## 📁 Structure

```
familoo-website/
├── index.html          # Page de détection de langue + redirection
├── style.css           # Styles partagés
├── images/
│   ├── app_icon.png    # Logo Familoo
│   └── ead_logo.png    # Logo EAD Studio
├── fr/
│   ├── index.html      # Page d'accueil française
│   └── privacy.html    # Politique de confidentialité FR
├── en/
│   ├── index.html      # English homepage
│   └── privacy.html    # Privacy policy EN
└── README.md
```

## 🌍 Fonctionnement

1. **Détection automatique** : La page racine détecte la langue du navigateur
2. **Redirection** : Redirige vers `/fr/` ou `/en/` automatiquement
3. **Préférence sauvegardée** : Le choix est mémorisé pour les visites suivantes
4. **Sélecteur manuel** : Drapeaux 🇬🇧/🇫🇷 dans le header pour changer de langue

## 🚀 Déploiement sur GitHub Pages

### Étape 1 : Créer le repository

1. Va sur [github.com](https://github.com) avec ton nouveau compte
2. Clique sur **"New repository"**
3. Nom : **`eadstudio.github.io`** (ou `familoo-app.github.io`)
4. Public, **sans** README
5. **"Create repository"**

### Étape 2 : Uploader les fichiers

1. Clique **"uploading an existing file"**
2. Glisse-dépose TOUS les fichiers et dossiers de ce zip
3. **"Commit changes"**

### Étape 3 : Activer GitHub Pages

1. **Settings** → **Pages**
2. Source : **Deploy from a branch**
3. Branch : **main** / **/ (root)**
4. **Save**

## 🔗 URLs finales

Une fois en ligne :

| Page | URL |
|------|-----|
| Accueil (auto) | `https://eadstudio.github.io` |
| Français | `https://eadstudio.github.io/fr/` |
| English | `https://eadstudio.github.io/en/` |
| Privacy FR | `https://eadstudio.github.io/fr/privacy.html` |
| Privacy EN | `https://eadstudio.github.io/en/privacy.html` |

## 📝 Pour Google Play Console

- **Site web** : `https://eadstudio.github.io`
- **Privacy Policy** : `https://eadstudio.github.io/en/privacy.html` (ou `/fr/`)

---
*EAD Studio - Neuilly-Plaisance, France*
