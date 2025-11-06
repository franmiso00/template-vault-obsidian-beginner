- Tipo:: [[Recursos]]
- Fecha:: 2025-11-06
---
# Desarrollo
Todo lo que veo que me interesa relacionado con **Política o Historia**

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

