# Proyecto Final — Redes Complejas · Red de Datos UCuenca

**Repositorio de entrega:** [jeanaucapina/ProeyctoFinal_RedesComplejas_Aucapina_Maldonado](https://github.com/jeanaucapina/ProeyctoFinal_RedesComplejas_Aucapina_Maldonado)

**Módulo 1217 · Redes Complejas · Universidad de Cuenca**
**Autores:** Jean Carlo Aucapiña · Henry Maldonado

Análisis de redes complejas sobre la infraestructura de datos real de la
Universidad de Cuenca (177 nodos, 209 aristas), aplicando los once problemas
del sílabo (P1–P11) en cuatro fases — caracterización estructural, recorrido
y partición, optimización de red, y percolación/robustez — más una síntesis
(P10) y una propuesta de rediseño acotada (P11).

## Contenido

- **[`ProyectoFinal/Resolución_ProyectoFinal/`](ProyectoFinal/Resolución_ProyectoFinal/)**
  — resolución completa de los 11 problemas:
  - `Informe.md` — informe fuente (definiciones, resultados, análisis por fase y problema)
  - `informe_latex/informe.pdf` — informe técnico compilado en PDF
  - `src/` — scripts Python de cada problema (reproducibles, ver README de esa carpeta)
  - `results/` — tablas (CSV) e imágenes (PNG) generadas
  - `presentacion.html` — presentación de resultados (grafo interactivo, gráficas animadas)
  - `presentacion_v2/` — segunda versión de la presentación (35 diapositivas, formato fijo)
  - `LIBRETO.md` — guion de presentación diapositiva por diapositiva
  - `Anexo_A/B/C_*.md` — glosario, notas extendidas y metodología detallada

- **[`ProyectoFinal/codigo_base/`](ProyectoFinal/codigo_base/)** — carga común de la red (`cargar_red.py`)
- **[`ProyectoFinal/codigo_referencia/`](ProyectoFinal/codigo_referencia/)** — implementaciones de referencia del curso (Ford-Fulkerson, Edmonds-Karp)

## Cómo reproducir los resultados

Ver [`ProyectoFinal/Resolución_ProyectoFinal/README.md`](ProyectoFinal/Resolución_ProyectoFinal/README.md).

## Cómo ver la presentación

Abrir `ProyectoFinal/Resolución_ProyectoFinal/presentacion_v2/main.html`
localmente en el navegador (no requiere servidor). Seguir el guion en
`LIBRETO.md` para la exposición.

## Origen

Este repositorio es la entrega independiente del Proyecto Final; el
desarrollo del módulo completo (todas las tareas y ejercicios del curso)
vive en el repositorio de trabajo del grupo:
[HenryM19/priv-Redes-Complejas-Grupo](https://github.com/HenryM19/priv-Redes-Complejas-Grupo).
