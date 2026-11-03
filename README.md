# KDou — Rapport web de la SAÉ S1.04

Site web présentant l’analyse de la base de données KDou réalisée dans le cadre de la SAÉ S1.04 (groupe 109).

Le site est développé en **HTML5 et CSS3**, sans JavaScript ni framework. Il peut être consulté directement dans un navigateur, sans installation ni serveur web.

## Contenu du site

| Page | Contenu |
|---|---|
| `index.html` | Page d’accueil, présentation du projet, chiffres clés et accès aux différentes parties du rapport. |
| `contexte.html` | Contexte de l’étude, schéma relationnel, clés, formules de calcul, méthode de travail sous Access et organisation du site. |
| `exploration.html` | Présentation des dix requêtes d’exploration, avec leur objectif, leur requête SQL et les résultats. |
| `indicateurs.html` | Indicateurs collectifs portant notamment sur l’origine des fournisseurs, les ventes, l’offre et les commandes. |
| `personnels.html` | Quatre indicateurs individuels : marge selon le pays d’origine (Gonçalo), produits les plus rentables (Timothee), chiffre d’affaires des produits en verre ou en carton (Aymen) et répartition des commandes par ville (Youssef). |
| `qualite.html` | Problèmes de qualité des données et choix retenus pour interpréter les informations. |
| `conclusion.html` | Synthèse des missions, limites de l’analyse et recommandations pour KDou. |

## Organisation des fichiers

```text
kdou-site/
├── index.html
├── contexte.html
├── exploration.html
├── indicateurs.html
├── personnels.html
├── qualite.html
├── conclusion.html
├── README.md
└── assets/
    ├── css/
    │   └── style.css
    └── images/
        ├── schema-relationnel.png
        ├── resultat_1a.png ... resultat_1j.png
        ├── resultat_indicateur_2.png ... resultat_indicateur_5.png
        ├── resultat_indicateur_personnel.png
        ├── resultat_indicateur_personnel_2.png ... resultat_indicateur_personnel_4.png
        └── resultat_nb_commandes.png
```

### Rôle des principaux éléments

- `assets/css/style.css` contient les règles de présentation communes aux sept pages : couleurs, typographie, mise en page, navigation et adaptation aux petits écrans.
- `assets/images/` contient le schéma relationnel et les captures des résultats obtenus dans Microsoft Access, intégrés aux pages du rapport.
- Les sept fichiers HTML correspondent aux différentes parties du rapport et partagent la même feuille de style.

## Technologies et fonctionnement

- **HTML5** : structure et contenu des pages.
- **CSS3** : mise en forme et adaptation de l’affichage.
- **Microsoft Access / SQL** : réalisation des requêtes et obtention des résultats présentés dans le rapport.


