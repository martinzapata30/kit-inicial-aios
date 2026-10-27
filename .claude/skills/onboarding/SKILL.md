---
name: onboarding
description: Asistente de setup del Día 1 del AIOS. Entrevista de 7 preguntas que arma los archivos de contexto del usuario. Úsala la primera vez que alguien abre su starter kit, o cuando diga "hagamos el onboarding", "configura mi AIOS" o "empecemos". Se puede volver a correr después de editar cuestionario-aios.md.
---

# Onboarding: Día 1 de tu AIOS

Entrevistas al dueño del AIOS con preguntas cortas y, con sus respuestas, armas su set de archivos del Día 1. Al terminar, su IA va a saber quién es y va a responder como alguien que lo conoce. Es idempotente: se puede volver a correr cuando edite `cuestionario-aios.md`.

## Paso 1: Revisa el cuestionario

Lee `cuestionario-aios.md`. Decide:
- Si está todo lleno → confirma y salta a armar los archivos.
- Si está a medias → pregunta solo lo que falta.
- Si está vacío (clon nuevo) → corre la entrevista completa.

## Paso 2: La entrevista (tope 7 preguntas)

**Regla de oro: una pregunta a la vez.** Nunca dispares todas juntas. Pregunta, espera la respuesta, y solo entonces sigue. La persona puede no ser técnica, mantenlo simple y cálido.

Antes de empezar, dile:

> "Te voy a hacer 7 preguntas cortas para conocerte. No hay respuestas malas. Si te cuesta escribir, dicta por voz, yo lo ordeno. Empecemos."

Las 7 preguntas (en este orden), tomadas de `cuestionario-aios.md`:

1. ¿Quién eres, qué vendes y a quién se lo vendes?
2. Pega 1 o 2 cosas que hayas escrito hace poco, sin editarlas.
3. ¿Tus 2-3 prioridades de los próximos 90 días?
4. ¿Dónde entra el dinero y dónde lo registras?
5. ¿Dónde hablas con clientes, equipo y el mundo, día a día?
6. ¿Dónde viven las grabaciones, notas y documentos importantes?
7. ¿Qué tarea se come tu semana, y dónde registras el trabajo?

**Sobre la P2 (la voz):** si la persona intenta escribir una muestra en el momento en vez de pegar algo que ya escribió, recuérdale que pegue texto real. Un texto hecho para el chat ensucia su voz. Si no tiene nada a mano, sigue sin muestra antes que con una falsa.

## Paso 3: Arma los archivos

Con las respuestas, escribe (ordenando y limpiando, no copiando en bruto):

- `contexto/sobre-mi.md` y `contexto/sobre-el-negocio.md` (de la P1)
- `contexto/prioridades.md` (de la P3, lista numerada, con la fecha de hoy)
- `referencias/voz.md` (las muestras de la P2, pegadas tal cual)
- `conexiones.md` (llena las 7 filas con lo de la P4-P7)
- `CLAUDE.md` (reemplaza los `{{...}}` con los datos reales)

Antes de sobrescribir, guarda una copia de respaldo de los archivos en `archivos/intake-{fecha}/`.

## Paso 4: El cierre (importante)

Cuando termines, dile:

> "Listo. Ya sé quién eres y de qué va tu negocio. Para probarlo, abre una conversación nueva y pregúntame: '¿En qué me debería enfocar esta semana?'. Vas a ver que ahora te respondo como alguien que te conoce. Ese es tu primer pilar funcionando: el Contexto."

No expliques de más. La persona tiene que **sentir** la diferencia en la siguiente conversación.

## Reglas

- El tope de 7 preguntas no se negocia.
- Una pregunta a la vez, siempre.
- No pidas claves de API en el Día 1.
- No edites los archivos del framework que vienen en el kit (solo los de contexto del usuario).
