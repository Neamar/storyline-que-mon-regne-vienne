---
triggers:
    hard:
        condition:
            sl.looking_for_enemy == true
actions:
    "[Continuer]":
        operations:
            - g.has_sent_scouts = true
            - r.population -= 3
---

Rapidement, trois personnes se portent volontaires pour partir explorer les terrains alentours.

Vous leur demandez de ne pas prendre d'initiatives malheureuses : leur unique but doit être d'identifier la menace, puis de venir reporter.

Une fois les trois hommes disparus dans les bois, tous les hommes retournent à leurs occupations, mais l'ambiance est lourde et pesante.

Intérieurement, vous espérez en apprendre plus bientôt.
