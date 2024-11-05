# Documentação de Condições em JavaScript


## O que é uma Condição?

Condições são usadas em programação para executar diferentes blocos de código com base em certas verificações, ou seja, permitem que o programa tome **decisões**. Em JavaScript, as condições são avaliadas como **verdadeiras** ou **falsas**.

### Estruturas Condicionais

1. **if**
2. **else if**
3. **else**
4. **switch**

### Estrutura Básica `if`

A estrutura básica de um `if` em JavaScript é:

```jsx
if (condição) {
  // código a ser executado se a condição for verdadeira
}

```

### Exemplo `if`

```jsx
let idade = 18;

if (idade >= 18) {
  console.log("Você é maior de idade.");
}

```

Neste exemplo:

- A condição `idade >= 18` é avaliada.
- Se for verdadeira, o código dentro do bloco `if` será executado.

### `if...else`

A estrutura `if...else` permite executar um bloco de código quando a condição é verdadeira e outro bloco quando ela é falsa.

```jsx
if (condição) {
  // código a ser executado se a condição for verdadeira
} else {
  // código a ser executado se a condição for falsa
}

```

### Exemplo `if...else`

```jsx
let idade = 16;

if (idade >= 18) {
  console.log("Você é maior de idade.");
} else {
  console.log("Você é menor de idade.");
}

```

### `if...else if...else`

O `else if` permite verificar múltiplas condições, executando o bloco de código do primeiro `if` ou `else if` que for verdadeiro. Se nenhuma condição for verdadeira, o bloco `else` será executado.

```jsx
if (condição1) {
  // código a ser executado se a condição1 for verdadeira
} else if (condição2) {
  // código a ser executado se a condição2 for verdadeira
} else {
  // código a ser executado se todas as condições acima forem falsas
}

```

### Exemplo `if...else if...else`

```jsx
let hora = 15;

if (hora < 12) {
  console

Aqui está uma documentação detalhada sobre **estruturas condicionais** em JavaScript.

---

# Documentação de Estruturas Condicionais em JavaScript

## Introdução

Estruturas condicionais são fundamentais para tomar decisões dentro do código. Elas permitem que determinadas partes do código sejam executadas com base em condições específicas, o que possibilita a criação de programas dinâmicos e interativos.

### Principais Estruturas Condicionais em JavaScript

1. `if`
2. `else if`
3. `else`
4. `switch`

---

## Estrutura `if`

A estrutura `if` executa um bloco de código se a condição especificada for **verdadeira**.

### Sintaxe

```javascript
if (condição) {
  // código a ser executado se a condição for verdadeira
}

```

### Exemplo `if`

```jsx
let idade = 20;

if (idade >= 18) {
  console.log("Você é maior de idade.");
}
// Saída: Você é maior de idade.

```

Nesse exemplo:

- Se a condição `idade >= 18` for verdadeira, o código dentro do bloco `if` é executado.

---

## Estrutura `if...else`

O `else` é usado em conjunto com o `if` para especificar um bloco de código que deve ser executado se a condição for **falsa**.

### Sintaxe

```jsx
if (condição) {
  // código a ser executado se a condição for verdadeira
} else {
  // código a ser executado se a condição for falsa
}

```

### Exemplo `if...else`

```jsx
let idade = 16;

if (idade >= 18) {
  console.log("Você é maior de idade.");
} else {
  console.log("Você é menor de idade.");
}
// Saída: Você é menor de idade.

```

Nesse exemplo, como `idade` é 16, a condição `idade >= 18` é falsa, então o bloco `else` é executado.

---

## Estrutura `if...else if...else`

Essa estrutura permite verificar várias condições. O primeiro `if` ou `else if` cuja condição seja verdadeira terá seu bloco de código execut
