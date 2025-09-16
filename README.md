# App Contactos con POO (PHP + MySQL)

Este proyecto es una aplicación para la gestión de contactos  
desarrollada en PHP utilizando Programación Orientada a Objetos (POO) y MySQL.  
Permite registrar, iniciar sesión y realizar operaciones CRUD (Crear, Leer, Actualizar y Eliminar) sobre contactos.

---

## Características

- Registro e inicio de sesión de usuarios.
- Gestión de contactos (CRUD completo).
- Arquitectura basada en MVC (Modelo - Vista - Controlador).
- Conexión segura a la base de datos con PDO.
- Uso de Composer para la carga automática de clases.

---

## Estructura del proyecto

APP_CONTACTOS/
│
├── app/
│ │
│ ├── config/
│ │ └── Database.php
│ │
│ ├── Controllers/
│ │ ├── ContactoController.php
│ │ └── UsuarioController.php
│ │
│ ├── Models/
│ │ ├── Contacto.php
│ │ └── Usuario.php
│ │
│ └── Views/
│ ├── contactos_crear.php
│ ├── contactos_editar.php
│ ├── contactos_index.php
│ ├── usuarios_login.php
│ └── usuarios_registro.php
│
├── public/
│ └── index.php
│
├── vendor/
│
└── composer.json

## Autor

- Harley Guerra 
