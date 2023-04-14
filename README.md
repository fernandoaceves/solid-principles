# solid-principles

La principal acción que se tomó para esta actividad en el codigo, fue separar en diferentes funciones todas las actividades que se realizan en el codigo fuente, para de esta manera cumplir uno por uno con los principios SOLID.

SRP: siguiendo el principio de una sola responsabilidad, dividí el código en 3 funciones principales, cada una con su responsabilidad unica lo que permite que mantengamos un codigo limpio y con capacidad de servir en su función.


OCP: las funciones ya tienen su objetivo claro y cumplen con su tarea, por lo que no es necesario modificarlas, sin embargo, pueden ser extensiones necesarias en algun punto posterior en el codigo. Por ejemplo, getMovies() podría obtener algun otro atributo de la variable "soup"


LSP: contamos con partes intercambiables del codigo que evitan que pueda fallar bajo ciertas circunstancias. Es decir, podríamos llamar la función de getMovies con alguna otra API siempre y cuando los parametros y la información de está ultima coincida


ISP: Evitamos depender de una o varias funciones gracias a la indenpendencia de estas, por dar un ejemplo, no es necesario llamar a la función de "createFile" si en algun momento decidimos desplegar nuestra información de alguna otra manera.


DIP: evitamos la dependencia de nuestro codigo de alto nivel al de nivel bajo mediante el uso de abstracciones o bien de interfaces, de esta manera si es necesario cambiar algo en el codigo, no tendremos que tocar nada de las conexiones en alto nivel, si no todo en la parte de nivel bajo de nuestro codigo.
