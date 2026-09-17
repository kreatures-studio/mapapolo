# Comunidad emprendedora activa del Polo
### Programa de construcción colaborativa: del mapa 2D al Polo 3D con robot

**Para:** Paula y Oficina Técnica del Polo Nacional de Contenidos Digitales
**De:** Kreatures Studio
**Fecha:** septiembre de 2026
**Base:** [prototipo MAPAPOLO](https://kreatures-studio.github.io/mapapolo)

---

## La idea acordada, en una frase

El Polo quiere una **comunidad emprendedora activa estilo Silicon Valley**: tanto talento junto que la gente decida unirse para hacer cosas. Como no está surgiendo solo, nosotros lo mentorizamos: **una jornada de presentación-reclutamiento, talleres semanales o quincenales donde se ejecuta (nada de charlas) y un evento final donde se presenta el proyecto terminado**.

El proyecto a construir: **modelar todo el Polo en 3D y poner dentro el robot en 3D como prototipo del futuro robot real**, conectado al mapa directorio MAPAPOLO.

---

## Por qué este enfoque

- La gente no se une a “reuniones”. Se une a **hacer algo visible** con otros.
- El 3D + robot es un reto atractivo para programadores, artistas 3D/2D, sonido, IA y organizadores de eventos: todos tienen un hueco.
- Cada taller deja una pieza terminada. Nadie siente que trabaja gratis para nada.
- El resultado final es demostrable en la pantalla de entrada y en el evento de cierre.

---

## Estructura del programa

1. **Jornada 0 — Presentación y reclutamiento** (1 sesión, 2 h).
2. **Talleres de construcción** (6 sesiones, cada 1-2 semanas, 2 h cada una, solo ejecución).
3. **Evento final — Showcase** (1 sesión, 2 h, demo pública).

Total orientativo: 8 sesiones entre octubre y diciembre de 2026.

---

## Jornada 0 — Presentación y reclutamiento

**Objetivo:** salir con 10-20 voluntarios apuntados a roles concretos.

**Formato (2 h, Ágora):**
- 15 min — Paula: por qué una comunidad activa y qué espera el Polo.
- 15 min — Kreatures: demo del mapa actual + visión “Polo en 3D con robot”.
- 30 min — Mesas por oficios: 3D, Unity/interacción, IA, arte 2D/UI, sonido, docs/difusión, testing. Cada mesa escribe en cartulina qué puede aportar en 4 horas al mes.
- 30 min — “Ofrezco / busco / aprendo”: cada persona se presenta en 1 minuto con esas tres palabras.
- 20 min — Compromiso: se rellenan las fichas de voluntariado (ver `ficha-voluntariado-polo.md`) y se eligen días/horarios de talleres.
- 10 min — Cierre: calendario, canal de comunicación y primera tarea para casa (traer 1 foto/medida de su zona del Polo).

**Salida:** lista de voluntarios con rol, disponibilidad y contacto + backlog inicial + fotos del evento.

---

## Talleres: reglas de juego

- **Nada de charlas.** Cada taller empieza con 10 min de objetivo y termina con demo de lo construido.
- **Mentoría por oficio:** cada mesa tiene un mentor de Kreatures.
- **Piezas pequeñas:** cada sesión produce algo integrable (un despacho modelado, una animación del robot, una ficha conectada al 3D).
- **Repositorio único:** todo se integra en `mapapolo`; `main` siempre estable para la pantalla de entrada.
- **Altruista pero serio:** la aportación es voluntaria; el compromiso es asistir o avisar, entregar a tiempo y aceptar revisión.

Programa detallado en `talleres-polo-3d-robot.md`. Resumen:

| Taller | Foco | Salida integrable |
|---|---|---|
| T1 | Levantamiento: medidas, fotos, referencias del edificio | Pack de referencias + plano de bloques 3D |
| T2 | Modelado base: спрос exterior + planta baja navegable | Escena 3D base cargando en web |
| T3 | Oficinas y detalles: OF1-OF6, ágoras, patios, coworkings | 6+ zonas reconocibles en 3D |
| T4 | Robot 3D: modelo, rig básico, animación idle/saludo | Robot prototipo dentro de la escena |
| T5 | Conexión mapa ↔ 3D: clic en 2D localiza en 3D y viceversa | Demo integrada web + táctil |
| T6 | Ensayo general + fixes + vídeo | Versión candidata al Showcase |

---

## Roles

**Kreatures Studio (mentores + integración):**
- Productora/concept: dirección, guion de talleres, backlog, calidad visual.
- Programador Unity + IA: escena 3D web, interacción, conexión con datos MAPAPOLO.
- Artista 3D eventos: levantamiento, organización de mesas, prueba en sala.
- Artista 2D/3D: modelado, texturas, UI.
- Lighting/TA: iluminación, optimización, rendimiento en táctil.

**Voluntarios (altruista):**
- Modelado 3D, texturas, iluminación.
- Unity/interacción web.
- IA/diálogos del robot (solo prototipo conversacional acotado).
- Arte 2D, iconos, cartelería.
- Sonido (idle, saludo, clicks).
- Documentación, fotos, vídeo, difusión.
- Testing en táctil y móvil.

**Oficina Técnica (Paula):**
- Convocatoria, espacio, pantalla táctil para pruebas.
- Validación de datos y de lo publicable.
- Decisión de alcance con mentores.

---

## Calendario orientativo

| Cuándo | Qué |
|---|---|
| Sep 2026 (semana tras 10-S) | Jornada 0 reclutamiento |
| Oct | T1 levantamiento + T2 base 3D |
| Nov | T3 oficinas + T4 robot |
| Dic (1ª quincena) | T5 integración + T6 ensayo |
| Dic (2ª quincena) | Showcase final + vídeo + acta 2027 |

Si un taller flojea de asistencia, se fusiona con el siguiente sin romper la cadena: cada sesión es autocontenida.

---

## Qué se presenta en el Showcase

- Recorrido: del mapa 2D actual al Polo 3D navegable.
- Robot 3D prototipo saludando y guiando a 2-3 zonas.
- Créditos de todos los voluntarios + empresas.
- Vídeo de 1-2 min del proceso (talleres, cartulinas, demos).
- Propuesta 2027: qué faltaría para un asistente/robot real (casos, datos, hardware).

---

## Métricas simples

- Voluntarios reclutados / que repiten 3+ talleres.
- Piezas integradas por taller.
- Zonas del Polo reconocibles en 3D.
- Tareas completadas sin ayuda en táctil.
- Colaboraciones entre empresas nacidas en talleres.

---

## Próximo paso

Reunión de 30 min con Paula para fijar Jornada 0, canal (grupo + repo), y validar el programa de talleres. En una semana, convocatoria lista.

**Kreatures Studio — Polo Nacional de Contenidos Digitales, Málaga**
