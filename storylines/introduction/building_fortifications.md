---
triggers:
    hard:
        condition:
            sl.is_building_fortifications == true
on_display:
    - r.happiness += 5
actions:
    "Aider les hommes et rejoindre la première équipe (creuser)":
        operations:
            - sl.is_helping_build = true
    "Aider les hommes et rejoindre la troisième équipe (discuter en tissant le cordage)":
            operations:
            - sl.is_discussing_with_troops = true
    "Aller explorer la forêt avoisinante":
        operations:
            - sl.exploring_forest = true
        condition:
            sl.exploring_forest != true
---

L'ordre à peine donné, Olrik est déjà en train d'organiser les roulements, comme si il avait déjà tout prévu depuis longtemps et n'attendait que votre ordre pour commencer.

> « Trois équipes ! La première, creusez un large fossé sur le périmètre du camp, utilisez la terre déblayée pour faire un monticule central sur lequel nous pourrons mettre en place une vigie ! La seconde, allez couper du bois pour construire une palissade ! La troisième, trouvez du chanvre ou de l'osier pour créer du cordage, et récupérez le petit bois de la seconde équipe pour préparer des réserves pour le feu ! On s'active ! »

Vous souriez dans votre for intérieur -- votre lieutenant a toujours été un homme d'actions capable de prendre des décisions rapides, et vous êtes fier de pouvoir compter sur lui !
