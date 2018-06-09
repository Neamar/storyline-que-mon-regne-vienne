---
triggers:
    hard:
        condition:
            sl.evening_gathering_with_mens == true
actions:
    "[Aller dormir]":
        operations:
            - sl.intro_event += 1
---

Certains discutent de tout et de rien, d'autres se rapellent d'anecdotes d'expéditions passées tandis qu'un autre groupe échange des plaisanteries grivoises.

Les hommes sont heureux ; si tout va bien, bientôt leur famille les rejoindra.
