import java.util.Scanner;

public class OperacionesMenu2{
  public static void main(String args[]){

  Scanner in = new Scanner(System.in);
  String nombre = "";
  int num_uno = 0, num_dos = 0, resultado = 0;
  int parametro = 0;

  System.out.println("");
  System.out.print("Hola,¿Cual es tu nombre? ");
  nombre = in.nextLine();

  System.out.println("");
  System.out.println("*******************************************************");
  System.out.println("Suma = 1 ");
  System.out.println("Resta = 2 ");
  System.out.println("Multiplicacion = 3 ");
  System.out.println("Division = 4 ");
  System.out.println("*******************************************************");
  System.out.println(""); 

  System.out.print(nombre + " dame el numero de la operacion que quieres hacer: ");
  parametro = in.nextInt();
  System.out.println("");

  switch(parametro){
   
   case 1: System.out.print("Dame el primer valor para tu suma: ");
           num_uno = in.nextInt();
           System.out.println("");
           System.out.print("Dame el segundo valor para tu suma: ");
           num_dos = in.nextInt();
           System.out.println("");
           resultado = num_uno + num_dos;
           System.out.print(nombre + " el resultado de la suma es: " + resultado); 
           System.out.println("");
           break;

   case 2: System.out.print("Dame el primer valor para tu resta: ");
           num_uno = in.nextInt();
           System.out.println("");
           System.out.print("Dame el segundo valor para tu resta: ");
           num_dos = in.nextInt();
           System.out.println("");
           resultado = num_uno - num_dos;
           System.out.print(nombre + " el resultado de la resta es: " + resultado);
           System.out.println("");
           break;

   case 3: System.out.print("Dame el primer valor para tu multiplicacion: ");
           num_uno = in.nextInt();
           System.out.println("");
           System.out.print("Dame el segundo valor para tu multiplicacion: ");
           num_dos = in.nextInt();
           System.out.println("");
           resultado = num_uno * num_dos;
           System.out.print(nombre + " el resultado de la multiplicacion es: " + resultado);
           System.out.println("");
           break;

   case 4: System.out.print("Dame el primer valor para tu division: ");
           num_uno = in.nextInt();
           System.out.println("");
           System.out.print("Dame el segundo valor para tu division: ");
           num_dos = in.nextInt();
           System.out.println("");
           resultado = num_uno / num_dos;
           System.out.print(nombre + " el resultado de la division es: " + resultado);
           System.out.println("");
           break;

   default: System.out.println("Error, la opcion no existe " + nombre);
            break;
  }
 }
}
