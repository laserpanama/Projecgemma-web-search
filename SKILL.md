---
name: web-search-pro
description: Búsqueda avanzada en tiempo real. Obtiene noticias, datos frescos y precios actualizados.
metadata:
  require-secret: true
  require-secret-description: Introduce tu API Key de Serper.dev
---

# Web Search Pro

## Instructions
Utiliza esta herramienta SIEMPRE que el usuario pregunte por eventos posteriores a 2025 o datos que requieran precisión externa (precios, clima, noticias).

**Protocolo de llamada:**
- **Acción**: `run_js`
- **Script**: `index.html`
- **Data**: `{"query": "término de búsqueda optimizado"}`

**Formato de respuesta esperado:**
Al recibir los datos, genera un resumen ejecutivo. Usa **negritas** para datos clave y proporciona siempre los enlaces de las fuentes al final.
