# 🗒️ Registro de Trabajo en Clase - Taller 2

## 📆 Fecha de la sesión
Sabado 08 de agosto de 2026

## 👥 Integrantes presentes
- Nicolas Esteban Muñoz Sendoya
- Juan David Orozco Rodriguez

## 🧠 Actividades realizadas en clase

Se trabajó el caso base de la Clínica Salud Viva siguiendo la metodología de 4 pasos de la guía paso a paso, tanto para el modelo entidad-relación (ERD) como para el diagrama de contexto de negocio.

**Modelo ER (Paso 1-4):**
- Se identificaron las 5 entidades del dominio: Paciente, Cita, Médico, Especialidad y Factura.
- Se definieron los atributos de cada entidad y se marcó su clave primaria (PK): CodPaciente, CodCita, CodMedico, CodEspecialidad y CodFactura.
- Se trazaron las relaciones nombradas con un verbo: Paciente **agenda** Cita; Cita **con** Médico; Cita **de** Especialidad; Cita **genera** Factura.
- Se asignó la cardinalidad de cada relación: Paciente (1) : Cita (N); Cita (N) : Médico (1); Cita (N) : Especialidad (1); Cita (1) : Factura (1).

**Diagrama de contexto (Paso 1-4):**
- Se identificaron los actores externos (Paciente, Médico, Asistente Administrativo) y el sistema externo (Aseguradora).
- Se trazó el límite organizacional de la Clínica Salud Viva y se ubicaron los sistemas internos: Sistema de Agendamiento, Notificador (SMS/Email) y ERP Clínico.
- Se trazaron los flujos de información entre actores y sistemas.
- Se etiquetó cada flujo con la información que transporta (p. ej. "Solicitud/confirmación de cita", "Validación de cobertura") y se verificó que ningún actor o sistema quedara sin conexión.

- **Herramientas usadas:** draw.io (archivos `.drawio` adjuntos en esta carpeta).
- **Parte del trabajo alcanzada:** ambos diagramas del caso base (ERD y contexto) completos, en borrador, pendientes de retroalimentación del docente antes de pasar a la Parte 2 (aplicación al cliente real).

## 🧩 Boceto inicial del modelo

> Ver `modelo-er-borrador.drawio` y `contexto-borrador.drawio` en esta misma carpeta (`clase/`).

## 🔁 Tareas definidas para complementar el taller

| Tarea asignada | Responsable | Fecha estimada |
|----------------|-------------|----------------|
| Adaptar el modelo ER al dominio del cliente real | [Nombre] | [Fecha] |
| Adaptar el diagrama de contexto al cliente real | [Nombre] | [Fecha] |
| Redacción del informe (`entrega/informe.md`) | [Nombre] | [Fecha] |
| Investigación y referencias (`entrega/referencias.md`) | [Nombre] | [Fecha] |

---

_Este documento resume el trabajo colaborativo realizado durante la sesión del Taller 2 en el curso AREM - Universidad de La Sabana._
