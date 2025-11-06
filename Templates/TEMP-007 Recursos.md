- Tipo:: [[Recursos]]
- Fecha:: {{date}}
---
# Desarrollo


## Índice de Notas Recurso
```dataview
table  without id 
	file.link as "Nota",
	Fecha as "Time Creation"
where Tipo = [[NotaRecurso]] 
	and file.folder = this.file.folder
	and Recurso = this.file.link
	and Link = null
```