# Second cerveau

Carte du workspace. Lue avant chaque tâche. Elle tient sous 200 lignes.

## Règle numéro un

Rien ne part vers un candidat, un client ou une plateforme sans un oui explicite du propriétaire. L'agent prépare, propose, attend, puis envoie.

## Comment on écrit ici

- Une langue par défaut, une autre pour les messages destinés à l'international.
- Pas de formule creuse, pas de flatterie, pas de tournure typique d'un texte généré.
- Une information vit à un seul endroit. Quand elle change, on la corrige à sa source, on ne la duplique pas.
- Les chiffres se vérifient dans les fiches ou se demandent. Un fait n'est jamais inventé.

## Trois vitesses de changement

- `01_About-Me/` : change en années, importé dans le contexte à chaque session.
- `02_Contexte/` : change en trimestres, lu à la demande.
- Section « Où on en est » d'une fiche : change en semaines, réécrite en fin de session.

## Arborescence

```
00_Inbox/          capture en vrac, à vider
01_About-Me/       qui je suis, mon activité, ma voix (toujours lu)
02_Contexte/       la vérité unique : positionnement, marché, méthode, tarifs, objectifs
03_Branding/       marque, charte visuelle
04_Projets/        une initiative avec une fin : un dossier, une fiche
05_Departements/   les responsabilités continues, chacune avec sa fiche
06_Clients/        une entreprise qui confie un mandat : un dossier, une fiche
07_Meeting/        transcripts de calls
08_Ressources/     templates, veille
09_Journal/        un fichier par jour, un fichier par semaine
11_Archives/       terminé ou remplacé, gardé accessible
```

## Forme d'une fiche

Mission, Cadre, Étapes (ou Périmètre et Objectif pour un département), Où on en est, Key Notes. Modèles dans `modeles/`.

## Où va quoi

- une idée en vrac : `00_Inbox/`
- un mandat signé : `06_Clients/<client>/<mandat>.md`
- un contenu publié ou en brouillon : `05_Departements/Marketing/`
- un transcript de call : `07_Meeting/`
- une initiative avec une fin : `04_Projets/`
- une responsabilité continue : `05_Departements/`
- la journée : `09_Journal/`
- ce qui est fini ou remplacé : `11_Archives/`

## Agents

Voir `ORGANISATION-AGENTS.md`. Règle de routage : un sujet de mission va à l'agent de la mission, un sujet de pilotage va à l'agent de régie, le reste passe par l'agent principal.

## Rituels

- Priorités du matin : liste courte tirée du journal et des fiches actives.
- Journal du jour : écrit en fin de créneau, met à jour la section « Où on en est » des fiches touchées.
- Revue hebdomadaire : ce qui avance, ce qui stagne, les relances, trois priorités.
- Lint mensuel : doublons, fiches obsolètes, contradictions, données périmées dans `02_Contexte/`.

## Les skills ne vivent pas ici

Les procédures réutilisables sont des skills, rangés dans la configuration de l'agent. Ce dossier contient des faits, pas des procédures.
