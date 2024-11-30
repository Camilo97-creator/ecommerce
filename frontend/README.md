# Proyecto E-comerce MERN

Este proyecto de ecmomerce desarrollado con el stack MERN (MongoDB, Express, React, y node.js). El sistema permite a los usuarios navegar por categorías de productos, ver detalles de los productos, agregar productos al carrito y procesar compras. Los administradores pueden gestionar prodcutos, categorías, y órdenes.

## Scripts disponibles

En el directorio del proyecto, puedes ejecutar:

### `npm start`

Ejecuta la aplicación en modo de desarrollo.\
Abre [http://localhost:3000](http://localhost:3000) para verla en tu navegador.
La página se volverá a cargar cuando realices cambios.\
También puedes ver errores de lint en la consola.

### Descripción del proyecto

El Ecommerce se creo en 2 parte principales:

-**Fronted**: Construido en React, con una interfaz interactiva y fácil de usar. Permite a los usuarios a realizar compras, agregar prodcutos al carrito y navegar por diferentes categorías.

-**Backend**: Configura con JavaScripts y con Express, proporciona los puntos finales necesarios para gestionar productos, categorías, usauario y órdenes. Además se utilizan JWT para autenticar a los usuarios y controlar el acceso de los administradores.

### Funcionalidades princiales:

- Navegar por categorías de prodcutos.
- Ver detalles de prodcutos.
- Agregar productos al carrito y realizar compras.
- Autenticación de usuarios con JWT.
- Administración de productos, categorías y órdenes con control de acceso.

## Tecnoologías Utilizadas

- **Frontend**: React, API (para gestión del estado), HTML, CSS Y JavaScript.
- **Backend**: Node.js, express, JWT.
- **Base de datos**: MongoDB, Postgress, Mongoose.
- **Control de versiones**: Git, GitHub.

## Configuración del Backend

- Navega al direcotrio = cd backend.
- Instala dependencias = npm install.

## Configuración del Frontend

- Navega  al directorio = cd frontend.
- Instala dependencias = npm install.

## Estructura de la base de datos
Las colecciones de la base de datos son:

    - Usaurios: Almacena infromación de los usuarios, incluidas las credenciales para la autenticación.
    - Prodcutos: Almacena los prodcutos disponibles para la venta.
    - Categorías: Almacena las categorías de prodcutos.
    - Carrito: Almacena el carrito de compras de cada usuario.
    - Órdeens: Almacena la información de las órdenes realizadas por los usuarios.