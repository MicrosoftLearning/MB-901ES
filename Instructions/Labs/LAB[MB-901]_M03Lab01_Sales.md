---
lab:
    title: 'Laboratorio 01: Explore Dynamics 365 Sales'
    module: 'Módulo 03: Introducción a Dynamics 365 Sales'
---

# MB-901: Dynamics 365 Sales
## Módulo 3, Laboratorio 1 - Explore Dynamics 365 Sales

**Requisitos previos:** Antes de realizar los pasos de este laboratorio, realice las siguientes tareas:

1. Cree y guarde un documento de Word con un texto de muestra como "Guía de Dynamics 365 Sales" en su escritorio.
1. Habilite la experiencia **Mejorar correo electrónico** en la configuración de la aplicación Centro de ventas. Esta característica permite que la ventana de redacción del correo electrónico se abra en una ventana emergente cuando crea un nuevo correo electrónico en la sección **Escala de tiempo**.
1. Actualice el explorador.

**Opcional:**
 
1. En su instancia de Dynamics 365, vaya a Configuración > Administración de datos.
1. Seleccione Datos de muestra.
1. Si los datos de ejemplo no están instalados, seleccione **Instalar datos de ejemplo**. Los datos de ejemplo pueden tardar unos minutos en aparecer, pero puede seguir usando la aplicación mientras se instala.
1. Seleccione **Cerrar**.

### Crear nuevo contacto

1. En el **Centro de ventas de Dynamics 365**, vaya a **Clientes** > **Contactos**.
1. Haga clic en **Nuevo**.
1. En el campo **Nombre**, escriba **"Cameron"**.
1. En el campo **Apellidos**, escriba **"Azadi"**.
1. En el campo **Puesto**, escriba **Administrador de desarrollo de Xbox Series X**.
1. En el campo **Teléfono del trabajo**, escriba **949-555-1212**.
1. En el campo **Dirección 1:** En el campo **Calle 1**, escriba **1 Microsoft Way**.
1. En el campo **Dirección 1:** En el campo **Ciudad**, escriba **Redmond**.
    - **Nota:** si se han cargado los datos de demostración, se mostrará el formulario **Sugerencias de dirección**. Haga clic en **Aceptar**. Los campos **Dirección 1** se completarán automáticamente. 
1. En el campo **Dirección 1:** En el campo **Estado/Provincia**, escriba **WA**.
1. En el campo **Dirección 1:** En el campo **Código postal**, escriba **98007**.
1. En el campo **Dirección 1:** En el campo **País/Región**, escriba **Estados Unidos**.
1. En el campo **Correo electrónico**, escriba su alias de correo electrónico.
1. Haga clic en **Guardar**.

### Crear un nuevo cliente potencial

1. En el **Centro de ventas de Dynamics 365**, vaya a **Ventas** > **Clientes potenciales**
1. Haga clic en **Nuevo**.
1. Haga clic en el icono **Calificar fase**.
1. En el campo **Contacto existente**  seleccione o escriba **"Cameron Azadi"**.
- **Nota:** Al seleccionar un contacto existente mientras se crea un registro de cliente potencial, se rellenan automáticamente los campos Nombre, Apellido, Puesto, Teléfono del trabajo, Teléfono móvil y Correo electrónico en el formulario de cliente potencial. Cuando seleccione una cuenta existente,  el nombre de la compañía se completará automáticamente en el formulario de cliente potencial. Esto hace que sea muy rápido y fácil introducir un registro de cliente potencial.
1. En el campo **Tema**, escriba **Le gustan nuestros productos Xbox**.
1. Haga clic en **Guardar**.

### Cambiar la configuración del sistema

1. Vaya hasta el icono de engranaje **Configuración** del menú superior derecho. Use el menú desplegable para elegir **Configuración avanzada**.
1. Haga clic en el menú desplegable junto a **Configuración** y vaya a **Administración** en **Configuración del sistema.**
1. Seleccione la pestaña **Ventas**.
1. En el campo **Calificar la experiencia del cliente potencial**, seleccione **No**.
1. Haga clic en **Aceptar**.

### Calificar al nuevo cliente potencial

1. En el **Centro de ventas de Dynamics 365**, vaya a **Ventas** > **Clientes potenciales**.
1. Seleccione **Cameron Azadi**.
1. Haga clic en el botón **Calificar**.
1. En el formulario **Calificar a un cliente potencial**, haga clic en **Contacto**. Esto cambiará el valor de **Sí** a **No**.
1. En el formulario **Calificar a un cliente potencial**, haga clic en **Oportunidad**. Esto cambiará el valor de **No** a **Sí**.
1. En el formulario **Calificar a un cliente potencial**, haga clic en **Aceptar**. 
**Nota:** El cliente potencial progresará a la etapa de desarrollo.

### Añadir notas al nuevo cliente potencial

1. En la sección **Escala de tiempo**, haga clic en **+** para agregar una nueva **Nota**.
1. En el campo **Título**, escriba **Reunión con Cameron sobre Xbox Series X**.
1. Haga clic en **Agregar nota**.
1. En la sección **Escala de tiempo**, haga clic en **+** para añadir otra **Nota** con datos adjuntos.
1. En el campo **Título**, escriba **información de producto de Xbox Series X**.
1. Haga clic en el icono del archivo adjunto y seleccione el documento de Word que ha creado al comienzo de este laboratorio.
1. Haga clic en **Agregar nota**.

### Verifique las notas creadas en el cliente potencial de Oportunidades

1. En el **Centro de ventas de Dynamics 365**, vaya a **Ventas** > **Oportunidades**.
1. Cambie la vista haciendo clic en el menú desplegable y seleccionando **Todas las oportunidades**.
1. Haga clic para seleccionar la oportunidad **Le gustan nuestros productos Xbox para Cameron Azadi**.
1. Tenga en cuenta que el archivo adjunto y las notas creadas en el formulario de cliente potencial también están disponibles en el formulario de oportunidad. 
1. En la sección **Escala de tiempo**, haga clic en **+** para redactar un borrador y enviar un **Correo electrónico**. Aparecerá la ventana emergente del correo electrónico.
1. En el campo **Asunto**, escriba **Xbox Series X**.
1. Escriba un mensaje como "Hola, Cameron. Gracias por su interés en Xbox Series X. Quedamos a la espera de nuestra reunión”. 
1. Opcionalmente, desde el registro de oportunidad o los registros relacionados, como el registro de contacto, navegando hacia él, en segundo plano, puede copiar y pegar cualquier información en el mensaje de correo electrónico sin perder el enfoque y ahorrar tiempo.
1. Haga clic en **Guardar**.




