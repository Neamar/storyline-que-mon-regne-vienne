---
triggers:
    hard:
        condition:
            sl.is_building_church == true
on_display:
    - r.happiness += 10
    - g.has_church = true
actions:
    "Espérons-le !":
        operations:
            - sl.intro_event += 1
    "Nous sommes dans les terres barbares... puisse notre Dieu vous entendre !":
        operations:
            - sl.intro_event += 1
---

Vikar, votre chapelain, s'est donné du mal ! Avec les matériaux disponibles, il a pu construire une chapelle respectable.
Cela a pris une grosse partie de la journée, mais à votre goût, cela en valait clairement la peine.

Le toit n'est qu'à moitié étanche, mais toute votre troupe se masse à l'intérieur pour participer à la première célébration dans la lumière du jour qui tombe.

Le moral semble au beau fixe, et presque comme un signe divin, alors que la cérémonie se termine, la pluie s'arrête enfin.

Vikar vous sourit :

> « Croyez-moi, Sire, ceci est le présage de jours heureux à venir ! »
