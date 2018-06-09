---
triggers:
    soft:
        condition:
            sl.tavern_may_open == true
actions:
    "J'ai déjà pris ma décision. Cette taverne sera ouverte.":
        operations:
            - sl.tavern_is_open = true
    "Tu as raison, j'ai eu tort. La taverne n'ouvrira pas.":
        operations:
            - sl.tavern_was_not_approved = true
            - g.happiness -= 3
---

Vikar, le chapelain, vous rejoint tandis que vous traversez le camp pour aller aux latrines.

> « La rumeur, ou plutôt, Bahil, dit que vous avez autorisé l'ouverture d'une taverne. Vous vous rendez pourtant bien compte que notre situation est difficile ! L'alcool n'est jamais un bon conseiller, et ses abus peuvent mettre à mal la machine militaire la mieux huilée. Je vous en conjure, interdisez cette taverne ; il en va de la survie de l'expédition.
