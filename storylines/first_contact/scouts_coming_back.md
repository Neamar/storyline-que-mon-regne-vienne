---
triggers:
    soft:
        condition:
            AND:
                - g.tutorial_finished == true
                - g.has_sent_scouts == true
                - sl.introduction_step >= 3

on_display:
    - r.population += 3
actions:
    "Merci pour ces informations":
        operations:
            - g.rougeaud_discovered = true
---

Les éclaireurs que vous aviez envoyés pour explorer les alentours du campement sont revenus, et les nouvelles ne sont pas idéales.

Alors que, à votre installation, vous pensiez repousser non seulement les limites de l'Empire, mais aussi celles du monde connu, il semblerait qu'une tribu d'indigènes considère déjà ces terres comme leur maison.

Les éclaireurs ont pu identifier au moins deux campements peuplés d'humains au teint rouge. La plupart des hommes semblent se coiffer du crâne d'animaux cornus ; l'un d'eux portait un crâne affublé d'immenses cors de rennes -- plus d'un mètre cinquante, d'après le récit des éclaireurs.
