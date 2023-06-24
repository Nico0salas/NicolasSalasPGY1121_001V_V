﻿# NicolasSalasPGY1121_001V_V
import numpy as np
print("Hola bienvenido")

personas=[]
#Opción 1. Grabar. Corresponde a guardar ciertos datos de una persona, entre ellos: NIF, nombre y edad.
#Debe verificar que el NIF sea correcto, que el nombre tenga mínimo 8 caracteres y que la edad sea mayor igual a 0.

#Opción 2. Buscar: Corresponde buscar a una persona por su NIF y mostrar toda su información almacenada.
#Además, debe mostrar si la persona pertenece o no a la Unión Europea. 

while True:
    print("1. Grabar ciudadano")
    print("2. Buscar")
    print("3. Ver certificado")
    print("4. Salir")

    op1=int(input())
#Debe verificar que el NIF sea correcto, que el nombre tenga mínimo 8 caracteres y que la edad sea mayor igual a 0
    edad=0
    edad=int(input())
    if op1==1:
        input("Ingrese su nombre: ")
        print("Ingrese su edad: ")
        edad=int(input())
        if edad >= 0 and edad <= 14:
            print("Edad no correspondiente")
        elif edad >=15:
            print("Tiene la edad suficiente para crear su NIF")
        print("Ingrese su NIF")
        nif=0
        if nif > 999999999 and nif < 10000000000:
            print("Su NIF es autentico")

    op2=int(input())
    if op2 == 1:
        print("Ingrese su NIF: ")
    elif nif <= 13:
        print("El NIF no corresponde")

    op3=int(input())
    if op3 == 1: 
        print("¿Desea ver su informacion?")
    
    op4=int(input())
    if op4 == 1:
        print("Has salido del programa :)")
