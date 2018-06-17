---
triggers:
    hard:
        condition:
                AND:
                    - sl.has_debriefed == true
                    - g.has_fortifications != true
actions:
    "Excellente idée !":
        operations:
            - g.has_fortifications = true

---

Une fois les hommes dispersés, Olrik s'approche.

> « Lorsque nous nous sommes installés, nous n'avions aucune raison de construire de fortifications... je pense que ces nouveaux éléments changent la donne. Il serait opportun de s'assurer que le camp soit un minimum protégé. Si vous le souhaitez, je me propose pour prendre ce chantier en charge. »
