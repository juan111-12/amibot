# amibot
Hoy trabajé en varios aspectos clave del diseño y funcionalidad del proyecto AmigoBot, centrados en mejorar la experiencia del usuario y la supervisión parental. A continuación, detallo los avances realizados:

🎯 1. Diseño Responsivo Mejorado
Implementé un diseño completamente responsivo, asegurando que la interfaz de AmigoBot se adapte correctamente a distintos tamaños de pantalla, desde computadoras de escritorio hasta celulares.
Para lograrlo utilicé:

CSS con media queries (@media max-width: 768px):
Ajusté el padding, los tamaños de fuente, el diseño de tarjetas, columnas, juegos y la barra de entrada del chat para mejorar la visualización en pantallas pequeñas.

JavaScript dinámico en el juego de dibujo:
Mejoré la función resizeCanvas() para que el lienzo de dibujo se adapte automáticamente al tamaño del contenedor sin perder proporciones ni calidad del trazo.

👨‍👩‍👧‍👦 2. Panel de Padres (con acceso seguro)
Desarrollé un Panel de Supervisión para Padres, al que se accede mediante un formulario con credenciales. Las claves están predefinidas de forma simple para pruebas:

Usuario: padre

Contraseña: password123

Si se ingresan datos incorrectos, se muestra un mensaje de error. Al ingresar correctamente, el panel permite ver:

El historial de juegos jugados por el niño, con tipo de juego, resultado y puntuación.

El historial de chat entre el niño y AmigoBot (guardado localmente).

Las notas guardadas por el niño en el Cuaderno Virtual.

Los recordatorios de salud programados por el niño.

Este panel facilita a los adultos el seguimiento del uso responsable de la aplicación.

🔒 3. Validación del nombre en el registro
Incorporé un sistema de validación del nombre en el formulario de inicio, con el objetivo de evitar registros con nombres falsos o aleatorios.
El campo de nombre ahora acepta únicamente:

Letras

Espacios

Guiones (-)

Apóstrofes (')

Y exige al menos 2 caracteres válidos

💡 Este sistema todavía necesita algunos ajustes, ya que en algunos casos no funciona como se espera. Será mejorado en los próximos días.
