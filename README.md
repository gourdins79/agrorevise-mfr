# 🌱 AgroRévise

**Application de révision en agronomie des grandes cultures**, à destination des apprenants en CAP agricole *Métiers de l'Agriculture* (option Grandes cultures) et Bac Pro *CGEA*, en Maison Familiale Rurale.

👉 **[Lancer l'application](https://gourdins79.github.io/agrorevise-mfr/)**

---

## À quoi ça sert ?

Un outil de révision rapide, sur smartphone, tablette ou PC, pour s'entraîner en autonomie (en cours, en stage, en alternance) sur les connaissances d'agronomie et de phytotechnie des grandes cultures. Pas de compte à créer, pas de connexion nécessaire une fois la page chargée.

## Pour qui ?

- **CAP agricole Métiers de l'Agriculture**, option Grandes cultures (capacités CP4, CP5, CP6)
- **Bac Pro CGEA**, modules MP4 (conduite de processus de production) et MP5 (agronomie)

## Ce que propose l'app

- **5 types de questions** : QCM à réponse unique, QCM à réponses multiples, Vrai/Faux justifié, appariement (relier des points), remise en ordre chronologique d'un itinéraire technique.
- **Aucune question revue deux fois** tant que la banque du couple niveau × culture n'est pas épuisée (rotation intelligente, mémorisée sur l'appareil).
- **Choix du type de questions** une fois le niveau et la culture sélectionnés.
- **Mode Rattrapage**, qui ne repioche que dans les questions déjà ratées.
- **Tableau de bord "Mes stats"** : taux de réussite par culture et par capacité du référentiel.
- **Score, série de bonnes réponses (streak), badges de maîtrise**, mode sombre, interface tactile pensée mobile-first.
- Chaque question rappelle, après validation, la **capacité du référentiel Chlorofil** travaillée.

## Cultures couvertes

| Culture | CAP agricole MA | Bac Pro CGEA |
|---|:---:|:---:|
| Blé tendre | ✅ | ✅ |
| Blé dur | ✅ | ✅ |
| Colza | ✅ | ✅ |
| Maïs | ✅ | ✅ |
| Orge | ✅ | ✅ |
| Tournesol | ✅ | ✅ |
| Pois chiche | ✅ | ✅ |
| Pois protéagineux | ✅ | ✅ |
| Chanvre | ✅ | ✅ |
| Lin | ✅ | ✅ |
| Betterave sucrière | ✅ | ✅ |

Les 11 cultures du cahier des charges initial sont couvertes, avec 30 questions par couple culture × niveau, soit **660 questions** au total.

## Fonctionnement technique

- **Fichier unique et autonome** (`index.html`) : HTML, CSS et JavaScript embarqués, aucune dépendance externe, aucun appel réseau une fois la page chargée.
- **Fonctionne hors connexion** après un premier chargement.
- **Toutes les données restent sur l'appareil** (progression, statistiques, erreurs à revoir) via le `localStorage` du navigateur — rien n'est envoyé sur un serveur, aucun cookie, aucun compte utilisateur.
- Utilisable en ouvrant directement le fichier (`file://`) ou via ce site GitHub Pages.

## Utilisation en cours / en formation

Le lien de l'application peut être partagé tel quel (ex. dans un onglet "Site web" sur Teams, ou tout autre LMS) : un clic ouvre directement le quiz dans le navigateur, sans téléchargement.

---

*Application développée pour un formateur en MFR, alignée sur les référentiels [Chlorofil](https://chlorofil.fr).*
