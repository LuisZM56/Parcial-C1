# Parcial-C1
# Integrantes: 
# Luis Angel Zuniga Menjivar
# Victor Arnoldo Iglesias Sandoval

1. ¿Qué valor agregado tiene el uso de WebComponents?

El uso de WebComponents permite crear elementos personalizados reutilizables, encapsulando estructura, estilo y funcionalidad en un solo componente. Esto mejora la organización del código, facilita el mantenimiento y permite escalar la aplicación sin afectar otras partes del sistema.

2. ¿De qué forma manipularon los datos sin recargar la página?

Se utilizó el evento submit del formulario junto con event.preventDefault() para evitar que la página se recargue. Los datos ingresados se capturaron mediante JavaScript, se procesaron y luego se mostraron dinámicamente en el componente personalizado usando el DOM.

3. ¿De qué forma validaron las entradas de datos?

Se validó que:

-Los campos no estén vacíos.

-Los valores numéricos no sean negativos ni cero.

-No se acepten valores que no sean números mediante isNaN().

-Si la validación falla, se muestra un mensaje de error en pantalla sin continuar el cálculo.

4. ¿Cómo manejaría la escalabilidad futura en su página?

Para escalar el proyecto se podría:

-Separar el código en módulos.

-Crear más WebComponents reutilizables.

-Implementar almacenamiento en base de datos.

-Convertir el sistema en una aplicación SPA usando un framework como React o Vue.

-Agregar autenticación de usuarios.
