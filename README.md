# GO

## Reto A
`````go
package main

import "fmt"

func main() {
    edad := 18
 if edad >= 18 {
        fmt.Println("Eres mayor de edad.")
    }
    else{
     fmt.Println("Menor de edad")   
    }
}
`````
si la edad es 17 no entrara al primer if y entrara al else y mostara que es menor de edad
si la edad es 18 al ser igual que la condicion del if entrara en este bloque y motrara eres mayor de edad
si la edad es 20 al ser mayo que 18 entrara en el bloque el if y mostrara que es mayor de edad

## Investigación y comparación

1. ¿Cómo se declara la variable o el contador?

con var var edad int = 25 var ciudad string = "Madrid"

Se puede declarar màs de una variable var ( nombre = "Ana" edad = 30 )

con := (forma corta) nombre := "Carlos" numero := 42

2. ¿Cómo se delimitan los bloques de código? Comparadlo con la indentación de Python. con las {}. En Python se hace con tabulaciones.

   3. ¿Qué símbolos o palabras cambian respecto al ejemplo en Python?
Crear la variable: en Python edad = 20, en Go edad := 20.
Los bloques: Python usa dos puntos y sangría; Go usa llaves { }.
Imprimir: en Python print(), en Go fmt.Println().
El else: en Python va solo en su línea (else:). En Go tiene que ir en la misma línea que la llave que cierra el if (} else {); si lo pones en la línea de abajo, da error.

4. ¿Qué decisiones o repeticiones se mantienen? Explicad el algoritmo en castellano, sin usar código.
Las palabras if y else, la condición edad >= 18 y las dos ramas.

Algoritmo:

Guardar la edad.
Comprobar si es mayor o igual que 18.
Si lo es, mostrar "Mayor de edad".
Si no, mostrar "Menor de edad".

5. ¿Habéis necesitado algún elemento adicional para ejecutar el programa, como una función principal? Separadlo de la estructura que estáis investigando.
Necesitamos una funcion main para que se pueda ejecutar el código por el tipo de lenguaje, a diferencia del caso en python
