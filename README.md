<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/3081/3081559.png" />

# 🛒 TiendaOnline

### Plataforma web de comercio electrónico con arquitectura MVC 🚀

<p align="center">
  <b>PHP MVC Online Store</b> es una tienda virtual desarrollada con PHP bajo arquitectura MVC, diseñada para gestionar productos, usuarios, compras y pedidos mediante una plataforma moderna, dinámica y escalable.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Ecommerce-WebPlatform-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/PHP-MVC-777BB4?style=for-the-badge&logo=php&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/OpenSource-FullStack-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-módulos-del-sistema">Módulos</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-vista-previa">Vista previa</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**PHP MVC Online Store** es una plataforma eCommerce desarrollada para administrar ventas online, productos, clientes y pedidos utilizando una arquitectura MVC que permite mantener una estructura organizada y escalable.

El sistema permite a los usuarios navegar por productos, agregarlos al carrito y realizar compras desde una interfaz intuitiva y moderna.

El sistema fue diseñado para:

- 🛒 Gestionar productos
- 👥 Administrar usuarios
- 📦 Gestionar pedidos
- 💳 Procesar compras
- 📊 Visualizar estadísticas
- 🔐 Administrar accesos
- 📁 Organizar catálogos
- 🌐 Facilitar ventas online

---

# ✨ Características

## 🛍️ Gestión de productos

- ➕ Registro de productos
- 🖼️ Gestión de imágenes
- 📂 Organización por categorías
- 💰 Configuración de precios
- 📦 Control de stock

---

## 👥 Gestión de usuarios

- 👤 Registro de clientes
- 🔐 Inicio de sesión
- 📄 Gestión de perfiles
- 📦 Historial de compras
- ⚡ Administración centralizada

---

## 🛒 Sistema de compras

- 🛍️ Carrito de compras
- 💳 Procesamiento de pedidos
- 📦 Gestión de envíos
- 📋 Resumen de compra
- ⚡ Confirmación automática

---

## 📊 Panel administrativo

- 📈 Dashboard administrativo
- 📦 Gestión de pedidos
- 🛒 Administración de productos
- 👥 Gestión de usuarios
- 🔐 Control del sistema

---

# 👨‍💼 Módulos del sistema

## 🛍️ Product Module

Este módulo administra todos los productos de la tienda.

### Funcionalidades:

- ➕ Registro de productos
- 🖼️ Gestión de imágenes
- 📂 Organización por categorías
- 💰 Configuración de precios
- 📦 Administración de stock

---

## 👤 Customer Module

Este módulo es utilizado por clientes de la tienda online.

### Funcionalidades:

- 🔍 Buscar productos
- 🛒 Agregar productos al carrito
- 💳 Realizar compras
- 📦 Consultar pedidos
- 📄 Gestionar perfil

---

## 📦 Order Module

Este módulo administra pedidos y operaciones comerciales.

### Funcionalidades:

- 📋 Gestión de pedidos
- 💰 Confirmación de pagos
- 🚚 Gestión de envíos
- 📊 Historial de compras
- ⚡ Actualización de estados

---

## 🛠️ Admin Module

Este módulo funciona como administrador principal del sistema.

### Funcionalidades:

- 👥 Gestión de usuarios
- 🛒 Administración de productos
- 📦 Supervisión de pedidos
- 📊 Dashboard administrativo
- 🔐 Gestión del sistema

---

# 🛠️ Tecnologías utilizadas

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,bootstrap,js" />
</p>

- HTML5
- CSS3
- Bootstrap
- JavaScript

---

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=php" />
</p>

- PHP
- Arquitectura MVC
- Sistema CRUD
- Gestión de sesiones

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql" />
</p>

- MySQL
- Relaciones SQL
- Persistencia de datos
- Gestión eCommerce

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode" />
</p>

- Git
- GitHub
- Visual Studio Code
- XAMPP / WAMP

---

# 📂 Estructura del proyecto

```bash
TiendaOnline/
│
├── app/
│   ├── controllers/          # Controladores MVC
│   ├── models/               # Modelos de datos
│   ├── views/                # Vistas del sistema
│   └── core/                 # Núcleo MVC
│
├── public/                   # Recursos públicos
│   ├── css/
│   ├── js/
│   ├── images/
│   └── uploads/
│
├── database/                 # Scripts SQL
├── routes/                   # Configuración de rutas
├── config/                   # Configuración general
├── index.php                 # Punto de entrada
├── README.md
└── LICENSE
```

---

# ⚡ Instalación

## 📋 Requisitos

- PHP 7+
- MySQL
- Apache
- Composer (opcional)
- XAMPP / WAMP

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isaireyesp1/TiendaOnline.git
```

---

## 2️⃣ Mover archivos

Copiar proyecto hacia:

```bash
xampp/htdocs/TiendaOnline/
```

---

## 3️⃣ Crear base de datos

Crear base:

```bash
php_mvc_store
```

---

## 4️⃣ Importar SQL

Importar:

```bash
database/php_mvc_store.sql
```

---

## 5️⃣ Configurar conexión

Editar:

```bash
config/database.php
```

Agregar:

```php
define('DB_HOST','localhost');
define('DB_USER','root');
define('DB_PASS','');
define('DB_NAME','php_mvc_store');
```

---

## 6️⃣ Ejecutar proyecto

Abrir:

```bash
http://localhost/TiendaOnline/
```

---

# 📊 Funcionalidades principales

## 🛒 Gestión de productos

- Administración de productos
- Gestión de categorías
- Control de stock
- Gestión de imágenes

---

## 👥 Administración de clientes

- Registro y autenticación
- Gestión de perfiles
- Historial de compras
- Gestión de pedidos

---

## 📦 Gestión de pedidos

- Carrito de compras
- Confirmación de pagos
- Gestión de envíos
- Historial comercial

---



# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y administración

- Desarrollo web MVC
- Arquitectura de software
- Bases de datos relacionales
- Sistemas eCommerce
- Gestión de usuarios
- Automatización comercial
- Programación backend PHP

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 📱 Aplicación móvil
- ☁️ Infraestructura cloud
- 💳 Pasarela de pagos
- 🤖 Recomendaciones inteligentes
- 🌐 API REST moderna
- 🔔 Notificaciones en tiempo real
- 📦 Seguimiento de pedidos

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — PHP Full Stack Developer

Desarrollador apasionado por plataformas eCommerce, sistemas MVC y aplicaciones web modernas 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source orientado al aprendizaje de arquitectura MVC, PHP y plataformas eCommerce.

---

<div align="center">

### 🛒 PHP MVC Online Store — comercio electrónico moderno y escalable 🚀

</div>
