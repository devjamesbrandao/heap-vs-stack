# Diferença entre memória heap e memória stack

<p align="center">
    <img src="/img/inicio.jpeg" alt="Memória heap e stack" title="Memória heap e stack">
</p> 

## Memória Stack e Value Types
- A memória stack é bem menor que a memória heap
- A memória stack armazena valores de tipos primitivos (bool, byte, char, decimal, double, enum, float, int, long, sbyte, short, struct, uint, ulong, ushort)
- Value Types (System.ValueType) são os valores armazenados na memória stack que são acessadas “direto” pelo processador
- Exemplo:

  > int maravilhasDoMundo = 7; // variável armazenada na memória stack <br />
  > double precoGasolina = 5.30; // variável armazenada na memória stack 
 
## Memória Heap e Reference Types
- A memória heap armazena objetos complexos e coleções (class, interface, delegate, object, string)
- Para acessar esses objetos e coleções o processador acessa um reference type ou ponteiro onde ele contém o exato endereço de memória onde os valores estão armazenados na memória heap
- Exemplo:

  > string maiorCantorDoBrasil = "Gustavo Lima"; // variável armazenada na memória heap

## Exemplo de uso da memória stack e heap
<p align="center">
    <img src="/img/diferenca.png" alt="Exemplo de uso memória heap e stack" title="Exemplo de uso memória heap e stack">
</p> 
