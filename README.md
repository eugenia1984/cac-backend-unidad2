# Codo a Codo - Back End - Unidad2

## Actividad practica obligatoria de la Unidad 2 - Java

Consigna: <br>
Crear un programa en java en el cual se pida al usuario ingresar su nombre, apellido, edad, hobbie, editor de código preferido, sistema operativo que utiliza, luego deberá mostrarse por consola los datos ingresados. <br>

Este es el código del archivo **CodoACodo.java**: <br>

```
package codoacodo;

import java.util.Scanner;

public class CodoACodo {

    public static void main(String[] args) {
        //Declaro mis variables y las inicializo vacias
        String nombre = "";
        String apellido = "";
        int edad = 0;
        String hobbie = "";
        String editorCodigo = "";
        String sistemaOperativo="";
        //Clase Scanner
        //Instancio a la clase Scanner creando un nuevo objeto leer
        //Para leer lo que el usuario ingrese por consola
        Scanner leer = new Scanner(System.in).useDelimiter("\n");
        
        //Pido por consola que ingrese los datos 
        //Leo lo ingresado y lo asigno (guardo) en variable
        System.out.println("Ingrese su nombre : ");
        nombre = leer.next();
        System.out.println("Engrese su apellido: ");
        apellido = leer.next();
        System.out.println("Ingrese su edad (en numeros) : ");
        edad = leer.nextInt();
        System.out.println("Ingrese su hobbie: ");
        hobbie = leer.next();
        System.out.println("¿Cual es tu editor de codigo preferido ?");
        editorCodigo = leer.next();
        System.out.println("¿Qué sistema operativo usas ? ");
        sistemaOperativo = leer.next();
        System.out.println("Su nombre es : " + nombre + "\n Su apellido es: " + apellido + "\n Su edad es : " + edad + "\n Su hobbie: " + hobbie + "\n Su editor de código favorito : " + editorCodigo + "\n Su sistema operativo es: " + sistemaOperativo);
    }
    
}
```

---

## Por favor: 🎁

* Comparte este proyecto con otros  📢
* Invita una cerveza 🍺 o un café ☕ a alguien del equipo. 
* Muchas gracias.

---
## Notas
GRacias por tu interés en este proyecto ⌨️ de [María Eugenia Costa](https://github.com/eugenia1984) me podés eguir en [LinkedIn](http://www.linkedin.com/in/maríaeugeniacosta) 

