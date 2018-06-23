---
triggers:
    soft:
        condition:
            OR:
                - sl.try_to_kill == true
                - sl.try_to_bring == true
actions:
    "Rapport, soldat !":
        operations:
            - sl.debrief = true
---

Au petit matin, le camp est en effervescence. Il ne vous faut pas longtemps pour comprendre : il semblerait que l'un des gardes ait eu un nouveau contact avec l'étrange créature qui avait été entr'aperçue auparavant.

Vous vous faufilez entre les différents hommes, jouant parfois des coudes. Au centre, le garde, assis sur un rondin de bois, n'a clairement pas dormi de la nuit, et semble apprécier l'attention générale.

Le silence se fait soudain tandis que tous se rendent compte de la présence de leur leader parmi eux.

