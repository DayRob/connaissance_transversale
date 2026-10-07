# TRD — Connaissance transversale

> Ce dépôt est une **base de connaissances open source**, pas une application : les rubriques techniques (flux, schéma, design) décrivent ici l'organisation du contenu, les parcours de lecture et de contribution, et les conventions de rédaction.

## 1. Format

| Élément | Choix |
|---|---|
| Contenu | Markdown (CommonMark + tableaux GitHub) |
| Métadonnées | En-tête YAML sur chaque fiche |
| Liens internes | `[[Nom de la fiche]]` (Obsidian) |
| Lecture | GitHub (web) et Obsidian (coffre) |
| Versionnement | git ; contributions par pull request |

## 2. Contraintes de compatibilité

- Les `[[wikilinks]]` ne sont pas cliquables sur GitHub : garder le nom exact de la fiche pour qu'il reste lisible.
- Noms de fichiers = titre de la notion, sans caractères interdits sous Windows (`: * ? " < > |`).
- Encodage UTF-8, fins de ligne LF.

## 3. Exploitation par des outils

- L'en-tête YAML permet de filtrer par `domaine` et `niveau`.
- Une fiche par notion = un découpage naturel pour l'indexation (RAG de Cybereduc, Study Copilot).

## 4. Qualité (à mettre en place)

- Vérification automatique en CI : en-tête YAML présent et valide, liens `[[…]]` pointant vers une fiche existante, liens externes vivants.
- Relecture humaine de chaque pull request.
