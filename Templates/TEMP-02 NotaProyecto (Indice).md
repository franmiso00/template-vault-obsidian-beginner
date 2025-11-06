- Tipo:: [[NotaProyecto]]
- Proyecto:: 
- Link::
- Fecha:: {{date}}
---



```dataview
table without id
	file.link as "Nota",
	Fecha as "Fecha"
	
Where Tipo = [[NotaProyecto]]
	and Link = this.file.link
sort Fecha desc
```
