# Le flux d'une mission

Du premier contact avec un client à la clôture, avec l'endroit où l'humain décide.

```mermaid
flowchart TD
    A[Prospect repéré] --> B[Échange de cadrage]
    B --> C{Mandat signé ?}
    C -- non --> Z[Archive, note dans 06_Clients]
    C -- oui --> D[Création de la fiche mission dans 06_Clients]
    D --> E[Création de l'agent de mission]
    E --> F[Cartographie du marché et sourcing]
    F --> G[Pré-tri sur grille écrite]
    G --> H[Brouillons d'approche par l'agent]
    H --> I{{Validation humaine}}
    I -- refus ou corrections --> H
    I -- oui explicite --> J[Envoi par la propriétaire ou sur son ordre]
    J --> K[Qualification des réponses]
    K --> L[Présentation au client]
    L --> M{{Décision du client}}
    M -- retour --> F
    M -- recrutement --> N[Clôture]
    N --> O[Fiche finale en archives, leçons reportées, agent désactivé]
```

## Les trois points de contrôle humains

1. **Avant tout envoi** : le texte d'approche est relu et validé, pour cet envoi précis.
2. **Avant toute présentation** : les profils présentés sont choisis par la propriétaire, pas par l'agent.
3. **À la clôture** : la propriétaire décide ce qui part en archives et ce qui devient une règle commune.

## Ce que l'agent fait seul

Cartographier, pré-trier sur la grille écrite, tenir la fiche à jour, rédiger les brouillons, signaler ce qui stagne. Il ne contacte personne et ne décide de rien qui engage la propriétaire.

## Ce qui reste hors du flux

Les sujets sensibles vivent dans un espace étanche, sans passerelle avec les agents de mission.
