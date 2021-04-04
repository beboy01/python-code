# python-code
# Exercice1 nombre Misterieux
# Pour commencer ,l'ordinateur va choisir au hasard un nombre compris entre 1 et 100.
# L'utiisateur doit alors deviner ce nombre comme ceci:
# L'utilisateur propose un nombre et l'ordinateur lui dit si est trop petit ou trop grand, et ainsi de suite jusqu'a ce que
# L'utilisateur aie trouver le bon nombre 
```python
from random import*
def nombre_misterieux(nb_min, nb_max):
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
   nombre = nombre_misterieux(NOMBRE_MIN, NOMBRE_MAX)
   if(nombre == nombre_Magie):
       print("bravo vous avez gagnez")
   elif(nombre > nombre_Magie):
      print("le nombre entrez est grand ")
   elif(nombre < nombre_Magie):
      print("le nombre entré est peptit" )
 ```
    # Exercice 2 purge un caractère dans une chaine de caractère
    # solution
    ```python
    def purge(text,lettre_suprimer):
    return text.replace(lettre_suprimer,"")
texte=input("Entrez une Chaine de caractère")
lettre= input("quelle lettre voulez vous purger")
    
print(purge(texte,lettre))
    
```
