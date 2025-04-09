# 🎓 Proyecto TFG: Aplicación Antiguos Alumnos

**👤 Autora:** Pilar Pagés Vallejo  
**📚 Grado:** Desarrollo de Aplicaciones Web (DAW)  
**🏫 Centro:** IES Punta del Verde  
**📅 Año académico:** 2025  


---

## 🧩 Descripción del proyecto

Esta aplicación web tiene como objetivo permitir que antiguos alumnos de colegios e institutos puedan **reencontrarse y comunicarse**, facilitando así la conexión entre compañeros del pasado.

Los alumnos se registran en una plataforma, pueden **buscar a otros usuarios**, **enviarles mensajes** y, en el caso de los administradores, gestionar **tareas automáticas generadas por la actividad** de los usuarios.

---

## 🎯 Objetivos principales

- ✅ Permitir el registro e inicio de sesión de usuarios.
- 🔍 Implementar un buscador avanzado para encontrar compañeros.
- ✉️ Desarrollar un sistema de mensajería interna entre usuarios.
- 🛠️ Crear un panel de tareas para administradores.
- 🔒 Establecer un sistema de roles con control de acceso seguro.

---

## 🛠️ Tecnologías utilizadas

| Área           | Tecnología                            |
|----------------|----------------------------------------|
| Lenguaje       | PHP                                    |
| Framework      | Laravel (Blade Templates)              |
| Base de datos  | MySQL                                  |
| Estilos        | Bootstrap                              |
| Entorno local  | Laravel Herd, XAMPP                    |
| Editor         | Visual Studio Code                     |
| Control de versiones | Git y GitHub                    |

---

## 🚀 Cómo instalar y ejecutar el proyecto

```bash
# Clona este repositorio
git clone https://github.com/Pilipa-VivaerBetis/AAA-TFG.git

# Entra en el directorio del proyecto
cd AAA-TFG

# Instala dependencias
composer install
npm install && npm run dev

# Copia el archivo de configuración
cp .env.example .env

# Genera la clave de aplicación
php artisan key:generate

# Crea la base de datos (configurada en .env)
php artisan migrate

# Inicia el servidor de desarrollo
php artisan serve

🖼️ Funcionalidades principales
🧑‍🎓 Usuarios normales:
Registro y login

Buscar compañeros por nombre, curso, colegio, etc.

Enviar y recibir mensajes

Ver historial de conversaciones

Actualizar datos del perfil

🧑‍💼 Administradores:
Panel de tareas

Visualización de mensajes enviados

Asignación automática de tareas al recibir mensajes

Gestión de usuarios

🧪 Pruebas y seguridad
✅ Hash de contraseñas con bcrypt

✅ Rutas protegidas según el rol

✅ Validación en formularios

✅ Manejo de sesiones y logout

✅ Pruebas funcionales básicas

📄 Licencia
Este proyecto ha sido desarrollado como parte del Trabajo de Fin de Grado en DAW.
Uso educativo y sin fines comerciales.

📚 Bibliografía y recursos consultados
Laravel Documentation

Bootstrap 5

YouTube - Laravel + Herd

GitHub Docs

💬 Contacto
📧 pilipa2000@gmail.com
🔗 GitHub - Pilipa-VivaerBetis

¡Gracias por visitar este repositorio! 😊
Si tienes sugerencias, no dudes en abrir un issue o contactarme.

