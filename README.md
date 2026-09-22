# Taller Integrador Individual - Cortes 1 y 2
**Estudiante:** Santiago José Penso Peña  
**Curso:** Buenas Prácticas de Desarrollo de Software  
**Institución:** Corporación Universidad de la Costa  

## Tabla de Hallazgos de la Auditoría

| Defecto encontrado | Por qué era un problema | Cómo lo corrigió |
| :--- | :--- | :--- |
| Nombres de archivos con espacios y mayúsculas (`Mi Pagina De Notas.HTML`)[cite: 2, 3] | Causa errores en servidores web y sistemas operativos sensibles a mayúsculas/minúsculas. | Se renombraron a minúsculas y sin espacios (`index.html` y `styles.css`)[cite: 1]. |
| Variables mal nombradas (`data1`, `TempValue2`, `x`)[cite: 3] | No indican qué almacenan y dificultan la lectura del código[cite: 1]. | Se renombraron a nombres semánticos (`notasArray`, `promedioFinal`, etc.). |
| Función genérica (`calc`)[cite: 3] | Es una abreviatura ambigua que no describe su propósito real[cite: 1]. | Se renombró a `calcularPromedioNotas`. |
| Identificadores HTML crípticos (`n1`, `r`, `cont1`)[cite: 2, 3] | Son cortos y no siguen un estándar claro para los elementos del DOM[cite: 1]. | Se cambiaron a identificadores descriptivos (`inputNota1`, `textoResultadoPromedio`, etc.). |
| Título de pestaña genérico (`<title>pagina</title>`)[cite: 3] | Carece de contexto profesional sobre la aplicación web[cite: 1]. | Se cambió a `Calculadora de Promedio de Notas`. |
| Código muerto / basura (función comentada)[cite: 3] | Ensucia el código fuente y dificulta el mantenimiento a futuro[cite: 1]. | Se eliminó por completo el bloque de código comentado obsoleto. |

## Enlace del Sitio Publicado
* **Netlify URL:** [Inserta aquí tu enlace público de Netlify]