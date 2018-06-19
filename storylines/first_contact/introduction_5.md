---
triggers:
    soft:
        condition:
                AND:
                    - sl.has_debriefed == true
                    - g.has_fortifications == true
actions:
    "[Sortir de la tente en prenant votre épée]":
        operations:
            - sl.introduction_step = 6
    "[Sortir de la tente sans épée]":
        operations:
            - sl.introduction_step = 6
---

Vikar et Olrik sont devant vous. Ligoté, à genoux, ils ricanent en se lancant la tête décapitée de l'Empereur.

Vous essayez de crier, mais une immense araignée sort de votre bouche. Vous savez qu'il suffirait d'un couteau pour couper vos liens, mais le couteau est par terre, coincé derrière une fissure trop large pour vos mains fébriles.

Un cri retentit soudain, vous tirant de votre cauchemar. Hébété, vous avez quelques secondes de désorientation -- pourquoi un tel cauchemar ?!

Un second cri, plus proche, plus humain par comparaison, retentit à nouveau.
