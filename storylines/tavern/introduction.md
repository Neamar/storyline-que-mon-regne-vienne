---
triggers:
    soft:
        condition:
            g.tutorial_finished == true
actions:
    "Avec plaisir !":
        operations:
            - sl.drink_some = true
    "L'alcool ne fait jamais bon ménage avec les camps militaires...":
        operations:
            - sl.no_tavern = true
---

Bahil se présente à l'entrée de votre tente. Il a une outre à la main.

> « Chef, ça fait maintenant longtemps qu'on est installés ici, et a priori on ne va pas bouger de si tôt. Je me suis dit que ça pourrait être une bonne chose d'avoir une petite taverne dans une des tentes internes, un endroit où les hommes pourraient venir se reposer quand ils le souhaitent. Je me suis permis de faire fermenter un peu de nos céréales, prélevées sur ma ration quotidienne. Vous voulez goûter la première tournée ?
