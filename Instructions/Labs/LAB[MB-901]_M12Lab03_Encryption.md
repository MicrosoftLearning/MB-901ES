---
lab:
    title: 'Laboratorio 3: Mejorar la seguridad mediante el cifrado de sus datos'
    module: 'Módulo 12: Reconocer la seguridad de Dynamics 365'
---

# MB-901: Fundamentos de Dynamics 365
## Módulo 12, Laboratorio 3: Mejore la seguridad encriptando sus datos

**Escenario:** Usted, como administrador del sistema, debe cambiar y copiar la clave de cifrado de la organización.

## Instrucciones

1. Vaya al Centro de administración de Power Platform.  
1. Estas opciones de configuración se pueden encontrar en **Entornos** >  [seleccione un entorno] > **Configuración** > **Cifrado** > **Cifrado de datos**.
1. En el cuadro **Cambiar clave de cifrado**, escriba la nueva clave de cifrado y luego seleccione **Cambiar**.
1. Seleccione **Aceptar** en el mensaje de confirmación y luego seleccione **Cerrar** para salir de la página de **Cifrado de datos**.

Le recomendamos encarecidamente que haga una copia de su clave de cifrado de datos.

1. Seleccione el mismo entorno que utilizó en los pasos 1-4 y vaya a **Configuración** > **Cifrado**.
1. En el cuadro de diálogo **Cifrado de datos**, seleccione **Mostrar clave de cifrado**, en el **Cuadro de clave de cifrado actual**, seleccione la clave de cifrado y cópiela en el portapapeles.
1. Pegue la clave de cifrado en un editor de texto, como Bloc de notas.

**Nota:** De forma predeterminada, las aplicaciones basadas en modelos en Dynamics 365 generan una frase de contraseña que es una colección aleatoria de caracteres Unicode. Por lo tanto, debe guardar la frase de contraseña generada por el sistema utilizando una aplicación y un archivo que admita caracteres Unicode. Algunos editores de texto, como el Bloc de notas, utilizan la codificación ANSI de forma predeterminada. Antes de guardar la frase de contraseña con el Bloc de notas, seleccione Guardar como y luego, en la lista Codificación, seleccione Unicode.

Como práctica recomendada, guarde el archivo de texto que contiene la clave de cifrado en un equipo en una ubicación segura en un disco duro cifrado.
