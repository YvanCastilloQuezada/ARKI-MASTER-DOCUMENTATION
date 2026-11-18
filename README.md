# ARKI Master Documentation — índice de recuperación

Estado del trabajo: auditoría de solo lectura en curso. Este repositorio reúne documentación recuperada por bloques temáticos; no sustituye ni modifica los repositorios fuente.

## Repositorios fuente y orden

1. `YvanCastilloQuezada/sicl-core` — primera prioridad.
2. `YvanCastilloQuezada/sicl-web` — segunda prioridad.
3. `YvanCastilloQuezada/arki-acs` — pendiente de auditoría posterior; no intervenir en esta fase.

## Reglas de recuperación

- Conservar repositorio, rama, SHA y ruta de origen de cada elemento.
- Recuperar bloques temáticos completos, incluyendo código, pruebas, contratos, fixtures y datos relacionados.
- No fusionar ramas, borrar fuentes ni declarar implementaciones terminadas sin evidencia.
- Diferenciar capacidades implementadas, verificadas, parciales, propuestas y pendientes.
- Las decisiones anteriormente denominadas `Decision Lock (DL)` se tratarán en este repositorio como decisiones arquitectónicas modificables (`DA`). Los nombres y estados anteriores solo se conservarán como trazabilidad histórica.
- SICL Core permanece como autoridad canónica de eventos; las proyecciones y colas locales de Web no constituyen un segundo Event Store.

## Índice de auditoría

### SICL Core

Auditoría de ramas: 118 ramas observadas en el inventario previo. Se inspeccionaron contratos principales de generación de diseño, evaluación multiobjetivo/Pareto, memoria institucional, intercambio BIM/IFC y corpus regulatorio peruano. Se identificaron líneas divergentes de trabajo en DAM/ACE88, concurrencia/promoción, VSM, dibujo/layout, casos controlados, simulación Monte Carlo e inteligencia de diseño/espacial.

Pendiente: completar la revisión temática de todas las ramas, recuperar las fuentes exclusivas y cerrar el manifiesto con SHA y rutas por bloque.

### SICL Web

Auditoría de ramas: 130 ramas observadas. Bloques divergentes identificados:
- Funnel de generación y selección 9–4–1.
- Persistencia de candidatos podados.
- Memoria y continuidad con outbox SQLite cifrado y proyección desde Core.
- Integración espacial y piloto de medios/representación.
- ARKI-GIA y tipologías.
- OECE/contratación pública.
- Autonomía acotada y proyección operativa del Árbol Vivo.
- Cabina de trabajo y componentes de interfaz.

Pendiente: reconciliar 9–4–1 con la especificación 16–4–1, inspeccionar en profundidad las ramas divergentes y contrastar su contenido con `main`.

### ARKI ACS

No intervenido en esta fase, conforme al alcance acordado.

## Límites de evidencia

Este índice registra hallazgos de inspección GitHub; no afirma que las pruebas se hayan ejecutado localmente ni que las capacidades estén desplegadas en producción. El estado de cada bloque deberá sustentarse con SHA, archivos, pruebas y evidencia de ejecución cuando corresponda.

## Estado de publicación

Este documento es el primer índice de trabajo. La recuperación y clasificación siguen abiertas; no debe interpretarse como cierre de auditoría ni como integración de código.
