---
triggers:
    soft:
        condition:
                g.has_informed_emperor != true
                # TODO: ensure this is only called at least a certain amount of turn after the introduction
        weight: 10
on_display:
    - r.population -= 1
actions:
    "Parfait. J'ai hâte de recevoir ces renforts !":
        operations:
            - storylines.introduction.has_informed_emperor = true
            - sl.thanks_olrik = true
    "Olrik, n'oublie pas qui dirige cette expédition... à l'avenir, évite les initiatives.":
        operations:
            - storylines.introduction.has_informed_emperor = true
            - sl.rebuke_olrik = true
            - g.olrik_meter ||= 0
            - g.olrik_meter -= 1
---

Olrik s'approche :

> « Je me suis permis d'envoyer un de nos hommes porter un rapport à l'empereur. Je lui ai décrit comment nous retrouver, le terrain avoisinant ainsi qu'une carte pour qu'il puisse nous envoyer des renforts dans le futur. 
Je me suis dit que malgré quelques soucis plus ou moins importants, ce campement est là pour durer, et il était plus que temps de rendre compte à l'Empereur. C'est lui qui a financé cette expédition, et il semble que le campement sur lequel vous avez commencé à bâtir est promis à un grand avenir. »
