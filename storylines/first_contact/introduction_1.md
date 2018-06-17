---
triggers:
    soft:
        condition:
            g.tutorial_finished == true
on_display:
    - r.food += 2
    - sl.introduction_step = 2
actions:
    "Instaurons des tours de garde obligatoires.":
        operations:
            - r.happiness -= 10
    "Je suis sûr que ce n'est rien.":
        operations: []
    "À partir de maintenant, doublons toutes les équipes de chasseurs par sécurité":
        operations:
            - r.food -= 10
---

C'est Éric qui vient vous trouver. Il tient dans sa main une flèche grossière.

> « Un de nos chasseurs vient de revenir avec un chevreuil qu'il a abattu... mais il est venu me voir directement, car le chevreuil avait été blessé auparavant par une flèche. »

Il vous tend la flèche. Le bois n'est pas droit, et l'empennage de plume semble avoir connu des jours meilleurs. Il est évident qu'il ne s'agit pas de l'œuvre d'un de vos hommes.

> « Il semblerait que nous ne soyons pas seuls... que voulez-vous faire ? »
