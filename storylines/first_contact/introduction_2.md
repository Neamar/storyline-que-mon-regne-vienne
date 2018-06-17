---
triggers:
    hard:
        condition:
            sl.introduction_step == 2
actions:
    "[Continuer]":
        operations:
            - sl.introduction_step = 3

---

> « Très bien messire, comme vous le désirez. »
