# El-mayor-que
Código para dar variables y saber cual es la mayor 

package el.mayor.de.los.tres;
import java.util.Scanner;
public class ElMayorDeLosTres {
    public static void main(String[] args) {
        Scanner S = new Scanner(System.in);
        int a,b,c;
        System.out.println("Dame el valor del numero a: ");
        a = S.nextInt();
        System.out.println("Dame el valor del numero b: ");
        b = S.nextInt();
        System.out.println("Dame el valor del numero c: ");
        c = S.nextInt();
        
        if(a == b && b == c){
            System.out.println("Todos son iguales: "+a+b+c);
        }
        else if(a>b && a>c){
            System.out.println("El mayor de los 3 es a: "+a);
        }
        else if(b>a && b>c){
            System.out.println("El mayor de los 3 es b: "+b);
        }
        else if(c>b && c>a){
            System.out.println("El mayor de los 3 es c: "+c);
        }
    }
}
