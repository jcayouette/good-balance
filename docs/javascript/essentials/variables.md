# Variables

Variables store information. Variables are one of the most important building blocks in coding.

```js
firstname = "Bob";
x = 5;
```
Can be assigned new values while code is running:

```js
firstname = "Jones";
x = 10;
```

## Declaring variables

When you create variables you declare them. There are three words for this. 

* **let**: Can be changed once declared. **let** has **block scope**. Blocks will always be surrounded by curly braces `{  }`.
* **var**: Can be changed when declared. **var** has **global scope** and a variable declared with var can be used throughout your entire script.
* **const**: Cannot be changed once declared. Once a value is assigned to const it cannot be altered. If you attempt to change a value with **const** you will throw an error.


!!! failure "const is forever!"

    ```js
    const pi = 3.14159;
    pi = 5.2;
    ```
    Throws the following error:

    ```terminal
    Uncaught TypeError: Assignment to constant variable.
    ```

```js
// Let can be reassigned { block scope }
let firstname = "Jamie";
firstname = "John";
```

In more advanced programming variables are typically not hardcoded (assigned a value). Rather they are dynamically filled in from some external input. For example an input box on a website that a user fills out to change their profile. It could also be a form that modifies a database. Hardcoding values is not best practice but is useful during the development process.


