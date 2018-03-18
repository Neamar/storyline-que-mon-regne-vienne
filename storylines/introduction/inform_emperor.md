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
        conditions:
            - sl.exploring_forest != true
    "Rejoindre Éric":
        operations:
            - sl.weird_object_dug_out = true
---

L'éclaireur disparaît à l'horizon, portant la missive que vous lui avez confié -- un rapport sur l'état de vos hommes, le terrain avoisinant ainsi qu'une carte pour pouvoir recevoir des renforts dans le futur.

À l'intérieur du campement, **Éric vous fait signe de le rejoindre**.
