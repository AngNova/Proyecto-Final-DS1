**1.Descripción General del Sistema**
El Sistema de Gestión de Inventario es una aplicación desarrollada en C# con Windows Forms que permite a los usuarios gestionar productos, categorías y proveedores en una tienda o almacén. Las principales características del sistema incluyen la capacidad de agregar, editar, eliminar y consultar productos, así como generar reportes sobre el estado del inventario.

**2.Objetivos:**
Facilitar la gestión de inventario de productos.
Permitir el control y la consulta de datos por categorías, proveedores y stock.
Generar alertas de inventario bajo.
Proveer una interfaz amigable y sencilla para los usuarios.

**3.Módulos del Sistema**

**Módulo de Productos**
**Funcionalidades**: Agregar, editar, eliminar y consultar productos.
Atributos: Nombre, Código de Producto, Categoría, Precio, Existencia, Proveedor.
**2. Módulo de Categoría**s
**Funcionalidades:** Gestión de categorías de productos.
Atributos: ID de Categoría, Nombre de Categoría, Descripción.
**3. Módulo de Proveedores**
Funcionalidades: Agregar y gestionar proveedores de productos.
Atributos: ID de Proveedor, Nombre de la Empresa, Contacto, Dirección, Teléfono.
**4. Consultas y Reportes**
Consultar productos por categoría o proveedor.
Generar reportes de productos con stock bajo (menos de 10 unidades).

**4.Estructura de la Base de Datos**

El sistema utiliza una base de datos SQLite con tres tablas principales: Productos, Categorías, y Proveedores.

**5.Conexión a la Base de **Datos** SQLite**

**Para manejar la conexión a la base de datos SQLite, se creó una clase llamada Database que maneja la apertura y cierre de la conexión.**

**6. Interfaz de Usuario**

**Componentes:**
TextBox para ingresar información de productos.
DataGridView para visualizar los productos.
Botones: Agregar, Editar, Eliminar, Consultar.

7.**Funciones**

Agregar Producto
Editar Producto
Eliminar Producto
