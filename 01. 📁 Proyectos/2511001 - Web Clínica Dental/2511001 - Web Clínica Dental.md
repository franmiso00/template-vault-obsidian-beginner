- Tipo:: [[Proyecto]]
- Área:: [[A000. Desarrollo Software]]
- Estado::  #EnCurso
- Fecha:: 2025-11-04
---
# Desarrollo del Objetivo

Desrarrollar la página web 

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
