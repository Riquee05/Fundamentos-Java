Em Java, estruturas condicionais são usadas para executar diferentes blocos de código com base em certas condições. As principais estruturas condicionais em Java são: if, if-else, if-else if-else, e switch. A seguir estão explicações e exemplos de cada uma:
1. Estrutura if

A estrutura if executa um bloco de código se a condição for verdadeira.



    int x = 10;
    if (x > 5) {
        System.out.println("x é maior que 5");
}

2. Estrutura if-else

A estrutura if-else executa um bloco de código se a condição for verdadeira, e outro bloco se a condição for falsa.



    int x = 10;
    if (x > 15) {
        System.out.println("x é maior que 15");
    } else {
        System.out.println("x não é maior que 15");
}

3. Estrutura if-else if-else

Essa estrutura permite verificar múltiplas condições em sequência.



    int x = 10;
    if (x > 15) {
        System.out.println("x é maior que 15");
    } else if (x > 5) {
        System.out.println("x é maior que 5, mas menor ou igual a 15");
    } else {
        System.out.println("x é menor ou igual a 5");
    }

4. Estrutura switch

A estrutura switch é usada para selecionar um dos muitos blocos de código para ser executado.



    int day = 3;
    switch (day) {
        case 1:
            System.out.println("Domingo");
            break;
        case 2:
            System.out.println("Segunda-feira");
            break;
        case 3:
            System.out.println("Terça-feira");
            break;
        case 4:
            System.out.println("Quarta-feira");
            break;
        case 5:
            System.out.println("Quinta-feira");
            break;
        case 6:
            System.out.println("Sexta-feira");
            break;
        case 7:
            System.out.println("Sábado");
            break;
        default:
            System.out.println("Dia inválido");
            break;
    }

Notas importantes

    Parênteses e chaves: As condições em if, else if e switch são envolvidas por parênteses (), e os blocos de código a serem executados são delimitados por chaves {}.
    break no switch: Cada caso no switch termina com a palavra-chave break para evitar que a execução continue nos casos seguintes. Se break for omitido, o programa continuará a executar as instruções nos casos subsequentes (comportamento conhecido como "fall-through").
    Valores permitidos no switch: Em um switch, os casos devem ser constantes, e o tipo da variável switch pode ser int, char, byte, short, String, ou um enum.

Essas são as principais estruturas condicionais em Java, que permitem controlar o fluxo de execução do programa com base em diferentes condições.