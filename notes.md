### Reportes Usuarios

* No se ve cuando se ha producido un error.
  * Revisado motivo del error. Se ha creado página de error 500 (Actualmente sin diseño). El usuario ya sabe que debe darle atrás.
* El loader no se ve con claridad, aparece como un flash causando molestia en la usabilidad.
  * Corregido, establecido tiempo mínimo de loader
* El loader si se ha producido un error se queda colgado.
  * Analizado, se debe cuando ha sucedido un error y volvías. El loader no se ocultaba.
* No puedo compartir enlace con filtros prestablecidos.
  * 🔨 Trabajando en esta mejora.
  * [Enlace de creación de directiva para ello](https://netbasal.com/a-simple-reusable-solution-for-binding-url-query-params-to-angular-forms-f33cc4b5bc7a)
    ➡️`modules/shared/services/bind-query-params.directive.ts`
  * No consigo que me funcione el ejemplo expuesto en [stackblitz](https://stackblitz.com/edit/angular-bitsman?file=src%2Fapp%2Fbind-query-params.directive.ts)
    * [Directiva appBindQueryParams](https://stackblitz.com/edit/angular-bitsman?file=src%2Fapp%2Fbind-query-params.directive.ts)
    * [Uso de directiva](https://stackblitz.com/edit/angular-bitsman?file=src%2Fapp%2Fapp.component.html)
* Puedo crear 2 usuarios con el mismo email
  * 🔨 Trabajando en esta mejora.
    * Añadir unique index to user db table
    * Captura de error para mostrar en front adecuadamente.
* Mostrar errores 4XX en la aplicación angular
  * 📓 Pendiente de investigar
