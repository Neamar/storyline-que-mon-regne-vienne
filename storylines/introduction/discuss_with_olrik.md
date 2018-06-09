---
triggers:
    hard:
        condition:
            sl.is_discussing_with_olrik == true
actions:
    "[Rester avec les hommes pour la veillée au coin du feu]":
        operations:
            - sl.evening_gathering_with_mens = true
    "[S'absenter pour aller dormir, demain sera une grosse journée]":
        operations:
            - sl.intro_event += 1
---

Olrik et vous sortez de la tente, heureux de l'air frais du crépuscule qui tombe après les heures de chaleur moite dans l'atmosphère confinée de la tente.

La pluie des derniers jours semble avoir disparue, et les quelques nuages dans le ciel colorent le ciel de lueurs rougeâtres qui ne tarderont pas à laisser place au noir profond de la nuit.

La réunion vous a permis d'avoir une bonne vision sur l'état de vos ressources :

* le peu de métal que vous avez pu transporter jusqu'ici, et qu'il faudra économiser au maximum tant qu'une route d'approvisionnement n'est pas mise en place ;
* l'état des différentes tentes et réserves de vêtements après les mauvaises conditions météorologiques des derniers jours ;
* le moral des hommes -- Olrik a noté qu'il était inquiet pour Olafùr, qui semblait morose et éteint ces derniers temps ;
* et surtout, sur les stocks d'eau et de nourriture, qui, sans être inquiétants, mériteront que vous vous y intéressiez sous peu.

Autour d'un feu, le reste des hommes se sont regroupés pour discuter.

Le crépitement du foyer est soudain remplacé par le cri sourd d'une bête sauvage au loin. Pendant quelques secondes, toutes les discussions s'arrêtent, avant de recommencer sur un ton étouffé, après ce rappel de la nature que vous étiez des intrus chez elle.
