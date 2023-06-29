# Historias de Usuario

## HU1
| Título: Traducir un número a Kichwa                                                                                                                                   |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Como** persona interesada en el idioma kichwa **quiero** traducir un número en dígitos a kichwa **para** tener a disposición el equivalente en kichwa de un número. |
| Criterios de Aceptación                                                                                                                                               |

    Criterio de Aceptación 1: Precisión en la traducción

    - Dado un número válido en la entrada.
    - Cuando la aplicación traduce el número a su equivalente en letras en kichwa.
    - Entonces la traducción mostrada por la aplicación debe ser gramaticalmente correcta y corresponder al valor numérico ingresado.


    Criterio de Aceptación 2: Tolerancia a errores y excepciones

    - Dado una entrada inválida, como una cadena de texto no numérica.
    - Cuando se ejecuta la aplicación.
    - Entonces la aplicación debe mostrar un mensaje de error indicando que la entrada es inválida y proporcionar instrucciones claras al usuario para ingresar un número válido.


## HU2
| Título: Ejecución continua de la traducción a Kichwa                                                                                                                  |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Como** persona interesada en el idioma kichwa **quiero** traducir un número en dígitos a kichwa de forma continua, sin necesidad de  **para** no tener que tener a disposición el equivalente en kichwa de un número. |
| Criterios de Aceptación                                                                                                                                               |
| - La aplicación debe proporcionar una opción clara al usuario para indicar si desea traducir otro número. |
| - Si el usuario elige traducir otro número, la aplicación debe permitirle ingresar un nuevo número y mostrar el resultado correspondiente. |
| - Si el usuario no desea traducir otro número, la aplicación debe finalizar de manera ordenada, cerrando la ejecución. |