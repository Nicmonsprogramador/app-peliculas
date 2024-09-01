Descripción
QuickbetMovies es una aplicación web que permite a los usuarios explorar, buscar y administrar una colección de películas. El proyecto incluye tanto el frontend como el backend, permitiendo una experiencia completa para el usuario final. Este proyecto está diseñado para demostrar las habilidades en desarrollo FullStack, abarcando desde la creación de interfaces de usuario hasta la gestión de bases de datos y APIs.

Características
Visualización de Películas: Lista de películas con detalles, como título, género, sinopsis y calificación.
Búsqueda y Filtros: Búsqueda de películas por título y filtrado por género.
Autenticación: Sistema de autenticación de usuarios (registro, inicio de sesión, logout).
Gestión de Películas: Funcionalidades para agregar, editar y eliminar películas (disponible para usuarios administradores).
Interfaz de Usuario Responsiva: Adaptada para diferentes dispositivos (móviles, tabletas, escritorios).
Tecnologías Utilizadas
Frontend
React/Angular/Vue.js: Framework para la construcción de interfaces de usuario.
CSS/SCSS: Estilización de la aplicación.
Axios/Fetch: Para la realización de solicitudes HTTP al backend.
Redux/Vuex/Context API: Gestión del estado de la aplicación.
Backend
Node.js con Express/Django: Framework para el desarrollo del servidor y las APIs.
MongoDB/MySQL/PostgreSQL: Base de datos para el almacenamiento de películas y usuarios.
JWT (JSON Web Tokens): Implementación de autenticación y autorización.
Mongoose/Sequelize: ORM para la gestión de la base de datos.
Instalación y Configuración
Prerrequisitos
Node.js y npm/yarn instalados en tu máquina.
MongoDB/MySQL/PostgreSQL configurado y en ejecución.
Instrucciones de Instalación
Clonar el repositorio:

bash
Copiar código
git clone https://github.com/tu-usuario/quickbetmovies.git
cd quickbetmovies
Configuración del Backend:

Navega al directorio del backend:
bash
Copiar código
cd backend
Instala las dependencias:
bash
Copiar código
npm install
Crea un archivo .env con las siguientes variables:
makefile
Copiar código
DB_URI=<tu_conexion_a_base_de_datos>
JWT_SECRET=<tu_secreto_para_jwt>
Inicia el servidor:
bash
Copiar código
npm start
Configuración del Frontend:

Navega al directorio del frontend:
bash
Copiar código
cd ../frontend
Instala las dependencias:
bash
Copiar código
npm install
Configura la URL del backend en tu aplicación frontend (si es necesario).
Inicia la aplicación frontend:
bash
Copiar código
npm start
Acceso a la Aplicación:

La aplicación estará disponible en http://localhost:3000 (puerto por defecto de React/Vue.js) o http://localhost:4200 (Angular).
La API estará en http://localhost:5000 (puerto por defecto de Express/Django).
Uso
Usuarios Regulares: Pueden explorar la lista de películas, buscar y ver detalles.
Usuarios Administradores: Pueden agregar, editar y eliminar películas.
Pruebas
Pruebas Unitarias
Ejecuta las pruebas unitarias con:
bash
Copiar código
npm test
Asegúrate de que tanto el frontend como el backend estén bien cubiertos por las pruebas.
Pruebas de Integración
Verifica que las interacciones entre el frontend y el backend funcionen como se espera.
Despliegue
Frontend: Compila y despliega el frontend en un servidor web como Nginx.
Backend: Despliega el backend en un servidor (puedes usar Heroku, AWS, DigitalOcean).
Configuración del Dominio: Configura tu dominio personalizado y ajusta las URLs del frontend y backend en consecuencia.
Contribuciones
Las contribuciones son bienvenidas. Por favor, sigue las siguientes instrucciones para contribuir:

Haz un fork del proyecto.
Crea una nueva rama (git checkout -b feature/nueva-caracteristica).
Haz los commits necesarios (git commit -m 'Agrega nueva característica').
Haz push a la rama (git push origin feature/nueva-caracteristica).
Abre un Pull Request.
Licencia
Este proyecto está bajo la Licencia MIT - consulta el archivo LICENSE para más detalles.

Contacto
Para cualquier pregunta o sugerencia, por favor contacta a nmonsalve28@misena.edu.co

