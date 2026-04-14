¿Qué hace la anotación @BeforeEach?
Hace que un método se ejecute antes de cada uno de los metodos de prueba o @Test dentro de una misma clase.

¿Para qué sirve assertTrue?
Para verificar que una condición que se da dentro de un test sea verdadera (ej: AssertTrue se utiliza cuando un test requiere que el nombre de usuario tenga al menos un caracter e introducimos uno o más caracteres).

¿Qué diferencia hay entre findElement() y findElements()?
findElement() busca un unico elemento web, detectando solo el primero que coincide con el localizador y en caso de no encontrar ninguno lanza una excepción, mientras que findElements() Detecta todos los elementos web que 
coinciden con el localizador, devolviendo una lista detodos los elementos encontrados y en el caso de no encontrar ninguno, no mostrará ninguna excepción.

¿Por qué utilizamos una clase LoginPage en lugar de escribir todo en el test?
Porque favorece a la mantenibilidad (al tener que modificar el codigo solamente en el LoginPage), reutilización de código y tambien resulta más legible y claro al omitirse gran cantidad de código.
