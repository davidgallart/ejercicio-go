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

¿Cómo se declara la variable o el contador?

con var var edad int = 25 var ciudad string = "Madrid"

Se puede declarar màs de una variable var ( nombre = "Ana" edad = 30 )

con := (forma corta) nombre := "Carlos" numero := 42

¿Cómo se delimitan los bloques de código? Comparadlo con la indentación de Python. con las {}. En Python se hace con tabulaciones.