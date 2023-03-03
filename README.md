# Zeynep_Kiic


SUBJECT: Print Star Pascal’s Triangle

JAVA

import java.util.Scanner;

public class Pascal {

 public static void main(String[] args) {
	    int  k = 0;
	    
	    Scanner in = new Scanner(System.in);
	    
	    System.out.println("Enter the number of rows in Pascal's Triangle:");
	    int rows=in.nextInt();
	    
	    for (int i = 1; i <= rows; ++i, k = 0) {
	      for (int space = 1; space <= rows - i; ++space) {
	        System.out.print("  ");
	      }

	      while (k != 2 * i - 1) {
	        System.out.print("* ");
	        ++k;
	      }

	      System.out.println();
	    }
	  }
	}
SAMPLE OUTPUT:

<img width="335" alt="Ekran Resmi 2023-03-03 22 32 04" src="https://user-images.githubusercontent.com/119444731/222814286-903b995f-aef2-4efc-862e-50f26445931a.png">

<img width="372" alt="Ekran Resmi 2023-03-03 22 32 18" src="https://user-images.githubusercontent.com/119444731/222814299-a187d9bf-533d-49f5-9b62-b7674f205d2c.png">

