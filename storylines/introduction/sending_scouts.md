---
triggers:
    hard:
        condition:
            sl.has_sent_scouts == true
on_display:
    - r.population -= 3
actions:
    "Aller explorer la forêt":
        operations:
            - sl.exploring_forest = true
        condition:
            sl.exploring_forest != true
    "Faire le point avec Olrik":
            operations:
            - sl.is_discussing_with_olrik = true
---

Les trois éclaireurs disparaîssent dans les trois directions opposées à celle d'où vous venez.

L'un d'eux a tiré à la courte paille la descente le long de la falaise, et certains de vos hommes regardent avec anxiété tandis qu'il déséscalade tant bien que mal la paroi rocheuse abrupte.

Dans un coin de votre tête, vous notez que cette falaise n'est peut être pas la protection parfaite dont vous auriez pu rêver, tandis qu'Olrik (votre lieutenant) passe un savon aux badauds, leur rappelant qu'eux aussi ont du boulot.
