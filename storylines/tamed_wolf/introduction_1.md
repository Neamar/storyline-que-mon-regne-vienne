---
triggers:
    soft:
        condition:
            g.tutorial_finished == true
actions:
    "Pas maintenant, je n'ai pas le temps":
        operations:
            - sl.tamed_wolf_in_the_woods = true
    "Bien sûr":
        operations:
            - sl.intro_event = 1
---

Steinar, un de vos chasseurs, demande si il peut vous parler en seul à seul.
