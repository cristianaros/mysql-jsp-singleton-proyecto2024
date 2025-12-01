📦 Proyecto Web en Java — Universidad (2024)
Aplicación web desarrollada utilizando Jakarta EE, JSP y JDBC, implementando arquitectura MVC y patrones de diseño como Singleton y Repository. El proyecto fue desplegado en Apache Tomcat, siguiendo buenas prácticas de modularidad, mantenibilidad y separación de responsabilidades.

Descripción
Este proyecto consiste en un sistema de administración que permite gestionar diversas entidades (usuarios, clientes, empleados y productos) mediante interfaces construidas con JavaServer Pages (JSP) totalmente integradas a una base de datos MySQL.
La aplicación está diseñada de forma escalable y organizada, orientada a ambientes académicos y de formación profesional.

Características Principales:
Arquitectura MVC completamente implementada.
Capas bien separadas: controladores, vistas y modelo.
JSP para la presentación y renderizado dinámico.
JDBC para la conexión directa con MySQL.
Patrón Singleton para la administración de la conexión a la base de datos.
Patrón Repository para encapsular lógica CRUD.
Despliegue en Apache Tomcat (versión 10+).

Formularios y vistas para agregar, editar, eliminar y listar los registros del sistema.
Tecnologías Utilizadas
Jakarta EE
JavaServer Pages (JSP)
Java 17+
JDBC
MySQL
Apache Tomcat 10+

Estructura del Proyecto
Modelo (Model)
Contiene las clases que representan las entidades del sistema y los repositorios para el manejo de datos.
Vista (View)
Controlador (Controller)
Servelts encargados de procesar solicitudes, administrar rutas, validar datos y comunicarse con los repositorios.

📂 Vistas JSP disponibles

El proyecto contiene múltiples vistas JSP orientadas a la administración del sistema:

index.jsp – Página principal.
login.jsp – Inicio de sesión.
logout.jsp – Cierre de sesión.
registrar.jsp – Registro de nuevos usuarios.
dashboard.jsp – Panel principal.
gestionUsuarios.jsp – Gestión de usuarios.
gestionProductos.jsp – Administración de productos.
agregarCliente.jsp, agregarProducto.jsp – Formularios de creación.
editarCliente.jsp, editarEmpleado.jsp, editarProducto.jsp – Formularios de edición.
resultado.jsp – Página para mostrar respuestas de operaciones.

🗄️ Base de Datos
El sistema utiliza una base de datos MySQL creada a partir del archivo:
proyecto.sql
Incluye tablas para:
Usuarios
Clientes
Empleados
Productos

Registros asociados según funciones del sistema
Archivos Incluidos
proyecto.sql – Estructura y datos iniciales de la base de datos.
mysql-connector-j-9.1.0.jar – Driver JDBC necesario para la conexión.
Diccionario de datos.pdf – Documentación técnica del modelo relacional.
ProyectoWeb [Cristian Aros].zip – Proyecto completo listo para importar en un IDE y ejecutar.

Instalación y Ejecución
1. Importar el proyecto
Descargar y extraer el contenido del archivo ZIP en el entorno de desarrollo (IntelliJ, Eclipse o NetBeans).
2. Configurar la base de datos
Crear una base de datos en MySQL.
Importar el archivo proyecto.sql.
3. Configurar conexión JDBC
Agregar el archivo mysql-connector-j-9.1.0.jar dentro de:
WEB-INF/lib/
4. Ejecutar en Tomcat
Configurar Apache Tomcat en el IDE.
Ejecutar el proyecto.

5. Acceder a la aplicación
http://localhost:8080/ProyectoWeb/

Estado del Proyecto
Proyecto académico funcional y apto para demostración, documentación o uso como base para sistemas web más complejos.

Autor:

Cristian Aros
Proyecto universitario – Ingeniería Civil Informática (2025)
