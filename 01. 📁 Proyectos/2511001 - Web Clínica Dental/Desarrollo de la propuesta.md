- Tipo:: [[NotaProyecto]]
- Proyecto:: [[2511001 - Web Clínica Dental]]
- Link::
- Fecha:: 2025-11-06
---
Espacio de trabajo para desarrollar la propuesta del proyecto.

```dataview
table without id
	file.link as "Nota",
	Fecha as "Fecha"
	
Where Tipo = [[NotaProyecto]]
	and Link = this.file.link
sort Fecha desc
```
