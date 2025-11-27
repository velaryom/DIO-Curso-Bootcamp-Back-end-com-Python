# Tipos de dados em Python 🎲💻

Resumo da aula "Tipos de dados" - Curso Bootcamp DIO Back-end com Python.

## O que são Tipos?

Os tipos são a forma como a linguagem define as caracteristicas e comportamentos de um valor — *objeto* — para o interpretador (vscode ou pycharm).
Por exemplo:
   
Com esses Tipos eu sou capaz de realizar operações matemáticas.
   
|Classe | Tipo                 |Aparência|
|-------|----------------------|---------|
|int    | inteiro              |1        |
|float  | flutuante ou quebrado|1.0      |
|complex| números e letras     |1A       |

Esse tipo para ser armazenado em memória irá consumir 24 bytes.

## Tipos de dados built-in mais utilizados

Tipos built-in são aqueles que já vem por padrão dentro da linguagem. Alguns exemplos válidos são:

|Tipo      | Classe                      | Função                    |
|----------|-----------------------------|---------------------------|
|Texto     |str                          |Armazena texto             |
|Númerico  |int, float ou complex        |Armazena numerais          |
|Sequência |list, tuple e range          |Armazena letras e numeros  |
|Mapa      |dict                         |Armazena chave e valor     |
|Coleções  |set e frozenset              |Similar ao list porém sem repetições |
|Booleano  |bool                         |Condiciona valor entre verdadeiro e falso |
|Binário   |bytes, bytearray, memoryview | Memória                   |

### Tipos de Números

#### Números inteiros

Os números inteiros são representados pela *classe* int e possuem precisão ilimitada. São exemplos válidos de números inteiros:

1, 10, 100, -1, -10, -100