# Garcia_Edgar_1182_3w_9
Edgar Gael Garcia Camacho 3-W
print(" ")
print("Edgar Gael garcia camacho :Examen ")
print(" ")

num=int(input("Ingresa un numero"))#Te pide que ingreses un numero.
if num > 40 and num % 7 == 0:#por si el numero que elegiste se divide a 7 y es mayor a 40.
    print("El numero es dividible por 7 es mayor a 40")
elif num > 40:#por si el numero que pusiste es solo mayor a 40.
    print("El numero es mayor a 40, pero no se puede dividir en 7 ")
elif num % 7==0:#por si el numero que seleccionaste es solo dividible a 7.
    print("El numero es dividible a 7,pero no es mayor que 40")
else:#por si el numero que escribiste no es ni mayor que 40 ni dividible a 7.
    print("No se puede hacer nada")
