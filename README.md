# practica-_3
from typing_extensions import Counter
import re 
##Pregunta 1

texto = """
Juan: 987654321
María: 912345678
Pedro: 998877665
Ana: 923456789
"""
numero= re.findall(r'9\d{8}', texto)
print(numero)
print("El total de numeros es: ",len(numero))
