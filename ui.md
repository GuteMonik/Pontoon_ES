# Entendiendo la interfaz de usuario de Pontoon

## Espacio de trabajo de traducción en Pontoon

El espacio de trabajo de traducción en Pontoon presenta la lista de cadenas en la barra lateral izquierda y el espacio de edición a la derecha.

![Translation Workspace](https://github.com/mozilla-l10n/localizer-documentation/blob/master/assets/images/pontoon/ui/translation_workspace.png)

### Barra de herramientas principal

La barra de herramientas principal te permite navegar dentro del proyecto sin salir del espacio de trabajo de traducción.

![main toolbar](https://github.com/mozilla-l10n/localizer-documentation/blob/master/assets/images/pontoon/ui/main_toolbar.png)

Para navegar a otro proyecto, debes dar clic en cada elemento para abrir el menú despegable y seleccionar la configuración regional, el proyecto, y el recurso para trabajar. A continuación, da clic en  `Go (IR)`. Ten en cuenta que el botón obtendrá un fondo verde tan pronto como tú cambies uno de los elementos.

![Navigating in the main toolbar](https://github.com/mozilla-l10n/localizer-documentation/blob/master/assets/images/pontoon/ui/main_nav.png)

Si das clic en `All (todo)` o `Current (actual)` en el menú desplegable, podrá desplazarse lejos del espacio de trabajo de traducción:
* En la sección `Locales`, `All Teams (Todos los equipos)` se enlazan con la *Página equipos*, mientras que `Current Team (Equipo actual)` se vincula a la *Página del equipo* del local actual.
* •	En la sección `Project (Proyectos)`, `All Projects (Todos los proyectos)` se enlaza con la *Página de proyectos*, mientras que `Current Project (Proyecto actual)` se vincula a la *Página del proyecto* para el proyecto actual.
* •	En la sección `Resources (Recursos)`, `All Resources (Todos los recursos)` pueden mostrar cadenas de todos los archivos de los proyectos, mientas `Current Localization (Localización actual)` se vincula a la *Página de Localización*.

Más información sobre cómo se organizan las páginas en Pontoon está disponible en [este documento](https://github.com/mozilla-l10n/localizer-documentation/blob/master/tools/pontoon/teams_projects.md).

Una visión general del estado del recurso seleccionado se encuentra a la derecha del menú de herramientas principal. Los traductores pueden ver la descripción en detalle dando click una vez. 

![Expanded String Overview](https://github.com/mozilla-l10n/localizer-documentation/blob/master/assets/images/pontoon/ui/string_overview.png)

El ícono de información de un proyecto se encuentra a la derecha de la vista general de cadenas. Los traductores pueden ver información respecto al proyecto, su nivel de prioridad, y pruebas dando clic en el icono.

El ícono de notificaciones, representado por una campana, está ubicado al lado derecho de la barra de herramientas principal. Los traductores pueden ser notificados de cualquier actualización importante respecto al proyecto actual. Dando clic en el ícono de la campana, los traductores pueden ver las notificaciones en más detalle o ver todas las notificaciones activas.

El menú de perfiles está ubicado en la parte derecha de la barra de herramientas principal. Dando clic en la imagen se mostrará el menú desplegable. Desde este menú, los traductores pueden realizar varias acciones, como navegar en su página de perfil, descargar y cargar traducciones, etc. Para más información sobre cargar y descargar mira [este documento](translate.md#downloading-and-uploading-translations), para ver maquinaria [aquí](resources.md#machinery-tab). 

![Profile menu](https://github.com/mozilla-l10n/localizer-documentation/blob/master/assets/images/pontoon/ui/profile_menu.png)

Ten en cuenta que algunos ítems del menú de perfil son restringidos por [derechos de usuario](users.md#user-roles).

### Barra lateral

La barra lateral muestra la lista de cadenas en el recurso del proyecto actual. Cada cadena se muestra con el estado de la cadena (Por ejemplo, *Faltante*, *Traducida*, etc.) identificada por un cuadro de color, la cadena de origen y la traducción aprobada o la sugerencia más reciente, si está disponible. 

![Sidebar](https://github.com/mozilla-l10n/localizer-documentation/blob/master/assets/images/pontoon/ui/sidebar.png)

En la parte superior de la barra lateral, el traductor puede acceder a los [filtros de búsqueda y filtros de cadena](search_filters.md) de Pontoon.

Ten en cuenta que la barra lateral cambia entre las cadenas y el espacio de edición cuando se utiliza el editor en-contexto.

### Espacio de trabajo de traducción

El espacio de trabajo de traducción es donde se traducen las cadenas.

![Translation workspace](https://github.com/mozilla-l10n/localizer-documentation/blob/master/assets/images/pontoon/ui/workspace_standard.png)

Un traductor puede navegar secuencialmente dando clic en los botones  `PREVIOUS (ANTERIOR)` or `NEXT (SIGUIENTE)` localizados en la parte superior del espacio de trabajo o usando los atajos del teclado (`ALT` + flecha hacía abajo o arriba).

En la sección superior del espacio de trabajo, el traductor puede ver la cadena de origen, comentarios relacionados con la cadena y la ruta de recursos donde se encuentra la cadena.

El espacio de edición está ubicado en el la sección inferior del espacio de trabajo. El traductor puede editar la traducción o sugerencia en el editor de texto.

En el lado inferior derecho del espacio de trabajo, el traductor puede `COPY (COPIAR)` la cadena de origen al editor, `CLEAR (BORRAR)` el área donde se escriben las traducciones, y `SUGGEST (SUGERIR)` o `SAVE (GUARDAR)` la traducción haciendo clic en el botón correspondiente. 

En la parte inferior izquierda, un traductor puede acceder a las opciones del espacio de trabajo, los atajos del teclado y ver el número de caracteres en las cadenas de destino y de origen.

Cuando trabajamos en archivos de 120n, el espacio de edición se verá poco diferente:

![Translation workspace for l20n files](https://github.com/mozilla-l10n/localizer-documentation/blob/master/assets/images/pontoon/ui/workspace_l20n.png)

En el anterior ejemplo, la cadena tiene 2 atributos: `value (valor)` y `title (título)`. Ambos se muestran en la sección fuente (destacado en rojo), y están disponibles como campos de entrada independiente en el área de edición (destacada en naranja). 

Al hacer clic en el ícono de la rueda, el traductor puede activar o desactivar los `Quality Checks (Controles de calidad)`o `Make Suggestions (Hacer sugerencias)` y navegar a su configuración de usuario. 

![Settings menu](https://github.com/mozilla-l10n/localizer-documentation/blob/master/assets/images/pontoon/ui/settings.png)

Ten en cuenta que el acceso a determinadas configuraciones puede estar restringida por los [derechos de usuario](users.md#user-roles).

Al hacer clic en el teclado, un traductor puede ver los atajos de teclado del área de trabajo.

![Keyboard Shortcuts](https://github.com/mozilla-l10n/localizer-documentation/blob/master/assets/images/pontoon/ui/shortcuts.png)

### Recursos del espacio de trabajo de Pontoon

Los recursos de traducción incorporados se encuentran abajo del espacio de edición. Los tres recursos integrados son `HISTORY (HISTORIAL)`, `MACHINERY (MAQUINARÍA)` , and `LOCALES (LOCALES)`.

![Translation Resources](https://github.com/mozilla-l10n/localizer-documentation/blob/master/assets/images/pontoon/ui/resources.png)

Aprende a usar los recursos de traducción de Pontoon [en este documento](resources.md).

## Editor de Pontoon en contexto

El editor en contexto de Pontoon muestra las cadenas traducidles tal como aparecen en la página web, junto con el espacio de edición. Esto significa que los traductores puede ver donde aparece la cadena de origen y se ve la traducción en tiempo real. El editor en contexto de Pontoon muestra las cadenas en contexto a la derecha con la traducción del banco de trabajo a la izquierda.

![in-context editor](https://github.com/mozilla-l10n/localizer-documentation/blob/master/assets/images/pontoon/ui/incontext_edit.png)

Cuando se utiliza el editor en contexto, la barra lateral incluye tanto la navegación por cadenas como el espacio de edición. Para ver el espacio de edición, dar doble clic en una cadena. Para regresar a la navegación por cadenas, dar clic en `BACK TO LIST (VOLVER A LA LISTA)` en la parte superior izquierda de la barra lateral. 
