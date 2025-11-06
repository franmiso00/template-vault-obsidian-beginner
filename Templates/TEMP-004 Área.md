- Tipo:: [[Área]]
- Fecha:: {{date}}
---
# Desarrollo 


## Índice de Notas del Área
```dataview
table  without id 
	file.link as "Nota",
	Fecha as "Time Creation"
where Tipo = [[NotaÁrea]] 
	and file.folder = this.file.folder
	and Área = this.file.link
	and Link = null
```

## Proyectos Relacionados
```dataview
table  without id 
	file.link as "Proyecto",
	Estado as "Estado"
where Tipo = [[Proyecto]]
	and Área = this.file.link
```
