⸻

🌿 Masaya Glamping

Masaya Glamping es un sistema web desarrollado en PHP + MySQL, diseñado para la gestión de reservas, usuarios y administración de un glamping (cabañas turísticas).
Permite a los visitantes registrarse, iniciar sesión y reservar cabañas, mientras los administradores pueden gestionar usuarios, empleados, reservas y alojamientos desde un panel interno.

⸻

🚀 Características principales
	•	🏕️ Visualización de cabañas con fotos, precios y características.
	•	👤 Registro e inicio de sesión de usuarios.
	•	📅 Sistema de reservas con fechas y servicios adicionales.
	•	🧑‍💼 Panel administrativo para gestionar usuarios, empleados, cabañas y reservas.
	•	💾 Base de datos MySQL con estructura optimizada.
	•	🔒 Validación de datos y conexión segura mediante mysqli.

⸻

⚙️ Tecnologías utilizadas
	•	Backend: PHP 8.x
	•	Base de datos: MySQL / MariaDB
	•	Servidor local: XAMPP
	•	Frontend: HTML5, CSS3, Bootstrap, jQuery
	•	Plugins: FlexSlider, Swipebox, DataTables, jQuery UI

⸻

🧩 Estructura del proyecto

Caba-as/
│
├── admin/                # Panel de administración
├── users/                # Vistas del usuario (login, reserva, detalle, etc.)
├── bd/                   # Base de datos (glamping_db.sql)
├── css/ , js/ , images/  # Archivos estáticos
├── db.php                # Conexión a MySQL
├── index.php             # Página principal (landing)
└── README.md             # Este archivo


⸻

💻 Instalación rápida
	1.	Instala XAMPP y activa Apache + MySQL
	2.	Copia el proyecto en la carpeta htdocs
	3.	Importa bd/glamping_db.sql en phpMyAdmin
	4.	Verifica db.php y ajusta credenciales si es necesario
	5.	Accede desde tu navegador:
	•	Sitio público: http://localhost/Caba-as/￼
	•	Panel admin: http://localhost/Caba-as/admin/login.php￼

⸻

🛠️ Funcionalidades para desarrolladores
	•	Estructura modular y comentada en PHP
	•	Uso de mysqli con prepared statements
	•	Rutas limpias y separadas por roles (users / admin)
	•	Base de datos con relaciones: usuarios, cabanas, reservas, empleado

⸻

🔐 Recomendaciones
	•	Cambiar credenciales de conexión antes del despliegue
	•	Usar password_hash() y password_verify() para contraseñas
	•	Proteger formularios con tokens CSRF
	•	Habilitar HTTPS en entornos productivos

⸻

📷 Capturas (opcional)

(Puedes agregar imágenes aquí cuando el proyecto esté corriendo)
Ejemplo:

/screenshots/home.png
/screenshots/admin-panel.png


⸻

👨‍💻 Autor

Desarrollado por Santiago Hernández Zambrano
📧 Contacto: [santiago_hez14@gmail.com]
💼 Proyecto académico — Entorno local con XAMPP

⸻
