---
triggers:
    hard:
        condition:
            sl.no_tavern == true
actions:
    "Je te fais confiance, Bahil. Ne refais plus jamais ça.":
        operations:
            - sl.bahil_leaves = true
    "Je sais que tu as un bon fond, mais parfois il faut savoir faire des sacrifices pour le bien commun.":
        operations:
            - sl.bahil_leaves = true
---

Bahil a l'air un peu triste.

À votre demande, il verse l'intégralité du contenu de son outre au sol, et vous fait la promesse de ne plus rien faire fermenter.
