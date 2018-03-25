---
triggers:
    soft:
        condition:
            sl.bring_body_in_tent = true
on_display:
    - r.population -= 1
actions:
    "Les remercier, et enterrer la tête vous-même":
        operations:
            - r.happiness += 2
    "Les remercier, et placer la tête bien en vue dans le campement à titre d'exemple":
        operations:
            - r.happiness -= 1
---

Le volet de la tente se referme derrière eux. Sans un mot, leur leader sort de derrière sa cape un grand sac en toile, et le pose sur la table sans ménagement.

Vos mains ouvrent le sac, sachant déjà ce qu'elles vont y trouver, tandis que votre tête se prépare psychologiquement.

Il n'y a pas d'erreur possible, c'est bien la tête d'Olafur. À en juger par l'état de décomposition, il a été abattu il y a quelques jours déjà.

Les hommes de l'expédition vous regardent, comme s'ils attendaient la suite des évènements.
