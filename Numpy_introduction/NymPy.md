

## NumPy
<a href='https://numpy.org/doc/stable/reference'> NumPy reference</a>

Les notions essentielles abordées pour avoir les bases en utilisation de NumPy <br>

import numpy as np <br>

NumPy permet de manipuler un array(ou tableau) qui stocke de même type (int, float, booléan, chaîne de charactère). sur ces tableaux il est possible de manipulation à travers l'utilisation des fonctions et des propriétés. <br>
Il est possible de les générer et de les indexer <br>

-liste[1,2,3,2]: transformation de list en array np.array(liste) <br>
-np.arange(5) # création de array <br>
-np.arange(8).reshape(2,4) : deux lignes et 4 colonnes <br>
-np.ones(2) <br>
-np.zero(2) <br>
-np.eye(5) <br>
-np.random.rand(a,b,c) <br>
-np.random.randint(a,b,c) <br>
-soit arr un array: arr[arr>4] <br>
-arr.max() <br>
-arr.min() <br>
-arr.sin() <br>
-arr.std() <br>
-arr.sum(axis=0) <br>
-arr[ : ] indexation <br>
-arr[ : , : ] <br>
-arr.linspace[ : ] <br>
