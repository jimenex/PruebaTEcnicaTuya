# PruebaTecnicaTuya
***
El Api esta desarrollado con C# NetCore 6.0 utilizando Microsoft.EntityFrameworkCore y Microsoft.EntityFrameworkCore.SqlServer
***
# Metodos Desarrollados:
***
1. POST /api/CrearCliente: Permite la creación de clientes en el sistema.
2. POST /api/CrearProducto: Permite la creación de productos en el sistema.
3. GET /api/GetClientes: Retorna el listados de clientes registrados en el sistema.
4. GET /api/GetProductos: Retorna el listados de productos registrados el sistema.
5. POST /api/Facturas: Registra los Datos en las Tablas de Factura y Detalle de Factura, ademas que genera el Pedido.
6. GET /api/GetPedidoId: Retorna los datos del pedido generado segun el Id.
***
# Generalidades:
***
En la carpeta ApiRest se encuenta los fuentes de la solución.
En la Carpeta BaseDeDatos se encuentra la estructura de la Base de Datos.
Se debe tener en cuenta de modificar en appsettings.json el valor de ConexionMaestra con los datos de conexión de la Base de Datos.
