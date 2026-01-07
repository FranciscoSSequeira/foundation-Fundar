# Fundar – Plataforma de Donaciones Solidarias

Fundar es una aplicación Full Stack Web desarrollada como proyecto final del bootcamp SoyHenry, cuyo objetivo es conectar personas que desean colaborar económicamente con obras de beneficencia o causas sociales.

La aplicación funciona como una plataforma de donaciones, permitiendo a los usuarios apoyar proyectos sociales (por ejemplo, la construcción de una escuela) de forma simple, segura y centralizada.

- 🔗 Enlace a la API: https://pf-back-zimt.onrender.com/api
- 🌐 Demo: https://demo2-five-phi.vercel.app
  
---

## ✨ Funcionalidades principales:
### 👤 Usuarios

✅ Registro y login de usuarios

✅ Autenticación con email/password

✅ Autenticación mediante Google (OAuth)

✅ Edición de perfil (datos personales e imagen)

✅ Visualización de obras de beneficencia disponibles

✅ Donaciones a proyectos sociales mediante pasarela de pagos

✅ Dashboard de usuario con historial de donaciones

✅ Envío de email automático al usuario al momento del registro

### 🛠️ Administradores

✅ Login y gestión de administradores

✅ CRUD de usuarios

✅ CRUD de obras de beneficencia

✅ Creación de nuevos administradores

✅ Acceso a dashboard administrativo

✅ Notificación por email al admin cuando se realiza una donación

✅ Recepción de reportes diarios del estado de los proyectos mediante tareas programadas (crons)

---

## 🖥️ Tipo de aplicación

🌐 Aplicación Web

🧩 Arquitectura Full Stack

🔌 Backend funcionando como API externa

💳 Integración de pasarela de pagos

📊 Dashboard de usuario y dashboard de administrador

📸 Subida de imágenes

🤖 Chatbot integrado con Botpress para redirigir a distintas secciones de la web

⏱️ Uso de tareas programadas (crons) para automatización de notificaciones

---

## 🎯 Propósito del proyecto

Fundar fue desarrollado como un proyecto académico y demostrativo, con foco en:

Integración de múltiples tecnologías modernas

Autenticación y autorización con roles

Manejo de pagos online

Automatización de procesos mediante crons

Comunicación por email con usuarios y administradores

Arquitectura backend robusta y escalable

El proyecto se encuentra funcional y deployado, aunque abierto a futuras mejoras.

---

## 🛠️ Stack Tecnológico
### Frontend

⚛️ React

▲ Next.js

🎨 Tailwind CSS

🟦 TypeScript

📋 Formik

✅ Yup

🔐 JWT Decode

### Backend

🧱 NestJS

🟦 TypeScript

🔐 Bcrypt

☁️ Cloudinary

📧 Nodemailer

🔑 JWT

🔓 Google OAuth

💳 Stripe

⏱️ Crons (tareas programadas)

📑 Swagger (documentación de API)

### Base de Datos

🐘 PostgreSQL

🗄️ TypeORM

### ☁️ Deploy

Frontend: Vercel

Backend: Render

Base de datos: Render (PostgreSQL)

---

## 📁 Estructura del proyecto (Backend)

```text
backend/
└── src/
    ├── app.controller.ts
    ├── app.module.ts
    ├── app.service.ts
    ├── main.ts
    ├── auth/                  # Autenticación
    ├── categories/            # Categorías de las obras
    ├── donations/             # Gestión de donaciones
    ├── email/                 # Notificaciones por email
    ├── enums/                 # Roles
    ├── file-upload/           # Subida de imágenes
    ├── middlewares/           # Middlewares personalizados
    ├── notifications/         # Gestión de notificaciones
    ├── payments/              # Gestión de pagos
    ├── projects/              # Gestión de obras a las que se puede donar
    └── users/                 # Gestión de usuarios

   
## 👥 Roles del sistema

- Usuario: Donar, editar perfil, ver obras y donaciones
- Admin:	Gestión completa de usuarios, obras y administradores

---

## 🖼️ Vistas de la aplicación

<table>

  <!-- Home / Register -->
  <tr>
    <td width="50%" align="center" valign="top">

### 🏠 Home
<img alt="Home Fundar" src="https://github.com/user-attachments/assets/650b5efb-31be-49df-97fc-862fef5c0293" />

</td>
    <td width="50%" align="center" valign="top">

### 📝 Register
<img alt="Register Fundar" src="https://github.com/user-attachments/assets/9978dd9c-c644-4243-b03d-ad095fc951f3" />

</td>
  </tr>

  <!-- Login -->
  <tr>
    <td colspan="2" align="center" valign="top">

### 🔐 Login
<img alt="Login Fundar" src="https://github.com/user-attachments/assets/098a3c08-28ff-4689-b289-e39038e424d5" />

</td>
  </tr>

  <!-- Dashboards -->
  <tr>
    <td width="50%" align="center" valign="top">

### 📊 Dashboard de Usuario
<img alt="Dashboard Usuario" src="https://github.com/user-attachments/assets/67dfa8dd-dc96-41ec-a355-1bfb0b22dc9f" />

</td>
    <td width="50%" align="center" valign="top">

### 🛠️ Dashboard de Administrador
<img alt="Dashboard Admin" src="https://github.com/user-attachments/assets/6cb5c24f-7edf-431a-9831-0cec670039bf" />

</td>
  </tr>

</table>

---

## 🔑 Usuarios de prueba

- Ingreso como Usuario => - email: pruebauno@gmail.com / password: Pass!123 / SingIn con cuenta de Google en boton SignIn with Gmail
- Ingreso como Admin => - email: admindeprueba@admin.com / password: Pass!123

---

## 🚀 Posibles mejoras futuras

📈 Métricas y reportes visuales

🧪 Testing automatizado

🔐 Mayor granularidad de permisos

🤖 Expansión del chatbot

---

## 👨‍💻 Sobre el desarrollador

Proyecto realizado en colaboración con otro desarrollador. Mi funciones fueron en el backend de la aplicación.

- 💼 LinkedIn: www.linkedin.com/in/francisco-sequeira-

