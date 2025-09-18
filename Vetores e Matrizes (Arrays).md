# 📚 Meus Estudos em Lógica de Programação

Bem-vindo ao meu repositório de estudos! Aqui eu documento meu progresso e aprendizado em Lógica de Programação, cobrindo desde os conceitos básicos até estruturas mais complexas.

---

## Tópico Atual: Vetores e Matrizes (Arrays)

Nesta seção, exploro como organizar e manipular conjuntos de dados de forma estruturada utilizando Vetores (Arrays de 1 dimensão) e Matrizes (Arrays de múltiplas dimensões).

### O que são Vetores?

Um **Vetor** (ou *Array*) é uma estrutura de dados que nos permite armazenar uma coleção de elementos do mesmo tipo em uma única variável. Pense nele como uma lista ou uma fileira de caixas, onde cada caixa possui uma posição (índice) e guarda um valor.

**Quando utilizar?**
* Quando precisamos guardar uma lista de itens: nomes de alunos, preços de produtos, etc.
* Para acessar, adicionar ou remover itens de forma organizada por sua posição.

**Exemplo prático em JavaScript:**
Aqui, criamos um vetor para guardar uma lista de nomes de Pokémon.

```javascript
// Cada nome é um elemento do vetor
let nomesPokemon = ["Pikachu", "Charmander", "Bulbasaur"];

// Para acessar o primeiro Pokémon (índice 0), usamos nomesPokemon[0]
console.log(nomesPokemon[0]); // Saída: Pikachu
```

### O que são Matrizes?

Uma **Matriz** é basicamente um "vetor de vetores". Ela nos permite criar estruturas de dados com mais de uma dimensão, como tabelas com linhas e colunas.

**Exemplo prático em JavaScript:**
Vamos criar uma matriz para organizar um time Pokémon, onde cada "linha" representa um Pokémon e as "colunas" representam suas características: `[NOME, SEXO, NÍVEL]`.

```javascript
let timePokemon = [
  // Linha 0: ["nome", "sexo", nível]
  ["Pikachu", "M", 1],

  // Linha 1: ["nome", "sexo", nível]
  ["Charmander", "F", 3]
];

// Acessando os dados do Charmander (linha 1)
let nome = timePokemon[1][0];   // Coluna 0 da linha 1
let sexo = timePokemon[1][1];   // Coluna 1 da linha 1
let nivel = timePokemon[1][2];  // Coluna 2 da linha 1

console.log("O Pokémon " + nome + " é do sexo " + sexo + " e está no nível " + nivel);
// Saída: O Pokémon Charmander é do sexo F e está no nível 3
```


---
