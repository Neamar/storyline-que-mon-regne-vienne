---
triggers:
    hard:
        condition:
            sl.intro_event == 5
on_display:
    - r.food -= 5
actions:
    "[Commencer à jouer]":
        operations:
            - g.tutorial_finished = true
---

Tandis que l'aube se lève une nouvelle fois sur votre campement maintenant bien installé, un sourire apparaît sur vos lèvres.

Un peu partout dans le camp, des traînées de boue indiquent l'emplacement de ce qui bientôt délimitera le sentier principal. La plupart des hautes herbes et des arbustes environnants ont été arrachés, le terrain aplani, et durant ces deux jours d'effort votre groupe a mis en place les bases de ce qui sera un campement prospère.

L'Empereur serait fier de vos efforts.
