---
triggers:
    soft:
        condition:
            # Only display this event when we've discovered the Rougeaud camp, OR we never sent any scouts during the introduction
            AND:
                - sl.introduction_step == 3
                - OR:
                    - g.rougeaud_discovered == true
                    - g.has_sent_scouts != true
actions:
    "Tirez à vue, pour tuer.":
        operations:
            - sl.try_to_kill = true
    "Invitez-le dans le camp, puis amenez-le dans ma tente, nous discuterons":
        operations:
            - sl.try_to_bring = true
---

Olrik, votre lieutenant, s'adresse à vous pendant son débriefing matinal :

> « Messire ! Durant la nuit, l'un des gardes a distinctement vu un intrus à l'orée du camp. L'individu marchait sur ses deux jambes et semblait tatoué de blanc sur tout son visage, et bien que de stature humaine, le garde jure que l'apparition avait des cornes ! Il a été saisi d'effroi et n'a rien fait -- lorsque leurs regards se sont croisés, il a déguerpi en courant. Que devons-nous faire si nous le revoyons ? »
