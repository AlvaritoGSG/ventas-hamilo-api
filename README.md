# 🛒 Sistema de Compraventa (ERP) - API REST con Laravel

Este es un proyecto personal desarrollado con Laravel que implementa una API RESTful completa para un sistema ERP básico de compraventa de productos. Incluye operaciones CRUD, autenticación.

<!-- , y estadísticas resumidas mediante un dashboard. -->

---

## 🚀 Características principales

-   CRUD completo para:
    -   Usuarios y perfiles
    -   Productos
    -   Compras
    -   Ventas
-   Módulo de autenticación (login/logout)
<!-- -   Dashboard con estadísticas generales (ventas, compras, productos) -->
-   Integración con base de datos **MySQL**
<!-- -   Migraciones y seeders incluidos -->

---

## 🧰 Tecnologías utilizadas

-   **Laravel** (versión 12)
-   **MySQL**
-   Autenticación con: Laravel Sanctum
-   Laravel Eloquent ORM
-   Laravel Migrations y Seeders

---

## 📦 Instalación

```bash
# Clonar el repositorio
git clone https://github.com/AlvaritoGSG/ventas-hamilo-api.git

# Acceder al directorio
cd ventas-hamilo-api

# Instalar dependencias
composer install

# Configurar variables de entorno
cp .env.example .env
php artisan key:generate

# Configurar base de datos en el archivo .env
DB_DATABASE=ventas-hamilo-api
DB_USERNAME=tuUsuario
DB_PASSWORD=tuContraseña

# Ejecutar migraciones y seeders
php artisan migrate --seed

# Iniciar el servidor de desarrollo
php artisan serve
```
