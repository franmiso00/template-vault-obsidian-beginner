- Tipo:: [[NotaÁrea]]
- Área:: 
- Link::
- Fecha:: {{date}}
---



```dataview
table without id
	file.link as "Nota",
	Fecha as "Fecha"
	
Where Tipo = [[NotaÁrea]]
	and Link = this.file.link
sort Fecha desc
```
