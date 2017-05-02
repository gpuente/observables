Observables
=======================

Este es un ejemplo de cómo funcionan los observables y la programación reactiva.
El ejemplo está escrito en JavaScript.

En el ejemplo se crea un objeto "observable", al cual se suscriben distintos objetos. Cuando el observable ejecuta algún
cambio en los datos, este informa a cada objeto suscrito sobre dicho cambio. Los objecots suscriptores actualizan sus
datos cuando el observable les informa del cambio.