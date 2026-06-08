# Sistema de Recursos Humanos (RRHH)

## Descripción

Sistema de gestión de personal desarrollado en C# utilizando Windows Forms y Programación Orientada a Objetos (POO) sobre .NET Framework.

La aplicación permite administrar los empleados de una empresa, controlar permisos según el rol de cada usuario, gestionar áreas de trabajo y asignar tareas a los empleados.

Además, el sistema almacena información sobre familiares de cada empleado y permite guardar los datos mediante archivos CSV y TXT.

---

## ¿Qué hace el programa?

El programa permite:

* Registrar nuevos usuarios.
* Iniciar sesión mediante DNI y contraseña.
* Gestionar empleados de la empresa.
* Crear y administrar áreas de trabajo.
* Asignar tareas a empleados.
* Consultar tareas asignadas.
* Administrar permisos según el rango del usuario.
* Registrar información del grupo familiar de cada empleado.
* Guardar y recuperar información desde archivos.

---

## Funcionalidades Principales

### Gestión de Usuarios

* Alta de empleados.
* Baja de empleados.
* Modificación de información.
* Asignación de roles.
* Consulta de usuarios registrados.

### Gestión de Áreas

* Crear áreas de trabajo.
* Modificar áreas existentes.
* Eliminar áreas.
* Asignar empleados y supervisores a un área.

### Gestión de Tareas

* Crear tareas.
* Asignar tareas a empleados.
* Modificar tareas.
* Eliminar tareas.
* Visualizar tareas asignadas.

### Gestión Familiar

Cada empleado puede registrar uno o más familiares indicando:

* Nombre.
* Apellido.
* Relación familiar.
* Fecha de nacimiento.

### Seguridad

* Inicio de sesión.
* Validación de credenciales.
* Control de acceso por roles.

---

## Roles del Sistema

### SuperUsuario

Posee acceso total al sistema.

Puede:

* Gestionar usuarios.
* Gestionar áreas.
* Gestionar tareas.

### Administrador

Puede:

* Gestionar usuarios.
* Gestionar tareas.

### Supervisor

Puede:

* Asignar tareas.
* Modificar tareas.
* Eliminar tareas.

### Empleado

Puede:

* Visualizar únicamente las tareas que le fueron asignadas.

---

## Tecnologías Utilizadas

* C#
* .NET Framework
* Windows Forms
* Programación Orientada a Objetos (POO)
* Archivos CSV
* Archivos TXT
* Visual Studio

---

## Estructura General del Sistema

```text
Login
 │
 ▼
Menú Principal
 │
 ├── Gestión de Usuarios
 │
 ├── Gestión de Áreas
 │
 ├── Gestión de Tareas
 │
 └── Consulta de Tareas
```

---

## Persistencia de Datos

El sistema permite almacenar información utilizando:

* Archivos CSV.
* Archivos TXT.

Los datos de usuarios, áreas, tareas y familiares permanecen disponibles entre ejecuciones de la aplicación.

---

## Autores

* Nicolas Antonopulos
* Gregorio Mantero
* Alejo Rico

Universidad Abierta Interamericana (UAI)

Facultad de Tecnología Informática

Ingeniería en Sistemas Informáticos

Proyecto desarrollado para la materia Programación Orientada a Objetos.
