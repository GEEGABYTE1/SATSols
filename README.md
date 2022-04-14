# SAT Problems ~ The Classical Way 

Solving SAT Problems (Boolean Satisfiability Problems) using classical bits. This was done using compariators and iterations.

There are two possible states: `True` and `False`. For every bit inputted, `n`, there is a 50% chance that it will be either True or False giving a state 1 or 0 (qc implementation will be seen futher along the doc).

The users will be prompted to type in the number of clauses and the bits specified to compute. It should be noted that the bits should have similar digits (no outliers or unique values), however, negatives of an integer are allowed. Negatives are allowed and are encouraged to be played with as that will give different results, which can be played with on the Quantum Circuit.

The algorithm will then convert the desired bits into bit-strings to be able to plot on the QuantumCircuit. It should be mentioned that the Quantum Circuit is the size of (`clause witdth^2`). The only way such bit strings will be inputted is if the algorithm can find a clause that meets the desired states (`positive or True`, and `negative or False`), which will then find the corresponding bit string and put it in an underlying array.

After finding the right bit strings, the program will plot them on the QuantumCircuit, which can be visually seen. The algorithm will end off by printing the probability of a common or repeated measured bit or bit string.


*Note*: A Sample usage of the algorithm can be found on `script.ipynb` with tested results.


Made by Jaival 🦖