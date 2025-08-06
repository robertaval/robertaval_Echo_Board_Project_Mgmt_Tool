🧩 Echo Board Herramienta de Gestión de Proyectos


Una aplicación moderna full-stack desarrollada con React y Python Flask, diseñada para facilitar la colaboración en equipo y el seguimiento de tareas.

🚀 Funcionalidades

Autenticación de Usuarios: Sistema seguro de inicio de sesión y registro.

Gestión de Tareas: Crear, actualizar y eliminar tareas fácilmente.

Actualizaciones en Tiempo Real: Sincronización instantánea entre todos los usuarios.

Diseño Responsivo: Adaptable para su uso en cualquier dispositivo.

🔧 Tecnologías
Frontend: React, Redux, Axios

Backend: Python, Flask, SQLAlchemy

Base de Datos: PostgreSQL

Autenticación: JWT (JSON Web Tokens)

Estilos: Bootstrap 5

Despliegue: Render, Gitpod

🛠️ Instalación
Clona el repositorio
bash
Copy
Edit
git clone https://github.com/robertaval/robertaval_Echo_Board_Project_Mgmt_Tool.git
cd robertaval_Echo_Board_Project_Mgmt_Tool
Configuración del Backend
Entra en el directorio backend:

bash
Copy
Edit
cd backend
Instala las dependencias:

bash
Copy
Edit
pip install -r requirements.txt
Configura las variables de entorno copiando el archivo de ejemplo:

bash
Copy
Edit
cp .env.example .env
Aplica las migraciones de base de datos:

bash
Copy
Edit
flask db upgrade
Ejecuta el servidor Flask:

bash
Copy
Edit
flask run
Configuración del Frontend
Entra en el directorio frontend:

bash
Copy
Edit
cd ../frontend
Instala las dependencias:

bash
Copy
Edit
npm install
Inicia el servidor de desarrollo:

bash
Copy
Edit
npm start
La aplicación estará disponible en http://localhost:3000.

📸 Capturas de pantalla


Panel principal mostrando las tareas del proyecto.



Vista detallada de una tarea seleccionada.

📈 Estructura del Proyecto
bash
Copy
Edit
/backend
  /app
    /models
    /routes
    /utils
  /migrations
  /tests
  .env
  requirements.txt
/frontend
  /public
  /src
    /components
    /redux
    /styles
  package.json
  .gitignore
.gitignore
README.md
🧪 Pruebas
Las pruebas del backend están en /backend/tests. Para ejecutarlas:

bash
Copy
Edit
pytest
Las pruebas del frontend están en /frontend/src/tests. Para ejecutarlas:

bash
Copy
Edit
npm test
🌍 Contribuciones
¡Se aceptan contribuciones! Para comenzar:

Haz un fork del repositorio.

Crea una nueva rama (git checkout -b nombre-rama).

Realiza tus cambios.

Haz commit de los cambios (git commit -am 'Agrega funcionalidad').

Envía la rama al repositorio remoto (git push origin nombre-rama).

Abre un Pull Request.

📬 Contacto
Email: roberta_valyte@hotmail.com

LinkedIn: linkedin.com/in/roberta-valyte

Portafolio: github.com/robertaval
