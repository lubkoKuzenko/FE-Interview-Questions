# TypeScript Interview Questions with Answers

<img src="./images/px52c3vht.jpg" width="960">

## Table of Contents

| No. | Questions                                                                        |
| --- | -------------------------------------------------------------------------------- |
| 1   | [List the built-in types in Typescript?](#List-the-built-in-types-in-Typescript) |
| 2   | [Explain generics in TypeScript](#Explain-generics-in-TypeScript)                |

<br/>

## Q1: List the built-in types in Typescript ⭐

These are also called the primitive types in TypeScript:

- **Number** type: it is used to represent number type values and represents double precision floating point values.

```js
var variable_name: number;
```

- **String** type: it represents a sequence of characters stored as Unicode UTF-16 code. It is the same as JavaScript primitive type.

```js
var variable_name: string;
```

- **Boolean** type: in Typescript, it is used to represent a logical value. When we use the Boolean type, we get output only in true or false. It is also the same as JavaScript primitive type.

```js
var variable_name: boolean;
```

- **Null** type: it represents a null literal and it is not possible to directly reference the null type value itself.

```js
var variable_name: number = null;
```

- **Undefined** type: it is the type of undefined literal. This type of built-in type is the sub-type of all the types.

```js
var variable_name: number = undefined;
```

## Q2: Explain generics in TypeScript ⭐

Generics are able to create a component or function to work over a variety of types rather than a single one.

```js
/** A class definition with a generic parameter */
class Queue<T> {
  private data = [];
  push = (item: T) => this.data.push(item);
  pop = (): T => this.data.shift();
}

const queue = new Queue<number>();
queue.push(0);
queue.push("1"); // ERROR : cannot push a string. Only numbers allowed

```
