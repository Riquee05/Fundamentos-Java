HashMap:



import java.util.HashMap;
import java.util.Map;

    public class Dictionary {
    private Map<String, String> dictionary;

    public Dictionary() {
        // Inicializando o dicionário
        dictionary = new HashMap<>();
    }

    // Método para adicionar uma entrada ao dicionário
    public void addEntry(String word, String definition) {
        dictionary.put(word, definition);
    }

    // Método para buscar a definição de uma palavra
    public String getDefinition(String word) {
        return dictionary.get(word);
    }

    // Método para verificar se uma palavra está no dicionário
    public boolean containsWord(String word) {
        return dictionary.containsKey(word);
    }

    // Método para remover uma entrada do dicionário
    public void removeEntry(String word) {
        dictionary.remove(word);
    }

    // Método para imprimir todo o dicionário
    public void printDictionary() {
        System.out.println("Dictionary:");
        for (Map.Entry<String, String> entry : dictionary.entrySet()) {
            System.out.println(entry.getKey() + ": " + entry.getValue());
        }
    }

    public static void main(String[] args) {
        Dictionary myDictionary = new Dictionary();

        // Adicionando entradas ao dicionário
        myDictionary.addEntry("apple", "A fruit that grows on trees.");
        myDictionary.addEntry("computer", "An electronic device for processing data.");

        // Verificando se uma palavra está no dicionário
        System.out.println("Definition of 'apple': " + myDictionary.getDefinition("apple"));

        // Removendo uma entrada do dicionário
        myDictionary.removeEntry("apple");

        // Imprimindo o dicionário atualizado
        myDictionary.printDictionary();
    }
    }

Este é um exemplo básico. Você pode expandir este código adicionando mais funcionalidades, como editar definições, contar o número de palavras no dicionário, etc.