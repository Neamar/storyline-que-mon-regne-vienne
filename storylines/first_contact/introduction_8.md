---
triggers:
    hard:
        condition:
            sl.introduction_step == 8
actions:
    "Nous devons trouver l'ennemi":
        operations:
            - sl.looking_for_enemy = true
    "Il est temps de fuir les lieux et de retourner à la capitale":
        operations:
            - sl.fleeing = true
---

La gorge nouée, sous le regard insistant de tous les hommes, il s'agit maintenant de décider de la suite.
