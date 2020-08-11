---
lab:
    title: 'Laboratorio 02: Explore los roles de seguridad en las aplicaciones de Dynamics 365 Finance and Operations'
    module: 'Módulo 03: Reconocer la seguridad de Dynamics  365'
---

# MB-901: Fundamentos de Dynamics 365
## Módulo 3, Laboratorio 2 - explore los roles de seguridad en las aplicaciones de Dynamics 365 Finance and Operations

### Excluir rol

**Escenario:** El departamento de RR. HH. de la empresa USMF solicitó que se quite el acceso al rol de Funcionario de clientes en las aplicaciones de Dynamics 365 Finance and Operations para un empleado que ha cambiado de rol. Usted, como administrador del sistema, debe excluir la función de empleado de Cuentas por cobrar para el empleado.

1. Vaya a **Administración del sistema** > **Seguridad** > **Asignar usuarios a roles**.
1. En el árbol, seleccione **'Funcionario de clientes'**.
1. Haga clic en **Asignar de forma manual**/**excluir usuarios**.
1. En la lista, seleccione un usuario.
1. Haga clic en **Excluir del rol** para excluir a los usuarios seleccionados.
1. Para eliminar exclusiones, seleccione a los usuarios para los que desea hacerlo y luego haga clic en **Restablecer estado**. 

### Cree una regla de segregación de controles

**Escenario:** El Departamento de RR. HH. de USMF ha solicitado una regla para la segregación de controles, de modo que **Acceder al área de trabajo de los beneficios** quede como el primer deber y **Acceder al diario de producción** quede como el segundo. Usted, como administrador del sistema, deberá crear la regla.

1. Vaya a **Administración del sistema** > **Seguridad** > **Segregación de controles** > **Reglas de segregación de controles**.
1. Haga clic en **Nuevo**.
1. En el campo **Nombre**, escriba un nombre exclusivo para la regla.
1. En el campo **Primer deber**, seleccione el botón desplegable para abrir la búsqueda.
1. En la lista, busque y seleccione el primer deber controlado por la regla.
1. En la lista, haga clic en el vínculo de la fila seleccionada.
1. En el campo **Segundo deber**, seleccione el botón desplegable para abrir la búsqueda.
1. En la lista, busque y seleccione el segundo deber controlado por la regla.
1. En la lista, haga clic en el vínculo de la fila seleccionada.
1. En el campo **Gravedad**, seleccione la gravedad del riesgo que se produce cuando el mismo usuario o rol realiza ambos deberes.
1. En el campo **Riesgo de seguridad**, introduzca una descripción del riesgo de seguridad.
1. En el campo **Mitigación de seguridad**, escriba un valor.
1. Escriba una descripción de las medidas que toma para mitigar el riesgo de seguridad. 
Por ejemplo, puede mitigar el riesgo al realizar revisiones más detalladas del proceso, al realizar una revisión administrativa mensual o al compartir recursos con otros departamentos.
1. Haga clic en **Guardar**.
