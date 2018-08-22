# Prueba de Ingenious Softworks para candidatos - Letra

Hola **candidato**, asegurate de haber leído el [README](../README.md) antes de leer la letra del problema, si tienes alguna duda nos puedes enviar un email a [gchertok@ingsw.com](mailto: gchertok@ingsw.com).

## Índice
* [Letra](#letra)
* [Requerimientos no funcionales](#requerimientos-no-funcionales)
* [Preguntas Frecuentes](#faq)
* [Siguiente paso](#siguiente-paso)

## Letra

Se pide desarrollar una web app que liste y permita crear eventos. El sistema final será una cartelera de eventos muy simple.

## Historias de usuario

### Listar eventos

Como un visitante del sitio al ingresar al mismo debo ver un listado inicial de eventos ordenados por fecha.

![Listar Eventos](images/event-list.png)

### Compartir evento

Como un visitante del sitio haciendo click en el botón compartir de un evento debo poder compartir el mismo en twitter.

El mensaje de twitter deberá ser el siguiente: "Iré al NOMBRE DEL EVENTO @ FECHA DEL EVENTO LINK DEL EVENTO".

![Compartir Evento](images/share-event.png)

### Ver detalle del evento

Como un visitante del sitio haciendo click en un evento debo navegar al detalle del mismo que deberá listar, además del nombre el resto de sus atributos.

![Detalle de Evento](images/event-detail.png)

### Listar eventos destacados

Como un visitante del sitio en la página principal debo ver un listado de eventos destacados.

![Eventos Destacados](images/highlighted-events.png)

### Login

Como un visitante del sitio debo poder loguearme a una sección de backend.

### Listado de eventos (backend)

Como un usuario una vez logueado debo ver un listado de eventos paginados.

### Crear evento

Como un usuario logueado debo poder crear un evento con todos sus campos.

* Título
* Descripción
* Lista de fechas
* Lugar
* Destacado
* Imágen (URL)

![Crear Evento](images/new-event.png)

## Requerimientos no funcionales

La aplicación deberá ser escrita en: 

* ruby
* .net
* node
* python

## FAQ

### Puedo agregar / quitar campos al dominio?

Sí, mientras se cumpla el mismo objetivo se pueden cambiar los campos.

### Hay algo en la letra que no quedó claro pero tengo dificultades para comunicarse por email

Si estás en esta situación asume lo que te sea más cómodo y continúa con la prueba. Si es posible deja constancia de la decisión tomada para poder evaluar la prueba en base a ella.

Por ejemplo, si no queda claro qué atributos del evento debes listar en la página principal asume unos y continúa adelante.

Recuerda que es una prueba para evaluar tu conocimiento no un trabajo para un cliente real.

### No entiendo lo qué se pide en la letra

Lo ideal es enviarnos un correo electrónico a [gchertok@ingsw.com](mailto: gchertok@ingsw.com) y trataremos de aclarar la duda.

### Me sobró tiempo y quisiera agregarle funcionalidades a la aplicación

Si bien las funcionalidades extra son un plus preferimos que las presentes estén lo más completas posibles. Si te ha sobrado tiempo sería interesante que agregaras **tests** y escribieras **documentación** sobre la app que has desarrollado.

### Es necesario hacer registro de usuario?

No, no es necesario registrar usuarios ni proveer ninguna otra funcionalidad de backend que las mencionadas. Se aconseja dejar en el archivo `seed` un usuario para poder testear el funcionamiento de la app.

### Puedo usar la gema / librería X?

Sí, siempre y cuando la misma sea una librería y no un framework completo.

Para poner un ejemplo, no esperamos que desarrolles un sistema de authenticación desde 0, se pueden usar librerías como [device](https://github.com/plataformatec/devise) o [sorcery](https://github.com/NoamB/sorcery), en cambio no está permitido usar [refinery](http://www.refinerycms.com/) o [spree](https://github.com/spree/spree) ya que de hacerlo no podremos evaluar tu forma de resolver el problema sino el conocimiento específico de estas herramientas.

### Tengo que hacer las vistas también?

Sí, es necesario desarrollar una versión funcional de la aplicación con sus páginas HTML pero **no es necesario desarrollar dos aplicaciones, una cliente y otra servidor** una simple apicación full stack es lo que se busca.

## Siguiente paso

Ya puedes empezar a desarrollar la aplicación dentro del directorio `app`. Mucha suerte!
