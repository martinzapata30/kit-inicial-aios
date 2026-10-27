# Registro de conexiones

Este es el registro de todos los sistemas que tu AIOS puede alcanzar. Cada fila es un dominio clave de tu negocio. La skill de onboarding lo llena con tus respuestas P4-P7. La skill de auditoría revisa qué tan al día está.

| # | Dominio | Herramienta | Mecanismo | Auth | Última revisión |
|---|---------|-------------|-----------|------|-----------------|
| 1 | Ingresos / Finanzas |: |: |: | sin conectar |
| 2 | Clientes |: |: |: | sin conectar |
| 3 | Calendario |: |: |: | sin conectar |
| 4 | Comunicación |: |: |: | sin conectar |
| 5 | Tareas / Proyectos |: |: |: | sin conectar |
| 6 | Reuniones |: |: |: | sin conectar |
| 7 | Conocimiento / Archivos |: |: |: | sin conectar |

## Mecanismos de conexión

- `mcp`: un servidor MCP (la forma más simple y sin código)
- `script`: llamadas a una API con Python o Bash
- `export`: descargas o volcados de datos
- `key+ref`: una clave de API guardada de forma segura + su guía de uso

Cuando conectes una herramienta nueva, guarda su guía de API en `referencias/` (endpoints, cómo se autentica, las consultas típicas). Así no la vuelves a investigar, y tus skills futuras la reusan.

## Sobre las claves (importante)

La forma más simple de conectar (un conector MCP) no necesita claves. Pero si conectas algo con un script, te va a pedir una clave de API. Esa clave va SIEMPRE en un archivo `.env`, nunca dentro de otro archivo ni pegada en el chat.

Este kit ya trae un `.gitignore` que excluye el `.env` y cualquier credencial. Así, si compartes tu kit o lo subes a GitHub, tus claves no se van con él. Regla de oro: tu `.env` no se comparte con nadie.
