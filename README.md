# Examen de la semana 2 Juan Pablo Saucedo

## ¿Cuál?

Para el patrón de de diseño elegí el de observer y chain of responsability.

## ¿Por qué?

Él hecho de que haya un evento pago que va a provocar que le demos permiso de usar la canción registrada me hace pensar en un observador que este atento a lo que ocurre con el observable que en este caso puede ser un pago en línea (suponiendo que solo hay una forma de pago), ya que independientemente de que sea Spotify, Amazon o Youtube la forma de pago será la misma y ahi nos indicara a cual de los sistemas de streaming se libera la canción. La cadena de responsabilidad es para ver cual se pago y darle acceso a la canción.

## Diagrama

En el diagrama podemos observar que el cliente genera un pago por lo que el observable Payment puede mandar una notificación para que el handler autorice la canción al servicio de streaming apropiado.

# ![alt text]()