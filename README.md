<div align="center">

<br/>

```
╔═══════════════════════════════════════════════════════╗
║                                                       ║
║    ▦  QR STUDIO  ▦                                    ║
║    Le générateur de QR codes le plus élégant          ║
║                                                       ║
╚═══════════════════════════════════════════════════════╝
```

<img src="https://img.shields.io/badge/version-1.0.0-7C3AED?style=for-the-badge&labelColor=080B10" />
<img src="https://img.shields.io/badge/HTML5-Pure-00FFE0?style=for-the-badge&labelColor=080B10&logo=html5&logoColor=00FFE0" />
<img src="https://img.shields.io/badge/CSS3-Styled-9F67FF?style=for-the-badge&labelColor=080B10&logo=css3&logoColor=9F67FF" />
<img src="https://img.shields.io/badge/JS-Vanilla-FFD166?style=for-the-badge&labelColor=080B10&logo=javascript&logoColor=FFD166" />
<img src="https://img.shields.io/badge/License-MIT-00D68F?style=for-the-badge&labelColor=080B10" />

<br/><br/>

> **Transformez n'importe quel lien en QR code instantané.**  
> Dark. Élégant. Ultra rapide. Sans backend. Sans compte obligatoire.

<br/>

---

</div>

## ✦ Aperçu

```
┌─────────────────────────────────────────────────────────────────┐
│  ▦ QR Studio                          Gratuit & sans compte     │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  ┌──────────────────────────────────┐  ┌──────────────────────┐ │
│  │  🔗 Votre lien ou texte          │  │                      │ │
│  │  https://votre-lien.com          │  │   ┌──────────────┐   │ │
│  ├──────────────────────────────────┤  │   │  ██  ████  ██│   │ │
│  │  Thèmes  [Classique] [Violet]    │  │   │  ██  ████  ██│   │ │
│  │           [Cyber] [Or] [Rose]    │  │   │  ████  ██████│   │ │
│  ├──────────────────────────────────┤  │   └──────────────┘   │ │
│  │  Couleur QR    Fond              │  │                      │ │
│  │  ████ #000000  ████ #FFFFFF      │  │  ✓ Prêt · lien...   │ │
│  │                                  │  │                      │ │
│  │  Taille    Correction            │  │  [⬇ Télécharger PNG] │ │
│  │  [220px▼]  [L] [M] [Q] [H]      │  │  [⧉ Copier image]   │ │
│  └──────────────────────────────────┘  └──────────────────────┘ │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

<br/>

## ⚡ Fonctionnalités

<table>
<tr>
<td width="50%">

### 🎨 Studio QR
- **Génération instantanée** à la frappe (350ms)
- **5 thèmes préréglés** : Classique, Violet, Cyber, Or, Rose
- **Couleurs entièrement personnalisables** (fg + bg)
- **4 niveaux de correction** (L / M / Q / H)
- **5 tailles d'export** : 180px → 512px
- **Téléchargement PNG** haute résolution
- **Copie presse-papier** en un clic

</td>
<td width="50%">

### 📋 Historique
- **Sauvegarde automatique** à chaque téléchargement
- **Aperçu miniature** de chaque QR code
- **Métadonnées** : URL, couleurs, date, taille
- **Lightbox** : clic pour voir en grand
- **Suppression** individuelle ou totale
- **Persistance locale** par utilisateur (localStorage)
- **Max 20 entrées** conservées

</td>
</tr>
<tr>
<td width="50%">

### 🔐 Authentification
- **Inscription** avec validation en temps réel
- **Connexion** email / mot de passe
- **Indicateur de force** du mot de passe
- **Connexion sociale** Google & GitHub (UI)
- **Session persistante** via localStorage
- **Historique isolé** par compte utilisateur

</td>
<td width="50%">

### 🎯 Design & UX
- **Dark mode** natif, fond `#080B10`
- **Grille et orbes** en arrière-plan
- **Animations** : pulse, shimmer, transitions
- **Toasts** pour chaque action
- **100% responsive** mobile / tablette / desktop
- **Aucun backend** requis
- **0 dépendance** externe (sauf QRCode.js CDN)

</td>
</tr>
</table>

<br/>

## 🗂 Structure du projet

```
QR-Code-Studio/
│
├── 📄 index.html          # Page de connexion / inscription
├── 📄 app.html            # Studio QR + historique
└── 📄 README.md           # Ce fichier
```

> **3 fichiers. C'est tout.** Aucun build, aucun npm install, aucun serveur.

<br/>

## 🚀 Démarrage rapide

### Option 1 — GitHub Pages (recommandé)

```bash
# 1. Cloner le repo
git clone https://github.com/noelmayele02-droid/QR-Code-Studio.git

# 2. Pousser sur main
cd QR-Code-Studio
git add .
git commit -m "🚀 Initial deploy"
git push origin main

# 3. Activer GitHub Pages
# Settings → Pages → Source: main → / (root) → Save
```

