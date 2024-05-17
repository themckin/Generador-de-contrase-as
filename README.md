import random

letras = "abcdefghijklmnñopqrstuvwxyz"
letras_mayus = letras.upper()
numeros = "0123456789"
simbolos = "@()[]{}*,:;/-_¿?.¡$<>#&+%="

p = letras+letras_mayus+numeros+simbolos

tamaño = 8 

pas = random.sample(p,tamaño)
password = "".join(pas)
print(f"tu nueva contraseña aleatoria es : {password}")
