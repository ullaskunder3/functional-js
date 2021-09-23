# Awesome Functional JavaScript

## 01. Why functional programming

## 02. Higher order function

## 03. map, filter, & reduce

## 03. Curring

## 04. Pure function & immutability

## 05. Closures

## 06. Function decoration

## 06. Functors

## 06. Promisis

## 06. Recurion

## 06. Streams

## 06. Monad

### 01. Functional programming

- Imperative
- Declarative
- Object Oriented
- __Functional__ :
- ...

first Its one of the programming paradigm

Difference Between Pure and impure function

Pure Function is deterministic means output is totally depends on the input

```js

function greet(name){
    return `Hello, ${name}`;
}

greet(Ullas); // Hello, Ullas
greet(Awesome); // Hello, Awesome

```

Impure Function

```js
let name = "Ullas"

function greet(){
    console.log("Hello, ", name);
}
greet(); // Hello, Ullas

name = "Awesome";
greet(); //Hello, Awesome

```
