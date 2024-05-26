Em Java, existem diferentes tipos de listas que podem ser usadas para armazenar coleções de elementos. Algumas das mais comuns são:

    ArrayList: Implementa a interface List e usa um array dinâmico para armazenar os elementos. Permite adicionar, remover, acessar e pesquisar elementos rapidamente.



import java.util.ArrayList;

    ArrayList<String> lista = new ArrayList<>();
    lista.add("elemento1");
    lista.add("elemento2");
    // Acesso aos elementos
    String primeiroElemento = lista.get(0);
    // Remoção de elementos
    lista.remove("elemento1");

LinkedList: Implementa a interface List e usa uma estrutura de lista duplamente encadeada para armazenar os elementos. É eficiente para adicionar e remover elementos no início ou no meio da lista.



import java.util.LinkedList;

    LinkedList<String> lista = new LinkedList<>();
    lista.add("elemento1");
    lista.add("elemento2");
    // Acesso aos elementos
    String primeiroElemento = lista.get(0);
    // Remoção de elementos
    lista.remove("elemento1");

Vector: Semelhante a ArrayList, mas é sincronizado, o que significa que é seguro para uso em threads concorrentes, porém menos eficiente.



import java.util.Vector;

    Vector<String> lista = new Vector<>();
    lista.add("elemento1");
    lista.add("elemento2");
    // Acesso aos elementos
    String primeiroElemento = lista.get(0);
    // Remoção de elementos
    lista.remove("elemento1");

Stack: Implementa a estrutura de dados de pilha, onde o último elemento adicionado é o primeiro a ser removido (LIFO - Last In, First Out).



import java.util.Stack;

    Stack<String> pilha = new Stack<>();
    pilha.push("elemento1");
    pilha.push("elemento2");
    // Acesso ao elemento no topo
    String topo = pilha.peek();
    // Remoção do elemento no topo
    String removido = pilha.pop();

Estes são alguns exemplos de listas em Java. Cada uma tem suas próprias características e é adequada para diferentes cenários de uso.