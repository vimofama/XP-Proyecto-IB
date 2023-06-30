| Tarjeta CRC                                                                                                                     |               |
| ------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| Clase: Traductor                                                                                                                |
| Descripcion: Recibe un numero entero entre 0 y 9999 proporcionado por el usuario y devuelve el correspondiente texto en kichwa. |
| Responsabilidades                                                                                                               | Colaboradores |
| - Recibir el numero ingresado por el usuario.                                                                                   | CLI           |
| - Almacenar el texto en kichwa de las unidades, decenas, centenas y miles.                                                      |
| - Devolver el correspondiente texto en kichwa, del numero ingresado.                                                            |

| Tarjeta CRC                                                                                                                              |               |
| ---------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| Clase: CLI                                                                                                                               |
| Descripcion: Pregunta al usuario el numero del cual desea obtener el correspondiente texto en kichwa y muestra el resultado por consola. |
| Responsabilidades                                                                                                                        | Colaboradores |
| - Preguntar al usuario el numero para obtener su correspondiente texto en kichwa.                                                        | Traductor     |
| - Llamar al metodo que devuelve el texto en kichwa.                                                                                      |
| - Imprimir por consola el texto en kichwa.                                                                                               |
