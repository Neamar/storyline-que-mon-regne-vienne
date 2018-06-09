---
triggers:
    soft:
        condition:
            AND:
                - sl.do_nothing == true
                - g.current_turn >= sl.do_nothing_turn
on_display:
    - r.population -= 1
    - r.happiness -= 5
actions:
    "Tu as bien fait. Je n'aurais pas dû laisser le départ d'Olafùr impuni":
        operations: []
    "Ici, c'est moi qui donne les ordres. Ne reprends jamais ce genre de décisions sans m'en parler avant":
        operations:
            - sl.olrik_pissed = true
    "[sortir votre épée et l'abattre]":
        operations:
            - sl.olrik_fight = true
---

Revenant d'une inspection du camp, vous voyez Olrik couvert de sang. Il a devant lui le corps d'un de vos guerriers. Il hurle à l'intention de tous les guerriers :

> « Il a voulu déserter ! Je sais que vous pensez tous qu'Olafùr est parti, alors laissez-moi clarifier une bonne fois pour toute : Olafùr est en mission officielle pour nous, et votre contrat ne permet pas la désertion. Tout le monde a bien compris ? »

Les hommes marmonnent vaguement leur assentiment avant de retourner à leurs tâches.
Olrik s'approche de vous : « mes excuses, mais j'ai dû agir. Depuis le départ d'Olafùr, j'ai surpris plusieurs fois des conversations parlant de retourner à la civilisation. J'ai préféré tuer -- littéralement -- la rébellion dans l'œuf. ».
