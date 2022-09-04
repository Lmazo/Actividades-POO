# Actividades-POO



Import.java.util.Scanner;
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
