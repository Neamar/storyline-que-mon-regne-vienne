---
triggers:
    hard:
        condition:
            sl.introduction_step == 8
actions:
    "Nous devons trouver l'ennemi":
        operations:
            - sl.looking_for_enemy = true
            - sl.introduction_step = 9
        condition:
            g.rougeaud_discovered != true
    "Nous savons déjà où est leur campement...":
        operations:
            - sl.introduction_step = 9
        condition:
            g.rougeaud_discovered == true
    "Il est temps de fuir les lieux et de retourner à la capitale":
        operations:
            - sl.fleeing = true
---

La gorge nouée, sous le regard insistant de chacun, il s'agit maintenant de décider de la suite.
