# Ejercicios Bash## Abril 19 / 2017  ## Bienvenido   **Ejercicio 1**  Contar la cantidad de procesos que se están ejecutando.  ```ps -A | wc -l```**Ejercicio 2**  Elevar 2 a la 4  ```export VAR1=$(( 2 ** 4 ))echo $VAR1```**Ejercicio 3**  Contar la cantidad de procesos que se estan ejecutando con tail```ps -A | tail -n +2 | wc -l```