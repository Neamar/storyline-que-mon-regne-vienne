---
triggers:
    hard:
        condition:
            sl.intro_event == 4
actions:
    "Prévenons l'Empereur que nous sommes installés.":
        operations:
            - sl.has_informed_emperor = true
        condition:
            sl.has_informed_emperor != true
    "Construisons une église.":
        operations:
            - sl.is_building_church = true
        condition:
            sl.is_building_church != true
    "Préparons des fortifications autour du camp.":
        operations:
            - sl.is_building_fortifications = true
        condition:
            sl.is_building_fortifications != true
    "Envoyons des éclaireurs découvrir les terres alentours.":
        operations:
            - sl.has_sent_scouts = true
        condition:
            sl.has_sent_scouts != true
---

Le jour se lève sur le campement, avec la mélodie des oiseaux locaux -- pas un que vous ne reconnaîssiez de vos anciennes campagnes.

Après quelques étirements -- la précédente journée a été éprouvante ! -- vous sortez de la chaleur relative de votre tente.

D'un peu partout émergent vos hommes, prêts pour cette seconde journée dans une terre toujours aussi étrangère.

Un groupe d'hommes est déjà en discussion autour du feu.

Vous souriez, vous sentant plus proches d'eux que jamais, et donnez le ton pour la journée :
