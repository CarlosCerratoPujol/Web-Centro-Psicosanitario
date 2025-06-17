CrazyCarlos es un proyecto web desarrollado como parte de una práctica académica. Simula el sitio oficial de un centro psicosanitario, con funcionalidades adaptadas a distintos roles de usuario (pacientes, profesionales y administradores), ofreciendo tanto contenido informativo como dinámico.

🚀 Tecnologías utilizadas
Este proyecto se ha desarrollado de forma incremental, siguiendo distintas iteraciones que incorporan progresivamente nuevas funcionalidades y tecnologías:

HTML5 & CSS3

Bootstrap 5 – Diseño responsive y componentes predefinidos

JavaScript (vanilla) – Manipulación del DOM y validaciones

Node.js + Express.js – Servidor web y enrutamiento

EJS – Motor de plantillas para renderizado dinámico

MongoDB + Mongoose – Base de datos NoSQL para usuarios y pruebas médicas

📦 Estructura del proyecto
bash
Copiar
Editar
crazycarlos/
├── public/                # Recursos estáticos (CSS, JS, imágenes)
├── views/                 # Plantillas EJS
├── routes/                # Rutas Express (pacientes, pruebas, etc.)
├── models/                # Esquemas de Mongoose
├── data/                  # Datos simulados (usados en iteraciones previas)
├── app.js                 # Punto de entrada de la app
├── README.md              # Este archivo
🔄 Iteraciones del desarrollo
Iteración 0 – Sitio estático con HTML, CSS y Bootstrap.

Iteración 1 – Interactividad básica en el cliente con JavaScript.

Iteración 2 – Uso de Express.js para levantar un servidor local.

Iteración 3 – Integración con MongoDB y renderizado dinámico con EJS.

Iteración 4 – Manejo de sesiones, autenticación y control de roles (en progreso o planificado).

👥 Roles de usuario
Paciente: Puede ver sus pruebas médicas e información general.

Profesional: Accede al historial de pacientes y resultados.

Administrador: Control total del sistema, gestión de usuarios y contenido.

📌 Objetivos del proyecto
Aplicar los conocimientos adquiridos sobre desarrollo web full-stack.

Simular una aplicación realista con autenticación, roles y persistencia de datos.

Desarrollar siguiendo una metodología modular e incremental.

Cómo ejecutarlo localmente:
git clone https://github.com/CarlosCerratoPujol/Web-Centro-Psicosanitario.git
cd crazycarlos
npm install
npm start
