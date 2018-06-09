---
triggers:
    hard:
        condition:
            AND:
                - sl.bring_him_alive == true
                - sl.listen_to_explanation == true
actions:
    "[Les remercier, et enterrer la tête vous-même]":
        operations:
            - r.happiness += 2
    "[Les remercier, et placer la tête bien en vue dans le campement à titre d'exemple]":
        operations:
            - r.happiness -= 1
---

> « Après l'avoir traqué, nous avons fini par retrouver sa trace. Il était en train de chasser, et nous a menacé de son arc. Heureusement pour nous, l'un de mes hommes était parti en éclaireur, et lorsqu'il a vu la situation périlleuse dans laquelle nous nous trouvions il a préféré l'abattre dans le dos pour éviter tout débordement. »

Les hommes de l'expédition vous regardent, comme s'ils attendaient la suite des évènements.
