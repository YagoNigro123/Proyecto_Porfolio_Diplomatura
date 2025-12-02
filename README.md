# Yago Nigro - Portfolio Web

Este proyecto fue desarrollado como entrega final para la Diplomatura en Desarrollo Web Full Stack.
La aplicación integra frontend y backend de forma completa, aplicando las principales tecnologías aprendidas durante la cursada.

En el backend utilicé Node.js y Express, implementando una arquitectura modular que permite gestionar y actualizar los proyectos del portfolio de manera dinámica. Para la capa de vistas incorporé Handlebars, lo que aporta mayor organización, reutilización de componentes y separación clara de responsabilidades.

El sistema incluye además un formulario de contacto funcional que utiliza Nodemailer para el envío de correos a través de Gmail. Este proceso se realiza mediante una API dedicada, asegurando una comunicación estable, segura y fácil de mantener.

El proyecto fue concebido originalmente como mi portfolio profesional. Si bien decidí no utilizarlo finalmente debido a mi autoexigencia y estándares actuales, continúa totalmente operativo y representa una excelente demostración del dominio de tecnologías full stack, buenas prácticas y estructura de proyecto escalable.

## Video del proyecto
https://youtu.be/CoJ1xo-MklY

<img width="1154" height="630" alt="Captura de pantalla 2025-09-04 134253" src="https://github.com/user-attachments/assets/ba8063be-c4f0-4188-b0d6-abf7375f534e" />

---

## Tecnologías utilizadas

- **Frontend:** React.js, HTML5, CSS3, JavaScript
- **Backend:** Node.js, Express.js
- **Base de datos:** MySQL
- **Autenticación:** JWT (JSON Web Tokens)
- **Correo:** Envío de emails desde formularios de contacto

---

## Instalación y uso

1. **Clona el repositorio:**
   ```bash
   git clone git@github.com:YagoNigro123/Portfolio.git
   ```

2. **Configura y ejecuta el backend:**
   ```bash
   cd back
   npm install
   npm start
   ```
   > Asegúrate de tener configurado el archivo `.env` con tus variables de entorno (puerto, credenciales de base de datos, etc).

3. **Configura y ejecuta el frontend:**
   ```bash
   cd ../front
   npm install
   npm start
   ```
   > El frontend estará disponible en [http://localhost:3000](http://localhost:3000) por defecto.

---

## Estructura del proyecto

```
portfolio/
│
├── back/        # Backend (Node.js, Express, MySQL)
└── front/       # Frontend (React.js)
```

---

## Funcionalidades principales

- Visualización de proyectos destacados
- Descarga de CV en PDF
- Página de certificados
- Formulario de contacto con envío de emails
- Autenticación de usuarios (admin)
- Panel de administración para gestión de proyectos

---

## 📬 Contacto

- **Email:** yago.gn007@gmail.com
- **GitHub:** [YagoNigro123](https://github.com/YagoNigro123)
- **LinkedIn:** [Yago Nigro](https://www.linkedin.com/in/yagonigro/)

---

¡Gracias por visitar mi portfolio!
