import random
import math
pi=3.14159265358979323846
def Sumatoria(num1,num2,num3):
    return num1 + num2 + num3
sumatoria=Sumatoria(num1,num2,num3)
def MaxTresNum(num1,num2,num3):
    if num1>num2 and num1>num3:
        mayor=num1
    elif num2>num1 and num2>num3:
        mayor=num2
    else:
        mayor=num3
    return mayor
def MinTresNum(num1,num2,num3):
    if num1<num2 and num1<num3:
        menor=num1
    elif num2<num1 and num2<num2:
        menor=num2
    else:
        menor=num3
    return menor
def Aletorio(mayor,sumatoria):
    num_aleatorio=random.uniform(sumatoria,mayor)
    return num_aletorio
def Raiz(num_aleatorio)
return raiz_cuadrada = math.sqrt(num_aleatorio)
num1 = float(input("Ingrese el primer numero: "))
num2 = float(input("Ingrese el segundo numero: "))
num3 = float(input("Ingrese el tercer numero: "))
pi=float(pi)
print("La sumatoria es:", sumatoria)
print("El numero mayor es:", mayor)
print("El número menor es:", menor)
print("El numero aleatorio entre la sumatoria y el numero mayor es:", num_aleatorio)
print("La raíz cuadrada del numero aleatorio es:", raiz_cuadrada)
print("Valor de pi:",pi)

#cadenas o trunc
#Funcion Formula (numero)
#Primer digito es elevado al cuadrado
#Los digitos de en medio se multiplican
#El ultimo digito (x )multiplicado por PI (3.1416)
#Se hace una sumatoria de todo esto
