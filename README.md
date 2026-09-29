# Convenio Laboral

Código para generar en Windows 11 un ejecutable único de consultas sobre el XVI Convenio colectivo general de centros y servicios de atención a personas con discapacidad (BOE-A-2025-7169).

La compilación de GitHub Actions descarga y comprueba el PDF del BOE y el modelo Qwen3-1.7B GGUF. El ejecutable incluirá ambos y responderá localmente, sin clave API.

El modelo local pequeño puede equivocarse. Comprueba siempre las páginas citadas. En equipos modestos, la primera apertura y cada respuesta pueden tardar.

El flujo se ejecuta al publicar estos archivos en la rama main y deja el EXE en una Release si superan las comprobaciones.
