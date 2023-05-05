import os
import re
if os.path.isfile("archivos.txt"):
    archivoTexto=open("archivos.txt", "r+"):
    print("Digito nombre del beneficiario, identificacion y numero de telefono")
    nombre=input()
    identificacion=input()
    numero=input()
    lineasTexto=archivoTexto.readlines()
    for elementos in lineasTexto:
        # Busqueda por elemento completo
        while re.search(identificacion, elemntos):
            print("La identificacion ya existe,intente de nuevo")
            nombre=input()
            identificacion=input()
            numero=input()
        archivoTexto.write(nombre + " ")
        archivoTexto.write(identificacion + " ")
        archivoTexto.write(numero + "\n")
        achivoTexto.close()
else:
    archivoTexto=open("archivos.txt","w")
    print("Digito nombre del beneficiario, identificacion y numero de telefono")
    nombre=input()
    identificacion=input()
    numero=input()
    archivoTexto.write(nombre + " ")
    archivoTexto.write(identificacion + " ")
    archivoTexto.write(numero + "\n")
    achivoTexto.close()
print("Ingrese el nombre del beneficiario para buscarlo") 
letra=input()
# Busqueda por letra
for elementos in lineasTexto:
    if re.findall(letra, elemento):
        print(elemento)
