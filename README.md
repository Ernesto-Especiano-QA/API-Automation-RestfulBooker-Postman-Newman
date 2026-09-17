# 🧪 E2E API Automation Suite - Restful Booker

![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Newman](https://img.shields.io/badge/Newman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

## 📌 Descripción del Proyecto
Este repositorio contiene una suite de pruebas automatizadas End-to-End (E2E) para la API de reservas **Restful-Booker**. 
El flujo valida la autenticación de usuarios, la creación de reservas (POST), actualización total y parcial de datos (PUT/PATCH), y la eliminación de registros (DELETE), asegurando la integridad de las variables entre peticiones.

## 🛠️ Tecnologías y Herramientas Utilizadas
- **Postman**: Diseño de la colección, variables de entorno y scripts de aserciones en JavaScript.
- **Newman**: Ejecución CLI de pruebas en entornos de integración continua (Headless Execution).
- **htmlextra**: Generación de reportes ejecutivos visuales e interactivos en HTML.
- **Git & GitHub**: Control de versiones y publicación de portafolio.

## ⚙️ Pre-requisitos
Asegúrate de tener instalado:
- [Node.js](https://nodejs.org/) (v14 o superior)
- [Newman](https://www.npmjs.com/package/newman) (`npm install -g newman`)
- [Newman Reporter HTMLExtra](https://www.npmjs.com/package/newman-reporter-htmlextra) (`npm install -g newman-reporter-htmlextra`)

## 🚀 Cómo Ejecutar las Pruebas

### 1. Clonar el repositorio
```bash
git clone https://github.com/Ernesto-Especiano-QA/API-Automation-RestfulBooker-Postman-Newman.git 
cd API-Automation-RestfulBooker-Postman-Newman