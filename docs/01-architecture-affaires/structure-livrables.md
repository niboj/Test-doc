# Structure des livrables d’architecture d’affaires

## Objectif

Définir la structure cible des fichiers Markdown à produire pour documenter l’architecture d’affaires de la PDM selon TOGAF.

## Arborescence cible

```text
docs/
  01-architecture-affaires/
    index.md
    01-vision-affaires.md
    02-moteurs-buts-objectifs.md
    03-parties-prenantes.md
    04-capacites-affaires.md
    05-services-affaires.md
    06-processus-affaires.md
    07-modele-operationnel-cible.md
    08-exigences-affaires.md
    09-ecarts.md
    10-feuille-route-architecture.md
    11-tracabilite.md
```

## Description des livrables

| Fichier | Contenu attendu |
|---|---|
| `01-vision-affaires.md` | Finalité, valeur attendue, portée et bénéfices de la PDM. |
| `02-moteurs-buts-objectifs.md` | Moteurs d’affaires, buts, objectifs, critères de succès et indicateurs. |
| `03-parties-prenantes.md` | Groupes concernés, besoins, attentes, responsabilités et préoccupations. |
| `04-capacites-affaires.md` | Carte et description des capacités d’affaires actuelles et cibles. |
| `05-services-affaires.md` | Services d’affaires, clientèles, modalités d’accès et résultats livrés. |
| `06-processus-affaires.md` | Processus nécessaires à l’offre, à l’exploitation et à la gouvernance des services. |
| `07-modele-operationnel-cible.md` | Responsabilités, interactions, mécanismes de décision et fonctionnement cible. |
| `08-exigences-affaires.md` | Exigences vérifiables classées par thème. |
| `09-ecarts.md` | Écarts entre l’état actuel et l’état cible, impacts et pistes de traitement. |
| `10-feuille-route-architecture.md` | Progression des capacités, livraisons, dépendances et résultats attendus. |
| `11-tracabilite.md` | Relations entre moteurs, objectifs, capacités, services, processus, exigences et livraisons. |

## Règles de classement

- Utiliser un préfixe numérique pour contrôler l’ordre d’affichage.
- Utiliser des noms de fichiers courts, en minuscules, sans accents.
- Regrouper les contenus selon leur nature d’artefact.
- Éviter les pages trop longues lorsque le contenu peut être divisé par sujet.
- Ajouter chaque nouveau fichier dans la navigation du site.
