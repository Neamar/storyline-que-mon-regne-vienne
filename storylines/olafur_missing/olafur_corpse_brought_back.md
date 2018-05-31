---
triggers:
    soft:
        condition:
            OR:
                - sl.kill_him == true
                - sl.bring_him_alive == true
actions:
    "Faire signe aux hommes de l'expédition de rentrer sous la tente":
        operations:
            - sl.discuss_in_tent = true
    "Rester en dehors, visible de tout le campement":
        operations:
            - sl.discuss_in_front_of_camp = true

---

Un léger tumulte dans le camp passe à travers les murs épais de votre tente.

Ouvrant le lourd tissu qui sépare la tente de l'extérieur, vous voyez que le petit groupe envoyé à la poursuite d'Olafùr, le déserteur, est revenu. Ils s'approchent de vous en silence, l'intégralité du camp stoppant ses occupations pour regarder la suite des évènements.
