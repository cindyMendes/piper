# Piper 🐾

Carte d'identité web pour Piper, au cas où elle se perd.
Accessible via un **QR code** imprimé sur son collier.

## 📁 Structure

```
piper/
├── index.html    → page principale
├── style.css     → styles
├── favicon.png   → icône de l'onglet
└── README.md
```

## 🚀 Déploiement

> Une fois le site en ligne, on peut génèrer un QR code avec l'URL sur [qrcode-monkey.com](https://qrcode-monkey.com)

### GitHub Pages (branche `dev`)

1. Dans **Settings → Pages** du repo
2. Source : branche `dev`, dossier `/root`
3. Clique **Save**
4. Le site est accessible sur `https://cindymendes.github.io/piper`

### Netlify (branche `main`)

Tout push sur la branche `main` déclenche un redéploiement automatique.

URL : [piper-dog-id.netlify.app](https://piper-dog-id.netlify.app)

## ✏️ Modifier les infos

Toutes les informations sont dans `index.html`, directement éditables.

