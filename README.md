//CAPITULO 3: ESTRUCTURA SECUENCIAL
import java.util.Scanner;
public class ejercicio18
{
	public static void main(String[] args) {
	    
	    int codigoEmp, horasMes, valorHoras, retencionFuente;
	    String nombres;
	    
	    nombres="Pepito Perez";
	    codigoEmp = 12345;
	    horasMes = 190;
	    valorHoras = 5000;
	    
	    System.out.println("Codigo trabajador: " + codigoEmp);
	    System.out.println("Nombres: " + nombres);
	    
	    int salarioBruto, salarioNeto;
	    
	    salarioBruto = valorHoras * horasMes;
	    retencionFuente = salarioBruto/12;
	    salarioNeto = salarioBruto - retencionFuente;
	    
	    System.out.println("Salario bruto: " + salarioBruto);
	    System.out.println("Salario Neto: " + salarioNeto);
		
		
	}
}

import java.util.Scanner;
public class ejercicio19
{
	public static void main(String[] args) {
	    
	    double lado, p, h, a;
	    
	    lado = 5;
	    p = lado*3;
	    h = (Math.sqrt(3)*lado)/2;
	    a =  (lado*h)/2;
	    
	    System.out.println("El perimetro del triangulo es: " + p);
	    System.out.println("La altura del triangulo es: " + h);
	    System.out.println("El area del triangulo es: " + a);
	}
}

import java.util.Scanner;
public class ejercicio21
{
	public static void main(String[] args) {
	    
	    int ladoA, ladoB, ladoC, p, sp;
	    double a;
	    ladoA = 3;
	    ladoB = 4;
	    ladoC = 5;
	    
	    p = ladoA +ladoB + ladoC;
	    sp = (ladoA + ladoB + ladoC)/2;
	    a = Math.sqrt((sp*(sp-ladoA))*(sp-ladoB)*(sp-ladoC));
	    
	    System.out.println("El Perimetro del triangulo es: " + p);
	    System.out.println("La semiperímetro del triángulo es: " + sp);
	    System.out.println("El area del triangulo es: " + a);

	}
}



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


    
  




