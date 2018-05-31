---
triggers:
    hard:
        condition:
            OR:
                - sl.kill_him == true
                - sl.bring_him_alive == true
on_display:
    - r.population -= 1
actions:
    "Qu'est ce que vous regardez tous ? Retournez au boulot !":
        operations: []
---

Les hommes disparaissent à l'horizon.

Vous espérez les revoir bientôt...
