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


