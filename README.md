# buclesycondicionales
package com.company;

public class Main {

    public static void main(String[] args){
         int numeroif = -10;

         if(numeroif >= 1){
             System.out.println("es positivo");
         }
          else if(numeroif < 0){
            System.out.println("es negativo");

        }
       else {

           System.out.println(" es cero");
        }


        }
    }


/******************************************bucle whilw****************************************************/
package com.company;

public class Main {

    public static void main(String[] args) {


      int numeroWhile = 0;


        while( numeroWhile < 3){
          System.out.println(numeroWhile);
          numeroWhile++;
        }


    }


/*************************************do while************************************************************/
 public static void main(String[] args) {


      int numeroWhile = 0;


      do {
          System.out.println(numeroWhile);
          numeroWhile++;

      }while( numeroWhile > 3);

        }


    }



/*******************************************************bucle for**************************************************/
package com.company;

public class Main {

    public static void main(String[] args) {
        


        for ( int numeroFor= 0; numeroFor < 3; numeroFor++){
            System.out.println(numeroFor);
        }
        

    }
}
