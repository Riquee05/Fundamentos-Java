Manipular strings em Java é uma tarefa comum e existem várias maneiras de fazê-lo. Aqui estão algumas operações comuns:

    Concatenação de Strings: Para juntar duas ou mais strings, você pode usar o operador + ou o método concat().



    String str1 = "Hello";
    String str2 = "World";
    String result = str1 + " " + str2; // Result: "Hello World"

Comparação de Strings: Para comparar duas strings, use o método equals() para comparar o conteúdo e == para comparar as referências.



    String str1 = "Hello";
    String str2 = "Hello";
    if (str1.equals(str2)) {
        System.out.println("As strings são iguais");
    }

Acessar caracteres individuais: Você pode acessar caracteres individuais em uma string usando o método charAt().



    String str = "Hello";
    char firstChar = str.charAt(0); // Result: 'H'

Dividir uma string em substrings: Você pode dividir uma string com base em um delimitador usando o método split().



    String str = "Hello World";
    String[] parts = str.split(" ");
    // Result: parts[0] = "Hello", parts[1] = "World"

Converter para maiúsculas/minúsculas: Você pode converter uma string para maiúsculas ou minúsculas usando os métodos toUpperCase() e toLowerCase().



    String str = "Hello World";
    String upperCase = str.toUpperCase(); // Result: "HELLO WORLD"
    String lowerCase = str.toLowerCase(); // Result: "hello world"

Remover espaços em branco: Para remover espaços em branco do início e do final de uma string, use o método trim().



    String str = "   Hello World   ";
    String trimmed = str.trim(); // Result: "Hello World"

Essas são apenas algumas das muitas operações que você pode realizar com strings em Java. Se precisar de mais informações sobre alguma operação específica ou tiver outras perguntas, fique à vontade para perguntar!
