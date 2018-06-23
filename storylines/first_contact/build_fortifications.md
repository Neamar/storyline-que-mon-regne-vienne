---
triggers:
    soft:
        condition:
                AND:
                    - sl.has_debriefed == true
                    - g.has_fortifications != true
actions:
    "Excellente idée !":
        operations:
            - g.has_fortifications = true

---

Olrik s'approche.

> « Lorsque nous nous sommes installés il y a maintenant plusieurs jours, nous n'avions aucune raison de construire de fortifications... je pense que les nouveaux éléments, avec tous ces intrus, changent la donne. Il serait opportun de s'assurer que le camp soit un minimum protégé. Si vous le souhaitez, je me propose pour prendre ce chantier en charge. »
