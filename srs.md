# Plataforma de Cursos

---

## Grupo de Desarrollo

**GCS - Grupo 4**

### Integrantes

- Sebastian Medina  
- Ana Henao  
- Jose Oñate  

---

## Documento de Requerimientos del Sistema  
**(Software Requirements Specification - SRS)**

---

**Fecha:** Marzo 2026  

---
## Introducción

Este documento presenta los requerimientos funcionales y no funcionales del sistema de gestión de cursos desarrollado por el Grupo 4. Su objetivo es definir de manera clara las funcionalidades principales que deberá ofrecer la plataforma, así como las condiciones de calidad que debe cumplir. Los requerimientos se describen mediante historias de usuario y criterios de aceptación que permiten validar el correcto funcionamiento del sistema.

---

# GCS-Grupo-4
# Requerimientos Funcionales

---

## RF-01 Registro de Estudiante

### HU-01 – Registro de Estudiante

Como visitante quiero registrarme como estudiante para acceder a los cursos disponibles

### Criterios de Aceptación

* El correo no debe repetirse en el sistema.
* Debe mostrarse confirmación de registro exitoso.
* Debe validarse el formato correcto del correo electrónico.

## RF-02 Inscripción a Curso

### HU-02 – Inscripción a Curso

Como estudiante quiero inscribirme en un curso disponible para acceder al contenido académico
## RF-02 Inscripción a Curso

### HU-02 – Inscripción a Curso

Como estudiante quiero inscribirme en un curso disponible para acceder al contenido académico

### Criterios de Aceptación

* Debe haber cupos disponibles antes de permitir la inscripción.
* El sistema debe confirmar la inscripción.
* El curso debe aparecer en la lista de cursos del estudiante.

### RF-03 – Subir Tarea

El sistema debe permitir que los estudiantes inscritos en un curso carguen y envíen archivos correspondientes a una tarea asignada, dentro del plazo establecido por el docente.

### HU-03 – Subir Tarea
Como estudiante inscrito en un curso quiero subir un archivo como entrega de una tarea para que el docente pueda evaluarlo.

Como estudiante inscrito en un curso quiero subir un archivo como entrega de una tarea para que el docente pueda evaluarlo.

#### Descripción:
El sistema debe permitir al estudiante adjuntar un archivo desde su dispositivo y enviarlo como entrega oficial de una tarea antes de la fecha y hora límite.

### Criterios de Aceptación

1. Solo los estudiantes inscritos en el curso pueden subir tareas.
2. El sistema solo debe permitir la carga dentro de la fecha y hora límite establecida.
3. El sistema debe aceptar únicamente archivos en formato **PDF** o **DOCX**.
4. El sistema debe validar que el archivo no esté vacío.
5. Debe mostrarse un mensaje de confirmación de envío exitoso.
6. El sistema debe registrar la fecha y hora exacta de la entrega.
7. Si la fecha límite ha expirado, el sistema debe mostrar un mensaje indicando que no es posible subir la tarea.

---
## Requerimientos No Funcionales

---

### RNF-01 – Usabilidad

El sistema debe garantizar una experiencia de usuario intuitiva y eficiente, permitiendo que el proceso de inscripción a un curso se complete en un máximo de cinco (5) pasos claramente definidos.

#### Criterios de Verificación:

- El flujo de inscripción no debe superar cinco pantallas o interacciones principales.
- El sistema debe mostrar mensajes claros ante errores o acciones exitosas.
- La interfaz debe mantener consistencia visual y de navegación en todas las secciones.
- El usuario debe poder regresar a pasos anteriores sin perder la información ingresada.


### RNF-02 – Disponibilidad

El sistema debe estar disponible las 24 horas del día, los 7 días de la semana (24/7), garantizando acceso continuo a estudiantes y docentes.

#### Criterios de Verificación:

- El sistema debe mantener un tiempo de disponibilidad (uptime) mínimo del 99% mensual.
- Las interrupciones programadas deben notificarse con anticipación a los usuarios.
- En caso de falla del sistema, no debe perderse la información almacenada.
- El acceso a cursos y entregas debe estar garantizado en cualquier momento.
---
# Tabla de Trazabilidad

| HU    | RF    | Caso de Prueba                                                                              | Estado    |
| ----- | ----- | ------------------------------------------------------------------------------------------- | --------- |
| HU-01 | RF-01 | Verificar que el estudiante pueda registrarse con un correo válido y único                  | Pendiente |
| HU-02 | RF-02 | Verificar que un estudiante pueda inscribirse si hay cupos disponibles                      | Pendiente |
| HU-03 | RF-03 | Verificar que el estudiante pueda subir tarea en formato permitido antes de la fecha límite | Pendiente |
---

