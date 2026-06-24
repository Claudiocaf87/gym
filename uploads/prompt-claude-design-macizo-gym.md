# PROMPT PARA CLAUDE DESIGN — MACIZO GYM

> Copia todo el bloque de abajo (desde "Quiero que construyas..." hasta el final) y pégalo en Claude Design en un solo mensaje, junto con el archivo del logo (macizo_gym.png) adjunto.

---

```
Quiero que construyas una landing page premium, de una sola página, para un gimnasio real llamado MACIZO GYM, ubicado en Neuquén, Argentina. Hazlo todo en un solo pase — no me preguntes 20 cosas, toma decisiones de diseño con criterio profesional y ejecuta.

## CONTEXTO DE MARCA

Macizo Gym es un gimnasio de musculación y pesas tradicional, de personalidad HARDCORE y AGRESIVA — culture de powerlifting, fuerza bruta, disciplina, sin pretensiones boutique ni wellness suave. El target es gente que entrena en serio: powerlifters, culturistas amateurs, gente que quiere ponerse "macizo" de verdad. El tono de voz es directo, motivacional pero sin ser cursi, con actitud — frases cortas, imperativos, cero relleno corporativo.

Adjunto el logo oficial (macizo_gym.png): un círculo negro con una mancuerna ilustrada en blanco sobre un disco verde lima, y el wordmark "MACIZO" en blanco itálico condensado bold + "GYM" en verde lima debajo. Usa este logo en el navbar y también quiero que generes/recortes una versión simplificada de él como favicon.

## DESIGN SYSTEM (derivado del logo, respetalo estrictamente)

**Paleta (hex exactos):**
- Negro base: #111111 (fondos, secciones principales)
- Verde lima (acento, SOLO para detalles, CTAs, resaltados — nunca como color de fondo grande): #DCFF31
- Blanco: #FFFFFF (texto principal sobre negro, fondos de secciones claras alternadas)
- Gris carbón (neutro de apoyo, para cards y separación sutil sobre negro): #1C1C1C
- Gris piedra (neutro claro, para texto secundario sobre blanco): #6B6B6B

**Tipografía:**
- Display/headlines: una tipografía ultra-condensada, bold, tipo industrial/stencil — usa "Anton" o "Oswald" (peso 700-900) de Google Fonts. Debe sentirse grabada, pesada, como tipografía de gimnasio de barrio real, no corporativa. Úsala en mayúsculas para headlines grandes, con tracking ligeramente ajustado (negativo) para que se sienta compacta y agresiva.
- Body/texto: "Inter" para legibilidad — pesos 400 y 600. Nunca compite con el display, es utilitaria.
- Caption/data (números de stats, horarios, precios pequeños): "Oswald" peso 500, con letter-spacing amplio en labels tipo eyebrow.

**Estética general:** Editorial de gimnasio hardcore en blanco y negro de alto contraste, con el verde lima como único color que "rompe" — úsalo con disciplina, no lo repitas en cada sección o pierde impacto. Texturas sutiles de fondo permitidas: chapa metálica rayada, textura de concreto, grano fino tipo film. Nada de gradientes suaves estilo SaaS, nada de ilustraciones tipo clip-art, nada de esquinas redondeadas exageradas (usa esquinas vivas o redondeo mínimo de 4-6px máximo, coherente con la actitud industrial de la marca). Fotografía: alto contraste, blanco y negro o duotono negro/verde lima, gente entrenando en serio (no sonrisas de stock) — usa placeholders descriptivos donde corresponda imagen real.

**Signature element (el elemento que hace memorable esta página):** un contador animado tipo "marcador de gimnasio" en el hero o cerca del hero, mostrando algo como "KILOS LEVANTADOS HOY POR LA COMUNIDAD MACIZO" con un número que cuenta hacia arriba al cargar la página (animación de conteo, formato con separador de miles), como si fuera el scoreboard de una competencia de powerlifting. Esto refuerza la identidad hardcore sin caer en cliché de stat gen��rica de SaaS.

## ESTRUCTURA DE SECCIONES (de arriba a abajo)

1. **Navbar** — fijo, fondo negro con blur sutil al hacer scroll. Logo a la izquierda, links de navegación al centro/derecha (Inicio, Planes, Servicios, Horarios, Contacto), botón CTA "RESERVAR CLASE" en verde lima a la derecha. En mobile, menú hamburguesa.

2. **Hero** — Full viewport height. Headline gigante en la tipografía display: algo como "ACÁ NO SE VIENE A MIRAR." o similar línea de impacto que vos refines, con subtexto corto debajo explicando qué es Macizo Gym (musculación, Neuquén, comunidad hardcore). Dos CTAs: uno principal "QUIERO ENTRENAR" (verde lima, lleva a la sección de planes) y uno secundario "VER HORARIOS" (outline blanco). Fondo con imagen de alto contraste (placeholder de alguien levantando pesas pesadas, blanco y negro) y overlay oscuro para legibilidad del texto. Incluye el signature element (contador animado) integrado de forma elegante en este bloque o inmediatamente después.

3. **Sección Problema/Posicionamiento** — 2-3 líneas editoriales cortas, tipo manifiesto, sobre por qué Macizo Gym es distinto (no es un gimnasio de cadena genérico, es para gente que entrena en serio). Tipografía grande, mucho espacio en blanco (negro en este caso), centrado.

4. **Sección Solución / Por qué Macizo** — 3 beneficios clave en cards o columnas: ej. Equipamiento de powerlifting real (barras olímpicas, racks, plataformas), Comunidad/coaching de entrenadores certificados, Horario extendido sin esperas. Cada uno con ícono simple (línea, no emoji) + título corto + 1 línea de descripción.

5. **Sección Servicios** — grid de servicios: Musculación libre, Zona de pesas olímpicas/powerlifting, Entrenamiento personalizado, Clases grupales (funcional), Nutrición y seguimiento, Vestuarios y duchas. Cards con fondo gris carbón sobre negro, hover con borde verde lima.

6. **Sección Planes y Precios** — 3 planes en cards comparativas: Plan Básico, Plan Macizo (destacado/recomendado, con badge verde lima), Plan Elite. Cada uno con precio en pesos argentinos, lista de qué incluye, y botón CTA. El plan del medio debe destacarse visualmente (borde verde lima, ligeramente más grande o elevado).

7. **Sección Horarios** — tabla o grid limpio con horarios de lunes a sábado, mañana/tarde/noche, y horarios de clases grupales específicas (ej: Powerlifting Class, Funcional). Diseño tipo "pizarra de gimnasio" — clara, escaneable.

8. **Sección Reservar Turno/Clase** — formulario funcional (con estado de React, sin backend real) donde el usuario elige: tipo de clase/actividad (dropdown), día (dropdown o date picker simple), horario (dropdown que depende del día elegido), nombre y teléfono. Al enviar, muestra un mensaje de confirmación in-page (no alert del navegador) tipo "¡Turno reservado! Te contactamos por WhatsApp para confirmar." Debe sentirse real y pulido, parte central de la conversión de la página.

9. **Sección Testimonios** — 3 testimonios placeholder de socios reales del gimnasio (nombre, antes/después o logro específico tipo "bajé 12kg y subí mi sentadilla a 140kg en 8 meses"), formato cards o carousel simple.

10. **Sección Ubicación/Contacto** — dirección inventada coherente en Neuquén capital (ej. una calle real de la zona céntrica o Parque Industrial), mapa placeholder o embed simple, teléfono, horario de atención, y los íconos de redes sociales.

11. **Footer** — logo, links rápidos, datos de contacto, redes sociales, copyright. Fondo negro puro, separador sutil verde lima como línea superior del footer.

**Botón flotante de WhatsApp:** fijo en la esquina inferior derecha, visible en todo momento durante el scroll, ícono de WhatsApp reconocible, color verde lima de fondo (no el verde tradicional de WhatsApp, para mantener coherencia de marca) con ícono blanco o negro según contraste. Al hacer click/tap, debe abrir un link tipo wa.me con un mensaje predefinido tipo "Hola! Quiero información sobre Macizo Gym".

## CONTENIDO A INVENTAR (coherente con todo lo anterior)

- **Dirección:** Av. Argentina 1450, Neuquén Capital, Neuquén (zona céntrica/Parque Industrial, a elección)
- **Horarios:** Lunes a viernes 6:00-23:00, sábados 8:00-20:00, domingos cerrado
- **Teléfono/WhatsApp:** +54 9 299 456-7890 (formato Neuquén)
- **Planes:** 
  - Básico: acceso a sala de musculación, horario diurno — ~$15.000/mes
  - Macizo (destacado): acceso full horario + 2 clases grupales/semana + evaluación inicial — ~$22.000/mes
  - Elite: todo lo anterior + entrenador personal 2x/semana + plan nutricional — ~$38.000/mes
- **Clases grupales:** Powerlifting Class (técnica de sentadilla/banca/peso muerto), Funcional Macizo, Movilidad y Recuperación
- Usa estos como punto de partida pero ajusta si encontrás algo más coherente con el resto del copy que generes.

## ESPECIFICACIONES TÉCNICAS

- **Mobile-first y completamente responsive** — probá mentalmente el layout en 375px de ancho antes de dar por terminada cada sección.
- **Animaciones:** fade-in + slight translate-Y al hacer scroll en cada sección (scroll reveal sutil, no exagerado), hover states claros en botones y cards (transform + glow sutil en verde lima), el contador animado del hero debe ejecutarse una sola vez al cargar.
- **Performance:** nada de imágenes pesadas sin optimizar, usa gradientes/CSS donde sea posible en vez de imágenes para texturas si no hay imagen real disponible.
- **Accesibilidad:** contraste de texto AA mínimo en todas las combinaciones de color, focus states visibles en todos los elementos interactivos, formulario de reserva con labels reales (no solo placeholder).
- **SEO básico:** estructura semántica de HTML (header, nav, main, section, footer), un solo h1 en el hero, jerarquía de headings lógica.
- **Favicon:** generá una versión recortada/simplificada del logo adjunto que funcione reconocible en 32x32px.

Quiero efecto WOW — esta landing va a ser usada como pieza de muestra para ofrecer a otros dueños de gimnasios, así que el nivel de pulido y la sensación de "esto es premium" importan mucho. Priorizá que el hero y el signature element (contador animado) generen impacto inmediato en los primeros 3 segundos.
```

