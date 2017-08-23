# Cuentas de usuario y configuración

- [Creando una cuenta](#Creando-una-cuenta)
- [Configuraciones de usuario](#Configuraciones-de-usuario)
- [Roles de usuarios](#Roles-de-usuario)
- [Administración de permisos](#Administrador-de-permisos)

## Creando una cuenta

Pontoon actualmente usa las cuentas de Firefox para administrar usuarios, entonces tú necesitarás [crear una cuenta](https://accounts.firefox.com/signup) para iniciar sesión.
Para crear una cuenta en  [Pontoon](https://pontoon.mozilla.org/), simplemente da clic en el icono menú en la esquina superior y selecciona <i>Sing in</i> (registrarse).

<img src= "https://github.com/mozilla-l10n/localizer-documentation/blob/master/assets/images/pontoon/users/menu_login.png">


## Configuraciones de usuario
Se puede acceder a la configuración de usuario dando clic en el avatar de usuario en la esquina superior derecha y seleccionando <i>Settings</i> (configuración).

<img src= https://raw.githubusercontent.com/mozilla-l10n/localizer-documentation/master/assets/images/pontoon/users/menu_settings.png>

Tú imagen de perfil puede ajustarse en [Gravatar](http://gravatar.com/), mientras que puedes editar el nombre que se muestra simplemente haciendo clic en él.

<img src= https://raw.githubusercontent.com/mozilla-l10n/localizer-documentation/master/assets/images/pontoon/users/profile_page.png>

Tanto *Controles de calidad* como *Hacer sugerencias* son cajas de verificación. En la imagen anterior, los *Controles de calidad* están desactivados mientras está activada la opción *Hacer sugerencias*.
* Los*Controles de calidad* (verificación del número de oraciones, marcadores de posición, etiquetas HTML, puntuación, etc.) se realizan al guardar una traducción.
* *Hacer sugerencias* permite que un traductor o un administrador presente sugerencias en lugar de traducciones.

Las dos configuraciones pueden cambiarse directamente desde el menú de cambios (resaltado con naranja) al traducir cadenas. También se puede acceder a los ajustes de usuario desde este menú seleccionado *Cambiar todos los ajustes*.

<img src= https://raw.githubusercontent.com/mozilla-l10n/localizer-documentation/master/assets/images/pontoon/users/translation_gear.png>

Los *Locales preferidos* se pueden utilizar para visualizar un grupo específico de locales antes que otros en la pestaña *LOCALES* cuando se traducen cadenas (resaltado en rojo). En este caso, el usuario optó por mostrar fr y es-ES antes de otras traducciones. Dado que ambos están disponibles, la pestaña muestra 2+72, lo que significa 2 locales preferidos más todos los demás. 

<img src= https://raw.githubusercontent.com/mozilla-l10n/localizer-documentation/master/assets/images/pontoon/users/translation_locales.png>

## Roles del usuario

Hay actualmente cuatro funciones de usuario en Pontoon.

* Los **Contribuidores** solo puede realizar sugerencias. Este es el rol predeterminado para los nuevos usuarios.
* Los **Traductores** pueden enviar traducciones directamente en un local específico, y revisar las sugerencias de los contribuidores.
* Los **Managers** pueden realizar las mismas acciones de los traductores, pero también administrar a otros usuarios y actualizar sus permisos.
* Los **Administradores** pueden administrar Pontoon, por ejemplo agregar o eliminar proyectos, y actuar como gestores de todos los locales.


## Administración de permisos

Un **manager** puede actualizar los permisos de otros usuarios dentro de un local. Para administrar los usuarios, abre la página del equipo y selecciona la pestaña de *CONTRIBUIDORES* (esto solo será visible para **managers** y **administradores**).

De forma predeterminada, solo hay una sección **General**: los permisos definidos aquí se aplicarán a todos los proyectos, pero podrían ser anulados por permisos de proyectos personalizados.

<img src= https://raw.githubusercontent.com/mozilla-l10n/localizer-documentation/master/assets/images/pontoon/users/permissions_general.png>

Para mover a un usuario a una columna diferente simplemente coloca la dirección de correo electrónico: las flechas aparecerán para mover el elemento a la izquierda o a la derecha. Ten en cuenta que un usuario necesita haber iniciado sesión al menos una vez en  [Pontoon](https://pontoon.mozilla.org/) con el fin de actualizar su permiso –simplemente tener una cuenta Firefox no es suficiente.

Utiliza el botón *GUARDAR* para almacenar la configuración antes de salir de esta ventana.

Por defecto, en la columna de *EQUIPO DE CONTRIBUIDORES* solo aparecerán los usuarios que han enviado sugerencias antes para este local. Tú puedes dar clic en *TODOS LOS USUARIOS* (resaltado en rojo) para mostrar todos los usuarios existentes, después usa el campo de búsqueda para restringir la lista.

Al hacer clic en *ADICIONAR PERMISOS PERSONALIZADOS POR PROYECTO* (resaltado en naranja), es posible agregar permisos específicos para un proyecto. Esto puede ser útil para asegurarse que solo algunos usuarios pueden enviar traducciones para un proyecto específico, por ejemplo si este es mantenido por una persona.

<img src= https://raw.githubusercontent.com/mozilla-l10n/localizer-documentation/master/assets/images/pontoon/users/permissions_project.png>

Ten en cuenta que no es posible invalidar a los managers, ellos siempre podrán enviar traducciones en cualquiera de los proyectos disponibles para su local.
