# Concurso_met_num

## Concurso de Belleza de Funciones


### Bases:

1. Se trata de crear la más bella función que aplique la **regla de Simpson compuesta** a una función en un intervalo y devuelva el valor obtenido. Los argumentos de la función serán: (función a *integrar*, intervalo, número de puntos de evaluación).

2. Podrá participar en 3 categorias:

    a. La más flaquita: la que utilize el menor número de caractéres (sin contar el nombre de la función).
    
    b. La más rápida: la que de el menor tiempo de ejecución cuando se aplique con argumentos:  y según el valor obtenido con el macro `@btime My_Simpson(sin,(0,\pi),101)` de la librería `BenchmarkTools`
    
    c. La menos alocada: la que utilize (`aloc`) la menor cantidad de memoria posible según el resultado que arroje `@btime My_Simpson(sin,(0,\pi),101)`
    
3. La participación será en grupos de al menos 3 estudiantes regulares del curso.

4. La propuesta deberá ser entregada el **día martes 31 de mayo a las 9:00 horas**, vía correo electrónico a *oreula@unc.edu.ar* en un notebook con una presentación (en markdown) acorde. La presentación será tenida en cuenta en caso de empate.