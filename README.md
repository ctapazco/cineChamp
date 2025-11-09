<div align="center">

  # 🎬 CineChamp
  
  <img width="452" height="448" alt="image" src="https://github.com/user-attachments/assets/b091f9ef-eaf4-4dfd-9b53-d089793b2c9d" />


### Plataforma de reseñas y comunidad para cinéfilos y seriéfilos

📽️ Proyecto Full Stack desarrollado como parte del CFGS en Desarrollo de Aplicaciones Web  
👨‍💻 Por [Cristian Tapasco](https://www.linkedin.com/in/ctapascozabala/)  
📍 Barcelona, España — 2025  

---
</div>

## 🚀 Descripción

**CineChamp** es una aplicación web que permite a los usuarios gestionar su historial de películas y series, calificar contenido, escribir reseñas, desbloquear logros y conectar con otros amantes del cine.  
Su objetivo es ofrecer una experiencia completa tipo red social, pero enfocada exclusivamente en el entretenimiento audiovisual.

---

## 🧩 Funcionalidades principales

✅ Registro y autenticación de usuarios (JWT)  
✅ Gestión completa del perfil y avatar  
✅ Búsqueda de películas y series con API de **TMDb**  
✅ Valoraciones y reseñas personalizadas  
✅ Sistema de **favoritos**, **historial** y **logros desbloqueables**  
✅ Interacción social con sistema de amigos  
✅ Estadísticas personales de visualización  
✅ Arquitectura **MVC** y pruebas de funcionalidad  

---

## ⚙️ Tecnologías utilizadas

<div align="center">

| Capa | Tecnologías |
|------|--------------|
| 🎨 **Frontend** | React · TypeScript · Vite |
| 🧠 **Backend** | Node.js · Express.js |
| 💾 **Base de datos** | MySQL |
| 🎞️ **API externa** | The Movie Database (TMDb) |
| 🧭 **Metodología** | Kanban (Trello) |
| 🧰 **Control de versiones** | Git + GitHub |

</div>

<div align="center">

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![TMDb](https://img.shields.io/badge/TMDb-01B4E4?style=for-the-badge&logo=tmdb&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

</div>

---

## 🧠 Arquitectura

El proyecto sigue el patrón **Modelo–Vista–Controlador (MVC)** para garantizar modularidad y escalabilidad:

- **Modelo:** MySQL gestiona usuarios, contenido, reseñas, logros y amistades.  
- **Vista:** React + TypeScript para una interfaz moderna e intuitiva.  
- **Controlador:** Express.js orquesta la comunicación entre frontend, backend y TMDb API.  

---

## 🖼️ Capturas de pantalla

<img width="681" height="697" alt="image" src="https://github.com/user-attachments/assets/0abaf888-e29d-4596-bd9f-b46a6a916c5d" />
<img width="722" height="772" alt="image" src="https://github.com/user-attachments/assets/e6be35b8-19bb-4e9d-b386-a619126a1b08" />
<img width="733" height="506" alt="image" src="https://github.com/user-attachments/assets/307282a2-2ffa-474a-a850-f08c49e0f76b" />


<div align="center">

![Pantalla principal](./assets/perfil-usuario.png)
![Búsqueda de contenido](./assets/busqueda.png)
![Detalle de película](./assets/detalle-pelicula.png)
![Sistema de logros](./assets/logros.png)

</div>

---

## 🧰 Instalación y ejecución

```bash
# Clonar el repositorio
git clone https://github.com/ctapazco/cineChamp.git

# Entrar en la carpeta del proyecto
cd cineChamp

# Instalar dependencias
npm install

# Configurar variables de entorno (.env)
# Ejemplo:
# TMDB_API_KEY=tu_clave_tmdb
# DB_USER=root
# DB_PASSWORD=tu_contraseña
# DB_NAME=cinechamp

# Iniciar el backend
npm run server

# Iniciar el frontend
npm run dev
