---
type: control-family
control-family: {{title}}
---

# {{title}}

```dataview
TABLE control-family AS "Control Family", control AS "Control", responsible-entities AS "Responsible Entities", implementation-status AS "Implementation Status"
WHERE control-family = "{{title}}" AND type = "control"
SORT control
```
