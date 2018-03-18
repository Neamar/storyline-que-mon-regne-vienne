---
triggers:
    hard:
        condition:
            sl.raise_praying_stone == true
actions:
    "Envoyer les hommes se coucher":
        operations:
            - sl.intro_event += 1
---

Les hommes s'affairent pendant une bonne partie de la journée et de la nuit, construisant différents ouvrages pour basculer la pierre à la verticale et la faire pivoter dans un trou construit pour l'occasion. Lorsqu'enfin la pierre est en place, un silence admiratif s'abat sur les lieux. C'est un magnifique ouvrage d'art, le signe d'une civilisation probablement disparue, et même si personne ne peut aujourd'hui la lire, le symbole est fort : dans ces lieux reculés, la civilisation est de retour.
