---
triggers:
    hard:
        condition:
            AND:
                - sl.kill_him == true
                - sl.listen_to_explanation == true
actions:
    "[Les remercier, et enterrer la tête vous-même]":
        operations:
            - r.happiness += 2
    "[Les remercier, et placer la tête bien en vue dans le campement à titre d'exemple]":
        operations:
            - r.happiness -= 1
---

> « Après l'avoir traqué, nous avons fini par retrouver sa trace. Il était en train de se laver dans une rivière, ses armes sur la berge. Conformément à vos ordres, nous l'avons empêché de sortir de l'eau jusqu'à ce que le froid fasse son office. Rendu fou par le froid, il a tenté une sortie. Je lui ai coupé la tête, que voici, afin que tous se souviennent de pourquoi nous sommes ici. »

Les hommes de l'expédition vous regardent, comme s'ils attendaient la suite des évènements.
