# PRD — Connaissance transversale

> Ce dépôt est une **base de connaissances open source**, pas une application : les rubriques techniques (flux, schéma, design) décrivent ici l'organisation du contenu, les parcours de lecture et de contribution, et les conventions de rédaction.

## 1. Résumé

Une base de connaissances **ouverte**, rédigée en Markdown, qui rassemble des fiches sur le développement, les réseaux, la cybersécurité, les bases de données et la méthodologie. Elle se lit sur GitHub, s'ouvre comme coffre Obsidian et peut servir de source à des outils (recherche, RAG, génération de quiz).

## 2. Problème

- Les connaissances accumulées en cours et en projets restent privées et dispersées.
- Les ressources en ligne sont souvent longues, en anglais, ou sans lien entre les notions.

## 3. Utilisateurs

| Persona | Besoin |
|---|---|
| Étudiant (BTS, BUT, école d'ingénieurs) | Fiches courtes et fiables pour réviser |
| Curieux / reconversion | Entrer dans un domaine par ses notions de base |
| Contributeur | Corriger ou ajouter une fiche facilement |
| Outils (Cybereduc, RAG) | Contenu structuré, découpé en notions, avec métadonnées |

## 4. Objectifs

| Objectif | Mesure |
|---|---|
| Une notion = une fiche | Fiches courtes, au même modèle |
| Fiches reliées | Section « Voir aussi » et liens `[[…]]` sur chaque fiche |
| Ouverte aux contributions | Guide de contribution, modèle de fiche, PR acceptées |
| Exploitable par une machine | En-tête YAML homogène (domaine, niveau, tags, sources) |

## 5. Fonctionnalités

1. Fiches rangées par domaine dans `notes/`.
2. Modèle de fiche (`templates/fiche.md`) : en bref, explication, exemple, à retenir, voir aussi.
3. Navigation par liens internes et par graphe dans Obsidian.
4. Guide de contribution (`CONTRIBUTING.md`).

## 6. Hors périmètre

- Site web dédié (GitHub et Obsidian suffisent au départ).
- Contenu copié sans autorisation.

## 7. Questions ouvertes

- **Licence** du contenu à choisir (CC BY-SA 4.0 recommandée pour une base de connaissances).
