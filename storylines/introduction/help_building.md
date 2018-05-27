---
triggers:
    hard:
        condition:
            sl.is_helping_build == true
actions:
    "Aller dormir":
        operations:
            - sl.intro_event += 1
---

Vous aidez les hommes au mieux de vos capacités.

De l'intérieur d'une tente, vous surprenez une discussion dans laquelle ils expriment leur plaisir de vous voir les aider.

Vous finissez votre part de travail, heureux d'être utile au campement.
