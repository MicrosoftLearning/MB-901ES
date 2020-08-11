---
lab:
    title: 'Laboratorio 01: Explore Dynamics 365 Supply Chain Management'
    module: 'Módulo 08: Introducción a Dynamics 365 Supply Chain Management'
---

# MB-901: Fundamentos de Dynamics 365 
## Módulo 8, Laboratorio 1 - Explore Dynamics 365 Supply Chain Management

### Crear un producto

En **USMF**, debe crear un nuevo elemento para una nueva configuración del gabinete que se comprará a los proveedores. 

1. Vaya a **Gestión de información de productos** > **Productos>Productos emitidos**.
1. Haga clic en **Nuevo**. 
1. En el campo **Tipo de producto**, seleccione **Artículo**
1. En el campo **Subtipo de producto**, seleccione **Producto**
1. En el campo **Número de producto**, escriba **GTL007**
1. En el campo **Nombre de producto**, escriba **Gabinete 2**
1. En el campo **Grupo de modelos de artículo**, seleccione **FIFO** (el último en entrar es el primero en salir)
1. En el campo **Grupo de artículos**, seleccione **Televisión y vídeo**
1. En el campo **Grupo de dimensiones de almacenamiento**, seleccione **SiteWH**
1. En el campo **Grupo de dimensiones de seguimiento**, seleccione **Ninguno**.
1. En el campo **Unidad de inventario**, seleccione **EA** (cada uno)
1. En el campo **Unidad de compra**, seleccione **EA** (cada uno)
1. En el campo **Unidad de ventas**, seleccione **EA** (cada uno)
1. En el campo **Unidad de L. MAT**, seleccione **EA** (cada uno)
1. En el campo **Precio de compra**, introduzca **"30,00"**
1. En el campo **Precio de venta**, introduzca **30,00**
1. En el campo **Fiscalidad de ventas, Grupo de impuestos de artículos**, seleccione **TODO** (todos los códigos de impuestos de ventas)
1. En el campo **Fiscalidad de compras, Grupos de impuestos de artículo**, seleccione **TODO** (todos los códigos de impuestos de ventas)
1. Haga clic en **Aceptar**.
1. Haga clic en **Validar** para garantizar que el producto esté completamente finalizado. Este botón se encuentra en el panel de acciones "Producto".
1. Cierre todas las páginas. 

### Cree productos maestros

En **USMF**, debe crear un nuevo artículo (una camiseta con cuello de pico) que comprar.  Este artículo estará disponible en tamaños pequeño, mediano y grande, y vendrá en los siguientes colores: Negro y rojo.

1. Vaya a **Gestión de información de productos** > **Productos** > **Productos emitidos**.
1. Haga clic en **Nuevo**.
1. En el campo **Tipo de producto**, seleccione **Artículo**
1. En el campo **Subtipo de producto**, seleccione **Producto maestro**
1. En el campo **Número de producto**, escriba **GTLPM001**
1. En el campo **Nombre del producto**, escriba **Camiseta con cuello en V**
1. En el campo **Nombre de búsqueda**, escriba **CamisetaCuelloEnV**
1. En el campo **Categoría comercial**, seleccione **Ropa y calzado**      
1. En el campo **Grupo de dimensiones de producto**, seleccione **ColorTamaño**
1. En el campo **Tecnología de configuración**, seleccione **Variante predefinida**
1. En el campo **Grupo de modelos de artículo**, seleccione **FIFO** (el último en entrar es el primero en salir)
1. En el campo **Grupo de artículos**, seleccione **Audio** 
1. En el campo **Grupo de dimensiones de almacenamiento**, seleccione **SiteWH**
1. En el campo **Grupo de dimensiones de seguimiento**, seleccione **Ninguno**.
1. En el campo **Unidad de inventario**, seleccione **EA** (cada uno)
1. En el campo **Unidad de compra**, seleccione **EA** (cada uno)
1. En el campo **Unidad de ventas**, seleccione **EA** (cada uno)
1. En el campo **Unidad de L. MAT**, seleccione **EA** (cada uno)
1. En el campo **Fiscalidad de ventas, Grupo de impuestos de artículos**, seleccione **TODO** (todos los códigos de impuestos de ventas)
1. En el campo **Fiscalidad de compras, Grupo de impuestos de artículo**, seleccione **TODO** (todos los códigos de impuestos de ventas)
1. En el campo **Precio de compra**, introduzca **"19,95"**
1. En el campo **Precio de venta**, escriba **"29,95"**
1. Haga clic en **Aceptar**. **parte que falta**
1. Cierre todas las páginas.
1. Vaya a **Gestión de información de productos** > **Productos** > **Productos emitidos**.
1. Usar el filtro de búsqueda rápida por número de artículo con **GTLS001**
1. Haga clic en el artículo **GTLS001** para abrir el registro del producto maestro.
1. Haga clic en el botón **Dimensiones de producto** del panel **Acción de producto**.
1. Seleccione la pestaña **Tamaños**.
1. Haga clic en **Nuevo en la sección Definir tamaños para un producto maestro**.
1. En el campo **Tamaño**, escriba **Pequeño**.
1. En el campo **Nombre**, escriba **Pequeño**.
1. En el campo **Descripción**, introduzca **Tamaño pequeño**.
1. Haga clic en **Nuevo**.
1. En el campo **Tamaño**, escriba **Medio**.
1. En el campo **Nombre**, escriba **Medio**.
1. En el campo **Descripción**, escriba **Tamaño medio**.
1. Haga clic en **Nuevo**.
1. En el campo **Tamaño**, escriba **Grande**.
1. En el campo **Nombre**, introduzca **Grande**.
1. En el campo **Descripción**, introduzca **Tamaño grande**.
1. Seleccione la pestaña **Colores**.
1. Haga clic en **Nuevo**, en la sección **Definir tamaños para un producto maestro**.
1. En el campo **Color**, escriba **Negro**.
1. En el campo **Nombre**, escriba **Negro**.
1. En el campo **Descripción**, introduzca el color **Negro**.
1. Haga clic en **Nuevo**.
1. En el campo **Nombre**, introduzca **Rojo**.
1. En el campo **Descripción**, introduzca el color **Rojo**.
1. Haga clic en **Guardar**.
1. Cierre el formulario.
1. Seleccione el botón **Variantes de productos emitidos** del panel de acciones **Producto**.
1. Haga clic en **Sugerencias de variantes** en el panel de acciones **Variante del producto**.
1. Haga clic en **Seleccionar todo**.
1. Haga clic en **Crear**.
1. Cierre todas las páginas.  

