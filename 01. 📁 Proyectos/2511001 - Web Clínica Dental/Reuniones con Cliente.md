- Tipo:: [[NotaProyecto]]
- Proyecto:: [[2511001 - Web Clínica Dental]]
- Link::
- Fecha:: 2025-11-04
---

En esta nota tenemos todas las reuniones que hemos realizado en el proyecto con cliente. 

```dataview
table without id
	file.link as "Nota",
	Fecha as "Fecha"
	
Where Tipo = [[NotaProyecto]]
	and Link = this.file.link
sort Fecha desc
```
