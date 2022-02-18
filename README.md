# Ejercicios Introducción a la Algorítmica

Ejercicio 8: Porcentajes, IVA e inversiones
1. Escribir un algoritmo que calcula el precio con todos los impuestos incluidos (TII) para un precio sin impuestos y un porcentaje de IVA dado.
2. Escribir un algoritmo que calcula el importe de los intereses generados por un capital invertido a un interés dado durante un tiempo dado, expresado en meses.

Algoritmo 1: Porcentajes, IVA e inversiones
    
    definir precio como REAL
    # precio1 no tiene impuestos
    # precio2 % de IVA 
    precondicción 
    precio > 0
    escribir "Introduce un precio " # te devolverá el precio final
    preciofinal = precioinicial - (impuestos/100 + )




Fin algoritmo


Ejercicio 9: Media aritmética ponderada
1. Escribir un algoritmo que calcula la media aritmética de tres números dados.
2. La misma pregunta para una media ponderada cuando se dan los números y los coeficientes de ponderación.

Algoritmo Media 

    definir num1, num2, num3 como entero
    escribir ("Introduce los 3 números")
    leer num1, num2, num3
    suma = (num1 + num2 + num3)/3
    escribir ("El resultado es", suma) 
                                                                                             
Fin Algoritmo

ALgoritmo Media aritmética ponderada
    definir num1, num2, num3 como entero
    escribir ("Introduce los 3 números")
    leer num1, num2, num3
    media = (num1 + num2 + num3)/3
    escribir ("El resultado es", media)
    si la parte decimal de media > 0.6:
        escribir ("EL resultado es ", parte entera de la media anterior + 1)
    sino
        escribir ("El resultado es:", parte entera de la media anterior)
    fin si
Fin Algoritmo
