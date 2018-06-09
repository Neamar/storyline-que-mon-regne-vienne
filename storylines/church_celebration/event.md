---
triggers:
    soft:
        condition:
            AND:
                - g.has_church == true
                - g.tutorial_finished == true
on_display:
    - r.happiness += 10
actions:
    "[Continuer]":
        operations: []
---

Vikar, votre chapelain, a invité tous les hommes à prendre un peu de repos après le déjeuner. Tous se réunissent autour de l'église pour un moment de prière.

Les sourires sur les visages de chacun font chaud au cœur, après les semaines de marche forcée pour atteindre les lieux.
