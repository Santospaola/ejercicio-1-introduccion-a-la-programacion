# ejercicio-1-introduccion-a-la-programacion
establecer funciones

-----primera parte-----

package
import "fmt"

func main (){
  resultado := suma (10, 20, 30)
  fmt.println(resultado)
}
func suma (a int, b int, c int) int{
  return a + b + c
}

----segunda parte----

package com.company;

public class Main {

    public static void main(String[] args) {
        Coche miCoche= new Coche();
        miCoche.AgregarPuerta();
        System.out.println(miCoche.puertas);
    }

class Coche{
        public int puertas= 0;
        public void AgregarPuerta(){
            this.puertas ++;
        }
    }
