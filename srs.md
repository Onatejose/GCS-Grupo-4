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


---

### RF-03 – Subir Tarea

El sistema debe permitir que los estudiantes inscritos en un curso carguen y envíen archivos correspondientes a una tarea asignada, dentro del plazo establecido por el docente.

---

### HU-03 – Subir Tarea

**Como** estudiante inscrito en un curso  
**quiero** subir un archivo como entrega de una tarea  
**para** que el docente pueda evaluarlo.



#### Descripción:
El sistema debe permitir al estudiante adjuntar un archivo desde su dispositivo y enviarlo como entrega oficial de una tarea antes de la fecha y hora límite.

---

### Criterios de Aceptación

1. Solo los estudiantes inscritos en el curso pueden subir tareas.
2. El sistema solo debe permitir la carga dentro de la fecha y hora límite establecida.
3. El sistema debe aceptar únicamente archivos en formato **PDF** o **DOCX**.
4. El sistema debe validar que el archivo no esté vacío.
5. Debe mostrarse un mensaje de confirmación de envío exitoso.
6. El sistema debe registrar la fecha y hora exacta de la entrega.
7. Si la fecha límite ha expirado, el sistema debe mostrar un mensaje indicando que no es posible subir la tarea.