✅ Votre site sera disponible sur :  
`https://noelmayele02-droid.github.io/QR-Code-Studio/`

---

### Option 2 — En local

```bash
# Cloner et ouvrir directement
git clone https://github.com/noelmayele02-droid/QR-Code-Studio.git
cd QR-Code-Studio
open index.html   # macOS
# ou
start index.html  # Windows
# ou double-clic sur index.html
```

---

### Option 3 — Avec un serveur local

```bash
# Python
python3 -m http.server 8080

# Node.js (npx)
npx serve .

# Puis ouvrir → http://localhost:8080
```

<br/>

## 🎨 Palette de couleurs

```
Background  ████  #080B10   →  Fond principal
Surface     ████  #0E1219   →  Cartes et panneaux  
Violet      ████  #7C3AED   →  Accent primaire
Violet 2    ████  #9F67FF   →  Hover et gradients
Cyan        ████  #00FFE0   →  Accent secondaire
Cyan 2      ████  #00C4AF   →  Succès et bordures actives
Gold        ████  #FFD166   →  Preset "Or"
Red         ████  #FF4D6A   →  Erreurs et suppression
Green       ████  #00D68F   →  Succès fort
```

<br/>

## 🛠 Technologies utilisées

| Technologie | Usage | Version |
|-------------|-------|---------|
| **HTML5** | Structure & sémantique | Native |
| **CSS3** | Design, animations, responsive | Native |
| **JavaScript ES6+** | Logique & interactivité | Native |
| **QRCode.js** | Génération des QR codes | 1.0.0 |
| **Space Grotesk** | Typographie display | Google Fonts |
| **Inter** | Typographie body | Google Fonts |
| **localStorage** | Persistance des données | Native |

<br/>

## 📱 Compatibilité

| Navigateur | Support |
|------------|---------|
| Chrome 90+ | ✅ Complet |
| Firefox 88+ | ✅ Complet |
| Safari 14+ | ✅ Complet |
| Edge 90+ | ✅ Complet |
| Mobile Chrome | ✅ Complet |
| Mobile Safari | ✅ Complet |

<br/>

## 🔒 Confidentialité & Sécurité

```
✓  Aucune donnée envoyée à un serveur
✓  Tout fonctionne 100% côté client (navigateur)
✓  Mots de passe stockés encodés en Base64 (démo locale)
✓  Historique isolé par compte utilisateur
✓  Aucun cookie tiers, aucun tracker
✓  Compatible avec un déploiement entièrement statique
```

> ⚠️ **Note** : L'authentification actuelle est une démonstration locale (localStorage).  
> Pour une production réelle, intégrez **Firebase Auth**, **Supabase**, ou un backend sécurisé.

<br/>

## 🗺 Roadmap

- [x] Génération instantanée de QR codes
- [x] Personnalisation couleurs & taille
- [x] Thèmes préréglés
- [x] Téléchargement PNG haute résolution
- [x] Historique avec aperçu & lightbox
- [x] Authentification (localStorage)
- [ ] Export SVG
- [ ] Logo/image au centre du QR code
- [ ] QR code pour WiFi, vCard, email
- [ ] Authentification Firebase / Supabase
- [ ] Partage direct (lien court)
- [ ] Mode clair / sombre

<br/>

## 👤 Auteur

<div align="center">

```
┌─────────────────────────────────────────────┐
│                                             │
│   Albert Isaac Noël MAYELE                  │
│   Étudiant Bachelor Cybersécurité           │
│   YNOV Campus Lille                         │
│                                             │
│   🌐 Portfolio  →  noelmayele02-droid.github.io   │
│   💼 LinkedIn   →  linkedin.com/in/albert-isaac-noël-mayele-93aa96288  │
│   🐙 GitHub     →  github.com/noelmayele02-droid  │
│                                             │
└─────────────────────────────────────────────┘
```

</div>

<br/>

## 📄 Licence

```
MIT License — Copyright (c) 2025 Albert Isaac Noël MAYELE

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software to use, copy, modify, merge, and distribute it freely.
```

<br/>

---

<div align="center">

```
▦ QR Studio — Fait avec passion par Isaac Noël Mayele ▦
```

⭐ **Si ce projet vous plaît, n'oubliez pas de mettre une étoile !** ⭐

[![GitHub stars](https://img.shields.io/github/stars/noelmayele02-droid/QR-Code-Studio?style=for-the-badge&labelColor=080B10&color=7C3AED)](https://github.com/noelmayele02-droid/QR-Code-Studio/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/noelmayele02-droid/QR-Code-Studio?style=for-the-badge&labelColor=080B10&color=00C4AF)](https://github.com/noelmayele02-droid/QR-Code-Studio/network)

</div>
