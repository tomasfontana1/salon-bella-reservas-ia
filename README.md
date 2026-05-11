# Salón Bella - Reservas con Asistente IA

## Descripción

MVP académico desarrollado en Henry para gestionar reservas automáticas de un salón de belleza mediante formulario web, asistente IA, base de datos y automatizaciones.

El proyecto permite recibir solicitudes de turnos, validar disponibilidad, registrar citas y enviar confirmaciones automáticas, reduciendo tareas manuales y mejorando la experiencia del cliente.

## Problema

Muchos negocios de servicios gestionan reservas de forma manual por WhatsApp, llamadas o planillas, lo que puede generar errores, pérdida de información, demoras en la confirmación y mala organización operativa.

## Solución

Se diseñó una solución integrada con Lovable, Supabase y n8n para centralizar la gestión de reservas y automatizar el proceso desde la solicitud del cliente hasta la confirmación del turno.

## Funcionalidades principales

- Formulario web para solicitar reservas.
- Asistente IA para interpretar consultas de clientes.
- Validación de datos del cliente, servicio, fecha y horario.
- Registro de clientes, servicios y citas en Supabase.
- Automatización de confirmaciones mediante n8n.
- Recordatorios automáticos de turnos.
- Gestión de citas: cancelar, reprogramar o completar.

## Stack utilizado

- Lovable
- Supabase
- n8n
- APIs REST
- Webhooks
- Gmail
- SQL básico
- No-Code / Low-Code
- AI Automation

## Arquitectura general

1. El cliente solicita una reserva desde el formulario o asistente IA.
2. Lovable envía la información mediante webhook.
3. n8n valida y procesa los datos.
4. Supabase guarda clientes, servicios y citas.
5. n8n envía confirmaciones o notificaciones.
6. El sistema mantiene trazabilidad del proceso de reserva.

## Base de datos

Tablas principales utilizadas:

- clientes
- servicios
- citas

## Estado del proyecto

Proyecto académico finalizado como parte de la formación AI Automation en Henry.

## Autor

Tomás Fontana  
LinkedIn: https://www.linkedin.com/in/tomas-fontana-459960356/
