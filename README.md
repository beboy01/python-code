# python-code
# Exercice1
```python
from random import*
def demande_nombre(nb_min, nb_max):
    # Quel est le nombre magique entre (  1 et 10)
    nombre_str = input(f" Quel est le nombre magique entre (  {nb_min} et {nb_max})")
    try:
        nombre_int = int(nombre_str)
    except:
        print("Erreur ,Vous devez entrer un nombre entier !")
    return nombre_int
NOMBRE_MIN = 1
NOMBRE_MAX = 100
nombre_Magie = randint(NOMBRE_MIN,NOMBRE_MAX)
nombre=0
while not nombre == nombre_Magie:
   nombre = demande_nombre(NOMBRE_MIN, NOMBRE_MAX)
   if(nombre == nombre_Magie):
       print("bravo vous avez gagnez")
   elif(nombre > nombre_Magie):
      print("le nombre entrez est grand ")
   elif(nombre < nombre_Magie):
      print("le nombre entré est peptit" )
 ```
    
