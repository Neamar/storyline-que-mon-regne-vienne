---
triggers:
    hard:
        condition:
            sl.intro_event == 1
actions:
    "Tu es sûr que ce n'est pas une bête sauvage ?":
        operations:
            - sl.intro_event = 2
    "D'accord, amène-le au camp et nourris-le.":
        operations:
            - sl.tamed_wolf_in_camp = true
            - r.food -= 5
    "On ne peut pas faire confiance à ces animaux. Abats-le la prochaine fois que tu le vois.":
        operations:
            - sl.tamed_wolf_in_the_woods = true
            - r.happiness -= 5

---

Une fois sous la tente, il commence à parler. Ses manières d'habitudes rudes et directes semblent oubliées :

> « Voilà, chef... comment dire... j'étais en train de faire du repérage pour voir le gibier aux alentours, rapport aux stocks de nourriture... Et là, j'entends un gémissement, comme une plainte, comme une chose qui souffre. Je m'approche doucement et j'vois une bête, un grosse bête hein, pas un lapin, genre un loup mais pas vraiment un loup, qui s'est pris la patte dans un des pièges qu'on a posé pour le petit gibier. Je m'suis approché doucement, en parlant gentiment, voir comment il se comportait. Il a rien fait de méchant, du coup je l'ai décroché et il a commencé à me suivre dans les bois. Je lui ai dit de m'lâcher, rapport au fait qu'c'est un animal, qu'il a rien à faire ici. J'ai fini par lui laisser un peu de bouffe, ça l'a calmé, et j'ai pu revenir au camp, mais la fois d'après où j'suis sorti, il est apparu et il m'a pas lâché, et ça fait trois fois maintenant... vous pensez que je peux l'amener au camp ? Il prendra un peu de nourriture, mais on peut le dresser et p'têtre en fait quelque chose, rapport au fait qu'il a probablement un bon odorat ? »
