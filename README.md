# 🍦 Danieladas – API y Aplicación Móvil

## Descripción
Danieladas es una aplicación desarrollada para neverías que permite a los clientes realizar pedidos desde su dispositivo móvil.  
El sistema gestiona los pedidos en tiempo real, mejora la atención al cliente y optimiza el trabajo de los empleados.

---

## ⚙ Dependencias principales
Estas son las herramientas y librerías utilizadas en el proyecto:

- **Node.js** – Entorno de ejecución para el backend.  
- **Express** – Framework para crear la API REST.  
- **MongoDB** – Base de datos en la nube para almacenar usuarios y pedidos.  
- **Mongoose** – Librería para conectar Node.js con MongoDB.  
- **jsonwebtoken (JWT)** – Para la autenticación de usuarios.  
- **dotenv** – Para manejar variables de entorno de forma segura.  
- **Cors** – Para permitir conexiones entre la app móvil y la API.

---

## 🔄 Flujo de datos
1. El usuario realiza una acción en la **aplicación móvil (Cordova)**, como registrarse o iniciar sesión.  
2. La app envía una solicitud a la **API REST** mediante peticiones HTTP (`POST` o `GET`).  
3. La **API procesa la solicitud**, valida los datos y se conecta con la **base de datos MongoDB** en la nube.  
4. La respuesta se envía de vuelta a la app, mostrando si la acción fue exitosa o si ocurrió un error.

---

## 🔐 Medidas de seguridad aplicadas
- **Validación de entradas:** se verifican los datos enviados por el usuario (correo, contraseña, etc.) antes de procesarlos.  
- **Autenticación con tokens JWT:** cada usuario tiene un token único que valida su sesión y protege las rutas privadas.  
- **Manejo de errores:** se usan bloques `try...catch` para evitar que el servidor se detenga ante fallos.  
- **Uso de .env:** se protegen datos sensibles como la clave secreta del token y la conexión a la base de datos.  
- **Comunicación segura:** la conexión entre la app y la API se realiza mediante solicitudes HTTPS.

---

## 📌 Versión
Versión actual: **v1.0.0**  
Repositorio: [Estrategia_Versionamiento_Danieladas](https://github.com/Eduardo10974/Estrategia_Versionamiento_Danieladas.git)

---

## 👨‍💻 Autores
Proyecto desarrollado por el equipo de **Danieladas**, como parte de la integración técnica con servicios en la nube.
