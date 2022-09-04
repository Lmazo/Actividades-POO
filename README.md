import java.util.Scanner;
class ejercicio7EDL {
  public static viod main(String[] args){
    Scanner entrada = new Scanner(System.in);
    int A, B;
    System.out.println("Ingrese A: ");
    A=entrada.nextInt();
    System.out.println("Ingrese B: ");
    B=entrada.nextInt();
    if (A>B){
      System.out.println("A es el mayor");
    } else {
      System.out.println("B es el mayor");
    }
  }
}


import java.util.Scanner;
class ejercicio10EDL {
  public static void main(String[] args){
    Scanner entrada = new Scanner(System.in);
    double  p, pagoM=50000;
    double eS, nI;
    String n;
    System.out.println("Ingrese nombre:");
    n=entrada.nextLine();
    System.out.println("Ingrese numero de inscripcion: ");
    nI=entrada.nextInt();
    System.out.println("Ingrese patrimonio: ");
    p=entrada.nextDouble();
    System.out.println("Ingrese estrato: ");
    eS=entrada.nextDouble();
    if (p>2000000&eS>3) {
      pagoM=pagoM+0.03+p;
    }
    System.out.println("el estudiante con numero de inscripcion " + nI + " y nombre " + n + " debepagar: $" + pagoM);
  }
}
    
  




