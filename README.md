# SgOVI – Sistema de gestión de la Oficina para la Vida Independiente

Aplicación web desarrollada en equipo para la asignatura **Diseño e Implementación de Sistemas de Información** (EI1027) del Grado en Ingeniería Informática de la Universitat Jaume I, curso 2025–2026.

El proyecto parte de un caso real: la Oficina para la Vida Independiente de Castelló (OVI), que ayuda a personas con diversidad funcional a encontrar y contratar profesionales de asistencia personal (PAP) y de asistencia terapéutica infantil (PATI). SgOVI digitaliza la gestión diaria de la oficina y el tratamiento de datos personales sensibles conforme al RGPD.

## Funcionalidades

**Gestión de personas usuarias**
- Alta y modificación de datos personales, con registro del consentimiento informado (RGPD)
- Generación automática de credenciales de acceso y validación del registro por parte del personal técnico (el envío de correos está simulado)

**Gestión de candidatos a PAP/PATI**
- Registro de candidatos con su formación y experiencia
- Revisión por el personal técnico, que acepta o rechaza cada candidatura, con notificación al candidato (simulada)

**Solicitudes de asistencia personal**
- Registro de solicitudes y seguimiento de su estado (en revisión, aprobada, cerrada con contrato, rechazada…)
- Propuesta de candidatos adecuados según disponibilidad, proximidad y preferencias
- Registro de los contratos (fechas y documento PDF)

**Mejora: tablero de monitorización**
- Panel para el personal técnico con los indicadores principales de la oficina: número total de contratos, contratos activos y número de solicitudes de asistencia, entre otros
- Permite ver de un vistazo el estado de la actividad sin consultar cada registro por separado

## Roles
- Personal técnico de la OVI
- Persona usuaria de la OVI
- Profesional PAP/PATI

## Tecnologías
Java · Spring Boot · PostgreSQL · HTML · CSS · Git/GitHub

## Equipo
- Ivan Maestre Soler
- Ruben Dobaño Solsona
- Jorge Vicente Valero
