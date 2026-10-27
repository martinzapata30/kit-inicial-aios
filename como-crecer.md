# Cómo crecer: qué agregar con el tiempo

El kit viene liviano a propósito. Tres skills, seis carpetas, un framework. Eso es todo. A medida que lo uses, lo vas a superar. Esta guía te dice qué agregar, cuándo y por qué.

Tu AIOS debe verse como un negocio chico bien llevado. No como el sótano de alguien que acumula todo.

---

## Lo que viene en el kit (no lo quites)

| Carpeta / archivo | Para qué |
|---|---|
| `contexto/` | Sobre ti, tu negocio, tus prioridades. Lo llena el onboarding. |
| `referencias/` | Frameworks, tu voz, guías de APIs, procesos que documentes. |
| `decisiones/log.md` | Registro de qué se decidió y por qué. |
| `archivos/` | Lo viejo. No borres, mueve aquí. |
| `conexiones.md` | Registro de cada sistema que tu AIOS alcanza. |
| `.claude/skills/` | Tus skills: onboarding, auditoría, subir-nivel. Agregas más con subir-nivel. |
| `cuestionario-aios.md` | La fuente del onboarding. Edita y vuelve a correrlo cuando quieras. |
| `CLAUDE.md` | El manual raíz. Lo llena el onboarding. Edítalo cuando cambie tu rol o tu voz. |

---

## Qué agregar a medida que creces

| Carpeta / archivo | Agrégalo cuando | Por qué |
|---|---|---|
| `proyectos/` | Tengas 2+ frentes activos con su propio contexto | Cada proyecto activo necesita contexto propio, aparte del contexto evergreen |
| `plantillas/` | Te descubras copiando y pegando los mismos prompts o documentos | Puntos de partida reusables; menos improvisación |
| `marca/` | Generes contenido visual (carruseles, slides, miniaturas) | Centraliza logos, colores, fuentes, tono. La IA los toma en vez de adivinar |
| `referencias/procesos/` | Documentes cómo corre un proceso recurrente | Procesos estándar que la IA lee para hacer las cosas igual siempre |
| `referencias/{herramienta}-api.md` | Conectes una API o MCP nuevo | Lo investigas una vez y queda guardado. La auditoría premia esto |
| `scripts/` | Escribas Python o Bash para APIs que no cubre un MCP | La segunda conexión de casi todos es un script, no un MCP |
| `.claude/agents/` | Necesites un sub-asistente para investigación o escritura repetitiva | Los agentes corren en su propio contexto y mantienen tu sesión principal liviana |

---

## Qué NO agregar

Trampas que parecen útiles pero pudren la estructura:

- **No vuelques correos o chats en bruto en `referencias/`.** Solo hechos interpretados, no volcados de documentos.
- **No armes carpetas dentro de carpetas para "organizar".** Plano y bien nombrado le gana al anidamiento profundo.
- **No agregues `notas/`, `varios/`, `tmp/` ni `inbox/`.** Son cementerios. Si es viejo, va a `archivos/`. Si es nuevo, escribe un archivo real en el lugar correcto.
- **No crees carpetas que todavía no necesitas.** Las carpetas vacías son ruido.
- **No tengas dos registros de decisiones.** Solo `decisiones/log.md`.
- **No dupliques tu manual.** Un solo `CLAUDE.md` en la raíz.

---

## Cómo saber si es hora de agregar una carpeta

Tres preguntas:

1. ¿Es algo conceptualmente nuevo, o cabe en algo que ya existe?
2. ¿Lo voy a tocar 3+ veces el próximo mes? Si no, es prematuro.
3. ¿La skill de subir-nivel podría usar esta carpeta de forma natural?

Dos "sí" = agrégalo. Un "sí" = espera.

> Tu AIOS debe verse como un negocio chico bien llevado. Cuando no encuentras algo, esa es la señal para consolidar, no para agregar otra carpeta.
