# 4. Bucle do-while

|Codi| Diagrama de flux|
|----|-----------------|
|**do{ <br> bloc d'accions; <br> } while (condició)**| ![Bucle do-while](uf4/bucle_do_while.jpg)|

En aquesta mena de bucle, el bloc d'instruccions s'executa sempre almenys una vegada, i aqueix bloc d'instruccions s'executarà mentre **condició** s'avalue a true.

**IMPORTANT**: En el bloc d'instruccions haurà d'existir alguna iteració que, en algun
moment, faça que ‘condición’ s'avalue a ‘false’. Si no el bucle no acabaria mai!

>**Exemple 4**: El mateix exemple 2 d’abans, fet amb un bucle do-while seria:
>::: details Codi
>```java
>public static void main(String[] args){
>   Scanner sc = new Scanner(System.in);
>   int max, cont;
>   System.out.print("Introdueix el número màxim: ");
>   max = sc.nextInt();
>   cont = 1;
>   
>   do {
>       System.out.println("Número: " + cont);
>       cont++;
>   } while (cont <= max)
>}
>```
>:::
>
>L'eixida és:
>
>```plaintext
>Introdueix el número màxim: 5
>Número 1
>Número 2
>Número 3
>Número 4
>Número 5
>```