### Crear un pedido de compra

Cree un pedido de compra para Acme Office Supplies, que se entregará hoy, con 5 artículos con número de artículo T0003 que se entregarán a Site 1 y 5 artículos de M1101 Foam Reacting Agent, que se entregarán al centro de pruebas de calidad de 123 W. Cherry Street, código postal 83642.

1. Vaya a **Adquisición y abastecimiento** > **Pedidos de compra** > **Todos los pedidos de compra**.
1. Haga clic en **Nuevo**.
1. **Cuenta del proveedor:** Seleccione **1001** (Suministros de oficina Acme)
1. **Fecha de entrega:** Verifique la fecha actual en el campo **Fecha de entrega** (este debe ser el valor predeterminado).
1. Haga clic en **Aceptar**.

### Agregar artículos al pedido de compra

1. **Número de artículo:** Seleccione **T0003**.
1. **Cantidad:** Escriba **5**.
1. **Unidad:** Escriba **EA**. 
1. Haga clic en **Agregar línea**
1. **Número de artículo:** Seleccione **C0004**.
1. **Cantidad:** Escriba **4**.
1. **Unidad:** escriba **piezas**.

### Seleccione las direcciones de entrega de los artículos

1. Seleccione la línea del artículo **T0003** en la ficha desplegable **Líneas de pedido de compra**.
1. En la ficha desplegable **Detalles de líneas**, cambie a la pestaña **Dirección**.
1. Cambie la **Dirección de entrega** a **Contoso Entertainment System USA**.
1. Seleccione la línea del artículo **C0004** en la ficha desplegable **Líneas de pedido de compra**.
1. Cambie a la ficha desplegable **Dirección**.  
1. Haga clic en el botón **Añadir dirección** **(+)**, situado a la derecha del campo **Dirección de entrega**.
1. **Nombre o descripción:** Introduzca **Centro de pruebas de calidad**.
1. **Código postal:** Escriba **83642**.
1. **Calle:** Introduzca **123 W. Cherry Street**.
1. Haga clic en **Aceptar**.
1. Haga clic en **Guardar**.
1. En el **panel de acciones**, haga clic en **Compra**.  
1. Haga clic en **Confirmar**.
1. En el **panel de acciones**, haga clic en **Recibir**.
1. Haga clic en **Recepción de producto**.
1. En el campo **Recepción de producto**, introduzca un número de recepción de producto. Por ejemplo, introduzca **PR123**.
1. Haga clic en **Aceptar** para publicar la recepción del producto.  
1. Cierre todas las páginas.  

### Crear pedidos de ventas

Este procedimiento muestra cómo crear un pedido de ventas. Puede usar el procedimiento en la compañía de datos de demostración USMF. Los pedidos de ventas generalmente se crean mediante un procesador de pedidos de ventas.

1. Vaya a **Ventas y marketing** > **Pedidos de ventas** > **Todos los pedidos de ventas**.
1. Haga clic en **Nuevo**.
1. En el campo **Cuenta de cliente**, haga clic en el botón desplegable para abrir la búsqueda.
1. En la lista, busque y seleccione el cliente **US-004**.
1. Haga clic en **Aceptar**.
1. Haga clic en **Línea de pedido de ventas**.
1. Haga clic en **Dimensiones**.
1. Para este ejemplo, seleccione Color, Ubicación y Dimensiones del almacén. Las dimensiones que seleccione aquí aparecerán en la cuadrícula de pedidos de venta. Si desea mantener sus selecciones, configure la opción **Guardar configuración** a **Sí**.
1. Haga clic en **Aceptar**.
1. En el campo **Número de artículo**, haga clic en el botón desplegable para abrir la búsqueda.
1. Para este ejemplo, seleccione el número de artículo **T0004**.
1. En el campo **Color**, seleccione el botón desplegable para abrir la búsqueda.
1. En la lista, busque y seleccione **Negro**.
1. En el campo **Cantidad**, escriba **1**.
1. En el **panel de acciones**, haga clic en **Pedido de ventas**.
1. Haga clic en **Totales**.
1. La página Totales muestra detalles sobre todo el pedido. Esto incluye el importe subtotal (una suma de todos los importes netos de las líneas que se ajustan para eventuales descuentos de las línea), el importe total de la factura (un importe subtotal que se ajusta para eventuales descuentos a nivel de pedido, cargos y el impuesto sobre las ventas) y la situación del límite de crédito del cliente, entre otros. El importe de la factura es el importe que aparecerá en el documento de la factura del cliente.
1. Haga clic en **Aceptar**.  
