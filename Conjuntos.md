Em Java, conjuntos são estruturas de dados que representam uma coleção de elementos únicos, o que significa que não podem conter elementos duplicados. A linguagem Java fornece várias implementações de conjuntos na biblioteca padrão, principalmente nas interfaces Set e SortedSet, bem como em suas implementações concretas, como HashSet, TreeSet, LinkedHashSet, entre outras.

Aqui está um exemplo simples de como usar conjuntos em Java:



import java.util.*;

public class ConjuntosExemplo {
    public static void main(String[] args) {
        // Criando um HashSet
        Set<String> conjunto = new HashSet<>();

        // Adicionando elementos ao conjunto
        conjunto.add("Maçã");
        conjunto.add("Banana");
        conjunto.add("Laranja");
        conjunto.add("Maçã"); // Elemento duplicado, não será adicionado

        // Exibindo o conjunto
        System.out.println("Conjunto: " + conjunto);

        // Verificando se o conjunto contém um elemento específico
        System.out.println("O conjunto contém Banana? " + conjunto.contains("Banana"));

        // Removendo um elemento do conjunto
        conjunto.remove("Laranja");

        // Exibindo o conjunto atualizado
        System.out.println("Conjunto após remover Laranja: " + conjunto);

        // Iterando sobre os elementos do conjunto
        System.out.println("Iterando sobre o conjunto:");
        for (String elemento : conjunto) {
            System.out.println(elemento);
        }

        // Limpando o conjunto
        conjunto.clear();
        System.out.println("Conjunto após limpar: " + conjunto);
    }
}

Este é um exemplo básico de como usar conjuntos em Java. Você pode escolher a implementação de conjunto que melhor atenda às suas necessidades com base nos requisitos de desempenho e comportamento específicos do seu aplicativo.
