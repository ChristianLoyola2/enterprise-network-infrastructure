# Segmentación mediante VLANs

## Objetivo

Implementar segmentación lógica de la red para separar diferentes áreas de una infraestructura empresarial y mejorar el control del tráfico.

## VLANs implementadas

| VLAN | Área | Red |
|---|---|---|
| 10 | Administración | 192.168.10.0/24 |
| 20 | Ventas | 192.168.20.0/24 |
| 30 | Logística | 192.168.30.0/24 |
| 40 | Servidores | 192.168.40.0/24 |
| 50 | WiFi | 192.168.50.0/24 |
| 99 | Management | 192.168.99.0/24 |

## Beneficios

La segmentación permite:

- Separar dominios de broadcast.
- Organizar los dispositivos por función.
- Controlar el tráfico entre segmentos.
- Facilitar la aplicación de ACLs.
- Mejorar la administración de la infraestructura.
- Reducir el impacto potencial de incidentes.

## Trunking

Los enlaces entre dispositivos de red utilizan trunking 802.1Q para transportar tráfico de múltiples VLANs.

## Inter-VLAN Routing

El routing entre VLANs se realiza mediante el dispositivo de capa 3 de la arquitectura, permitiendo comunicación controlada entre diferentes segmentos.

## Seguridad

La segmentación se complementa con ACLs y controles de acceso para restringir comunicaciones que no sean necesarias entre determinados segmentos.

## Validación

La implementación fue validada mediante pruebas de:

- Creación de VLANs.
- Asignación de puertos.
- Trunking.
- Comunicación entre dispositivos.
- Routing inter-VLAN.
- Restricción de tráfico mediante ACLs.

## Entorno

Proyecto desarrollado en Cisco Packet Tracer con fines educativos y de práctica profesional.
