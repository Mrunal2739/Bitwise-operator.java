# Bitwise-operator.java

/*Bitwise Operators */

import java.util.*;

class Bitwise{

public static void main(String[] args){

Scanner sc = new Scanner(System.in);

System.out.println("Enter Value of a :");

int a = sc.nextInt();

System.out.println("Enter value of b :");

int b = sc.nextInt();

System.out.println("Bitwise & Operator:"+(a&b));

System.out.println("Bitwise | Operator:"+(a|b));

System.out.println("Bitwise << Operator:"+(a<<2));

System.out.println("Bitwise >> Operator:"+(a>>1));

}

}
