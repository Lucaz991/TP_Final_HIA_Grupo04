#  Proyecto Final HIA - Grupo 13

Repositorio unificado para el trabajo final de la materia Infraestructura (HIA). Este proyecto integra el frontend, backend y la base de datos en un único entorno orquestado.

##  Estructura del Repositorio

* **/frontend:** Aplicación cliente desarrollada en Angular.
* **/backend:** API REST desarrollada en Node.js y Express.
* **/database:** Scripts de inicialización y dataset para PostgreSQL.
* **compose.yaml:** Archivo de orquestación de contenedores (Docker).

##  Equipo de Trabajo y Roles

* **Lucas Zerpa:** Arquitectura y Despliegue (Git, Docker, CI/CD)
* **Matías Churquina:** Redes y Ciberseguridad
* **Rodrigo Guanactolay:** Base de Datos Core (PostgreSQL, Optimización)
* **Luján Cansino:** Alta Disponibilidad y Monitoreo
* **Abigail Terán:** Operaciones y Automatización (Ops)

##  Ejecución Local (Desarrollo)

1. Clonar el repositorio y posicionarse en la rama `develop`.
2. Para el backend: `cd backend` -> `npm install` -> `npm run dev`
3. Para el frontend: `cd frontend` -> `npm install` -> `npm start`