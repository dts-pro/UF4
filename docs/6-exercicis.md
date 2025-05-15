# Exercicis

## Exercicis - Nivell bàsic

1. Realitza un programa que mostre per pantalla els 20 primers nombres naturals (1, 2, 3... 20).
2. Realitza un programa que mostre els nombres parells compresos entre l'1 i el 200. Per a això utilitza un comptador i suma de 2 en 2.
3. Realitza un programa que mostre els nombres parells compresos entre l'1 i el 200. Aquesta vegada utilitza un comptador sumant d'1 en 1.
4. Realitza un programa que mostre els números des de l'1 fins a un número N que s'introduirà per teclat.

## Exercicis - Nivell mitjà

5. Realitza un programa que llija un número positiu N i calcule i visualitze la seua factorial N!
Sent el factorial:
0! = 1  
1! = 1  
2! = 2 *1  
3! = 3* 2*1  
N! = N* (N-1) *(N-2)........* 3 *2* 1  
6. Realitza un programa que llija 10 números no nuls i després mostre un missatge de si ha llegit algun número negatiu o no.
7. Realitza un programa que llija 10 números no nuls i després mostre un missatge indicant quants són positius i quants negatius.
8. Realitza un programa que llija una seqüència de números no nuls fins que s'introduïsca un 0, i després mostre si ha llegit algun número negatiu quants positius i quants negatius.
9. Realitza un programa que calcule i escriga la suma i el producte dels 10 primers nombres naturals.
10. Realitza un programa que llija una seqüència de notes (amb valors que van de 0 a 10) que acaba amb el valor -1 i ens diu si va haver-hi o no alguna nota amb valor 10.
11. Realitza un programa que sume independentment els parells i els imparells dels números compresos entre 100 i 200, i després mostre per pantalla totes dues sumes.
12. Realitza un programa que calcule el valor A elevat a B (A^B) sense fer ús de l'operador de potència (^), sent A i B valors introduïts per teclat, i després mostre el resultat per pantalla.
13. Realitza un programa on l'usuari "pensa" un número de l'1 al 100 i l'ordinador intenta endevinar-lo. És a dir, l'ordinador anirà proposant números una vegada i una altra fins a endevinar-lo (l'usuari haurà d'indicar-li a l'ordinador si és major, menor o igual al número que ha pensat).
14. Realitza un programa que donada una quantitat d'euros que l'usuari introdueix per teclat (múltiple de 5 €) mostrarà els bitllets de cada tipus que seran necessaris per a aconseguir aquesta quantitat (utilitzant bitllets de 500, 200, 100, 50, 20, 10 i 5). Cal indicar el mínim de bitllets possible. Per exemple, si l'usuari introdueix 145 el programa indicarà que serà necessari 1 bitllet de 100 €, 2 bitllets de 20 € i 1 bitllet de 5 € (no serà vàlid per exemple 29 bitllets de 5, que encara que sume 145 € no és el mínim nombre de bitllets possible).

## Exercicis - Nivell avançat

15. Realitza un programa que compte els múltiples de 3 des del 1 fins a un número que introduïm per teclat.
    - Exemple:

```plaintext
Dona'm un número: 13
Nombre de múltiples de 3: 4
```

16. Realitza un programa en java que demane un nombre primer (en castellà “número primo”) positiu i ens diga si és primer o no.

```plaintext
Dis-me un número
És primer
```

17. Realitza un programa que llija i accepte únicament aquells números que siguen majors que l'últim donat, es a dir, l'anterior introudït. La introducció de números finalitza amb la introducció d'un 0. Al final es mostrarà:

     - El total de números introduïts, exclòs el 0.
     - El total de números fallats

```plaintext
Dis-me un número inicial: 20
Dis-me un número: 21
Dis-me un número: 8
Error, és menor.
Dis-me un número: 15
Dis-me un número: 10
Error, és menor.
Dis-me un número: 0
Total de números introduïts: 5
Número d'errors: 2
```

18.  Realitza un programa per a calcular la suma dels quadrats dels 5 primers nombres naturals.
19. Realitza un programa que lija un número i a continuació escriga el caràcter “*” tantes vegades com el valor numèric llegit. En aquells casos en què el valor llegit no siga positiu s'haurà d'escriure un únic asterisc.

```plaintext
Dis-me un número: 8
* * * * * * * *
```

20. Realitza un programa que demane un número enter N entre 0 i 20 i després mostre per pantalla els números des d'1 fins a N, un en cada línia, repetint cada número tantes vegades com el seu valor.

```plaintext
Dis-me un número: 5
1
22
333
4444
55555
```

21. Realitza un programa que demane dos números enters A i B, sent B major que A. Després visualitze els números des d’A fins a B i indique quants d'aquestos són parells.

```plaintext
Dis-me un número: 5
Dis-me un número major que l'anterior: 11
5 6 7 8 9 10 11
La quantitat de parells són: 3
```

22. Realitza un programa que demane un número i construïsca per pantalla la seua piràmide.

```plaintext
Dis-me un número per a realitzar la seua piràmide: 6
     *     
    ***
   *****
  *******
 *********
***********
```

## Exercicis d'ampliació

23. Escriu un programa que llija un número n d’un digit i imprimisca una piràmide de números amb n files com la següent.

Exemple:

```plaintext
   1   
  121
 12321
1234321
```

24. Escriu un programa que, donat un número enter positiu, ens diga quants són i quant sumen els dígits parells que conté. Els dígits parells es mostraran ordenadament d’esquerra a dreta. Per a fer-ho utilitzarem el tipus long en lloc de l’int per poder admetre números grans.

Exemple:

```plaintext
Introdueix un número enter positiu: 94026782
Dígits parells: 4 0 2 6 8 2
Suma dels dígits parells és: 22
```

25. Escriu un programa que diga si un número introduït per teclat és o no capicua. Els números capicua es lligen igual cap endavant i cap endarrere. El programa acceptarà números de qualsevol longitud dins del permesos en el tipus de dades long.

Exemple:

```plaintext
Introdueix un número enter positiu: 2019102
El 2019102 es capicua.
```

26. Realitza un programa que calcule el màxim, mínim i mitjana d'una sèrie de nombres enters positius introduïts per teclat. El programa acabarà quan l'usuari introduïsca un nombre primer. Aquest darrer número no es tindrà en compte per als càlculs. El programa ha d'indicar també quants números ha introduït l'usuari (sense comptar el número primer que serveix per eixir).

Exemple:

```plaintext
Introdueix números enters positius. Per finalitzar, introdueix un número primer:
Introdueix número: 6
Introdueix número: 8
Introdueix número: 15
Introdueix número: 12
Introdueix número: 23
Has introduït 4 números no primers.
Màxim: 15
Mínim: 6
Mitjana: 10.25
```

27. Implementa el joc pedra, paper i tisora. Primer, l'usuari introdueix la seva jugada i després l’ordinador genera a l’atzar una de les opcions. Si l'usuari introduïu una opció incorrecta, el programa haurà de mostrar un missatge de error.
