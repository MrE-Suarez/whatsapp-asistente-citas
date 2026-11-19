# whatsapp-asistente-citas

Asistente de WhatsApp con n8n + WhatsApp Cloud API (oficial) + IA que entiende texto libre, agenda citas en Google Calendar y guarda prospectos en Google Sheets.

## Estado
- [x] Entorno local: Node.js 24 + n8n
- [ ] Cloud API: app de Meta y número de prueba
- [ ] n8n recibe y contesta un mensaje
- [ ] IA calificadora (giro, ciudad, volumen)
- [ ] Agenda en Google Calendar
- [ ] Demo 24/7 en servidor
- [ ] Caso real 1: pestañista
- [ ] Caso real 2: uñas

## Arquitectura
_(diagrama pendiente)_

## Decisiones
| Fecha | Decisión | Por qué |
| --- | --- | --- |
| 2026-11-19 | Ir directo al Nivel 2 (asistente con IA) | El Nivel 1 (menú y catálogo) lo puede hacer cualquiera con un tutorial |
| 2026-11-19 | Solo la API oficial de Meta | Los conectores no oficiales pueden provocar el bloqueo del número |
| 2026-11-19 | Desarrollar con el número de prueba de Meta | No exponer el número personal; costo $0 |
| 2026-11-19 | Node.js 24 LTS | n8n soporta Node 20.19–24.x |

## Métricas (casos reales)
_(desde enero: mensajes resueltos solos, citas agendadas, faltas)_
