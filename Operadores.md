Em Java, operadores são símbolos que realizam operações em variáveis e valores. Eles podem ser classificados em várias categorias com base na funcionalidade que oferecem. Abaixo estão as principais categorias de operadores em Java:
1. Operadores Aritméticos

    Esses operadores realizam operações matemáticas básicas.

        Adição (+): Soma dois operandos.

        

        int a = 10 + 5; // a será 15

        Subtração (-): Subtrai o segundo operando do primeiro.

        

        int a = 10 - 5; // a será 5

        Multiplicação (*): Multiplica dois operandos.

        

        int a = 10 * 5; // a será 50

        Divisão (/): Divide o primeiro operando pelo segundo.

        

        int a = 10 / 5; // a será 2

        Módulo (%): Retorna o resto da divisão do primeiro operando pelo segundo.

        

            int a = 10 % 3; // a será 1

2. Operadores de Incremento e Decremento

Esses operadores são usados para incrementar ou decrementar o valor de uma variável.

        Incremento (++): Aumenta o valor da variável em 1.

    

    int a = 5;
    a++; // a será 6

    Decremento (--): Diminui o valor da variável em 1.

    

        int a = 5;
        a--; // a será 4

3. Operadores de Atribuição

Esses operadores são usados para atribuir valores às variáveis.

        Atribuição (=): Atribui o valor do operando direito ao operando esquerdo.

        

    int a = 5;

Atribuição Adição (+=): Adiciona o valor do operando direito ao operando esquerdo e atribui o resultado ao operando esquerdo.



    int a = 5;
    a += 3; // a será 8

Atribuição Subtração (-=): Subtrai o valor do operando direito do operando esquerdo e atribui o resultado ao operando esquerdo.



    int a = 5;
    a -= 3; // a será 2

Atribuição Multiplicação (*=): Multiplica o valor do operando direito pelo operando esquerdo e atribui o resultado ao operando esquerdo.



    int a = 5;
    a *= 3; // a será 15

Atribuição Divisão (/=): Divide o valor do operando esquerdo pelo operando direito e atribui o resultado ao operando esquerdo.



    int a = 6;
    a /= 3; // a será 2

Atribuição Módulo (%=): Calcula o módulo do operando esquerdo pelo operando direito e atribui o resultado ao operando esquerdo.



    int a = 5;
    a %= 3; // a será 2

4. Operadores de Comparação

Esses operadores comparam dois valores e retornam um booleano.

    Igual a (==): Verifica se dois operandos são iguais.

    

    int a = 5;
    int b = 5;
    boolean result = (a == b); // result será true

Diferente de (!=): Verifica se dois operandos são diferentes.



    int a = 5;
    int b = 3;
    boolean result = (a != b); // result será true

Maior que (>): Verifica se o operando esquerdo é maior que o operando direito.



    int a = 5;
    int b = 3;
    boolean result = (a > b); // result será true

Menor que (<): Verifica se o operando esquerdo é menor que o operando direito.



    int a = 5;
    int b = 3;
    boolean result = (a < b); // result será false

Maior ou igual a (>=): Verifica se o operando esquerdo é maior ou igual ao operando direito.



    int a = 5;
    int b = 5;
    boolean result = (a >= b); // result será true

Menor ou igual a (<=): Verifica se o operando esquerdo é menor ou igual ao operando direito.



    int a = 5;
    int b = 5;
    boolean result = (a <= b); // result será true

5. Operadores Lógicos

Esses operadores são usados para combinar expressões booleanas.

    E Lógico (&&): Retorna verdadeiro se ambos os operandos forem verdadeiros.

    

    boolean a = true;
    boolean b = false;
    boolean result = (a && b); // result será false

OU Lógico (||): Retorna verdadeiro se pelo menos um dos operandos for verdadeiro.



    boolean a = true;
    boolean b = false;
    boolean result = (a || b); // result será true

Não Lógico (!): Inverte o valor do operando booleano.



    boolean a = true;
    boolean result = !a; // result será false

6. Operadores Bitwise

Esses operadores realizam operações bit a bit nos operandos.

    E Bit a Bit (&): Realiza uma operação E bit a bit.

    

    int a = 5;  // 0101 em binário
    int b = 3;  // 0011 em binário
    int result = a & b; // result será 1 (0001 em binário)

OU Bit a Bit (|): Realiza uma operação OU bit a bit.



    int a = 5;  // 0101 em binário
    int b = 3;  // 0011 em binário
    int result = a | b; // result será 7 (0111 em binário)

    XOR Bit a Bit (^): Realiza uma operação OU exclusivo bit a bit.



    int a = 5;  // 0101 em binário
    int b = 3;  // 0011 em binário
    int result = a ^ b; // result será 6 (0110 em binário)

    Complemento (~): Inverte todos os bits do operando.



    int a = 5;  // 0101 em binário
    int result = ~a; // result será -6 (invertendo 0101 fica 1010, que é -6 em complemento de dois)

Deslocamento à Esquerda (<<): Desloca os bits do operando para a esquerda pelo número de posições especificado.



    int a = 5;  // 0101 em binário
    int result = a << 1; // result será 10 (1010 em binário)

Deslocamento à Direita (>>): Desloca os bits do operando para a direita pelo número de posições especificado.



    int a = 5;  // 0101 em binário
    int result = a >> 1; // result será 2 (0010 em binário)

Deslocamento à Direita sem Sinal (>>>): Desloca os bits do operando para a direita pelo número de posições especificado, preenchendo com zeros.



    int a = -5; // 11111111111111111111111111111011 em binário
    int result = a >>> 1; // result será 2147483645 (01111111111111111111111111111101 em binário)

7. Operador Ternário

Esse operador é uma forma compacta de realizar uma verificação condicional.

    Condicional (? :): Retorna um valor com base em uma condição booleana.

    

    int a = 10;
    int b = (a > 5) ? 1 : 0; // b será 1

8. Operadores de Instância

Verifica se um objeto é uma instância de uma classe específica.

    instanceof: Verifica se um objeto é uma instância de uma classe ou de uma subclasse.

    

    String s = "Hello";
    boolean result = s instanceof String; // result será true

Esses são os principais operadores em Java, cada um com sua função específica. Saber como usá-los corretamente