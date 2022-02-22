# Ejercicios Introducción a la Algorítmica

Ejercicio 8: Porcentajes, IVA e inversiones
1. Escribir un algoritmo que calcula el precio con todos los impuestos incluidos (TII) para un precio sin impuestos y un porcentaje de IVA dado.
2. Escribir un algoritmo que calcula el importe de los intereses generados por un capital invertido a un interés dado durante un tiempo dado, expresado en meses.

Algoritmo 1: Porcentajes, IVA e inversiones
    
    Entrada
    p: REAL # definir precio como REAL, precio no tiene impuestos
    i: REAL # % de IVA a aplicar
    resultado: REAL #
    precondicción 
    precio > 0
    escribir "Introduce un precio " # te devolverá el precio final, con impuestos incluidos
    resultado = 

Fin Algoritmo 1


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

Ejercicio 10: Área del triángulo
1. Escribir un algoritmo que calcula el área de un triángulo del que se da la medida de un lado y la de la altura relativa a este lado.
2. ¿Se puede utilizar este algoritmo para un triángulo rectángulo si se dan las medidas de sus dos lados perpendiculares?

Ejercicio 11: Salario y horas extra

El cálculo de una nómina tiene en cuenta el salario bruto asociado a las horas «normales» que debe hacer el empleado y las horas «extra» trabajadas en el mes. Las horas extra se remuneran según las siguientes normas administrativas:
Tarifa por hora aumentada en un 125 % para las horas entre la 36.ª y la 43.ª.
Tarifa por hora aumentada en un 150 % para las horas a partir de la 44.ª.

El aumento se realiza sobre la tarifa por hora normal, calculado a partir del salario mensual bruto para un año de 52 semanas repartidas en 12 meses, sobre la base de 35 horas trabajadas por semana.

Escribir el algoritmo que calcula el importe de las horas extra que hay que pagar, a partir del salario mensual bruto y de la cantidad de horas extra. (horas superior a 8)

Ejercicio 12: Cuenta de depósito

Se considera las cuentas de depósitos alojadas en un banco por los clientes. Solo se permite hacer una retirada si el saldo que queda en la cuenta no es negativo.
1. Definir el tipo de datos CUENTA..
2. Definir las operaciones aplicables.
En determinadas circunstancias y para determinados clientes, la banca autoriza un descubierto limitado y temporal.
3. Volver a hacer las definiciones previas para permitir estos descubiertos.