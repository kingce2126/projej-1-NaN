# projej-1-NaN
EXERCICE



## EXERCICE 1

```python
import random
nombre_magic=random.randint(1,100)
nombre=input("entrer un nombe")
nombre=int(nombre)
while nombre != nombre_magic:
    if nombre < nombre_magic:
        print("Désolé, le nombre est plus petit que le nombre magique. Reessayer!")
        nombre = input()
        nombre = int(nombre)
    else:
        print("Désolé, le nombre est plus grand que le nombre magique. Reessayer!")
        nombre = input()
        nombre = int(nombre)
print("Félicitation, vous avez trouvé!")
```

## EXERCICE 2

```python
ma_chaine="bonjour, chef comment vous alLez?"
ma_chaine=ma_chaine.replace(',','')
print(ma_chaine)
ma="je n'aime pas les imbeciles"
ma=ma.replace('e','a')
print(ma)
il="sans moi paris serait,pris"
il=il.replace('a','')
print(il)

