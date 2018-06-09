---
triggers:
    hard:
        condition:
            sl.drink_some == true
actions:
    "Ouvre ta taverne !":
        operations:
            - sl.tavern_may_open = true
    "L'alcool ne fait jamais bon ménage avec les camps militaires...":
        operations:
            - sl.no_tavern = true
---

La bière a un goût étrange, très fort. Ce n'est pas désagréable, mais on peut sentir que Bahil n'a pas encore autant d'expérience que les artisans de la capitale.

Le taux d'alcool ne semble pas extrêmement élevé, mais c'est votre première boisson alcoolisée en plusieurs mois et vous sentez rapidement le liquide vous monter à la tête.
