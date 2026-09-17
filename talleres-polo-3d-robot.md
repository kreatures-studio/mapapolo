# Talleres Polo 3D + Robot
### 6 talleres de ejecución (nada de charlas) + Jornada 0 + Showcase

**Duración:** 2 h por taller · **Frecuencia:** semanal o quincenal · **Lugar:** Polo (Ágora o sala con pantalla) · **Material:** portátil propio, móvil para fotos, cuenta de GitHub (la creamos allí si hace falta).

**Mentores Kreatures por mesa:** producción, Unity/IA, 3D eventos, 2D/3D, lighting/TA.

---

## T0 — Jornada 0: reclutamiento (2 h)
- Demo mapa + visión 3D/robot (15 min).
- Mesas por oficio con cartulina (30 min).
- Ronda “ofrezco / busco / aprendo” 1 min por persona.
- Fichas de voluntariado + calendario + tarea: 1 foto y 1 medida de tu zona.
- **Salida:** 10-20 voluntarios con rol + backlog inicial.

## T1 — Levantamiento del Polo (2 h)
- **Objetivo:** salir con referencias suficientes para modelar sin volver a medir.
- 10 min: cómo medir (metro/láser/app), fotos (ortogonales + detalle), nomenclatura de archivos.
- 70 min: equipos por zona (fachada, planta baja, OF1-6, ágoras, patios, coworkings). Fotos + medidas + notas de materiales/colores.
- 30 min: volcado al repo (`/refs`), checklist de huecos.
- 10 min: demo — galería de referencias ordenada.
- **Salida:** pack `/refs` + lista de bloques a modelar. **Mentor principal:** artista 3D eventos.

## T2 — Base 3D navegable (2 h)
- **Objetivo:** escena web que carga con el volumen del edificio y planta baja transitable.
- Mesas: bloque exterior, suelo/muros planta baja, cámaras + controles (orbitar/pan/zoom + presets táctil).
- Criterio: 60 fps en portátil medio, carga < 5 s en local.
- **Salida:** `polo-3d-base` navegable en web. **Mentor:** programador Unity + lighting/TA.

## T3 — Oficinas y espacios reconocibles (2 h)
- **Objetivo:** que un habitante reconozca su zona.
- Mesas por paquetes: OF1-OF2, OF3-OF4, OF5-OF6, ágoras+patios, coworkings+comunes.
- Low-poly + texturas simples + cartel de cada zona (nombre real del mapa 2D).
- **Salida:** 6+ zonas identificables con cartel. **Mentores:** 2D/3D + concept.

## T4 — Robot 3D prototipo (2 h)
- **Objetivo:** robot simpático dentro de la escena, no un robot real.
- Mesa modelado: cuerpo CAD low-poly con seña del Polo (color/visor).
- Mesa rig/anim: idle (respiración), saludo (giro + brazo), “guíame” (apunta).
- Mesa voz/texto (acotado): 5 frases + 3 respuestas a preguntas fijas (“¿dónde está OF3?”, “¿quién hace videojuegos?”).
- **Salida:** robot colocado en hall que saluda y apunta. **Mentores:** 3D + Unity/IA + sonido.

## T5 — Conexión mapa 2D ↔ 3D (2 h)
- **Objetivo:** clic en el plano 2D localiza en 3D y viceversa.
- Mesas: eventos cruzados, resaltado de zona, tooltip compartido, modo táctil (botones grandes).
- Prueba cruzada: cada grupo testea el trabajo de otro sin ayuda.
- **Salida:** demo integrada web + táctil. **Mentor:** programador + TA.

## T6 — Ensayo general + fixes (2 h)
- **Objetivo:** versión candidata al Showcase sin vergüenzas.
- 60 min: lista de bugs críticos (top 10) y fixes en vivo por mesas.
- 30 min: ensayo de la demo con guion y tiempos.
- 30 min: grabación de clips para el vídeo final + repaso de créditos.
- **Salida:** candidata + guion del Showcase. **Todos los mentores.**

## Showcase final (2 h, otra fecha)
- Demo en pantalla grande + táctil de entrada.
- Recorrido 2D → 3D → robot guía → casos 2027.
- Créditos, fotos, vídeo 1-2 min, acta de mantenimiento y propuesta robot real.

---

## Normas de taller (1 página, se lee en voz alta en T0)
1. Llegar a hacer, no a escuchar. 10 min de contexto y a producir.
2. Pieza pequeña y terminada mejor que grande a medias.
3. Todo va al repo con nombre claro; nada se queda en un USB.
4. Se acepta revisión de mentores; `main` no se rompe.
5. Si faltas, avisas y dejas tu pieza documentada.
6. Lo altruista no quita lo serio: fecha y criterio de terminado por pieza.
