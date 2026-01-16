# 🌍 Familoo Website - 9 Languages

Site web multilingue pour Familoo avec détection automatique de la langue du navigateur.

## 📁 Structure

```
familoo-website/
├── index.html          # Détection langue + redirection instantanée
├── style.css           # Styles partagés (avec menu déroulant)
├── images/
│   ├── app_icon.png
│   └── ead_logo.png
├── fr/                 # 🇫🇷 Français
├── en/                 # 🇬🇧 English
├── de/                 # 🇩🇪 Deutsch
├── es/                 # 🇪🇸 Español (España)
├── es-latam/           # 🇲🇽 Español (Latinoamérica)
├── it/                 # 🇮🇹 Italiano
├── nl/                 # 🇳🇱 Nederlands
├── pt/                 # 🇵🇹 Português (Portugal)
└── pt-br/              # 🇧🇷 Português (Brasil)
```

Chaque dossier langue contient :
- `index.html` - Page d'accueil
- `privacy.html` - Politique de confidentialité

## 🌐 Détection automatique

Le visiteur est redirigé **instantanément** selon la langue de son navigateur :

| Langue navigateur | Redirection |
|-------------------|-------------|
| fr, fr-FR, fr-CA... | `/fr/` |
| de, de-DE, de-AT... | `/de/` |
| es-ES | `/es/` |
| es-MX, es-AR, es-CO... | `/es-latam/` |
| it, it-IT... | `/it/` |
| nl, nl-NL, nl-BE... | `/nl/` |
| pt-PT | `/pt/` |
| pt-BR | `/pt-br/` |
| Autre (en, etc.) | `/en/` |

## 🔄 Sélecteur de langue

Menu déroulant dans le header avec drapeaux SVG (flagcdn.com) pour changer de langue à tout moment.

## 🚀 Déploiement GitHub Pages

1. Crée un repository **`eadstudio.github.io`**
2. Upload tous les fichiers (pas le zip, le contenu)
3. Settings → Pages → Deploy from branch `main`
4. Attends 1-2 min → Site en ligne !

## 🔗 URLs

| Page | URL |
|------|-----|
| Auto-détection | `https://eadstudio.github.io` |
| Français | `https://eadstudio.github.io/fr/` |
| English | `https://eadstudio.github.io/en/` |
| Deutsch | `https://eadstudio.github.io/de/` |
| Español | `https://eadstudio.github.io/es/` |
| Español (LA) | `https://eadstudio.github.io/es-latam/` |
| Italiano | `https://eadstudio.github.io/it/` |
| Nederlands | `https://eadstudio.github.io/nl/` |
| Português | `https://eadstudio.github.io/pt/` |
| Português (BR) | `https://eadstudio.github.io/pt-br/` |

## 📝 Pour Google Play Console

- **Website URL**: `https://eadstudio.github.io`
- **Privacy Policy URL**: `https://eadstudio.github.io/en/privacy.html`

---
*EAD Studio — Neuilly-Plaisance, France*
