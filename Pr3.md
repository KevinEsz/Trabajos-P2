#Imprime el nombre del autor y el grupo del curso.

print("Esparza Mares Kevin Daniel 3-W")

print("")

#Imprime una breve descripción del propósito del programa.

print("En este programa se pregunta los números triunfadores de la lotería, y llena una lista que se va a mostrar en pantalla de menor a mayor.")

print("")

#Solicita al usuario ingresar el primer número ganador.

num1 = int(input("Ingresa el primer numero ganador:"))

print("")

#Solicita al usuario ingresar el segundo número ganador.

num2 = int(input("Ingresa el segundo numero ganador:"))

print("")

#Solicita al usuario ingresar el tercer número ganador.

num3 = int(input("Ingresa el tercer numero ganador:"))

print("")

#Solicita al usuario ingresar el cuarto número ganador.

num4 = int(input("Ingresa el cuarto numero ganador:"))

print("")

#Solicita al usuario ingresar el quinto número ganador.

num5 = int(input("Ingresa el quinto numero ganador:"))

print("")

#Crea una tupla con los números ingresados por el usuario.

#Las tuplas son inmutables, pero se utilizan aquí para almacenar los números de manera ordenada antes de convertirlos en una lista.

mi_tupla = (num1, num2, num3, num4, num5)

#Convierte la tupla a una lista y ordena los números de mayor a menor usando el parámetro `reverse=True`.

#La función `sorted()` devuelve una lista ordenada, sin modificar la tupla original.

lista = sorted(mi_tupla, reverse=True)

#Convierte la lista ordenada de nuevo en una tupla.

Tupla_O = tuple(lista)

#Imprime los números ordenados en orden descendente (de mayor a menor).

print("El orden de tus números ganadores es el siguiente:", Tupla_O)

![image](https://github.com/user-attachments/assets/57014a5d-6588-4420-a00b-8052d1633775)

![image](https://github.com/user-attachments/assets/beb597ec-9d6c-4187-b7e7-ea186dc21f05)

