

## NumPy
<a href='https://numpy.org/doc/stable/reference'> NumPy reference</a>

Les notions essentielles abordées pour avoir les bases en utilisation de NumPy <br>

import numpy as np <br>

NumPy permet de manipuler un array(ou tableau) qui stocke de même type (int, float, booléan, chaîne de charactère). sur ces tableaux il est possible de manipulation à travers l'utilisation des fonctions et des propriétés. <br>
Il est possible de les générer et de les indexer 

-liste[1,2,3,2]: transformation de list en array np.array(liste)
-np.arange(5) # création de array
-np.arange(8).reshape(2,4) : deux lignes et 4 colonnes
-np.ones(2)
-np.zero(2)
-np.eye(5)
-np.random.rand(a,b,c)
-np.random.randint(a,b,c)
-soit arr un array: arr[arr>4]
-arr.max()
-arr.min()
-arr.sin()
-arr.std()
-arr.sum(axis=0)
-arr[ : ] indexation
-arr[ : , : ]
-arr.linspace[ : ]