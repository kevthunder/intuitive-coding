# Intuitive Coding

## What is Intuitive Coding ?

Intuitive Coding is a set of rules I have written to improve productivity and code readability while programming.

It was originally written for myself but could possibly help many people to write better code.

## Rule 1 - Write your code as you would oraly explain what it does

To achieve perfect readybility, your code should be as easy to read as a book even if that person have limited knowledge of the language you are using. Not an easy thing to do, but why not begin by writing code as you naturaly talk. When you start codding a function just tell to yourself what this function do without thinking too much about it and do not get too technical, then write that as code.

- The subject is the object
- The verb is the function
- The complements are your arguments

While carefully thinking about how your application will work and know it's its feature well, is a base principle of good programming, now, we are past that. We are codding. We know what we want to do (right?) and we just need to write it down. 

### Rule 1.1 - The subject is the object

### Rule 1.2 - The verb is the function

### Rule 1.3 - The complements are your arguments

### Adding context to you object

### Rule 1.4 - Isolate any code you cant use this method in the smalest possible functions

At some point you wont be able to write code like you would say it, because actual programing statement are not always expresive for human or because sometime somethig is more performent yet not thet readable or because... regular expressions... In that case just make sur they are alone in their function that is named to reflect what they actually do.

## Rule 2 - Write your fonction calls before the function themselves

## Rule 3 - Start from the more complex and abtract part of the code to the simpliest parts in possibly many iterations

## Rule 4 - Prefer data over code

### Rule 4.1 - Never use switch case, use associative array or dictionaries

## Rule 5 - No more than 2 arguments, after that, use named options

Some complex function can have a lot of arguments, one of the problem with that is that it can become hard to remember what argument does what. You then have to waste time looking at the doccumentation or the function definition. Some IDE may help with that but you still have to waste time reading tooltips.

A second worse problem of arguments is that for someone that read your code, it's impossible to get an good idea of what each argument of the function call do unless they know the function definition. He would basicly have to interupt his reading, go look at the function definition, the start reading again, all that without losing his train of thought. We dont want that.

Named argument or options are acheived differently depending of the langage your are using but they allways help immensly the redability of the code that call the function.

There is sometime alternatives that work just as well as named argument. Some function, for example, can get flags as argument and those flag can be nicely named constants which whould result in function calls with pretty explicit meaning.

## Rule 5.1 - The function name should hint the argument order

When you have 2 unamed arguments (hopefully not more), their may still be confusint on a reader point of view about what a function call do if it's unclear what argument should go in front of the other. 

## Rule 6 - Keep it short

## Rule 7 - Calcul things only when you need it

### Rule 7.1 - Constructor should never or at least rarely trigger logic

### Rule 7.2 - Store the result somewhere so it can be used again without going through all the logic

### Rule 7.3 - If you language does not have getters and setters, try to allways use function instead of properties
