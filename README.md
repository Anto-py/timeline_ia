# timeline_ia

Frise chronologique animée des dates clés de l'intelligence artificielle, conçue pour être projetée devant un groupe et parcourue arrêt par arrêt.

En ligne : <https://anto-py.github.io/timeline_ia/>

## Contenu

Onze jalons répartis en trois chapitres.

| Chapitre | Période | Jalons |
| --- | --- | --- |
| I, Fondations | 1950 à 1980 | test de Turing, conférence de Dartmouth, ELIZA, réseaux de neurones |
| II, Apprentissage | 1997 à 2010 | Deep Blue, apprentissage profond, assistants vocaux |
| III, Génératif | 2014 à 2022 | GAN, AlphaGo, GPT, ChatGPT |

## Navigation

Seize arrêts en tout : l'ouverture, les trois titres de chapitre, les onze jalons, la vue d'ensemble finale.

| Touche | Effet |
| --- | --- |
| Flèche droite, espace, entrée, page suivante | Arrêt suivant |
| Flèche gauche, page précédente, retour arrière | Arrêt précédent |
| Origine (Home) | Retour à l'ouverture |

## Technique

Un seul fichier, `index.html`, qui pèse 1,3 Mo parce qu'il embarque tout : React, les polices et la composition animée y sont empaquetés puis dépaquetés au chargement. Ni étape de construction, ni dépendance réseau, ni fichier annexe.
