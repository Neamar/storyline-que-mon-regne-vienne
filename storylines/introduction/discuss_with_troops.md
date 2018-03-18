---
triggers:
    hard:
        condition:
            sl.is_discussing_with_troops == true
on_display:
    - r.happiness += 10
actions:
    "Rester avec les hommes pour la veillée au coin du feu bâti par la seconde équipe":
        operations:
            - sl.intro_event += 1
    "S'absenter dans la tente pour aller dormir, demain sera une grosse journée":
        operations:
            - sl.intro_event += 1
---

Tisser les cordages n'est pas une opération extrêmement complexe, mais cela prend du temps.

Les hommes apprécient votre présence à leur côté, et vous font part de leurs rêves et espoirs.
La plupart ont rejoint la troupe attirés par la prime offerte par l'empereur pour les maraudeurs, et la perspective d'une vie nouvelle pour eux et leur famille une fois le campement bien établi.
