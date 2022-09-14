INFLUENCE
#########


:date: 2022-09-14
:tags: machine learning AI analyse des données 
:author: Julia
:summary: Plus de lecture 2



Plusieurs grands organismes ont adopté ce langage tel que Google, la NASA, etc. et certains logiciels libres l’on comme langage de commande tels libreoffice, Blender et paraview
En France, il est enseigné dès les classes préparatoires scientifiques.
Aux Etats-unis, près de 8 sur 10 des meilleures universités poussent Python pour initier à la programmation pour le cursus d’informatique. 
Avec l’évolution de la Big data et du machine learning, Python est fortement sollicité dans ces cas en plus de l’essor de l’analyse des données. Puisque la majorité des bibliothèques qui sont utilisé ont python pour interface, ce dernier va devenir l’interface de commande le plus populaire pour les bibliothèques de Machine Learning et autres algorithmes numériques.  

Voici 2 des plusieurs notions vues en cours d’Algorithme et programmation 
Nous y insérerons les concepts de base de Python :
Points-virgules ; pour terminer les lignes
Dièse # pour les commentaires
Egal = pour créer ou déclarer une variable
== , < , > , + , _ , * , / les opérations.

 1. Les Boucles 

    a. La boucle WHILE

Permet d’éxécuter une ou plusieurs instructions de manière repetée jusqu’à ce qu’une condition soit vérifiée.

.. code-block:: python

   Max_age = 10
   Age = 1
   While age < max_age :
	Print(f"L’age {age} est inferieur à {max_age}"")
	Age = age +1


Pour cette boucle, il est donc important de mettre à jour la condition lorsque le code tourne autrement la boucle tourne indéfiniment.

   b. La boucle FOR

Celle-ci répète plusieurs fois la même action sur les éléments d’une même séquence dans l’ordre dans lequel ils apparaissent dans la séquence. 

.. code-block:: python

   For x in range(20) :
    print(f"Le nombre actuel est {x}")

2.	Les Alternatives 

Elles sont des structures de programmation effectuant un test logique sur une condition et permettant un choix entre divers blocs d'instructions suivant le résultat de ce test.
Pour faire simple, une alternative nous permet d'exécuter de manière conditionnelle une partie de notre code.
En Python, 
•	If : pour autoriser ou empêcher l’exécution d’une ou de plusieurs instructions.
•	Elif : pour autoriser ou empêcher l’exécution d’une ou de plusieurs commandes si if n’est pas vérifié. 
•	Else : si les deux premières conditions ne sont pas vérifiées alors c’est la condition Else qui va être exécuté.

.. code-block:: Python

   a = 2
   b = 3
   c = 1
   Delta = b*2 - (4*a*c)
   print(Delta)

   if Delta < 0:
      print("Il n'y a pas de solution à l'équation")
   elif Delta == 0: #else if / sinon si
      x1 = (-1*b)/2*a
      x2 = x1
      print ("Il n'existe qu'une seule solution à l'équation. Cette solution est :", x")
   elif Delta >= 0:
      racine_delta = Delta**0.5
      x1= ((-1*b) - racine_delta)/(2*a)
      x2= ((-1*b) + racine_delta)/(2*a)
      print(f"Il existe deux solutions : x1={x1} , x2={x2}")

.. code-block:: bash
    
    Il existe deux solutions : x1=-1.0 , x2=-0.5