# Creador de tests

## Resumen

Esto es un repositorio que contiene las preguntas para el creador de tests que está en el repositorio [GRIA-TestCreator](https://github.com/SantiagoRR2004/GRIA-TestCreator).

## Contribuir

**Importante:** Al hacer un pull request se realiza una comprobación de formateo que para pasarla deben estar los ficheros con un formato en específico. La mejor manera de asegurarse de que esto siempre ocurra es ejecutar la acción sobre formateo en el fork que has creado. Es necesario que sea en el fork; y solo se necesita una vez manualmente, ya que se ejecuta cada vez que haya un cambio en el fork. No se ejecuta de manera automática inicialmente por razones de seguridad en GitHub.

La manera fácil de contribuir es añadiendo más preguntas. Estas se encuentran en los ficheros .json que hay en la carpeta de cada asignatura. Los ficheros tienen que ser `.json`. Cada fichero es un diccionario con una única clave `questions` cuyo valor es una lista de diccionarios. Más bajo se explica cada tipo de pregunta que está implementado. Antes de subir una pregunta nueva asegúrate de que está bien escrita, la respuesta es la correcta y que el programa sigue funcionando.

Para añadir tus cambios haz un fork con el nombre de la asignatura a la que quieres añadir preguntas y añade las preguntas. Luego haz un pull request y si todo está bien se añadirá al programa.

Para ver los tipos de preguntas disponibles, consulta la documentación del creador de tests.
