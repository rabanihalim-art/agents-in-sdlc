---
title: "Lección 2 - Añadir valoraciones con estrellas: una mejora rápida"
description: "Usa Copilot CLI para hacer un cambio pequeño en las tarjetas de juegos, revisarlo en un navegador reenviado y combinarlo como tu primera solicitud de incorporación de cambios."
authors:
  - geektrainer
lastUpdated: 2026-09-18
---

Ahora que has instalado Copilot CLI, realiza tu primer cambio en el proyecto. Pide al agente que muestre en las tarjetas la valoración que ya existe en los datos.

## Escenario

Cada juego de Tailspin Toys puede tener una valoración con estrellas. En esta lección mostrarás la valoración existente en cada tarjeta y mantendrás el cambio aislado.

## Iniciar una conversación y solicitar el cambio

1. Vuelve a tu Codespace.
2. Inicia Copilot con `copilot --yolo`.
3. Usa `/new` y pide que muestre `starRating` sobre cinco; cuando sea `null`, debe mostrar `No rating yet`.
4. Revisa los cambios con `/diff`, ejecuta las comprobaciones y abre la solicitud de incorporación de cambios con `/pr create`.

## Resumen y próximos pasos

Has enviado tu primer cambio con GitHub Copilot CLI. A continuación, [trabaja con los modos Plan y Autopilot][next-lesson].

[next-lesson]: ../3-agent-modes/
