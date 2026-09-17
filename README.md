# 🏋️ GymHub - Frontend

Frontend de **GymHub**, una aplicación web desarrollada como proyecto final de la **Tecnicatura Universitaria en Programación - UTN**.

GymHub permite gestionar usuarios, rutinas y ejercicios de un gimnasio mediante diferentes roles y permisos.

## 🎓 Sobre el proyecto

GymHub fue desarrollado como proyecto académico grupal por:

- Matías Gomez
- Juan Manuel Lantermo
- Juan Pablo Fernandez
- Santiago Oller

El proyecto está dividido en un frontend desarrollado con React y una API REST desarrollada con .NET.

## 🚀 Tecnologías

- React
- Vite
- React Router
- React Bootstrap
- JavaScript
- JWT para autenticación
- Context API

## ✨ Funcionalidades

La interfaz permite, según el rol del usuario:

- Iniciar sesión.
- Acceder a rutas protegidas.
- Consultar y gestionar el perfil.
- Visualizar rutinas asignadas.
- Crear y administrar rutinas.
- Gestionar ejercicios.
- Gestionar usuarios.
- Diferenciar funcionalidades según los roles Administrador, Profesor y Cliente.

## 🔐 Autenticación

El frontend utiliza autenticación mediante **JWT**.

El token recibido desde la API permite identificar al usuario y su rol, controlar el acceso a rutas protegidas y realizar solicitudes autenticadas al backend.

## 📁 Estructura del proyecto

```text
src/
│   App.jsx
│   index.css
│   main.jsx
│
├── assets/
├── components/
│   ├── account/
│   ├── auth/
│   ├── dashboard/
│   ├── header/
│   ├── home/
│   ├── newRoutine/
│   ├── partners/
│   ├── routes/
│   ├── routineItem/
│   ├── routines/
│   └── toggleTheme/
│
└── services/
    ├── authFetch.js
    ├── jwtDecode.js
    ├── authContext/
    └── theme/
```

## ⚙️ Instalación

### 1. Clonar el repositorio

```bash
git clone https://github.com/juanlantermo/GymHub-Frontend.git
```

### 2. Entrar al proyecto

```bash
cd GymHub-Frontend
```

### 3. Instalar dependencias

```bash
npm install
```

### 4. Iniciar la aplicación

```bash
npm run dev
```

## 🔗 Backend

La API REST utilizada por GymHub se encuentra en un repositorio separado:

👉 [GymHub-Backend](https://github.com/juanlantermo/GymHub-Backend)

El backend fue desarrollado con **.NET 8, ASP.NET Core, Entity Framework Core y SQL Server/Azure SQL**.

> El entorno de Azure utilizado para la presentación académica actualmente no se encuentra activo.
