- crear un archivo JS llamado users.js en la carpeta 'src/public/js'
- adaptar rutas y controladores para que al ingresar a la ruta '/users', se renderice la vista 'users'
- implementar en dicha vista el archivo users.js (llamar el script)
- utilizar el atributo style de las etiquetas correspondientes para lograr que:
  - el header tenga:
    - 30px de alto
    - padding a los costados de 40px
    - que sea flexible y ordene a sus hijos de manera centrada vertical y horizontalmente, pero con un espacio entre ellos de 30px
    - que el color de todos los textos sea #f00
  - el h1 tenga:
    - color #f00
    - tamaño de la letra de 30px
- implementar un modo oscuro (fondo negro en vez de blanco y el titulo blanco en vez de negro) con el atributo style de los elementos que correspondan, utilizando funciones para encapsular toda la logica
- implementar con el confirm si el usuario desea realmente cambiar el modo actual al opuesto cuando se haga clic en los botones correspondientes
- una vez se haya hecho clic en algun boton de cambiar modo, hacer un console.log del nuevo modo seteado
- implementar que al cargar la pagina se le avise al usuario que la pagina va a cargar en modo claro, pero que va a disponer de los botones para cambiar de modo
- implementar un nuevo boton que permita que el usuario pueda escribir un nuevo titulo, y que ese valor se refleje en el h1
