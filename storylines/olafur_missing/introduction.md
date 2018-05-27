---
triggers:
    soft:
        condition:
            g.tutorial_finished == true
on_display:
    - r.population -= 1
    - sl.started_at = g.current_turn
actions:
    "Lancer des hommes à sa poursuite, avec ordre de le ramener vivant":
        operations:
            - sl.bring_him_alive = true
    "Lancer des hommes à sa poursuite, avec ordre d'abattre le déserteur":
        operations:
            - r.happiness -= 5
            - sl.kill_him = true
    "Ne rien faire":
        operations:
            - r.happiness -= 5
            - sl.do_nothing = true
            - sl.do_nothing_turn = g.current_turn
            - sl.do_nothing_turn += 5
---

Tandis que la troupe se réunit pour partager ensemble le petit-déjeuner, votre lieutenant Olrik note l'absence d'Olafùr.

Alors que les hommes commencent à manger et à discuter, Olrik se dirige vers la tente d'Olafùr, puis revient vers vous et vous murmure à l'oreille :

> « La tente est vide, toutes ses affaires ne sont plus là. Je crains qu'il n'ait déserté... »
