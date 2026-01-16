# 🏠 Site Familoo - familoo.github.io

Site web statique pour la validation du compte développeur Google Play.

## 📁 Structure

```
familoo-website/
├── index.html      # Page d'accueil
├── privacy.html    # Politique de confidentialité (obligatoire Play Store)
├── style.css       # Styles
├── images/
│   ├── app_icon.png    # Logo Familoo
│   └── ead_logo.png    # Logo EAD Studio
└── README.md
```

## 🚀 Déploiement sur GitHub Pages

### Étape 1 : Créer le repository

1. Va sur [github.com](https://github.com) et connecte-toi
2. Clique sur **"New repository"** (bouton vert)
3. Nom du repository : **`familoo.github.io`** (exactement ce nom !)
4. Laisse en **Public**
5. **NE COCHE PAS** "Add a README file"
6. Clique **"Create repository"**

### Étape 2 : Uploader les fichiers

**Option A - Via l'interface web (plus simple) :**
1. Sur la page du repo vide, clique **"uploading an existing file"**
2. Glisse-dépose TOUS les fichiers de ce dossier (index.html, privacy.html, style.css, et le dossier images/)
3. Clique **"Commit changes"**

**Option B - Via Git (si tu préfères) :**
```bash
cd familoo-website
git init
git add .
git commit -m "Initial commit - Familoo website"
git branch -M main
git remote add origin https://github.com/TON_USERNAME/familoo.github.io.git
git push -u origin main
```

### Étape 3 : Activer GitHub Pages

1. Va dans **Settings** du repository
2. Menu **Pages** (dans la sidebar gauche)
3. Source : **Deploy from a branch**
4. Branch : **main** / **/ (root)**
5. Clique **Save**

### Étape 4 : C'est en ligne ! 🎉

Après 1-2 minutes, ton site sera accessible à :
- **https://familoo.github.io** (page d'accueil)
- **https://familoo.github.io/privacy.html** (privacy policy)

## 📝 URLs pour Google Play Console

Utilise ces URLs dans ta fiche Play Store :
- **Site web** : `https://familoo.github.io`
- **Politique de confidentialité** : `https://familoo.github.io/privacy.html`

## ✏️ Modifications futures

Pour modifier le site :
1. Va sur le repo GitHub
2. Clique sur le fichier à modifier
3. Clique sur l'icône crayon (Edit)
4. Fais tes modifications
5. Clique "Commit changes"

Le site se met à jour automatiquement en 1-2 minutes.

---
*EAD Studio - Neuilly-Plaisance, France*
