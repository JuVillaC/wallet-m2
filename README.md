Para ingresar utilizar
- usuario: usuario@wallet.cl
- contraseña: 1234
---
v1.3
En esta versión del proyecto se incorporó jQuery con el fin de agregar dinamismo e interactividad a la wallet, manteniendo la lógica original del sistema.  

## Cambios principales realizados
- Se reemplazaron los selectores y eventos de JS puro por selectores y eventos de jQuery, mejorando la legibilidad del código.
- Se implementaron mensajes visuales con alertas de bootstrap, reemplazando el uso de aler() para una mejor experiencia de usuario.
- En la pantalla de login, se manejó el envío del formulario con jQuery y se agregó validación visual antes de redirigir al menú principal.
- En el menú principal, los botones ahora muestran leyendas dinámicas indicando la redirección a cada sección.
- En la pantalla de depósito, se muestra el saldo actual, se valida el monto ingresado y se agrega una alerta de confirmación antes de redirigir.
- En la pantalla de enviar dinero, se mejoró la interacción permitiendo agregar contactos, validar datos, mostrar u ocultar el botón de envío y confirmar visualmente la transferencia.
- En últimos movimientos, se renderizan las transacciones dinámicamente y se agregó un filtro por tipo de movimiento utilizando jQuery.
- Se mantuvo el uso de localStorage para simular la persistencia de datos sin necesidad de backend.

## Tecnologías usadas
- HTML5: estructura de las vistas y formularios.
- CSS3: estilos personalizados y animaciones básicas.
- Bootstrap 4: diseño responsivo, componentes visuales y alertas.
- JavaScript: lógica principal de la aplicación.
- jQuery: manejo de eventos, manipulación del DOM y dinamismo de la interfaz.
- LocalStorage: almacenamiento de datos en el navegador (saldo, contactos y transacciones).
