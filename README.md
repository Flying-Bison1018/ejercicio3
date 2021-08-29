# ejercicio3
actividad
package ejercico3;

/**
 *
 * @author PC
 */
import java.util.Scanner;
public class Ejercico3 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Scanner decimal = new Scanner(System.in);
        float num1;
        float num2;
        float suma;
        float promedio;
        float cociente;
        float modulo;
        
        System.out.printf("Ingrese numero\n");
        num1=decimal.nextFloat();
        System.out.printf("Ingrese numero 2\n");
        num2=decimal.nextFloat();
        
        
       suma = num1+num2;
       promedio =(num1+num2)/2;
       cociente = num1/num2;
       modulo = num1 % num2;
     
       System.out.printf("El resultado es:"+suma);
       System.out.printf("\nEl resultado es:"+promedio);
       System.out.printf("\nEl resultado es:"+cociente);
       System.out.printf("\nEl resultado es:"+modulo);
        // TODO code application logic here
    }
    
}
