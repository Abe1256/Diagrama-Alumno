# CLASES
Para empezar, en este diagrama hay dos clases: CURSOS y ESTUDIANTES

# ELEMENTOS DE LAS CLASES
**CURSOS**
- Sus atributos son el nombre, el cual será de tipo string, y el código único del curso, el cual también será un string. Estos atributos tienen una visibilidad Privada, ya que tienen el signo -.
- Mientras tanto, su función es agregarAlumno. Esta función, la cual tiene visibilidad pública (tiene el signo +), tiene como funcionalidad agregar un alumno que se ha inscrito al curso, haciendo referencia a la segunda clase.

**ESTUDIANTES**
- Sus atributos son el nombre, que será tipo string, y el DNI único del estudiante. Al igual que en la clase anterior, estos atributos tienen visibilidad privada, debido al signo -.
- Esta clase tiene dos funciones: inscribirse y mostrarInscritos. La funcionalidad de inscribirse(curso) ess, como su propio nombre indica, inscribir al estudiante al curso que desee. Por otro lado, mostrarInscritos() tiene como función mostrar una lista de los alumnos inscritos a un curso.

# RELACIÓN DE LAS CLASES
Para empezar, la multiplicidad es de varios a uno, es decir, un número inespecificado de alumnos (representado con *) se inscriben en un curso. La relación es por agregación debido al rombo blanco. Un curso está compuesto por uno o muchos alumnos.
