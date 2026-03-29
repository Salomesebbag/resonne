# Résonne — Site de Salomé Sebbag

Site officiel de la formation vocale Résonne par Salomé Sebbag, ostéopathe de la voix.

## Structure
```
resonne/
├── index.html              ← Page principale
├── vercel.json             ← Config Vercel
├── assets/
│   ├── images/
│   │   └── salome.jpg      ← Photo de Salomé
│   └── videos/
│       ├── temoignage-1.mp4
│       └── temoignage-2.mp4
└── README.md
```

## Déploiement

### 1. GitHub
```bash
git init
git add .
git commit -m "🎤 Initial commit — Résonne website"
git branch -M main
git remote add origin https://github.com/TON_USERNAME/resonne.git
git push -u origin main
```

### 2. Vercel
1. Aller sur vercel.com → New Project
2. Importer le repo GitHub
3. Framework Preset: **Other**
4. Cliquer Deploy

### 3. Domaine custom (osteodelavoix.fr)
Dans Vercel → Settings → Domains → ajouter `osteodelavoix.fr`
Puis chez ton registrar, pointer les DNS :
- A record : `76.76.19.61`
- CNAME `www` : `cname.vercel-dns.com`

## À connecter plus tard
- [ ] Stripe pour paiement Résonne (remplacer `STRIPE_LINK` dans index.html)
- [ ] Formspree pour formulaire B2B (remplacer `FORMSPREE_ID`)
- [ ] Systeme.io webhook pour leads
