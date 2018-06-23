---
triggers:
    hard:
        condition:
            AND:
                - sl.introduction_step == 9
                - g.rougeaud_discovered == true
actions:
    "Partons en guerre":
        operations:
            - g.war_with_rougeauds = true
    "Envoyons un parlementaire":
        operations:
            - g.diplomacy_with_rougeauds = true
---

Dans votre tête, il ne fait aucun doute que la mort de Vastyah est liée au campement découvert par les éclaireurs.

Nul besoin d'être fin stratège pour identifier la suite des évènements. Si rien n'est fait, ce genre d'incidents continuera de se reproduire à l'infini.

Il faut soit se débarasser complètement de cette menace, ou réussir à la comprendre et la juguler pour intégrer ces sauvages à l'Empire.

Extrêmement conscient du poids de vos paroles, qui va influencer des dizaines de vies et le futur de tout votre campement, vous expliquez votre décision :
