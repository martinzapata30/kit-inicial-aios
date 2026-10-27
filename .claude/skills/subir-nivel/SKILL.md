---
name: subir-nivel
description: Entrevista semanal con el framework de las 3 M para encontrar y armar UNA automatización por corrida. Úsala cuando alguien diga "subamos de nivel", "qué automatizo esta semana", "encuentra una automatización" o "ayúdame a mejorar mi AIOS". Primera corrida el Día 14, luego cada semana.
---

# Subir de nivel: una automatización por semana

Conduces una entrevista semanal usando las 3 M para sacar a la luz y armar **una sola** automatización por corrida. Lee `referencias/framework-3-m.md` antes de empezar.

## Las 3 fases (en orden)

**1. Mentalidad**: entrevista corta para sacar 1-3 candidatos, ordenados por impacto en el negocio.

**2. Método**: toma el candidato elegido y defínelo con:
- **EAD**: ¿se puede Eliminar? Si parar la tarea no rompe nada, terminas aquí, eso es una victoria. Si no, ¿Automatizar o Delegar?
- Los 5 elementos del proceso: disparador, fuentes de datos, transformaciones, ramas de decisión, destino.
- Nivel de autonomía: por default el más bajo que funcione (manual > sugerido > borrador > supervisado > autónomo). Para subir de nivel, que la persona lo pida explícito.
- KPI: la automatización tiene que mover uno de tres frentes: más clientes, más valor por cliente, o menos costo.

**3. Máquina**: arma el artefacto (un prompt, una skill o un agente) al nivel de autonomía más bajo que sirva.

## Reglas

- **Una corrida = un artefacto.** Nada de planear varios candidatos en paralelo.
- **Eliminar primero.** Si parar la tarea no rompe nada, la skill termina ahí. Eso es ganar.
- **Default a la menor autonomía.** La persona tiene que pedir explícito subir el nivel.
- **Atado a impacto medible.** Si no mueve más clientes, más valor o menos costo, no se hace.

## Salida

Cada corrida:
- Registra una entrada con fecha en `decisiones/log.md` con el spec completo del Método.
- Arma un artefacto (prompt, skill o agente).
- Lo entrega en fase 1 del Método de la bici (observación manual antes de soltarlo solo).

## Cuándo correrla

Primera vez el Día 14 (después de al menos 1 conexión y de correr la auditoría). Luego, los viernes por la tarde, con corridas a mitad de semana si aparece fricción manual.

> *Adaptado de The Three Ms of AI™ © 2026 Nate Herk.*
