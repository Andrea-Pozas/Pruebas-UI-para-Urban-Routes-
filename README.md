# Pruebas UI para Urban Routes :taxi:
Urban Routes es una aplicación proveedora de movilidad como servicio. Antes del lanzamiento de su versión web al público, he llevado a cabo rigurosas pruebas manuales para asegurar la calidad y funcionamiento correcto de acuerdo con los requerimientos y diseños establecidos con el fin de garantizar que Urban Routes no solo cumpla, sino que supere los estándares de calidad esperados por los usuarios.

![Urban Routes Web](https://github.com/Andrea-Pozas/Pruebas-UI-para-Urban-Routes-/blob/main/images/Urban%20Routes.png)

## Herramientas
![Static Badge](https://img.shields.io/badge/Excel-black?style=for-the-badge&logoColor=white&color=%233CB371) ![Static Badge](https://img.shields.io/badge/Jira-%230052CC?style=for-the-badge) ![Static Badge](https://img.shields.io/badge/Figma-%23F24E1E?style=for-the-badge) ![Static Badge](https://img.shields.io/badge/DevTools-black?style=for-the-badge)




## Pruebas manuales del formulario de reserva de Automóvil 

### Lista de comprobación del formulario de reserva
<p align="justify">
El usuario debe seleccionar el punto de partida y de llegada en la aplicación Web Urban Routes, una vez seleccionada la ruta se abrirá el formulario de reserva. El furmulario permite elegir entre las siguientes tarifas: Casual, Camping y de Lujo. Con el fin de garantizar que el usuario puede realizar una reserva de un vehiculo exitosamente se realizaron pruebas de funcionalidad y diseño. Al realizar las pruebas documenté cada uno de los errores que encontré en Jira, entre los errores descubrí que el usuario no tenía la posibilidad de cancelar la reserva de un viaje debido a que la ventana emergente no aparece por lo que considere un error crítico con una prioridad alta. 
</p>
![Formulario de reserva](https://github.com/Andrea-Pozas/Pruebas-UI-para-Urban-Routes-/blob/main/images/Formulario.png)

### Lista de comprabación de las ventanas emergentes Método de pago y Agregar tarjeta
<p align="justify"> El formulario de reserva cuenta con dos ventanas emergentes Método de pago y Agregar tarjeta. Cuando el usuario da clic en el método se abre una ventana emergente que permité al usuario agregar una tarjeta y el código de seguridad para realizar su pago, para la ventana emergente Método de pago llevé a cabo pruebas de diseño y funcionales, mientras que para los campos de entrada de la venta emergente agregar tarjeta relicé pruebas positivas y negativas para corroborar que los campos sólo aceptaban datos válidos según los requerimientos. </p>


### Casos de prueba y pruebas: la lógica del botón "Reservar"
<p align="justify"> Redacté y ejecute casos de prueba para el el botón de reserva si un usuario rellena todos los campos correctamente el botón de reserva debería mostrar el siguiente mensaje: El recorrido será de ... kilómetros y se hará en ... minutos y al hacer clic se abré una ventana emergente del automóvil reservado. Bajo esta lógica se crearon casos de prueba donde el usuario llena todos los campos obligatorios y obtiene un resultado éxitoso y otros casos de prueba donde el usuario no llena alguno de los campos obligatorios para reservar un autómovil y la plataforma redirige al usuario al campo que le falto llenar. Al realizar los casos de prueba descubrí que la plataforma no redirigía al usuario al campo que le faltaba llenar, permitiendo que se reservará un viaje sin la información necesaria.  </p>


:arrow_right:__Si deseas observar las listas de comprobación y los casos de prueba da clic aquí:__ [Pruebas UI Urban Routes](https://docs.google.com/spreadsheets/d/11OqDTIItugfeixfS3mfHmcMZ1DH8We9T/edit?usp=sharing&ouid=103915261935983096380&rtpof=true&sd=true)

## Conclusión 
Urban Routes es una plataforma que permite al usuario elegir entre distintos tipos de modos de viaje, de automóviles y tarifas que se ajustan a la búsqueda del consumidor. Además, tiene una interfaz intuitiva lo que favorece su interacción al ser amigable con la persona que lo utiliza. 
 Aunque Urban Routes contiene elementos que le permiten al usuario rapidez y comodidad, sin embargo al interactuar con la plataforma se presentan algunos errores importantes de funcionalidad que deberían ser solucionados, por ejemplo: 
- Cuando el usuario elige una tarifa en el mapa no se muestra el icono del automóvil más cercano ni su marca. https://anliz24.atlassian.net/browse/BR-2 
- Cuando el usuario elige una tarifa en el mapa no se visualizan todas las opciones de automóviles que se encuentran cerca. https://anliz24.atlassian.net/browse/BR-3 
- El botón de cancelar reserva no funciona. https://anliz24.atlassian.net/browse/BR-6 

Así mismo hay errores que hacen menos cómoda la experiencia del usuario, por ejemplo: 
- Cuando el usuario decide agregar más de una tarjeta en método de pago, la interfaz no muestra los 4 últimos dígitos del número de cada tarjeta. https://anliz24.atlassian.net/browse/BR-13 
- Cuando el usuario da clic en reservar sin haber introducido los campos obligatorios no se abre alguna ventana que permita el llenado de alguno de los campos obligatorios. https://anliz24.atlassian.net/browse/BR-15

A pesar de que Urban Routes podría ofrecer un buen servicio al consumidor gracias a sus diferentes elementos. Aún no está lista para que los usuarios y usarías comiencen a interactuar con la plataforma ya que los errores de funcionalidad podrían ocasionar que el usuario decida abandonar la aplicación al no poder realizar alguna de las acciones esenciales para el cumplimiento de su pedido.

