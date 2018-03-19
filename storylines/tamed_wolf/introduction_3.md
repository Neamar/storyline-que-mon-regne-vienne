---
triggers:
    hard:
        condition:
            sl.intro_event == 2
actions:
    "D'accord, amène-le au camp et nourris-le.":
        operations:
            - sl.tamed_wolf_in_camp = true
            - r.food -= 5
    "Malgré ça, on ne peut pas faire confiance à ces animaux. Abats-le la prochaine fois que tu le vois.":
        operations:
            - sl.tamed_wolf_in_the_woods = true
            - r.happiness -= 2

---

Steinar ne semble pas surpris par la question, comme si il se l'était déjà posée lui-même.

> « C'est-à-dire qu'on n'est jamais sûr, rapport au fait que c'est un animal et qu'il parle pas... mais il a jamais été agressif avec moi, ça c'est sûr, et puis il a la fourrure vraiment douce et chaude et il me laisse l'approcher sans problème »
