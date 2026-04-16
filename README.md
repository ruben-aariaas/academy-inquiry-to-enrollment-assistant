# Academy Inquiry-to-Enrollment Assistant

## Resumen
Academy Inquiry-to-Enrollment Assistant es un sistema de automatización con IA orientado a academias y centros formativos.

Su objetivo es gestionar la primera capa de consultas comerciales y operativas: entender qué quiere la persona, detectar qué falta, priorizar la oportunidad, proponer el siguiente paso y generar un borrador de respuesta útil.

El sistema está pensado para reducir trabajo manual, acelerar la respuesta y mejorar la conversión de consultas en matrículas, clases de prueba o contactos útiles.

---

## Problema de negocio
Las academias suelen recibir muchas consultas repetidas o incompletas sobre:
- precios
- horarios
- disponibilidad
- clases de prueba
- matrícula
- seguimiento
- incidencias de alumnos actuales

Estas consultas suelen llegar mezcladas y requieren:
- leer el mensaje
- entender qué quiere la persona
- pedir datos faltantes
- decidir si es una oportunidad real
- responder o derivar

Eso genera:
- tiempo perdido
- lentitud de respuesta
- oportunidades que se enfrían
- falta de seguimiento
- desorden comercial y operativo

---

## Solución
Este proyecto automatiza la primera gestión de consultas de academia.

El sistema:
- recibe una consulta
- la clasifica por tipo
- detecta datos faltantes
- calcula score de oportunidad
- asigna prioridad
- genera un resumen
- propone la siguiente acción
- genera un borrador de respuesta
- guarda el resultado con trazabilidad

---

## Vertical objetivo
Academias, centros formativos y negocios educativos que reciben consultas sobre cursos, horarios, precios, pruebas y matrícula.

---

## Tipos de consulta que maneja
- informacion_general
- precios
- horarios
- disponibilidad
- clase_prueba
- matricula
- seguimiento
- soporte_alumno_actual
- ruido_o_spam

---

## Outputs principales
- tipo_consulta
- prioridad
- score_oportunidad
- datos_faltantes
- resumen
- siguiente_accion
- borrador_respuesta
- estado
- human_review_required

---

## Valor que aporta
- menos trabajo manual
- menos ida y vuelta innecesaria
- mejor priorización
- más rapidez en la respuesta
- más orden en la entrada comercial
- mejor base para convertir una consulta en matrícula o clase de prueba

---

## Modos del sistema

### Modo evaluación
Usa un dataset de prueba para medir:
- tipo de consulta detectado
- score
- prioridad
- datos faltantes
- y comportamiento del sistema

### Modo real
Usa un webhook para recibir consultas reales y generar una salida operativa.

---

## Stack previsto
- n8n
- OpenAI API
- JavaScript
- Webhooks
- Google Sheets

---

## Arquitectura documental del proyecto
- `architecture.md`
- `dataset_test.md`
- `system_logic.md`
- `technical_flow_v1.md`

---

## Qué demuestra este proyecto
- pensamiento orientado a negocio
- diseño de automatizaciones con IA
- priorización comercial
- detección de datos faltantes
- generación de siguiente acción
- diseño de flujos medibles y vendibles

---

## Limitaciones de la v1
- no debe inventar precios
- no debe inventar disponibilidad
- no debe cerrar matrículas automáticamente
- debe marcar revisión humana cuando haya ambigüedad
- todavía no integra calendario real ni tabla de precios

---

## Mejoras futuras
- integración con calendario
- integración con precios/cursos
- deduplicación
- seguimiento automático
- segmentación por tipo de academia
- analítica de consultas
- confianza del modelo

---

## Enfoque comercial
No es un chatbot genérico.

Es una solución de preventa y gestión inicial de consultas que ayuda a una academia a responder mejor, pedir menos veces la misma información y no perder oportunidades por lentitud o desorden.

---

## Frase resumen
Convierte consultas desordenadas en oportunidades claras, priorizadas y listas para avanzar.
