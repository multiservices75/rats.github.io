# Souris & Rats · Dératisation

Site vitrine statique — prêt à déployer sur GitHub Pages.

## URL de production
https://multiservices75.github.io/rats/

## Structure du repo
```
.
├── index.html          Page principale (à laisser à la racine)
├── sitemap.xml         Plan du site pour Google
├── robots.txt          Autorise l'indexation, pointe vers le sitemap
└── images/
    ├── hero.jpg        Image du hero (~1600×900 recommandé)
    ├── gallery-1.jpg   Photos galerie (~1200×900, ratio 4:3)
    ├── gallery-2.jpg
    └── gallery-3.jpg
```

## Déployer

1. Crée un nouveau repo GitHub nommé **`rats`** (public)
2. Glisse-dépose TOUT le contenu de ce dossier à la racine du repo → Commit
3. **Settings → Pages → Branch: `main` / (root) → Save**
4. Attends ~1 minute → ton site est en ligne sur https://multiservices75.github.io/rats/

## Formulaire de contact
Les demandes arrivent automatiquement dans la boîte mail associée à la clé
Web3Forms `582a59ba-…`. Au premier envoi, Web3Forms peut envoyer un email
de validation à cliquer une seule fois.

## Personnalisation
Toutes les données (couleurs, textes, avis) sont dans le fichier
`/app/scripts/gen_sites.py` du projet source — re-génère les 4 sites d'un
`python3 gen_sites.py`.
