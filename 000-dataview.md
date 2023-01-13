
```dataview
TABLE 
WHERE implementation-status = "implemented"
```

```dataview
TABLE controls AS "Control Family", control AS "Control", responsible-entities AS "Responsible Entities", implementation-status AS "Implementation Status"
WHERE type = "ssp"
SORT controls
```