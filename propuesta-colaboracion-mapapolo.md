# Propuesta de proyecto colaborativo: MAPAPOLO
### Del mapa directorio al ecosistema inteligente del Polo

**De:** Kreatures Studio — estudio independiente de videojuegos en transformación a outsourcing para proyectos de videojuegos y eventos
**Para:** Oficina Técnica del Polo Nacional de Contenidos Digitales (vía Paula)
**Fecha:** Septiembre 2026
**Web prototipo:** https://kreatures-studio.github.io/mapapolo/
**Documentación:** https://kreatures-studio.github.io/mapapolo/ (README)

---

## 1. Quiénes somos

Somos un estudio de programación de videojuegos independiente con oficina en el Polo de Contenidos Digitales, en proceso de transformación hacia un estudio de outsourcing para videojuegos y eventos.

Equipo actual (5 personas):

- **Productora + Concept Artist** — dirección, producción y visión visual.
- **Programador Unity + Máster en IA** — gameplay, sistemas e inteligencia artificial.
- **Artista 3D + Organizador de eventos** — entornos y producción de eventos.
- **Artista 2D/3D** — personajes, props e ilustración.
- **Artista 3D Lighting / Technical Artist** — iluminación, optimización y pipeline técnico.

Combinamos capacidad de ejecución técnica (Unity, 3D, IA) con experiencia en eventos. Por eso proponemos no solo entregar un mapa, sino **mentorizar su co-creación**.

## 2. Punto de partida

La Oficina Técnica ha aceptado la propuesta inicial de MAPAPOLO: mapa directorio interactivo de la planta baja con buscador semántico y recomendador de sinergias con IA, pensado también para la pantalla táctil de la entrada del Polo.

Lo que nos piden ahora: **transformarlo en una experiencia colaborativa dentro del Polo**, donde las empresas integrantes propongan y colaboren, y nosotros ejerzamos de mentores y llevemos a ejecución (o integremos si ejecuta una empresa).

Este documento propone cómo hacerlo en 3 eventos mensuales hasta final de año, dejando la puerta abierta a un proyecto mayor en 2027: **un robot asistente con IA para todo el ecosistema del Polo**.

## 3. Objetivo del proyecto colaborativo

1. Completar y validar los datos reales del mapa (empresas, zonas, planta baja + primera).
2. Que las empresas del Polo co-diseñen funcionalidades útiles para ellas (no solo para visitantes).
3. Dejar un proceso y un repositorio vivo que la Oficina Técnica pueda mantener.
4. Sentar la base técnica y de comunidad para el asistente IA / robot de 2027.

## 4. Modelo de trabajo: mentoría + integración

Nuestro rol:

- **Mentores:** facilitamos cada evento, ayudamos a las empresas a convertir ideas en propuestas ejecutables (alcance, datos necesarios, criterios de aceptación).
- **Ejecutores / integradores:** implementamos las propuestas aprobadas en el repositorio MAPAPOLO, o integramos el código si la ejecuta una empresa (revisión, estándares, merge).

Rol de las empresas participantes:

- Aportan datos (quiénes son, dónde están, qué necesitan, qué ofrecen).
- Proponen mejoras en un formato corto común.
- Votan / priorizan con la Oficina Técnica.
- Opcionalmente ejecutan una propuesta con nuestra mentoría.

Rol de la Oficina Técnica:

- Validación de datos de espacios y empresas.
- Cesión de espacio y difusión para los 3 eventos.
- Decisión final de priorización junto a mentores.

Principio clave: **el proyecto puede cambiar sobre lo planteado**. El prototipo actual es la base, no el techo. Cada evento puede reorientar el roadmap.

## 5. Los 3 eventos (uno al mes)

### Evento 1 — MAPEA (Octubre): Descubrimiento y datos
**Pregunta:** ¿Qué hay realmente en el Polo y qué necesita cada empresa?

- Demo en vivo del prototipo (incluida pantalla táctil si está disponible).
- Dinámica "Mi ficha en 5 minutos": cada empresa revisa/corrige su ficha (nombre, web, sector, tecnologías, ubicación planta baja / primera, ofrece / necesita).
- Mapa de necesidades: qué buscan (colaboradores, clientes, testers, talento).
- Salida: **base de datos validada v1 + backlog priorizado de propuestas**.

Entregable nuestro (2 semanas tras evento): datos actualizados en `js/datos.js`, planta primera esbozada si hay datos suficientes.

### Evento 2 — CO-CREA (Noviembre): Prototipado
**Pregunta:** ¿Qué funcionalidad nos sería útil a todos?

