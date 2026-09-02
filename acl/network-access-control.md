# Control de acceso mediante ACL

## Objetivo

Implementar Access Control Lists (ACLs) para controlar el tráfico entre diferentes segmentos de la infraestructura.

## Aplicación

Las ACLs permiten definir qué tráfico puede ser permitido o denegado según:

- Red origen
- Red destino
- Protocolo
- Dirección
- Servicio

## Seguridad

Las ACLs complementan la segmentación mediante VLANs y permiten aplicar políticas de comunicación entre departamentos, servidores y otros segmentos.

## Proceso

```text
Tráfico
   ↓
Evaluación de ACL
   ↓
¿Permitido?
 ┌──┴──┐
Sí     No
↓       ↓
Forward  Deny
