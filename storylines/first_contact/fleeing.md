---
triggers:
    hard:
        condition:
            sl.fleeing == true
actions:
    "Changement de plan ! On ne va pas se laisser abattre par un homme cornu. Allons chercher son logement !":
        operations:
            - sl.looking_for_enemy = true
            - sl.introduction_step = 9
            - g.olrik_meter ||= 0
            - g.olrik_meter -= 1
        condition:
            g.rougeaud_discovered != true
    "Changement de plan ! Nous savons déjà où le meurtrier se trouve... il est temps de leur montrer la grandeur de l'Empire !":
        operations:
            - sl.introduction_step = 9
            - g.olrik_meter ||= 0
            - g.olrik_meter -= 1
        condition:
            g.rougeaud_discovered == true
    "Olrik, tu parles trop... nous rentrons.":
        operations:
            - sl.fleeing_confirmed = true
---

Surpris, dépassés par les évènements de la journée, tous vous regardent avec des yeux ronds, comme s'ils ne pouvaient pas en croire leurs oreilles.

Olrik, toujours à vos côtés, s'approche discrètement et parle dans un ton qui n'est pas un murmure, mais tout de même suffisamment discret pour ne pas être entendu de tous : « si nous fuyons... l'Empereur n'aura pas de pitié pour nous. Il demandera si nous avons tout fait pour éviter la débâcle, et je ne suis pas sûr que nous ayons effectivement tout tenté... »
