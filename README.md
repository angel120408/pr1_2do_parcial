# Codigo Creado Por Ramirez Torres Angel Manuel De 3°W
- Almacenar en una lista los siguientes precios, 43, 57, 92, 20, 37, 5, 9, y mostrar en pantalla  el menor y el mayor de los precios.


print(" ")
print("Ramirez Torres Angel Manuel De 3°W")
print("-INSTRUCCIONES-")
print("Almacenar en una lista los siguientes precios, 43, 57, 92, 20, 37, 5, 9, y mostrar en pantalla  el menor y el mayor de los precios.")
print(" ")


# Almacenar los precios en una lista
precios = [43, 57, 92, 20, 37, 5, 9]


# Inicializar menor y mayor con el primer elemento de la lista
menor_precio = precios[0]
mayor_precio = precios[0]

# Recorrer la lista para encontrar el menor y mayor precio
for precio in precios:
    # Comparar el precio actual con el menor encontrado hasta ahora
    if precio < menor_precio:
        menor_precio = precio  # Actualizar el menor precio si se encuentra uno más bajo
    
    # Comparar el precio actual con el mayor encontrado hasta ahora
    if precio > mayor_precio:
        mayor_precio = precio  # Actualizar el mayor precio si se encuentra uno más alto

# Mostrar los resultados
print("El menor precio es:", menor_precio)  # Imprimir el menor precio
print("El mayor precio es:", mayor_precio)  # Imprimir el mayor precio


![image](https://github.com/user-attachments/assets/5d34690b-cdeb-4981-b393-cf9969ed005b)
![image](https://github.com/user-attachments/assets/5e4b2b8e-7a90-487d-af5d-57724aafde25)
![image](https://github.com/user-attachments/assets/fee77505-8721-4b79-9a4f-f774cdb21286)


# Codigo #2 Creado Por Ramirez Torres Angel Manuel
- Almacenar las materias de 1 curso (ejemplo Pensamiento matemático, español, Inglés, química, civismo y francés) en una lista luego despliegue en pantalla

print("Ramirez Torres Angel Manuel De 3°W")
print("-INSTRUCCIONES-")
print("Almacenar en una lista los siguientes precios, 43, 57, 92, 20, 37, 5, 9, y mostrar en pantalla  el menor y el mayor de los precios.")
print(" ")


# Almacenar las materias en una lista
materias = [
    "Pensamiento matemático",  # Materia 1
    "Español",                 # Materia 2
    "Inglés",                  # Materia 3
    "Química",                 # Materia 4
    "Civismo",                 # Materia 5
    "Francés"                  # Materia 6
]

# Desplegar las materias en pantalla
print("Materias del curso:")  # Mensaje inicial antes de mostrar las materias

# Imprimir las materias, cada una en una nueva línea
print("\n".join(materias))

![image](https://github.com/user-attachments/assets/bcd2d3d1-0cec-4696-a3f9-d2f459ac061a)
![image](https://github.com/user-attachments/assets/d1993a89-a74d-4da5-87a1-2400e590d478)


#Codigo 3 Creado Por Ramirez Torres Angel Manuel
- De esa misma lista que aparezca un mensaje Estoy cursando <materia>, donde <materia> es cada una de las de la lista  .


print("Ramirez Torres Angel Manuel De 3°W")
print("-INSTRUCCIONES-")
print("De esa misma lista que aparezca un mensaje Estoy cursando <materia>, donde <materia> es cada una de las de la lista  .")
print(" ")


# Almacenar las materias en una lista
materias = [
    "Pensamiento matemático",  # Materia 1
    "Español",                 # Materia 2
    "Inglés",                  # Materia 3
    "Química",                 # Materia 4
    "Civismo",                 # Materia 5
    "Francés"                  # Materia 6
]

# Desplegar un mensaje para cada materia
for materia in materias:
    print(f"Estoy cursando {materia}.")  # Mensaje que indica que se está cursando la materia

![image](https://github.com/user-attachments/assets/91ea158d-9e5f-4bf2-9862-e0137a5234fd)
![image](https://github.com/user-attachments/assets/c540a875-e718-4450-a319-624003f9061d)


# Codigo 4 Creado Por Ramirez Torres Angel Manuel De 3°W
-  De igual forma con la lista que tenemos creada que pida al usuario la calificación de cada materia lo despliegue en pantalla y que muestre:
En <materia> has obtenido <calificación> y asíi cada una de las que correspondan

print(" ")
print("Ramirez Torres Angel Manuel De 3°W")
print("-INSTRUCCIONES-")
print("De esa misma lista que aparezca un mensaje Estoy cursando <materia>, donde <materia> es cada una de las de la lista  .")
print(" ")


# Almacenar las materias en una lista
materias = [
    "Pensamiento matemático",  # Materia 1
    "Español",                 # Materia 2
    "Inglés",                  # Materia 3
    "Química",                 # Materia 4
    "Civismo",                 # Materia 5
    "Francés"                  # Materia 6
]

# Inicializar una lista para las calificaciones
calificaciones = []  # Lista vacía para almacenar calificaciones

# Pedir al usuario la calificación de cada materia
for materia in materias:  # Recorrer cada materia en la lista
    calificacion = input(f"Ingresa la calificación para {materia}: ")  # Solicitar calificación
    calificaciones.append(calificacion)  # Agregar la calificación a la lista

# Desplegar las calificaciones
print("\nCalificaciones obtenidas:")
for i in range(len(materias)):  # Recorrer el índice de las materias
    print(f"En {materias[i]} has obtenido {calificaciones[i]}.")  # Imprimir materia y su calificación



![image](https://github.com/user-attachments/assets/01d6a356-0756-4e47-b5f8-3bc4001003c2)
![image](https://github.com/user-attachments/assets/04ee030d-eef7-444b-9f5f-f2d568b8194d)
![image](https://github.com/user-attachments/assets/2508be22-a48b-4107-b43d-7beb717d17eb)


Codigo 5 Creado Por Ramirez Torres Angel Manuel De 3°W
- Haz uno que pregunte los numero triunfadores de la lotería , y llene una lista que se va a mostrar en pantalla de menor a mayor.

print(" ")
print("Ramirez Torres Angel Manuel De 3°W")
print("-INSTRUCCIONES-")
print("Haz uno que pregunte los numero triunfadores de la lotería , y llene una lista que se va a mostrar en pantalla de menor a mayor.")
print(" ")


# Pedir al usuario que ingrese los números triunfadores en una sola línea
entrada = input("Ingresa los números triunfadores, separados por comas: ")

# Procesar la entrada del usuario
try:
    # Dividir la entrada por comas, convertir a enteros y almacenar en una lista
    numeros_triunfadores = [int(num.strip()) for num in entrada.split(',')]
    
    # Ordenar la lista de números de menor a mayor
    numeros_triunfadores.sort()
    
    # Mostrar los números triunfadores en pantalla
    print("\nNúmeros triunfadores de la lotería (de menor a mayor):")
    print(numeros_triunfadores)  # Imprimir la lista completa
except ValueError:
    # Mensaje de error si hay un valor no numérico en la entrada
    print("Por favor, asegúrate de ingresar solo números válidos.")


 ![image](https://github.com/user-attachments/assets/5db2d72d-d6bf-4a15-bb16-d37b8f194634)
![image](https://github.com/user-attachments/assets/07993bb8-e44b-4914-8072-a5e977ef9938)








