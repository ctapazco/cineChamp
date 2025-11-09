![CineChamp Banner](./docs/banner-cinechamp.png)

<div align="center">

# 🎬 CineChamp

### Plataforma web social para cinéfilos y seriéfilos

📽️ Proyecto Full Stack desarrollado como parte del **CFGS en Desarrollo de Aplicaciones Web**  
👨‍💻 Por [Cristian Tapasco](https://www.linkedin.com/in/ctapascozabala/)  
🤝 En colaboración con [Cristian Calderón](https://github.com/Cristian-Calderon)  
📍 Barcelona, España — 2025  

---

</div>

## 🚀 Descripción general

**CineChamp** es una plataforma web que combina una base de datos de películas y series con funciones sociales y gamificadas.  
Los usuarios pueden buscar contenido, valorarlo, escribir reseñas, desbloquear logros, seguir a otros usuarios y gestionar su historial audiovisual.  

El proyecto fue desarrollado en equipo por **Cristian Tapasco** y **Cristian Calderón**, bajo la tutoría de **Yago Morales**, utilizando metodologías ágiles y herramientas colaborativas como Trello y GitHub.

---

## 🧭 Cómo se usa (flujo básico)

1. 🔐 **Registro / Inicio de sesión** con autenticación segura (JWT).  
2. 🎞️ **Explora películas y series** usando la API de TMDb.  
3. ⭐ **Valora o reseña** el contenido que hayas visto.  
4. ❤️ **Agrega favoritos** o guarda títulos para ver más tarde.  
5. 🏆 **Desbloquea logros** y consulta tus estadísticas personales.  
6. 👥 **Conecta con otros usuarios** y visualiza sus actividades.  
7. ⚙️ **Gestiona tu perfil**, imagen y preferencias desde tu cuenta.

---

## ⚙️ Stack tecnológico y versiones

| Capa | Tecnologías |
|------|--------------|
| 🎨 **Frontend** | React 18 · TypeScript · Vite |
| 🧠 **Backend** | Node.js 20 · Express.js |
| 💾 **Base de datos** | MySQL 8 |
| 🌐 **API externa** | The Movie Database (TMDb) |
| 🧭 **Metodología** | Kanban (Trello) |
| 🧰 **Control de versiones** | Git + GitHub |

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

## 🧩 Arquitectura y flujo de datos

CineChamp sigue el patrón **Modelo–Vista–Controlador (MVC)** para mantener un desarrollo modular y escalable.

- **Modelo (MySQL):** Define las tablas para usuarios, películas, reseñas, logros y relaciones sociales.  
- **Vista (React):** Interfaz dinámica con componentes reutilizables, navegación y hooks personalizados.  
- **Controlador (Express):** Gestiona la lógica del servidor, validaciones, autenticación y comunicación con TMDb.  

**Flujos clave:**
- Autenticación JWT → rutas protegidas y gestión de sesión.  
- API TMDb → búsqueda, fichas y sinopsis de contenido.  
- Base de datos MySQL → reseñas, logros, amigos y favoritos.  
- React Hooks + Context → estado global de usuario e interfaz reactiva.

---

## 🗂️ Estructura del proyecto

cineChamp/
├─ cinechamp/ # Frontend (React + TS)
│ ├─ components/ # Componentes reutilizables (cards, modals, etc.)
│ ├─ pages/ # Páginas principales (Home, Perfil, Reseñas, etc.)
│ ├─ services/ # Conexiones API y hooks personalizados
│ └─ assets/ # Imágenes y estilos
│
├─ server/ # Backend (Node + Express)
│ ├─ controllers/ # Lógica de negocio
│ ├─ models/ # Esquemas y conexión a la BD
│ ├─ routes/ # Rutas REST
│ └─ middleware/ # Autenticación, validaciones
│
├─ iconos/ # Iconografía y recursos visuales
├─ docs/ # Documentación y materiales de apoyo
└─ cinechamp.sql # Script de base de datos

---
## 🧠 Arquitectura

El proyecto sigue el patrón **Modelo–Vista–Controlador (MVC)** para garantizar modularidad y escalabilidad:

- **Modelo:** MySQL gestiona usuarios, contenido, reseñas, logros y amistades.  
- **Vista:** React + TypeScript para una interfaz moderna e intuitiva.  
- **Controlador:** Express.js orquesta la comunicación entre frontend, backend y TMDb API.  

---

## 🖼️ Capturas de pantalla

<img width="771" height="405" alt="image" src="https://github.com/user-attachments/assets/9e0f0649-4d3d-4d48-a3c4-4411e82f60ea" />
<img width="681" height="697" alt="image" src="https://github.com/user-attachments/assets/0abaf888-e29d-4596-bd9f-b46a6a916c5d" />
<img width="765" height="531" alt="image" src="https://github.com/user-attachments/assets/aaf56494-f56a-4fc6-b2fd-80a3207f244b" />
<img width="722" height="772" alt="image" src="https://github.com/user-attachments/assets/e6be35b8-19bb-4e9d-b386-a619126a1b08" />
<img width="733" height="506" alt="image" src="https://github.com/user-attachments/assets/307282a2-2ffa-474a-a850-f08c49e0f76b" />


</div>

---

## 📄 Documentación técnica

Puedes consultar el documento completo del proyecto aquí:  
👉 [Ver documentación (PDF)](./Xarxa%20social%20per%20aficionats%20al%20cine.pdf)

---

💬 Aprendizajes y reflexión personal

Durante este proyecto aprendí lo importante que es la comunicación con el equipo y la correcta gestión del tiempo de trabajo para cumplir los objetivos del desarrollo.
También reforcé mis conocimientos en React, Express, bases de datos relacionales y metodologías ágiles.


---

🧱 Hoja de ruta

🔔 Sistema de notificaciones internas

🤖 Recomendaciones automáticas basadas en gustos

🧩 Roles y permisos de moderador

🌍 Internacionalización multilenguaje

📱 Adaptación a app móvil (React Native)

--
## 🧰 Instalación y ejecución


<div align="center">

👨‍💻 Cristian Tapasco
💼 Desarrollador Full Stack Junior
📧 ctapasco907@gmail.com

🔗 LinkedIn
 · GitHub

</div> ```

📜 Licencia de Uso para Portafolio — No Comercial v1.0

Copyright © 2025 Cristian Tapasco & Cristian Calderón

Todos los derechos reservados, salvo lo permitido a continuación.

1. Permisos limitados

Se concede permiso gratuito y no exclusivo para:

Ver, clonar y ejecutar este proyecto con fines personales, académicos o de evaluación (por ejemplo, procesos de selección).

Crear modificaciones privadas con los mismos fines.

2. Restricciones

No está permitido, salvo autorización escrita:

Uso comercial de cualquier tipo (venta, SaaS, consultoría, monetización directa o indirecta).

Redistribuir o publicar el código fuente en repositorios públicos.

Integrarlo en productos distribuidos a terceros.

Eliminar avisos de copyright o licencia.

Usar este proyecto o sus recursos (imágenes, texto, estructura) para entrenamiento de modelos de IA o datasets.

3. Atribución

En presentaciones públicas o portafolios se solicita mencionar:

“Proyecto CineChamp, desarrollado por Cristian Tapasco y Cristian Calderón (2025).”




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

