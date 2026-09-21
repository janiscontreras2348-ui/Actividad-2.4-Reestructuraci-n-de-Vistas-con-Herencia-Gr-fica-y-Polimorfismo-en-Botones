Actividad: Capa de Modelos - Sistema de Biblioteca
Integrantes del Equipo
CONTRERAS Rodríguez Janis Isabel
TORRES Barrera José Ángel
MACÍAS Cruz Meredith Miranda
Descripción del Proyecto
Este proyecto corresponde a la capa de dominio/modelos de un sistema de gestión de biblioteca escolar desarrollado en C# (.NET). Implementa la lógica de encapsulamiento, herencia, validación de datos, sobrecarga de constructores y métodos de negocio para 10 entidades principales del sistema.

Estructura de Entidades ( Models/)
Persona (Clase Base)
Autores (Hereda de Persona)
Usuarios (Hereda de Persona)
Administrador (Hereda de Persona)
Libros
Prestamos
Género
Editorial
Multa
Reserva
Instrucciones para ejecutar las pruebas
Clonar o descargar este repositorio.
Abrir la solución .slnen Visual Studio .
Asegúrese de que el proyecto Biblioteca esté configurado como proyecto de inicio.
Compilar y ejecutar la solución ( F5o Ctrl + F5).
La consola ejecutará las pruebas de las clases ( Program.cs), demostrando:
Creación de objetos con constructores vacíos y parametrizados.
Captura de excepciones al ingresar datos inválidos ( try-catch).
Ejecución de sobrecarga de métodos de negocio.
Salida formateada con ToString().