- Las empresas presentan propuestas en formato de 5 min (plantilla que proveemos: problema, propuesta, datos necesarios, impacto).
- Mesas de trabajo mentorizadas: refinamos 3-4 propuestas elegidas (ej: filtros por sector, modo evento/visita, fichas ampliadas, rutas temáticas, versión táctil kiosko).
- Se decide quién ejecuta qué: nosotros o empresa voluntaria con nuestra mentoría.

Entregable nuestro: **prototipos funcionales de las 3-4 propuestas** integrados en rama de test + demo.

### Evento 3 — INTEGRA (Diciembre): Lanzamiento colaborativo
**Pregunta:** ¿Qué dejamos funcionando para el Polo?

- Integración final en `main` de lo validado en el Evento 2.
- Prueba en pantalla táctil de entrada + test con usuarios reales (visitas, otras empresas).
- Ceremonia de cierre: qué se queda, quién mantiene qué, y presentación del camino hacia el asistente IA 2027.
- Salida: **MAPAPOLO v1.0 colaborativa publicada + acta de mantenimiento + propuesta robot 2027**.

## 6. Formato de propuesta de las empresas (plantilla)

Para evitar dispersión, toda propuesta usa una ficha de media página:

1. Título + empresa proponente + contacto
2. Problema que resuelve (1-2 líneas)
3. Propuesta concreta (qué se vería / haría)
4. Datos o ayuda que necesita de otros
5. Criterio de "está terminado" (cómo sabemos que funciona)

Nosotros proveemos la plantilla y ayudamos a rellenarla durante los eventos.

## 7. Gobernanza técnica (simple)

- Repositorio único: `mapapolo` (HTML/CSS/JS puro, sin build, GitHub Pages).
- Ramas: `main` (estable, lo que se ve en entrada) + ramas por propuesta.
- Toda contribución externa pasa por revisión nuestra antes del merge (calidad, rendimiento en táctil, accesibilidad).
- Decisiones de alcance: Oficina Técnica + mentores, con voto consultivo de empresas.

## 8. Cronograma orientativo

| Fecha | Hito |
|---|---|
| Sep 2026 | Aprobación de esta propuesta + convocatoria Evento 1 |
| Oct 2026 | Evento 1 MAPEA + entrega datos v1 |
| Nov 2026 | Evento 2 CO-CREA + prototipos |
| Dic 2026 | Evento 3 INTEGRA + v1.0 + demo táctil |
| Ene 2027 | Propuesta detallada robot asistente IA (si se decide continuar) |

Cada evento: 2-2,5 h en el Polo (tarde). Nosotros necesitamos 1 semana previa para preparar materiales y 2 semanas posteriores para ejecutar/integrar.

## 9. Qué necesitamos de la Oficina Técnica

- Validación de esta propuesta y fechas de los 3 eventos.
- Espacio (ágora o similar) + pantalla/proyector para demos.
- Difusión a empresas (email + cartel) con la plantilla de propuesta.
- Acceso a datos oficiales de espacios (planos, m², usos) y validación de ubicaciones.
- Acceso a la pantalla táctil de entrada para pruebas (idealmente desde Evento 1).

## 10. Métricas de éxito (sencillas)

- Nº de empresas con ficha validada (objetivo: 80% planta baja + 50% primera).
- Nº de propuestas recibidas / prototipadas / integradas.
- Uso demo: búsquedas y clics durante eventos + primera semana en táctil.
- Satisfacción (encuesta de 3 preguntas al final de cada evento).

## 11. Hacia 2027: robot asistente con IA

El mapa colaborativo genera exactamente lo que un asistente necesitaría: datos estructurados y validados de empresas, espacios y sinergias + una comunidad que ya lo usa. Proponemos que el Evento 3 incluya una sesión de 30 min para recoger casos de uso del futuro robot (recepción, visitas, matchmaking de empresas, guía por voz en táctil), que servirá de base para la propuesta 2027.

## 12. Próximos pasos

1. Reunión de 45 min con Oficina Técnica para cerrar fechas y formato.
2. Publicamos convocatoria Evento 1 con plantilla de ficha.
3. Congelamos prototipo actual como `v0` de partida.

---

**Anexo:** prototipo funcional en https://kreatures-studio.github.io/mapapolo/ — mapa interactivo, buscador semántico (`/`), sinergias IA por empresa, tooltips con nombre de empresa, responsive + modo claro/oscuro.

*Kreatures Studio — Polo de Contenidos Digitales, Málaga.*
