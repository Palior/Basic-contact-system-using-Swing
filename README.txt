# Proyecto: Sistema de Contacto

Este proyecto es un sistema básico de contacto desarrollado en Java utilizando Swing para la interfaz gráfica. Permite a los usuarios enviar información de contacto y recibir retroalimentación.

## Estructura del Proyecto

El proyecto consta de dos clases principales:

1. NewJFrame
   - Esta clase representa la ventana principal del formulario de contacto.
   - Permite a los usuarios ingresar su nombre, RUT, dirección, región y teléfono, además de un motivo de contacto.
   - Incluye botones para enviar y cancelar la acción.

2. FormularioEnviado
   - Esta clase es un diálogo que se muestra después de enviar el formulario.
   - Proporciona una serie de campos de evaluación sobre la experiencia del usuario al llenar el formulario.
   - Incluye un botón para finalizar y cerrar la aplicación.

Requisitos:

- Java Development Kit (JDK): Asegúrate de tener instalado JDK 8 o superior.
- IDE: Se recomienda utilizar un IDE como IntelliJ IDEA, Eclipse o NetBeans para facilitar la ejecucion o edicion.

Cómo usar:

Al ejecutar la aplicación, se abrirá la ventana de contacto.
Completa los campos requeridos.
Haz clic en "Enviar" para enviar el formulario. Se abrirá un nuevo diálogo donde podrás evaluar tu experiencia.
Haz clic en "Finalizar" para cerrar la aplicación.

Funcionalidades

Ingreso de datos: Permite a los usuarios ingresar su información de contacto.

Evaluación de satisfacción: Después de enviar el formulario, los usuarios pueden evaluar diferentes aspectos del formulario.

Interfaz gráfica: Utiliza componentes de Swing para una experiencia de usuario amigable.