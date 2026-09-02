# Redundancia y Spanning Tree

## EtherChannel

EtherChannel permite agrupar múltiples enlaces físicos en un enlace lógico.

### Objetivos

- Aumentar capacidad.
- Proporcionar redundancia.
- Mejorar disponibilidad.
- Utilizar múltiples enlaces como una unidad lógica.

## STP

Spanning Tree Protocol se utiliza para prevenir bucles de capa 2.

El diseño utiliza **Rapid PVST** para proporcionar una convergencia más rápida que STP tradicional.

## Funciones de seguridad y disponibilidad

La combinación de EtherChannel y STP permite:

```text
Múltiples enlaces
      ↓
EtherChannel
      ↓
Redundancia
      ↓
STP / Rapid PVST
      ↓
Prevención de loops
