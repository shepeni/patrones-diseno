# patrones-diseno

Patron Template (Plantilla)

Define el algoritmo a utilizar, dejando metodos abstractos para realizar la tarea especifica de la implementacion.

Por ejemplo podemos definir una clase Trabajador con los siguientes metodos:

      levantarse()
      prepararse()
      irAlTrabajo()
      trabajar()
      regresar()
      relajarse()
      dormir()
      
La ejecucion del metodo define el orden y como se utilizaran las clases, cada clase derivada, de esta implementara los 
metodos especificos y necesarios para ejecutar la tarea, por ejemplo una clase Albañil que extienda de esta clase 
implementara diferente el metodo trabajar, pero los otros metodos los implementara de la misma manera


https://dzone.com/articles/3-best-practices-java-programmers-can-learn-from-s?edition=383226&utm_source=Daily%20Digest&utm_medium=email&utm_campaign=Daily%20Digest%202018-06-19