---

## NOTAS DE EJECUCIÓN

- **Antes de pegar el prompt:** adjuntá el archivo `macizo_gym.png` en el mismo mensaje donde pegás este prompt — Claude Design lo necesita para extraer la tipografía del wordmark y usarlo en el navbar/favicon.
- **Si el resultado no te convence del todo en el primer pase:** no reescribas el prompt entero — pedí ajustes puntuales sobre el canvas ya generado (ej. "hacé el hero más alto", "el verde está sobreusado en la sección de servicios, bajalo a solo el borde en hover"). Es más rápido y consume menos que regenerar de cero.
- **Sobre el contador animado (signature element):** si Claude Design lo hace muy genérico tipo "stat de SaaS", pedile explícitamente que lo rediseñe como "scoreboard de gimnasio/competencia de powerlifting" con referencia visual a marcadores de placas/LED.
- **Sobre las fotos:** como no tenés fotos reales del gimnasio todavía, esta versión va a usar placeholders descriptivos o imágenes de stock de alto contraste B&N. Cuando tengas fotos reales del local, es la primera sección que conviene reemplazar — sube el nivel de "esto es real" inmediatamente.
- **Botón de WhatsApp:** el número inventado (+54 9 299 456-7890) hay que reemplazarlo por el real antes de usar esto con un cliente de verdad — point that out cuando muestres esto como demo.
