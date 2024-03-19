
1) Observe o trecho de código abaixo:
```
int INDICE = 13, SOMA = 0, K = 0;

enquanto K < INDICE faça

{

K = K + 1;

SOMA = SOMA + K;

}

imprimir(SOMA);


```
Ao final do processamento, qual será o valor da variável SOMA?

91 

2) Dado a sequência de Fibonacci, onde se inicia por 0 e 1 e o próximo valor sempre será a soma dos 2 valores anteriores (exemplo: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34...), escreva um programa na linguagem que desejar onde, informado um número, ele calcule a sequência de Fibonacci e retorne uma mensagem avisando se o número informado pertence ou não a sequência.
   <code>
   def fibonacci(n):
    a, b = 0, 1
    while b < n:
        a, b = b, a + b
    return b == n
n = int(input("Escola um numero"))
if fibonacci(n):
    print("Pertence a sequencia de Fibonacci")
else:
    print("Não pertence à sequência de Fibonacci.")
</code>

4) Descubra a lógica e complete o próximo elemento:

a) 1, 3, 5, 7, <strong>9</strong>

b) 2, 4, 8, 16, 32, 64,  <strong>128</strong>

c) 0, 1, 4, 9, 16, 25, 36, <strong>49</strong>

d) 4, 16, 36, 64, <strong>100</strong>

e) 1, 1, 2, 3, 5, 8,<strong>13</strong
                                 
f) 2,10, 12, 16, 17, 18, 19, <strong>20</strong>

4) Você está em uma sala com três interruptores, cada um conectado a uma lâmpada em uma sala diferente. Você não pode ver as lâmpadas da sala em que está, mas pode ligar e desligar os interruptores quantas vezes quiser. Seu objetivo é descobrir qual interruptor controla qual lâmpada.
Como você faria para descobrir, usando apenas duas idas até uma das salas das lâmpadas, qual interruptor controla cada lâmpada?

Ligo um dos interruptores, por certo tempo, o suficiente para lampada esquentar, desligo ele e ligo outro ao ir verificar as salas, passo em uma sala caso esteja com a lampada desligada e que não esteja quente, é o interruptor na qual não encostei, caso esteja desligado e quente, é o interruptor no qual deixei ligado por certo tempo. E caso esteja ligada, pertence ao interruptor no qual liguei. Na segunda volta, repito o processo e saberei assim os 3 interruptores.

5) Escreva um programa que inverta os caracteres de um string.
IMPORTANTE:
a) Essa string pode ser informada através de qualquer entrada de sua preferência ou pode ser previamente definida no código;
b) Evite usar funções prontas, como, por exemplo, reverse;

<code>string = input("Digite a palavra qu deseja inverter")
print(string[::-1])</code>
