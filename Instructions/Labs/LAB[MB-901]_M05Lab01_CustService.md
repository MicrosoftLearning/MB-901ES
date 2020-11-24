---
lab:
    title: 'Laboratorio 01: Explorar Dynamics 365 Customer Service'
    module: 'Módulo 05: Introducción a Dynamics 365 Customer Service'
---

# MB-901: Fundamentos de Dynamics 365 
## Módulo 5, Laboratorio 1: explorar Dynamics 365 Customer Service 

**Escenario:**
Como representante de servicio al cliente, debe realizar un seguimiento de las solicitudes y problemas de sus clientes creando casos de soporte en Dynamics 365 Customer Service. Cuando un cliente contacta al soporte técnico con una pregunta o problema, puede verificar rápidamente si hay un caso existente o abrir uno nuevo y comenzar a rastrear el problema. También puede escalar, reasignar o volver a colocar un caso en la cola del servicio si no tiene suficiente información o tiempo para trabajar en él.

Antes de proporcionar soporte técnico, también puede verificar los derechos del cliente. Los derechos son como contratos que le dicen para qué tipo de soporte es elegible un cliente. Puede ver si los términos de soporte se basan en el número de horas o casos, el canal de soporte o en el producto o servicio que el cliente ha comprado.

Para seleccionar el estado correcto de un caso, su administrador puede haber configurado las cosas para que solo vea un conjunto limitado de estados basados en el estado actual de un caso.

## Instrucciones

### Crear un caso

1. En el **Centro de servicio al cliente**, vaya a **Servicio** > **Casos**.
1. Seleccione **Caso nuevo**.
1. En el campo **Título del caso**, escriba **Reloj inteligente Seahorse**.
1. En el campo **Cliente**, seleccione el cliente **Fabrikam** y luego haga clic en un registro existente para la cuenta.
1. En el campo **Descripción**, escriba **Problema con el reloj inteligente**
1. Haga clic en la pestaña **Detalles**.
1. Haga clic en **Guardar**.
1. Para realizar un seguimiento de su conversación con el cliente, en la sección **Cronograma** haga clic en **+** para agregar información y actividades.
1. Haga clic en **Nota**.
1. En el campo **Título**, escriba **Defecto en reloj inteligente**.
1. En el campo **Nota**, escriba **Enviar para reparación**.
1. Haga clic en **Agregar nota**. 
14.	Para ver qué tipo de soporte debe proporcionar al cliente, seleccione el botón **Búsqueda de derechos** y, luego, seleccione un derecho activo.
 **Nota:** Si no hay derecho sobre el cliente, este estará en blanco.
1. Haga clic en **Guardar**.

### Encuentre una solución de casos similares

**Nota:** Puede ver los casos resueltos para comprobar si pueden ayudarlo a solucionar el caso abierto en el que está trabajando. Por ejemplo, si el tema del caso en el que está trabajando es "**Defecto en reloj inteligente**", podría buscar casos resueltos con el mismo tema para obtener ayuda con su caso actual.

### Resolver caso

Antes de resolver un caso, asegúrese de que todas las actividades del caso estén cerradas. De lo contrario, recibirá un mensaje en el que se explica que todavía tiene actividades abiertas asociadas con el caso, que se cancelarán si se resuelve el caso.

1. Vaya a **Servicio** > **Casos**.
1. En la lista de casos activos, abra el caso **Reloj inteligente Seahorse** a resolver.
1. En la barra de comandos, seleccione **Resolver caso**.
1. En el cuadro de diálogo **Resolver caso** en la lista **Tipo de resolución**, seleccione **Problema resuelto**.
1. En el cuadro **Resolución**, escriba **Reparado**.
1. El tiempo real dedicado a todas las actividades para este caso, tal como se registra en el cuadro **Duración** en cada actividad, se rellena automáticamente en el cuadro **Tiempo total**.
1. En la lista **Tiempo facturable**, seleccione **30 minutos** como la cantidad de tiempo dedicado al caso a facturar al cliente.
 **Nota:** Si este caso está vinculado a un contrato o derecho, el tiempo facturable se restará de los minutos asignados para ese contrato.
1. Seleccione **Resolver**. Se crea una actividad de resolución de casos y se muestra en el área **Actividades**. 

La actividad de resolución contiene información sobre un caso resuelto, incluida la resolución y el tiempo total dedicado al caso. Puede reactivar un caso resuelto en cualquier momento.
