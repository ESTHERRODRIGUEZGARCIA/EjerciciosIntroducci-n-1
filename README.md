# Ejercicios Introducción a la Algorítmica

Ejercicio 8: Porcentajes, IVA e inversiones
1. Escribir un algoritmo que calcula el precio con todos los impuestos incluidos (TII) para un precio sin impuestos y un porcentaje de IVA dado.
2. Escribir un algoritmo que calcula el importe de los intereses generados por un capital invertido a un interés dado durante un tiempo dado, expresado en meses.

Algoritmo 1: Porcentajes, IVA e inversiones
    
    Entrada
    p: REAL # definir precio como REAL, precio no tiene impuestos
    i: REAL # % de IVA a aplicar
    resultado: REAL # devuelve el precio final (con impuestos incluidos)

    precondicción: 
    p > 0
    i > 0

    realización: 
    resultado = p + (p * i)

Fin Algoritmo 1

Algoritmo 2: Interés

    Entrada:
    p: REAL #importe inicial
    m: REAL #tiempo expresado en meses
    i: REAL #intereses
    resultado: REAL #importe de los intereses generados

    precondición:
    p >= 0
    i > 0

    realización: 
    resultado = p * (i/12)*m

Fin Algoritmo 2


Ejercicio 9: Media aritmética ponderada
1. Escribir un algoritmo que calcula la media aritmética de tres números dados.
2. La misma pregunta para una media ponderada cuando se dan los números y los coeficientes de ponderación.

Algoritmo 1: Media 

    Entrada: #supongo que me dan los datos, 3 en este caso
    num1: REAL
    num2: REAL
    num3: REAL
    M = REAL #media
    
    realización:
    S = num1 + num2 + num3
    M = S/3

    resultado = M
                                                                                             
Fin Algoritmo 1

ALgoritmo 2: Media aritmética ponderada
    entrada:
    num1: REAL
    num2: REAL
    num3: REAL
    #porcentajes de las ponderaciones
    p1: REAL
    p2: REAL
    p3: REAL
    
    realización:
    resultado = num1*p1 + num2*p2 + num3*p3 : REAL

Fin Algoritmo 2

Ejercicio 10: Área del triángulo
1. Escribir un algoritmo que calcula el área de un triángulo del que se da la medida de un lado y la de la altura relativa a este lado.
2. ¿Se puede utilizar este algoritmo para un triángulo rectángulo si se dan las medidas de sus dos lados perpendiculares?

Algoritmo 1: Área del triángulo
    Entrada: 
    L: REAL #lado
    H: REAL #altura

    precondición:
    L > 0
    H > 0

    realización:
    resultado = (L*H)/2 : REAL

Fin Algoritmo 1

Algoritmo 2: Área del triángulo rectángulo

    #observación: se puede usar el algoritmo nº1

    entrada: #lados dados
    L1: REAL
    L2: REAL

    precondición:
    ángulo entre L1 y L2 (90 º)
    
    realización:
    resultado = (L1*L2)/2 : REAL

Fin Algoritmo 2

Ejercicio 11: Salario y horas extra

Algoritmo 1: Salario

Fin ALgoritmo 1

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