# Problema de Josephus

Para resolver el problema de Josephus, se puede seguir la estrategia propuesta por el historiador judío Flavius Josephus: sentar a los soldados en un círculo y matar al soldado a la izquierda en cada ronda hasta que quede solo uno vivo. ¿En qué posición debería sentarse Josephus para sobrevivir?

Para resolver el problema, se pueden utilizar diferentes enfoques, como la recursión, las fórmulas matemáticas y los algoritmos de simulación. Una posible estrategia para resolver el problema de forma general es utilizar la fórmula:

$f(n, m) = (f(n - 1, m) + m) % n$

donde n es el número de soldados y m es el número de saltos que se deben dar antes de matar a un soldado. La función f(n, m) devuelve la posición del soldado que sobrevive en una ronda de n soldados después de saltar m soldados. Para encontrar la posición ganadora en una ronda de n soldados, se puede llamar a la función f(n, m) con m = 1.
