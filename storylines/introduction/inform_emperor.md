---
triggers:
    hard:
        condition:
            sl.has_informed_emperor == true
on_display:
    - r.population -= 1
actions:
    "Aller explorer la forêt":
        operations:
            - sl.exploring_forest = true
        condition:
            sl.exploring_forest != true
    "Retourner au campement":
        operations:
            - sl.praying_stone = true
---

L'éclaireur disparaît à l'horizon, portant la missive que vous lui avez confié -- un rapport sur l'état de vos hommes, le terrain avoisinant ainsi qu'une carte pour pouvoir recevoir des renforts dans le futur.

Au sein du campement, les hommes sont tous rassemblés et discutent autour du feu.
