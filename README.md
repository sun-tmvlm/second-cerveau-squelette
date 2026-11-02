# Second cerveau, squelette

Une architecture de travail pour un recruteur ou un chasseur de têtes indépendant qui s'appuie sur des agents IA. Ce dépôt ne contient aucune donnée : uniquement la structure, les règles et les fiches types.

## L'idée

Des fichiers markdown que les agents lisent avant chaque tâche. Une information vit à un seul endroit, un fichier carte (`AGENTS.md`) dit où tout se trouve, et chaque mission ou initiative a une fiche qui porte son état.

## Trois vitesses de changement

| Dossier | Rythme | Rôle |
|---|---|---|
| `01_About-Me/` | des années | qui je suis, mon activité, ma voix. Lu à chaque session |
| `02_Contexte/` | des trimestres | positionnement, marché, méthode, tarifs. Lu à la demande |
| section « Où on en est » d'une fiche | des semaines | état courant, réécrit en fin de session |

Séparer ainsi les rythmes évite de recharger dans le contexte de l'agent ce qui ne bouge pas, et de laisser vieillir ce qui bouge vite.

## Arborescence

Voir `AGENTS.md`. Chaque dossier contient un `README.md` qui dit ce qu'on y met.

## Organisation en agents

Voir `ORGANISATION-AGENTS.md` : un agent principal, des agents de fonction, un agent par mission, des espaces étanches.

## Fiches types

Voir `modeles/`. Cinq rubriques, toujours les mêmes : Mission, Cadre, Étapes, Où on en est, Key Notes.

## Ce que ce dépôt ne contient pas

Aucun nom de client, de candidat ou d'employeur, aucun chiffre d'activité, aucun identifiant. Les procédures réutilisables (skills) vivent hors du dossier de données, dans la configuration de l'agent.
