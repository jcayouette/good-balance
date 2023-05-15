# String Type

Strings are used to store text values. 
You can declare strings in the following ways:


* Double quotes "This is a string"
* Single quotes 'This is also a string'
* Backticks \`This is a special kind of template string`


## Single and double quote use

``` js
let singleString = 'Welcome to Astronomy 101';
let doubleString = "Do you know what the celestial equator is?";
```

Use double strings to avoid the following error. 
This will end the string early:

``` js
let astronomy = 'Don't scratch your mirror!';
```

Using double quotes works just fine:

``` js
let astronomy = "Don't scratch your mirror!";
```

You would encounter the same error with double quotes:

``` js
let learnAstro = "Will you learn astronomy? "Yes! I love space"";
```

## Backtick use

``` js
let planet = "Jupiter";
let msg = ` What do you know about ${planet}`;
console.log(msg);
```

## Escape characters

If you want to use single, double and backticks in your strings you need to also add escapes. The `\` backslash.




