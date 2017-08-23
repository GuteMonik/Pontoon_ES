# Búsqueda y filtros

Las cadenas en Pontoon pueden ser filtradas por su estado. Una cadena puede estar en uno de los siguientes estados:
* *Ausente*: la cadena no está disponible en el archivo localizado y no tiene traducciones ni sugerencias en Pontoon.
* *Sugerida*: al menos se ha enviado una sugerencia para esta cadena. Ten en cuenta que, en este caso, la traducción sólo existe en la base de datos de Pontoon, esta no se guarda en el archivo localizado.
* *Traducida*: la cadena tienen una traducción aprobada.
* *Confusa*: la cadena es marcada como [confusa](../../misc/glossary.md#fuzzy) en el archivo localizado.

Las sugerencias pueden estar en dos estados:
* *Sin revisar*: se ha sugerido la cadena, pero no se ha aprobado o rechazado.
* *Rechazada*: la cadena fue revisada y rechazada por el traductor.

Hay algunos criterios adicionales que se pueden utilizar para filtrar cadenas:
* *Sin traducir*: esto mostrará las cadenas que se sugieren, falta traducir o su traducción es difusa. Básicamente, cualquier cosa menos traducida. Una vez seleccionado, también notarás que esos 3 filtros se comprueban automáticamente.
* *Sin cambiar*: la cadena es idéntica al lenguaje de referencia (normalmente en-US).
* *Sugerencias no revisadas*: se mostrarán cadenas que tienen al menos una sugerencia sin revisar. Observa que se incluirán cadenas en estado *sugerido *, *confuso* y *traducido*, siempre y cuando tengan sugerencias no revisadas.
* *Rechazada*: muestra cadenas que tienen sugerencias rechazadas.

Al hacer clic en el icono del embudo de la izquierda, es posible acceder a los filtros.

 https://raw.githubusercontent.com/mozilla-l10n/localizer-documentation/master/assets/images/pontoon/search_filters/filters.png


En este punto es posible:
* Da clic directamente en la descripción de uno de los filtros. Esto seleccionará y activará sólo este filtro y el marcador de posición del campo de búsqueda cambiará en consecuencia. Por ejemplo, al hacer clic en *Faltante* mostrará sólo las cadenas que faltan, y el marcador de posición leerá *Buscar en Faltante*.
* Da clic en los iconos de cada filtro, o en los avatares del usuario, para aplicar varios filtros. Al colocar los iconos, puedes observar que se transforman en marcas de verificación. Aparecerá un nuevo botón *APPLY X FILTERS* en la parte inferior del panel, donde `X` es el número de filtros activos.

https://raw.githubusercontent.com/mozilla-l10n/localizer-documentation/master/assets/images/pontoon/search_filters/filters_multiple.png

En este caso se seleccionan 3 filtros. 

Para seleccionar un **rango de tiempo**, tú necesitas hacer clic en *EDITAR RANGO*, a continuación, selecciona uno de los valores predeterminados (30 días, 7 días, 24 horas, 60 minutos) o utiliza el selector de fecha (o deslizador) para adaptar el rango. Da clic en * SAVE RANGE * para almacenar el rango, luego aplica el filtro.

Es posible buscar dentro de un proyecto utilizando el campo de búsqueda. Las búsquedas incluyen cadenas, identificación de cadena y comentarios.

https://raw.githubusercontent.com/mozilla-l10n/localizer-documentation/master/assets/images/pontoon/search_filters/search_field.png


Ten en cuenta que las búsquedas tienen en cuenta los filtros activos, por ejemplo, una búsqueda se realizaría sólo en cadenas perdidas si se selecciona ese filtro.
