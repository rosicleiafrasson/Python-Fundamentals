No terminal(cmd) após digitar o comando python, um REPL é iniciado. É possível efetuar operações simples como:

```
2 + 2
6 * 7
x = 5
print('Hello, Python')
```
Para sair do REPL Python e voltar para o terminal normal, no Windows devem ser pressionadas as teclas CTRL+Z e ENTER.


Para inserir um bloco de código como este representado a seguir, é necessário digitar dois pontos no final da primeira linha; e nas linhas subsequentes devem ser adicionados 4 espaços em branco. Para finalizar o bloco, é necessário deixar uma linha em branco. No terminal, aparecem ... em cada linha do bloco.
```
 for i in range(5):
     x = i * 10
     print(x)
```

O resultado da execução desse bloco de código é:
```
0
10
20
30
40
```

```
import math
math.sqrt(81)
help(math)
help(math.fatorial)
math.factorial(5)

from math import factorial
n = 3
factorial(n)

from math import factorial as fac
fac(n)
```

/ - divisor que retorna float
// - divisor que retorna integer

### Tipos Primitivos ###

int - inteiro
float - decimal
none - null
bool - booleano








