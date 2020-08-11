---
lab:
    title: 'Laboratorio 01: Explore Dynamics 365 Finance'
    module: 'Módulo 10: Introducción a Dynamics 365 Finance'
---

# MB-901: Fundamentos de Dynamics 365 
## Módulo 10, Laboratorio 1 - Explore Dynamics 365 Finance 


**Requisitos previos**: Antes de realizar los pasos de este laboratorio, realice las
siguientes tareas: 

**Nota:** Necesita un entorno implementado con datos de demostración antes de realizar
este laboratorio. Su instancia de aplicaciones Dynamics 365 Finance and Operations puede
lanzarse desde LCS o directamente a la URL de la instancia.

Deberá cambiar la compañía a **USMF.** Para iniciar sesión en la instancia de aplicaciones Dynamics 365 Finance and Operations, debe tener un nombre de usuario y una contraseña con un rol de seguridad de**Director Ejecutivo** o **Administrador del sistema**.

En caso de que su entorno no tenga datos de demostración, siga las instrucciones
abajo:

Navegue hasta **Módulos>Datos de demostración**, haga clic en **Generar datos** y luego haga clic en
    **Aceptar.**

### Importar tipos de cambio

1.  Cambiar empresa a **USMF.**

2.  Vaya a **Contabilidad general > Divisas > Tipos de cambio**.

3.  Haga clic en **Nuevo**.

4.  En el campo **Tipo de cambio**, escriba 'GTL-EXCH'.

5.  En el campo **Nombre**, escriba 'Seahorse Exchange Rate'.

6.  Haga clic en **Tipos de cambio**.

7.  Tenga en cuenta que no hay ningún tipo de cambio disponible.

8.  Cerrar formulario de tipos de cambio

9.  Cerrar formulario de tipo de cambio

10. Vaya a **Libro de contabilidad general > Divisas > Configurar proveedores de tipo de cambio**.

11. Haga clic en **Nuevo**.

12. Seleccione **Banco Central de la Federación Rusa**

13. Haga clic en **Aceptar**.

14. Cierre la página.

15. Vaya a **Libro de contabilidad general > Divisas > Importar tipos de cambio de divisa**.

16. En el campo **Tipo de cambio**, introduzca o seleccione GTL-EXCH

17. Seleccione **Banco Central de la Federación Rusa**

18. En el campo **Proveedor de tipo de cambio**, introduzca o seleccione **Banco Central de
    la Federación Rusa**

19. Haga clic en **Aceptar**.

20. Vaya a **Contabilidad general > Divisas > Tipos de cambio**.

21. Seleccione **GTL-EXCH**

22. Haga clic en **Tipos de cambio**.

23. Observe los valores importados

24. Cierre todos los formularios

### Cree un pedido de compra, registre una recepción de producto

1.  Vaya a **Cuentas por pagar > Pedidos de compra > Todos los pedidos de compra**.

2.  Haga clic en **Nuevo**.

3.  En el campo **Cuenta de proveedor**, seleccione **1001 Acme Office Supplies**.

4.  En el campo **Almacén**, seleccione **11**.

5.  Haga clic en **Aceptar**.

6.  En el campo **Número de artículo**, seleccione el artículo **1000 Surface Pro 128 GB**.

7.  En el panel de acciones, haga clic en **Compra**.

8.  Haga clic en **Confirmar**.

9.  En el panel de acciones, haga clic en **Recibir**.

10. Hacemos clic en **Recepción de producto**.

11. En el campo **Recepción de producto**, escriba **GTL02020**.

12. Haga clic en **Aceptar**.

13. Cierre todos los formularios.

### Crear una factura de texto libre

1.  Vaya a **Clientes > Facturas > Todas las facturas de texto libre**.

2.  Seleccione **Nuevo**.

3.  En el campo **Cuenta de cliente**, seleccione **US-003**.

4.  En el campo **Descripción**, introduzca **Guía para la factura de texto libre**. En el
    cuadro de diálogo, haga clic en **Sí**.

5.  En el campo **Cuenta principal**, seleccione el número de cuenta **110180**.

6.  En el campo **Cantidad**, escriba **17**.

7.  En el campo **Precio unitario**, especifique **817,00**. La cantidad se calcula como
    la cantidad de veces para el precio unitario. Sin embargo, puede reemplazar ese
    cálculo introduciendo una cantidad.

8.  Seleccione **Gastos** para agregar un cargo a la factura.

9.  En el campo **Código de gastos**, introduzca **FLETE**.

10. En el campo **Valor de gastos**, escriba **150**.

11. Cierre la página.

12. Seleccione **Totales** para ver un resumen de los detalles y totales de la factura.

13. Seleccione **Cerrar**.

14. Para registrar la factura, haga clic en **Registro**. Aún tendrá la oportunidad de
    cancelar antes de registrar de verdad.

    -  Puede modificar el momento de la impresión de facturas. Seleccione **Actual** a
        imprimir cada factura según se actualiza. Seleccione **Después** para imprimir después de que todas las
        facturas se hayan actualizado.

    -  Para cambiar cómo se comprueba el límite de crédito del cliente antes de que la factura
        se publique, cambie el valor en el campo **Tipo de límite de crédito**.

    -  Para imprimir la factura, configure la opción en **Sí**.

    -  Para registrar la factura, configure la opción en **Sí**. Puede imprimir la
        factura sin registrarla.

15. Seleccione **Aceptar**.
