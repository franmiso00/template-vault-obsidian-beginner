# 🧰 Proyectos 

```dataview
list 
WHERE Tipo = [[Proyecto]]
	and Estado != "#Completado"  
	and file.folder != "Templates"
	

sort file.name
```
---
# 🚩 Áreas de Conocimiento

```dataview
list 
WHERE Tipo = [[Área]]
	and file.folder != "Templates"
sort file.name
```
---
# 🌐 Recursos

```dataview
list 
WHERE Tipo = [[Recursos]]
	and file.folder = "03. 🗒️ Recursos"

Sort Fecha asc

```

