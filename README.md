/*
 Ejercicios Java 
 */
package javaproject;

/**
 *
 * @author Lidia
 */
public class Javaproject {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        int numero = 15; // Reemplaza este valor con el número que quieras comprobar

        // Comprueba si un número es mayor que 10 y menor que 20.
        if (numero > 10 && numero < 20) {
            System.out.println("El número " + numero + " es mayor que 10 y menor que 20.");
        } else {
            System.out.println("El número " + numero + " no cumple con la condición.");
        }
        
         String cadena = "hola como estas?"; // Reemplaza esta cadena con la que quieras verificar

        //  2Determina si una cadena de texto contiene la letra "a" y la letra "b".
 
        if (cadena.contains("a") && cadena.contains("b")) {
            System.out.println("La cadena de texto contiene las letras 'a' y 'b'.");
        } else {
            System.out.println("La cadena de texto no contiene ambas letras 'a' y 'b'.");
        }
        
        //  3Verifica si un número es par o si es múltiplo de 5.
         int numeroone = 10;

        // 

        if (numeroone % 2 == 0) {
            System.out.println("El número " + numeroone + " es par.");
        } else {
            System.out.println("El número " + numero + " no es par.");
        }

         if (numeroone % 5 == 0) {
            System.out.println("El número " + numeroone + " es múltiplo de 5.");
        } else {
            System.out.println("El número " + numeroone + " no es múltiplo de 5.");
        }
        
         double calificacion = 7.0;

        //  4Determina si un estudiante ha aprobado si su nota es mayor o igual a 60 y menor 
 
        if (calificacion >= 60.0 && calificacion <= 100.0) {
            System.out.println("El estudiante ha aprobado con una calificación de " + calificacion);
        } else {
            System.out.println("El estudiante no ha aprobado con una calificación de " + calificacion);
        }
        
        
         int shop = 150;

        // 5 Verifica si un número es menor que 50 o mayor que 100.

        if (shop < 50 || shop > 100) {
            System.out.println("El número " + shop + " es menor que 50 o mayor que 100.");
        } else {
            System.out.println("El número " + shop + " no cumple con ninguna de las condiciones.");
        }
        
         int entero = 100;

        // 6 Comprueba si un número es mayor que 5 y menor que 10 

        if (entero > 5 && entero < 10) {
            System.out.println("El número " + entero + " es mayor que 5 y menor que 10.");
        } else {
            System.out.println("El número " + entero + " no cumple con la condición.");
        }
        
        int numerob = 30;

        //  7 o si es mayor que 20 y  menor que 30.
 
        if (numerob > 20 && numerob < 30) {
            System.out.println("El número " + numerob + " es mayor que 20 y menor que 30.");
        } else {
            System.out.println("El número " + numerob + " no cumple con la condición.");
        }
    
         String texto = "Me gusta estudiar programación, me gusta usar Java en vez de JavaScript";

        // 8 Verifica si una cadena de texto contiene la palabra "Java" y no contiene la palabra
 
        if (texto.contains("Java") && !texto.contains("Python")) {
            System.out.println("La cadena de texto contiene 'Java' y no contiene 'Python'.");
        } else {
            System.out.println("La cadena de texto no cumple con la condición.");
        }
        
        
         int numeroabc = 45;

        // 9 Comprueba si un número es múltiplo de 3 y no es múltiplo de 5.
 
        if (numeroabc % 3 == 0 && numeroabc % 5 != 0) {
            System.out.println("El número " + numeroabc + " es múltiplo de 3 y no es múltiplo de 5.");
        } else {
            System.out.println("El número " + numeroabc + " no cumple con la condición.");
        }
        
         int numerocinco = -5;

        // 10 Comprueba si un número es mayor que 100 o si es menor que -100.
        if (numerocinco > 100 || numerocinco < -100) {
            System.out.println("El número " + numerocinco + " cumple con alguna de las condiciones.");
        } else {
            System.out.println("El número " + numerocinco + " no cumple con ninguna de las condiciones.");
        }
    }
    
}
