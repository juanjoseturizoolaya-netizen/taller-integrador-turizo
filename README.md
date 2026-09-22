# Taller Integrador — Auditoría y corrección de sitio web

**Nombre completo:** [COMPLETA TU NOMBRE]
**Grupo:** [COMPLETA TU GRUPO]

## Tabla de hallazgos de la auditoría

| Defecto encontrado | Por qué era un problema | Cómo lo corregí |
|---|---|---|
| Nombres de archivo `Mi Pagina De Notas.HTML` y `Estilos Del Sitio.CSS` (con espacios, mayúsculas y extensión en mayúscula) | Los espacios y mayúsculas en nombres de archivo son propensos a errores en URLs, sistemas Unix (case-sensitive) y control de versiones | Renombrados a `index.html` y `styles.css` |
| Título de la pestaña `<title>pagina</title>` | No describe el contenido real de la página para el usuario ni para buscadores | Cambiado a `Calculadora de Promedio de Notas` |
| Función `calc()` | Nombre demasiado genérico, no indica qué hace la función | Renombrada a `calcularPromedio()` |
| Variables `a`, `b`, `c` | No indican qué almacenan; obligan a leer todo el código para entenderlas | Renombradas a `nota1`, `nota2`, `nota3` |
| Variable `x = 3` | Nombre de una sola letra sin significado, usado como divisor mágico | Reemplazada por la constante `CANTIDAD_NOTAS` |
| Variable `TempValue2` | Nombre en PascalCase inconsistente con el resto del código (camelCase) y que no describe su contenido | Renombrada a `promedio` |
| Número mágico `3.0` en la condición de aprobación | Un valor suelto en el código no explica su significado ni es fácil de reutilizar/cambiar | Reemplazado por la constante `NOTA_MINIMA_APROBACION` |
| IDs de HTML `n1`, `n2`, `n3`, `r`, `r2` | Identificadores crípticos que no describen el elemento ni su propósito | Renombrados a `notaUno`, `notaDos`, `notaTres`, `resultadoPromedio`, `resultadoEstado` |
| Clase CSS `.cont1` | Nombre no descriptivo del propósito del contenedor | Renombrada a `.contenedor-principal` |
| Llamadas `console.log(...)` de depuración (3 en total) | Código de depuración que no debe quedar en producción | Eliminadas |
| Función comentada `calcularAntiguo(...)` | Código muerto (comentado) que ya no se usa y solo agrega ruido | Eliminada |
| Variable `data1 = []` | Declarada pero nunca utilizada en ningún lugar del código | Eliminada |

## Sitio publicado de Netlify

https://taller-integrador-turizo.netlify.app

## Repositorio

https://github.com/juanjoseturizoolaya-netizen/taller-integrador-turizo.git
