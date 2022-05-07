## Reportes Usuarios

### Feedback usuarios (1/4/2022 - 10/4/2022)

#### Correcciones

* No se ve cuando se ha producido un error.
  * ✅ Revisado motivo del error. Se ha creado página de error 500 (Actualmente sin diseño). El usuario ya sabe que debe darle atrás.
* El loader si se ha producido un error se queda colgado.
  * ✅ Analizado y corregido, se debe cuando ha sucedido un error y volvías. El loader no se ocultaba.
* Si no relleno correctamente un formulario no se cual es el motivo solo aparece error.
  * 📓 Analizando este punto de corrección, se puede realizar:
    * Mapear de propiedades back-front
    * O bien, definir reglas de formulario en parte front
  * 🧐 Analizando, para scope del MVP, es más rápido y filtra llamadas back si se realiza el control previo en front, para evitar errores back.
    * ✅🔨 Implementamos validaciones front. Realizada para formularios existentes.
  * 🔥 No obstante, debemos mostrar de algún modo aquellos errores que nos pueda devolver el back. Como email de usuario repetido. Por lo que:
    * ✅ Debemos mostrar errores 4XX en la aplicación angular
* Puedo crear 2 usuarios con el mismo email
  * ✅ Corregido

#### Mejoras

* Applicación en inglés
  * ✅ Realizada traducciones
* El loader no se ve con claridad, aparece como un flash causando molestia en la usabilidad.
  * ✅ Corregido, establecido tiempo mínimo de loader
* No puedo compartir enlace con filtros prestablecidos.
  * ⚠️⏳️Dificultades para llevarla a cabo ➡ Lo sacamos del scope del MVP
    * 📓 [Enlace de creación de directiva para ello](https://netbasal.com/a-simple-reusable-solution-for-binding-url-query-params-to-angular-forms-f33cc4b5bc7a)
      ➡ `modules/shared/services/bind-query-params.directive.ts`
    * 😵‍💫 No consigo que me funcione el ejemplo expuesto en [stackblitz](https://stackblitz.com/edit/angular-bitsman?file=src%2Fapp%2Fbind-query-params.directive.ts)
      * [Directiva appBindQueryParams](https://stackblitz.com/edit/angular-bitsman?file=src%2Fapp%2Fbind-query-params.directive.ts)
      * [Uso de directiva](https://stackblitz.com/edit/angular-bitsman?file=src%2Fapp%2Fapp.component.html)

#### Notas positivas

* 🖖 Me gusta el objectivo que se quiere conseguir con esta aplicación.
* 🏷️ Me gusta el nombre añadido con la forma de llave, transmite muy bien el mensaje.
* ⏱️ Va muy rápida.
* 🤓 Me gusta lo fácil que se accede al contenido.
* 💪 Me gusta que cuando dejo de escribir en los filtros realiza el filtro en la tabla.

### Feedback usuarios (29/4/2022 - 8/5/2022)

#### Correcciones

* Algunas cosas siguen sin traducir y otras no:
  * 🔨 Realizando traducciones pendientes
  * 📓 Las traducciones provenientes de la parte back siguen pendientes.
    * Mejora tras la entrega de MVP. Ya que requiere de análisis, por si se debe crear algún tipo de mapeo con formularios.

#### Mejoras

* Falta traducciones en email
  * 📓 Pendiente de investigar. Traducciones en back.
    * Traducciones de emails
    * Traducciones de errores

#### Notas positivas

* 🇪🇦 Aplicación en español, la recuerdo en inglés

### Feedback usuarios (7/5/2022 - 7/5/2022)

#### Correcciones

*Me gustaría filtrar los proyectos y máquinas por clientes
*Hay que revisar bien el front en visualización móvil, no se ve correctamente y fallan algunos scroll como el del menú de la izquierda cuando se está en visualización escritorio y se gira el móvil.
