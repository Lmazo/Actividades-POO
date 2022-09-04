//CAPITULO 4: ESTRUCTURA DECISIÓN LÓGICA 

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


import java.util.Scanner;
class ejercicio11EDL {
  public static void main(String [] args){
    Scanner entrada = new Scanner(System.in);
    int a, b, c;
    System.out.println("ingrese el primer numero: ");
    a=entrada.nextInt();
    System.out.println("ingrese el segundo numero: ");
    b=entrada.nextInt();
    System.out.println("ingrese el tercer numero: ");
    c=entrada.nextInt();
    if (a>b &  a>c) {
      System.out.println("el mayor es: " + a);
    } 
    if (b>a & b>c) {
      System.out.println("el mayor es: " + b);
    } Else {
        System.out.println("el mayor es: " + c);
      }
  }
}


import java.util.Scanner;
class ejercicio12EDL {
  public static void main(String [] args){
    Scanner entrada = new Scanner(System.in);
    String n;
    double nht, vht, het, hett, s;
    System.out.println("Ingrese su nombre: ");
    n=entrada.nextLine();
    System.out.println("ingrese el numero de horas trabajadas: ");
    nht=entrada.nextDouble();
    System.out.println("ingrese el valor por hora  de trabajo: ");
    vht=entrada.nextDouble();
    if (nht>40){
      het=nht-40;
      if (het>8){
        hett=het-8;
        s=40*vht+16*vht+vhtt*3*vht;
      } else {
          s=40*vht+het*2*vht;
        } 
     }else {
        s=nht*vht;
    }
    System.out.println("el trabajador " + n + " devengo: $" + s);
}
}


import java.util.Scanner;
class ejercicio13EDL {
  public static void main(String [] args){
    Scanner entrada = new Scanner(System.in);
    double vC, vP, pD;
    String c;
    System.out.println("ingrese el color de la bolita: ");
    c=entrada.nextLine();
    vC=543450;
    if ("blanco".equals(c)){
       pD=0;
    }else{
       if ("verde".equals(c)){
          pD=10;
       }else{ 
          if ("amarillo".equals(c)){
             pD=25;
          }else{
             if ("azul".equals(c)){
                pD=50;
             }else{
                pD=100;
             }
}
}
}
vP=((pD*vC)/100);
System.out.println("el cliente debe pagar: $"+ vP);
}
}
  




