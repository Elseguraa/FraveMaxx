# Sistema de Gestión de Inventario para FraveMax

Este proyecto consiste en una aplicación Java con base de datos MySQL para gestionar el inventario de FraveMax, una empresa que vende electrodomésticos y productos para el hogar.

## Características principales

- **Gestión de Clientes:** Permite añadir, modificar, y eliminar clientes.
- **Gestión de Productos:** Facilita la administración del catálogo de productos disponibles.
- **Gestión de Ventas y Compras:** Registra las transacciones de compra y venta de productos.
- **Informes y Estadísticas:** Genera informes sobre ventas, inventario y más.

## Tecnologías utilizadas

- Java
- MySQL
- JDBC para la conexión a la base de datos

## Estructura del proyecto

- **`src/`**: Contiene los archivos fuente Java.
- **`sql/`**: Scripts SQL para la creación de la base de datos y tablas.
- **`docs/`**: Documentación adicional.

## Instrucciones de uso

1. **Configuración de la base de datos:**
   - Ejecutar el script `crear_base_datos.sql` en MySQL para crear la base de datos y las tablas necesarias.
   
2. **Configuración del proyecto:**
   - Importar el proyecto en tu IDE Java preferido.
   - Configurar la conexión JDBC en el archivo `ConexionBD.java` con los detalles de tu servidor MySQL.

3. **Compilación y ejecución:**
   - Compilar y ejecutar el proyecto desde tu IDE.

4. **Uso:**
   - Iniciar la aplicación y navegar por las opciones del menú para gestionar clientes, productos, ventas, etc.

## Contribución

Si deseas contribuir a este proyecto, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios.
4. Confirma los cambios (`git commit -am 'Añade nueva funcionalidad'`).
5. Sube los cambios a la rama (`git push origin feature/nueva-funcionalidad`).
6. Crea una solicitud de extracción.

## Autor

- Nombre: [Tu nombre]
- Contacto: [Tu email]

 
