print (" ") #Esta linea define el espacio del nombre
print ("Cristian David salas De La O 3-W") #Esta linea define el nombre 
print (" ") #Esta linea define el espacio del nombre
persona = {} #Esta linea define la persona

def agregar_dato(clave, mensaje): #Esta linea define la funcion 

    valor = input(mensaje) #Esta linea define el valor 
    persona[clave] = valor #Esta linea define la clave de la persona
    print("\nContenido del diccionario actualizado:") #Esta linea muestra un mensaje del diccionario 
    print(persona)

def menu(): #Esta linea define el menu

    while True: #Esta linea defune el opicion multiple
        print("\n--- Menu de información ---") #Esta linea muestra el menu 
        print("1. Ingresar nombre") #Esta linea solicita el nombre
        print("2. Ingresar edad") #Esta linea define la edad
        print("3. Ingresar sexo") #Esta linea solicita el sexo
        print("4. Ingresar telefono") #Esta linea solicita el telofono 
        print("5. Ingresar correo electrónico") #Esta linea solicita el correo 
        print("6. Salir") #Esta linea es para salir 

        opcion = input("Selecciona una opcion (1-6): ") #Esta linea solicita escoger 

        if opcion == '1': #Esta linea define el if
            agregar_dato("nombre", "Introduce el nombre: ") #Esta linea solicita  introducirr el nombre
        elif opcion == '2': #Esta linea define elif
            agregar_dato("edad", "Introduce la edad: ") #Esta linea solicita  introducirr la edad 
        elif opcion == '3': #Esta linean define elif
            agregar_dato("sexo", "Introduce el sexo: ") #Esta linea solicita  introducirr el sexo
        elif opcion == '4': #Esta linea deifne elif
            agregar_dato("telefono", "Introduce el telefono: ") #Esta linea solicita  introducirr el telofono 
        elif opcion == '5': #Esta linea define elif
            agregar_dato("correo", "Introduce el correo electronico: ") #Esta linea solicita  introducirr el correo 
        elif opcion == '6': #Esta linea define elif
            print("Adios") #Esta linea solicita  introducirr el nombre
            break #Esta linea concluye la funcion 
        else: #Esta linea define que hacer si no se cumple la concidcion 
            print("Opcion no valida por favor selecciona una opción valida (1-6).") #Esta linea define que esa opcion no existe

menu() #Esta linea convluye el diccionario
![image](https://github.com/user-attachments/assets/65657d28-25af-44b3-a4a4-83d137b65b18)
![image](https://github.com/user-attachments/assets/094354bf-76e9-477c-963c-128d55d87a85)


