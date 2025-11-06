- Tipo:: [[NotaÁrea]]
- Área:: [[A000. Desarrollo Software]]
- Link::
- Fecha:: 2025-11-04
---



```dataview
table without id
	file.link as "Nota",
	Fecha as "Fecha"
	
Where Tipo = [[NotaÁrea]]
	and Link = this.file.link
sort Fecha desc
```
