# What is a variable? 

A variable is a container for a value, like a number we might use in a sum, or a string that we might use as part of a sentence.

# Declaring a variable 
To use a variable, you've first got to create it — more accurately, we call this declaring the variable. To do this, we type the keyword let followed by the name you want to call your variable.

* Example 

```js 
 let myName;
 let myAge;
 ```
 Here we're creating two variables called 
`myName` and `myAge`

# Initializing a variable
 Once you've declared a variable, you can initialize it with a value. You do this by typing the variable name, followed by an equals sign (=), followed by the value you want to give it.
 For example:
  ```js 
 myName = "Chris";
 myAge = 37;
 ```
# Variable naming rules 
You can call a variable pretty much anything you like, but there are limitations. Generally, you should stick to just using Latin characters (0-9, a-z, A-Z) and the underscore character. 
* You shouldn't use other characters because they may cause errors or be hard to understand for an international audience. Don't use underscores at the start of variable names — this is used in certain JavaScript constructs to mean specific things, so may get confusing.

* Don't use numbers at the start of variables. This isn't allowed and causes an error.
 A safe convention to stick to is lower camel case, where you stick together multiple words, using lower case for the whole first word and then capitalize subsequent words.
 * Make variable names intuitive, so they describe the data they contain. Don't just use single letters/numbers, or big long phrases.
 * Variables are case sensitive — so myage is a different variable from myAge.
 * One last point: you also need to avoid using JavaScript reserved words as your variable names — by this, we mean the words that make up the actual syntax of JavaScript! So, you can't use words like var, function, let, and for as variable names. Browsers recognize them as different code items, and so you'll get errors.

 