# Résonne — Site de Salomé Sebbag

Site de la formation vocale **Résonne** par Salomé Sebbag, ostéopathe de la voix.

## Stack
- HTML/CSS/JS vanilla — un seul fichier `resonne-project/index.html`
- Hébergé sur **Vercel** (déploiement automatique à chaque push sur `main`)
- Repo GitHub : `github.com/Salomesebbag/resonne`

## Structure
```
resonne-project/
├── index.html          ← tout le site (HTML + CSS + JS inline)
├── assets/
│   ├── images/
│   │   └── salome.jpg  ← photo principale
│   └── videos/
│       ├── temoignage-1.mp4
│       └── temoignage-2.mp4
└── vercel.json         ← config Vercel
```

## Modifier le site

### Option A — Via GitHub (petites modifs)
1. Aller sur `github.com/Salomesebbag/resonne/edit/main/resonne-project/index.html`
2. Modifier directement dans l'éditeur
3. Cliquer **Commit changes** → Vercel redéploie en 30s

### Option B — En local (dev)
```bash
git clone https://github.com/Salomesebbag/resonne.git
cd resonne/resonne-project
# Ouvrir index.html dans le browser directement
# Les images/vidéos pointent vers resonne.vercel.app donc besoin d'internet
```

### Déployer
Tout push sur `main` déclenche un redéploiement automatique sur Vercel.
URL live : **resonne.vercel.app**

## Intégrations à connecter
Les éléments suivants sont en placeholder et doivent être configurés :

| Élément | Status | À faire |
|---|---|---|
| Formulaire lead magnet | Placeholder | Connecter Systeme.io ou Mailchimp |
| Quiz vocal | Fonctionnel (front) | Connecter webhook pour envoyer les résultats |
| Paiement | Placeholder | Remplacer par lien Stripe réel |
| Formulaire B2B | Formspree placeholder | Remplacer `FORMSPREE_ID` par le vrai ID |
| Lien Doctolib | ✅ Connecté | `doctolib.fr/osteopathe/paris/salome-sebbag` |
| Instagram | ✅ Connecté | `@salomesebbag` |

## Notes techniques
- Polices : Google Fonts (Fraunces + DM Sans)
- Animations : Canvas (waveform), IntersectionObserver (reveal), CSS (breathing, ripple)
- Vidéos : format MP4, hébergées dans `assets/videos/`
- Certification Qualiopi + financement AFDAS/OPCO/CPF intégrés dans le contenu

## Contact
- Site : osteodelavoix.fr
- Instagram : @salomesebbag
