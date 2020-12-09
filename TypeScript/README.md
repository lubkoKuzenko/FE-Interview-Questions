# TypeScript Interview Questions with Answers

<img src="./images/px52c3vht.jpg" width="960">

## Table of Contents

| No. | Questions                                                                        |
| --- | -------------------------------------------------------------------------------- |
| 1   | [List the built-in types in Typescript?](#List-the-built-in-types-in-Typescript) |
| 2   | [Explain generics in TypeScript](#Explain-generics-in-TypeScript)                |
| 3   | [What is TypeScript and why would I use it in place of JavaScript?](#)           |
| 4   | [What is TypeScript and why do we need it?](#)                                   |
| 5   | [What are the benefits of TypeScript?](#)                                        |
| 6   | [Do we need to compile TypeScript files and why?](#)                             |
| 7   | [How to call base class constructor from child class in TypeScript?](#)          |
| 8   | [What are the difference beetween Typescript and JavaScript?](#)                 |
| 9   | [What is Interface in TypeScript?](#)                                            |
| 10  | [When to use interfaces and when to use classes in TypeScript?](#)               |
| 11  | [What is the difference between Classes and Interfaces in Typescript?](#)        |
| 12  | [What is "Decorators" in TypeScript?](#)                                         |
| 13  | [Does TypeScript support all object oriented principles?](#)                     |
| 14  | [Which object oriented terms are supported by TypeScript?](#)                    |

<br/>

## Q: List the built-in types in Typescript ⭐

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

## Q: Explain generics in TypeScript ⭐

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

## Q: What is TypeScript and why would I use it in place of JavaScript? ⭐

**TypeScript** is a superset of JavaScript which primarily provides optional static typing, classes and interfaces. One of the big benefits is to enable IDEs to provide a richer environment for spotting common errors as _you type the code_. For a large JavaScript project, adopting TypeScript might result in more robust software, while still being deployable where a regular JavaScript application would run.

In details:

- TypeScript supports new ECMAScript standards and compiles them to (older) ECMAScript targets of your choosing. This means that you can use features of ES2015 and beyond, like modules, lambda functions, classes, the spread operator, destructuring, today.
- JavaScript code is valid TypeScript code; TypeScript is a superset of JavaScript.
- TypeScript adds type support to JavaScript. The type system of TypeScript is relatively rich and includes: interfaces, enums, hybrid types, generics, union and intersection types, access modifiers and much more. TypeScript makes typing a bit easier and a lot less explicit by the usage of type inference.
- The development experience with TypeScript is a great improvement over JavaScript. The IDE is informed in real-time by the TypeScript compiler on its rich type information.
- With strict null checks enabled (`--strictNullChecks` compiler flag) the TypeScript compiler will not allow undefined to be assigned to a variable unless you explicitly declare it to be of nullable type.
- To use TypeScript you need a build process to compile to JavaScript code. The TypeScript compiler can inline source map information in the generated .js files or create separate .map files. This makes it possible for you to set breakpoints and inspect variables during runtime directly on your TypeScript code.
- TypeScript is open source (Apache 2 licensed, see github) and backed by Microsoft. _Anders Hejlsberg_, the lead architect of C# is spearheading the project.

## Q: What is TypeScript and why do we need it? ⭐

JavaScript is the only client side language universally supported by all browsers. But JavaScript is not the best designed language. It’s not a class-based object-oriented language, doesn’t support class based inheritance, unreliable dynamic typing and lacks in compile time error checking. And TypeScript addresses all these problems. In other words, TypeScript is an attempt to “fix” JavaScript problems.

TypeScript is a free and open source programming language developed and maintained by Microsoft. It is a strict superset of JavaScript, and adds **optional static typing** and **class-based object-oriented programming** to the language. TypeScript is quite easy to learn and use for developers familiar with C#, Java and all strong typed languages. At the end of day “TypeScript is a language that generates plain JavaScript files.”

As stated on [Typescript official website](http://www.typescriptlang.org/), “TypeScript lets you write JavaScript the way you really want to. TypeScript is a typed superset of JavaScript that compiles to plain JavaScript. Any browser. Any host. Any OS. Open Source.” Where “**typed**” means that it considers the types of variables, parameters and functions.

## Q: What are the benefits of TypeScript? ⭐

TypeScript has following benefits.

- It helps in code structuring.
- Use class based object oriented programming.
- Impose coding guidelines.
- Offers type checking.
- Compile time error checking.
- Intellisense.

## Q: Do we need to compile TypeScript files and why? ⭐

Yes we do. Typescript is just a language Extension browsers can't interpret it. Converting from TypeScript to JavaScript is called compiling. Compiling doesn't mean binary code is created in this case. For this kind of translation, also the term transpilation is used instead of compilation.

## Q: How to call base class constructor from child class in TypeScript? ⭐

We can call base class constructor using `super()`.

## Q: What are the difference beetween Typescript and JavaScript? ⭐

- It is an object oriented programming language (not pure).
- Here it is static typing (We can declare a variable in multiple ways). ex: var num : number.
- It has interfaces.
- It has optional parameter feature.
- It has Rest Parameter feature.
- Supports generics.
- Supports Modules
- Number, string etc. are the interfaces.

## Q: What is Interface in TypeScript? ⭐

One of TypeScript’s core principles is that type-checking focuses on the _shape_ that values have.

An `interface` is a virtual structure that only exists within the context of TypeScript. The TypeScript compiler uses interfaces solely for type-checking purposes.

When you define your interface you’re saying that any object (not an instance of a class) given this contract must be an object containing interfaces properties.

## Q: When to use interfaces and when to use classes in TypeScript? ⭐

If you need/wish to create an instance of perhaps a custom object, whilst getting the benefits of type-checking things such as arguments, return types or generics - a class makes sense.

If you’re not creating instances - we have interfaces at our disposal, and their benefit comes from not generating any source code, yet allowing us to somewhat “virtually” type-check our code.

## Q: What is the difference between Classes and Interfaces in Typescript? ⭐

We use classes as object factories. A class defines a blueprint of what an object should look like and act like and then implements that blueprint by initialising class properties and defining methods. Classes are present throughout all the phases of our code.

Unlike classes, an interface is a virtual structure that only exists within the context of TypeScript. The TypeScript compiler uses interfaces solely for type-checking purposes. Once code is transpiled to its target language, it will be stripped from interfaces.

A class may define a factory or a singleton by providing initialisation to its properties and implementation to its methods, an interface is simply a structural contract that defines what the properties of an object should have as a name and as a type.

## Q: What is "Decorators" in TypeScript? ⭐

A _Decorator_ is a special kind of declaration that can be attached to a class declaration, method, accessor, property, or parameter. Decorators are functions that take their target as the argument. With decorators we can run arbitrary code around the target execution or even entirely replace the target with a new definition.

There are 4 things we can decorate in ECMAScript2016 (and Typescript): constructors, methods, properties and parameters.

## Q: Does TypeScript support all object oriented principles? ⭐

The answer is **YES**. There are 4 main principles to Object Oriented Programming:

- Encapsulation,
- Inheritance,
- Abstraction, and
- Polymorphism.

## Q: Which object oriented terms are supported by TypeScript? ⭐

TypeScript supports following object oriented terms:

- Modules
- Classes
- Interfaces
- Data Types
- Member functions
