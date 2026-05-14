#SINTAXIS, VARIABLES, TIPOS DE DATOS Y "HOLA MUNDO"

# Esto es un comentario de una linea
"""
Esto es un comentario en varias lineas
"""
'''
Esto tambien
'''
mi_variable = "esto es una variable de texto (entre dos comillas)"
mi_variable = "Se puede cambiar el valor a una variable conforme se compila"

MI_CONSTANT = "no hay constantes en python, pero en algunos se pone asi"

#DATOS PRIMIVOS
my_int = 1 #esto es una variable de numero entero
my_float = 1.5 #var. de numero decimal
my_bool = True 
my_bool = False #cierto o falso (boleanos)
my_srting = "hola :3" #cadena de texto
my_string = 'hola :3' #cadena de texto (otra sintaxis)

#IMPRIMIR TEXTO POR CONSOLA
print ("¡Hola mundo!")

#Para saber que tipo de DATOS
print (type (my_int))
print (type (my_float))
print (type (my_bool))
print (type (my_string)) #
'''
usamos type (funcion del sistema) para hacer cosas, en este 
caso para saber tipo de datos
'''
my_bool:bool = "hola" 
'''
aunque tambien podemos especificar el dato con ":y el tipo" aunque solo sea como
una nota más y no se tome importancia para el programa
'''
#OPERADORES Y ESTRUCTURAS DE CONTROL

#operadores aritmeticos
print(f"Suma: 10 + 3 = {10+3}") #usamos la f para interpolar (meter una función dentro)
print(f"Resta: 10 - 3 = {10-3}")
print(f"multiplicación: 10 * 3 = {10*3}")
print(f"división: 10 / 3 = {10/3}")
print(f"modulo: 10 % 3 = {10%3}") #residuo de la división entera
print(f"exponente: 10 ** 3 = {10**3}")
print(f"división entera: 10 // 3 = {10//3}") #resultado entero de la división

#operadores de comparación
print(f"igualdad: 10 == 3 es {10==3}") #da en boleanos
print(f"desigualdad: 10 != 3 es {10!=3}")
print(f"mayor que: 10 > 3 es {10>3}")
print(f"menor que: 10 < 3 es {10<3}")
print(f"menor o igual que: 10 <= 3 es {10<=3}")
print(f"mayor o igual que: 10 >= 3 es {10>=3}")

#operadores logicos
print(f"AND: 10 + 3 == 13 and 5 - 1 == 4 es {10+3==13 and 5-1==4}") #and dos valores 1 = True
print(f"OR: 10 + 3 == 13 and 5 - 1 == 7 es {10+3==13 or 5-1==7}") #or con que uno sea 1 = True
print(f"NOT: 10 + 3 == 13 es {not 10+3==13}") #not invierte el valor

#operadores de asignación
numero = 10 #asignas un valor a la variable
print (numero)
numero += 2 #asignas una suma al valor de la variable
print (numero) 
numero -= 2 #asignas una resta al valor de la variable
print (numero)
#así se pueden asignar todos los operadores aritmeticos posibles ya vistos
#le va haciendo las operaciones asignadas a los valores preestablecidos de la variable

#operadores de identidad
otro_numero = 10
print (f"numero is otro_numero {otro_numero is numero}") 
#aunque los dos valores 
