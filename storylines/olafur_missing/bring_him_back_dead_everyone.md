---
triggers:
    soft:
        condition:
            sl.body_in_front_of_camp = true
actions:
    "Les remercier, et enterrer la tête vous-même":
        operations:
            - r.happiness += 2
    "Les remercier, et placer la tête bien en vue dans le campement à titre d'exemple":
        operations:
            - r.happiness -= 1
---

Sans un mot, conscient de l'attention générale portée sur lui, le leader de l'expédition sort de derrière sa cape un grand sac en toile, qu'il secoue sans élégance.

Son contenu tombe dans la boue du camp.
Il n'y a pas d'erreur possible, c'est bien la tête d'Olafur. À en juger par l'état de décomposition, il a été abattu il y a quelques jours déjà.

Les hommes de l'expédition vous regardent, comme s'ils attendaient la suite des évènements.
