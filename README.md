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
