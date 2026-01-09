# Administrador de Tarea con Node

## Descripción
Aplicación en Node.js para gestionar tareas y usuarios con autenticación, roles y actualizaciones en tiempo real.

## Roles
- **Administrador**: crea, edita, asigna y elimina tareas. Puede generar usuarios automáticamente.
- **Usuario estándar**: visualiza tareas, se asigna tareas y cambia su estado.

## Tareas
Cada tarea incluye:
- Descripción
- Duración estimada
- Dificultad: XS, S, M, L, XL
- Estado: por hacer, haciendo, hecha

Las rutas del CRUD están agrupadas bajo `/tasks`.

## Tiempo real
- Contador de tareas sin asignar actualizado automáticamente.
- Listas de tareas sincronizadas en tiempo real.

## Tecnologías
- Node.js
- Express
- Socket.io
- @faker-js/faker

