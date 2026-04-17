# 🧑‍💻 Portafolio de Proyectos – Java & Desarrollo Web

Este repositorio reúne proyectos desarrollados como práctica académica y portafolio personal, enfocados en el aprendizaje y aplicación de Java, bases de datos y desarrollo web.

Los proyectos aquí presentados demuestran habilidades en:

* Programación orientada a objetos
* Desarrollo backend con Java y Spring Boot
* Diseño y gestión de bases de datos relacionales (MySQL)
* Desarrollo frontend básico (HTML y CSS)
* Arquitectura MVC aplicada a proyectos reales
* Uso de Git y GitHub como control de versiones

---

## 📂 Proyectos incluidos

---

### 🏨 1. SIGHO+ – Sistema Integral de Gestión Hotelera y Apartahotelera

**SIGHO+** es un sistema web de gestión hotelera diseñado para centralizar, automatizar y optimizar las operaciones de un hotel o apartahotel en un solo entorno digital. Inspirado en soluciones profesionales del sector como **OPERA** y **ZEUS**, el sistema busca eliminar procesos manuales y herramientas dispersas (Excel, papel, mensajería), integrando en una sola plataforma la gestión operativa, administrativa, financiera y comercial.

> ⚠️ Esta es la **primera versión del sistema (SIGHO+ v1)**, desarrollada de forma individual con un enfoque académico y tecnologías base. Sirvió como base conceptual y funcional para su evolución hacia **FACILE PMS**, una versión más robusta con arquitectura de microservicios.

#### 🎯 Objetivo

Desarrollar un sistema que permita:

* Centralizar la información del hotel en una sola plataforma
* Automatizar procesos operativos críticos
* Mejorar la toma de decisiones mediante datos en tiempo real
* Optimizar la experiencia del cliente
* Reducir errores humanos en facturación, reservas y control de ocupación

#### 🧩 Módulos del sistema

* Dashboard central con KPIs y estado general del hotel
* Gestión de reservas en tiempo real
* Check-in / Check-out digital
* Gestión de habitaciones y unidades
* Servicios (housekeeping, mantenimiento, extras)
* Facturación y finanzas
* Control de inventario con alertas
* Gestión de empleados y roles
* Documentos y contratos
* Atención al cliente (chat y comunicación interna)
* Página web de reservas orientada al cliente

#### 🚀 Funcionalidades clave

* Control de ocupación en tiempo real
* Automatización de facturación y servicios
* Reportes operativos y financieros
* Notificaciones automáticas (correo / mensajería)
* Seguridad basada en roles de usuario
* Acceso multiplataforma

#### ⚙️ Tecnologías utilizadas

* **Backend:** Java con Spring Boot
* **Base de datos:** MySQL
* **Frontend:** HTML5 / CSS3
* **Arquitectura:** MVC (Controller – Service – Repository)

#### ⚠️ Limitaciones (v1)

* Arquitectura básica y escalabilidad limitada
* Interfaz simple sin frameworks modernos
* Integraciones externas no implementadas
* Seguridad y manejo de concurrencia en fase inicial

#### 🔄 Evolución del proyecto

Este sistema evolucionó hacia **FACILE PMS**, una versión avanzada con:

* Arquitectura de microservicios con Spring Cloud
* Frontend moderno con React 18
* Seguridad robusta con JWT
* Contenedores con Docker Compose
* Mayor cobertura de módulos y preparación para entorno productivo

---

### 📌 2. CRUD de Personas – Spring Boot & MySQL

Aplicación web desarrollada en Java con Spring Boot que permite registrar, listar, editar y eliminar personas, aplicando validaciones de negocio como la no repetición de correos electrónicos ni números de celular.

#### 🚀 Funcionalidades

* ✅ Registrar personas
* ✅ Listar personas registradas
* ✅ Editar información
* ✅ Eliminar personas con confirmación
* ❌ No permite correos electrónicos duplicados
* ❌ No permite números de celular duplicados
* 📢 Mensajes de éxito y error al usuario
* 🔄 Persistencia automática en base de datos MySQL

#### 🛠️ Tecnologías utilizadas

* Java 21
* Spring Boot
* Spring Data JPA
* Spring Validation
* Thymeleaf
* MySQL
* Maven
* HTML5 / CSS3





Incluyen:

* Registro de personas
* Listado
* Edición
* Eliminación
* Mensajes del sistema

---

### 🌐 3. Página Web – HTML & CSS

Página web estática desarrollada como práctica de estructura HTML y estilos CSS, enfocada en reforzar conceptos de maquetación, organización visual y presentación de información.

#### 🛠️ Tecnologías utilizadas

* HTML5
* CSS3



---

## 🔧 Requisitos del entorno (Proyectos Java)

* Java JDK 21 (versión utilizada para el desarrollo y pruebas)
* MySQL
* Maven (incluido mediante Maven Wrapper)
* Un IDE compatible con Java y Spring Boot

#### IDEs compatibles

* ✅ NetBeans (IDE utilizado durante el desarrollo)
* ✅ IntelliJ IDEA
* ⚠️ Visual Studio Code (requiere extensiones de Java y Spring Boot)

> 📌 El proyecto fue desarrollado y probado con Java 21. Versiones superiores o inferiores pueden funcionar, pero no están garantizadas.

---

## 🗄️ Base de datos (CRUD de Personas)

* **Base de datos:** `crud_java`
* **Motor:** MySQL
* Las tablas se generan automáticamente gracias a JPA (`ddl-auto=update`)

Ejemplo de configuración `application.properties` (no incluida por seguridad):

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/crud_java
spring.datasource.username=tu_usuario
spring.datasource.password=tu_password
```

---

## ▶️ Cómo ejecutar el proyecto CRUD

1. Clona el repositorio:

```bash
git clone https://github.com/Sebastian-122/Sebastian_Parada.git
```

2. Abre el proyecto en tu IDE preferido.

3. Configura la base de datos MySQL con las credenciales correspondientes.

4. Ejecuta la clase principal:

```
RegistroApplication.java
```

5. Abre en el navegador:

```
http://localhost:8080/personas
```

---

## 📌 Estado del repositorio

* ✔ Proyectos funcionales
* ✔ Uso académico y de portafolio
* ✔ Código organizado y documentado
* ✔ Base sólida para futuras mejoras y proyectos más avanzados

---

## 👤 Autor

**Sebastian Parada**
Aprendiz SENA – Análisis y Desarrollo de Software (ADSO)

📎 *Portafolio en construcción – nuevos proyectos serán añadidos progresivamente.*
