---
lab:
    title: 'Laboratorio 01: Crear su primera aplicación basada en modelos desde cero'
    module: 'Módulo 13: Conectar y analizar los datos de Dynamics 365'
---

# MB-901: Fundamentos de Dynamics 365
## Módulo 13, Laboratorio 1: Cree su primera aplicación basada en modelos desde cero

**Escenario:** Debe simplificar para crear una aplicación basada en modelos mediante una de las entidades estándar disponibles en el entorno de Power Apps. Las aplicaciones basadas en modelos no se ejecutan en la aplicación móvil Power Apps. En su lugar, se ejecuta una aplicación basada en modelos en un dispositivo móvil mediante la aplicación móvil Dynamics 365 o en el explorador web del teléfono.

Inicie sesión con la identificación en vivo de su ventana en Power Apps. Si aún no tiene ninguna cuenta de Power Apps, seleccione el vínculo Comenzar gratis en https://signup.microsoft.com/Start?sku=powerapps_viral&ru=https%3a%2f%2fweb.powerapps.com%2flogin%2fportal

## Instrucciones
1. Acceda al Centro de administración de Power Platform.
12.	Seleccione **Entornos**.
13.	Seleccione su entorno de prueba de CRM. 
14.	Seleccione el vínculo de ![Centro de administración de Dynamics 365](https://port.crm.dynamics.com/G/Instances/InstancePicker.aspx?redirect=False0).
15.	Seleccione **GTLPowerApps**.
16.	Seleccione **Abrir**.
17.	Seleccione **Crear nueva aplicación**.
19.	En la página **Crea una nueva aplicación**, introduzca los siguientes detalles y luego seleccione **Hecho**:
    - **Nombre:** Escriba **GuideToPowerApp**.
    - **Nombre único:** De manera predeterminada, el nombre único utiliza el nombre que especifique en el cuadro Nombre sin espacios y precedido por el prefijo del editor y un guión bajo (_).
    - **Descripción:** Escriba **GuideToPowerApp**.
20.	Seleccione **Listo**.
21.	Desde el diseñador de la aplicación, agregue componentes a su aplicación. Seleccione el icono de lápiz en el botón del **Mapa del sitio** para abrir el diseñador del mapa del sitio.
22.	Utilizará la entidad Cuentas en esta instancia de Power Apps para administrar las cuentas de los clientes.
22. En la pestaña **Propiedades**, escriba **Cuentas** para el nombre del área.
23.	En el diseñador del mapa del sitio, seleccione **Nueva subárea**, en el panel derecho, seleccione la pestaña **Propiedades** y luego seleccione el valor de las siguientes propiedades:
    - **Tipo: Entidad**
    - **Entidad: Cuenta**  
    - Seleccione **Guardar**. 
24.	Seleccione **Diseñador de estructuras**.
25.	En el lienzo del diseñador de aplicaciones, seleccione **Formularios** y luego en el panel derecho debajo del grupo **Formularios principales** seleccione el formulario **Cuenta**.
26.	Seleccione el botón **Volver**.
27.	En el lienzo del diseñador de aplicaciones, seleccione **Vistas** y luego. seleccione las vistas **Cuentas activas**, **Todas las cuentas** y **Mis cuentas activas**.
28.	Seleccione el botón **Volver**.
29.	En el lienzo del diseñador de aplicaciones, seleccione **Gráficos** y luego el gráfico **Cuentas por sector**.
30.	Seleccione el botón **Volver**.
31.	En la barra de herramientas del diseñador de aplicaciones, haga clic en **Guardar** y luego en **Publicar**.
32.	Seleccione **Ejecutar**.
34.	Revise los resultados e interactúe con su primera aplicación basada en modelos.
35.	Pruébelo en su dispositivo móvil instalando la aplicación Dynamics 365 para teléfonos o Dynamics 365 para tabletas desde la tienda de aplicaciones de su dispositivo. Más información: https://docs.microsoft.com/dynamics365/customer-engagement/mobile-app/install-dynamics-365-for-phones-and-tablets
36.	Escriba la dirección URL de la aplicación directamente en el explorador web de su teléfono y siga las instrucciones en pantalla para cargar la aplicación. 
  **Nota:** Un ejemplo de la dirección URL de su aplicación se verá así: https://orgxxxxx.crm.dynamics.com/main.aspx?appid=e4547538-e20f-ea01-a811-000d3a33438d&pagetype=entitylist&etn=account
