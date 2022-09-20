```dataview
TABLE tipo AS "Raça", detalhe AS "Ocupação"
FROM #ORIESÊN 
WHERE contains(categoria,"personagem")
SORT tipo ASC, file.name ASC
```