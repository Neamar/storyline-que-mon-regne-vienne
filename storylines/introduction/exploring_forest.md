---
triggers:
    hard:
        condition:
            sl.exploring_forest == true
actions:
    "[Suivre le sentier de gauche]":
        operations:
            - sl.exploring_forest_back = true
    "[Suivre le sentier de droite]":
        operations:
            - sl.exploring_forest_back = true
---

Marchant dans la forêt, repensant à tout ce qui est arrivé récemment, il vous faut plusieurs centaines de mètres avant de vous rendre compte que votre visage n'est plus griffé par les ronces et autres buissons qui parsèment normalement la forêt.

Un regard en arrière vous confirme votre suspicion : cette forêt a déjà vu le passage de l'homme. Derrière et devant vous, un chemin se dégage clairement : trop large pour être l'œuvre de bêtes sauvages, et aussi trop rectiligne.

Pris d'une impulsion, vous continuez de suivre le chemin sans vraiment y penser.

Après presque deux heures de marche, le chemin ne vous a toujours mené nulle part, et vous n'avez rien croisé de plus qu'un chevreuil apeuré. Décidant de faire demi-tour, **vous reprenez la route jusqu'à vous retrouver devant un croisement**... étrange. Vous ne l'avez pas remarqué à l'aller !
