# Pago-en-Websites
TechStore
1. Descripción del Proyecto

TechStore es una tienda web funcional construida como proyecto de portafolio. Permite a los usuarios registrarse, iniciar sesión, agregar productos a un carrito y completar el pago de forma segura mediante Stripe.

El objetivo del proyecto es demostrar habilidades en desarrollo web full-stack, integración de pagos y seguridad básica de aplicaciones web.

2. Estructura de Archivos

El proyecto está organizado de la siguiente manera:

tienda_web/
├── app.py                # Servidor principal (Flask)
├── database.py           # Base de datos (SQLite)
├── auth.py               # Seguridad (contraseñas y tokens)
├── requirements.txt      # Librerías necesarias
├── .env.example          # Variables de entorno (plantilla)
├── templates/            # Páginas HTML
│   ├── base.html
│   ├── index.html
│   ├── login.html
│   ├── registro.html
│   ├── carrito.html
│   ├── pago_exitoso.html
│   └── pago_cancelado.html
│
└── static/
    ├── css/style.css     # Estilos visuales
    └── js/main.js        # JavaScript del frontend
3. Características
Registro e inicio de sesión de usuarios
Carrito de compras
Integración de pagos con Stripe
Sistema básico de autenticación
Diseño responsive
Separación entre frontend y backend
4. Tecnologías Utilizadas
Python
Flask
SQLite
HTML5
CSS3
JavaScript
Stripe API
5. Instalación

Clona el repositorio:

git clone https://github.com/LuiM7/techstore.git

Entra a la carpeta del proyecto:

cd techstore

Instala las dependencias:

pip install -r requirements.txt

Configura las variables de entorno:

cp .env.example .env

Ejecuta el proyecto:

python app.py
