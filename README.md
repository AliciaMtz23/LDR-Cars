# LDR Cars – Sistema Web de Renta de Vehículos

LDR Cars es una aplicación web desarrollada para gestionar el proceso de renta de vehículos de forma digital, permitiendo a los usuarios consultar vehículos disponibles, realizar reservas y seleccionar ubicaciones de recolección y entrega mediante una interfaz intuitiva.

El sistema integra funcionalidades para usuarios y administración, incluyendo autenticación, catálogo dinámico y gestión de reservas.

---

## 📌 Descripción del Proyecto

La plataforma fue desarrollada con el objetivo de mejorar la experiencia de renta de vehículos mediante un sistema centralizado que facilite:

* Consulta de vehículos disponibles
* Registro e inicio de sesión
* Gestión de reservas
* Visualización de ubicaciones
* Administración del catálogo

---

##  Funcionalidades

### Usuarios

* Registro de cuenta
* Inicio y cierre de sesión
* Consulta del catálogo de vehículos
* Visualización de características del vehículo:

  * Marca
  * Modelo
  * Descripción
  * Capacidad de pasajeros
  * Precio por día
* Generación de reservas
* Selección de fecha y horario
* Consulta de ubicaciones de entrega y recolección
* Generación automática de folio de reserva

### Administración

* Acceso administrativo
* Gestión del catálogo de vehículos
* Administración de registros
* Control de disponibilidad

---

##  Tecnologías Utilizadas

### Frontend

* HTML5
* CSS3
* JavaScript

### Backend

* PHP

### Base de Datos

* MySQL

### Herramientas

* XAMPP
* Git
* GitHub

---

## 🗂️ Estructura del Proyecto

```bash
LDR/
│
├── CatalogoCoches.php
├── login.php
├── loginadmin.php
├── admin_dashboard.php
├── dashboard.php
├── procesar_reserva.php
├── ubicaciones.php
├── logout.php
│
├── style.css
├── stylelogin.css
├── styleadmin.css
├── styleconsulta.css
├── styleubicacion.css
│
└── scripts/
```

---

## 🚘 Flujo del Sistema

1. El usuario accede al catálogo.
2. Consulta vehículos disponibles.
3. Selecciona un vehículo.
4. Completa el formulario de reserva.
5. Selecciona fecha y lugar de recolección.
6. El sistema calcula automáticamente:

   * Días de renta
   * Costo total
7. Se genera un folio único de confirmación.

## 🗄️ Configuración Base de Datos

Crear una base llamada:

```sql
renta
```

Configurar conexión:

```php
$servidor="localhost";
$usuario="root";
$password="";
$db="renta";
```




## Objetivo del Proyecto

Desarrollar una solución web orientada a la administración y renta de vehículos que permita automatizar el proceso de reservación, mejorar la accesibilidad para el usuario y centralizar la gestión operativa.

---

## Desarrollado por

**Rosa Martínez**
Frontend Developer | Desarrollo Web | UI/UX

