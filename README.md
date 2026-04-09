# Agente Corrector · Evaluación de Diagnóstico CyL 2025-26
## Lengua Castellana y Literatura · 4º Educación Primaria

Herramienta para la corrección automática de la Evaluación de Diagnóstico de Castilla y León, desarrollada para el **CEIP Puente de Simancas (Valladolid)**.

### Uso

1. Acceder a la URL de GitHub Pages del repositorio
2. Introducir la contraseña de acceso
3. Subir la guía de corrección oficial (PDF o imagen)
4. Subir el examen escaneado del alumno/a (PDF o imágenes)
5. Pulsar **"Analizar y corregir automáticamente"**
6. Revisar los resultados y exportar CSV para EVDE

### Privacidad

- Los exámenes **no llevan nombres de alumnos**, solo número identificador
- Los datos se envían únicamente a la API de Anthropic (Claude) para su análisis
- No se almacena ningún dato en servidores propios
- La sesión expira al cerrar el navegador (sessionStorage)
- La API Key se guarda en localStorage del navegador local

### Cambiar la contraseña

1. Generar el SHA-256 de la nueva contraseña en: https://emn178.github.io/online-tools/sha256.html
2. Abrir `index.html` y localizar la línea `const PASS_HASH = '...'`
3. Sustituir el hash y hacer commit

### Marco normativo

- Orden EDU/17/2024, de 15 de enero (BOCyL 23/01/2024)
- Resolución de 5 de marzo de 2026 (BOCyL 17/03/2026)
- Marco General CCL Español — INEE / Comunidades Autónomas
- Decreto 38/2022 — Currículo Educación Primaria CyL

### Desarrollado por

Luis Ángel González Ortega · [@luisgeria](https://twitter.com/luisgeria)  
Licencia por Estudios 2024/2025 · Proyecto IAprendizaje  
Junta de Castilla y León
