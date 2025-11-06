- Tipo:: [[Proyecto]]
- Área:: 
- Estado:: #Pendiente #EnCurso #Completado #AlngúnDía 
- Fecha:: {{date}}
---
# Desarrollo del Objetivo



## Índice de Notas del Proyecto
```dataview
table  without id 
	file.link as "Nota",
	Fecha as "Time Creation"
where Tipo = [[NotaProyecto]] 
	and file.folder = this.file.folder
	and Proyecto = this.file.link
	and Link = null
```
