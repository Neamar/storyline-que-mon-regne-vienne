---
triggers:
    hard:
        condition:
            sl.intro_event == 3
actions:
    "Prévenons l'Empereur que nous avons trouvé un emplacement":
        operations:
            - sl.has_warned_emperor = true
    "Construisons dès maintenant une église à la gloire de Dieu !":
        operations:
            - sl.is_building_church = true
    "Préparons des fortifications autour du camp, au cas où des hostiles souhaiteraient nous rendre visite":
        operations:
            - sl.is_building_fortifications = true
    "Envoyons des éclaireurs investiguer sur cette colonne de fumée à l'horizon":
        operations:
            - sl.has_sent_scouts = true
---

Tandis que votre poignée d'hommes investit la clairière, vous jetez un œil derrière la falaise qui protège le plateau. Des hectares de forêt devant vous, un territoire encore inconnu des hommes... du moins, c'est ce que vous pensiez, jusqu'à ce qu'au loin vous notiez ce qui semble être une fine colonne de fumée. Se pourrait-il que d'autres personnes aient déjà poussé l'exploration ?

Vous êtes tirés de vos rêveries par Eric, votre intendant. **Il souhaite savoir quelle doit être votre priorité pour la journée**.
