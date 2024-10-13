# Suite de Fibonacci en C++

Ce projet contient une implémentation simple en C++ de la suite de Fibonacci. Le programme demande à l'utilisateur d'entrer un nombre entier, puis affiche la suite de Fibonacci jusqu'à ce terme.

## Fonctionnement du code

Les principales caractéristiques du code sont les suivantes :
- La fonction `fibonacci(int n)` calcule le nombre de Fibonacci pour une position donnée `n`. Elle utilise une approche itérative pour calculer la suite.
- Le programme demande à l'utilisateur d'entrer le nombre de termes de la suite de Fibonacci qu'il souhaite afficher.
- La suite de Fibonacci est affichée jusqu'au nième terme, en commençant par `Fibonacci(0)`.

### Points clés :
- `fibonacci(0)` renvoie 1.
- `fibonacci(1)` renvoie 1.
- La formule utilisée dans le code est : `f(n) = f(n-1) + f(n-2)`.

## Utilisation

1. Compilez le programme avec un compilateur C++ comme `g++` :
   ```bash
   g++ -o fibonacci fibonacci.cpp

### Exemple d'exécution
````bash
Entrez le nombre de termes de la suite de Fibonacci à afficher : 5
Fibonacci(0) = 1
Fibonacci(1) = 1
Fibonacci(2) = 2
Fibonacci(3) = 3
Fibonacci(4) = 5
