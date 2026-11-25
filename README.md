# timeline_ia

Frise chronologique animée des dates clés de l'intelligence artificielle, conçue pour être projetée devant un groupe et parcourue arrêt par arrêt. Elle sert de correction au jeu de cartes « Timeline de l'IA » du dispositif MétropédIA (Pôle Louvain) : chaque carte du jeu y a son jalon, à l'année imprimée sur la carte.

En ligne : <https://anto-py.github.io/timeline_ia/>

## Contenu

Dix-huit jalons répartis en quatre chapitres.

| Chapitre | Période | Jalons |
| --- | --- | --- |
| I, Pionniers | 1950 à 1997 | test de Turing, conférence de Dartmouth, ELIZA, voitures autonomes de Daimler-Benz, Deep Blue |
| II, L'IA s'installe | 2011 à 2018 | Watson, Alexa, reconnaissance faciale en Chine, Cambridge Analytica |
| III, Sous tension | 2020 à 2021 | drones autonomes en Libye, IA éducatives pendant la pandémie, réseaux sociaux et santé mentale des adolescents |
| IV, L'ère générative | 2022 à 2025 | ChatGPT, Claude, Neuralink, AI Act, Hypnocratie, plan Continent IA |

Deux cartes partagent la même année en 2020, en 2024 et en 2025 : leur ordre entre elles est indifférent pour le jeu.

Chaque jalon porte au-dessus de sa date un petit objet dessiné en gravure (un masque à deux faces pour Turing, un génie qui sort de sa lampe pour ChatGPT, un globe qui tourne jusqu'à l'Europe pour Continent IA). Seul l'objet de la date affichée s'anime.

## Cartes du jeu

La page d'ouverture propose un bouton « Télécharger les cartes » : le PDF des dix-huit cartes, recto et verso, issues du dispositif MétropédIA (Pôle Louvain), sous licence Creative Commons BY-SA.

## Navigation

Vingt-quatre arrêts en tout : l'ouverture, les quatre titres de chapitre, les dix-huit jalons, la vue d'ensemble finale.

| Touche | Effet |
| --- | --- |
| Flèche droite, espace, entrée, page suivante | Arrêt suivant |
| Flèche gauche, page précédente, retour arrière | Arrêt précédent |
| Origine (Home) | Retour à l'ouverture |

## Technique

Un seul fichier, `index.html`, qui pèse 1,7 Mo parce qu'il embarque tout : React, les polices, la composition animée, ses dix-huit illustrations et le PDF des cartes y sont empaquetés puis dépaquetés au chargement. Ni étape de construction, ni dépendance réseau, ni fichier annexe.
