# Basics features of C

Material from video: https://www.youtube.com/watch?v=rLf3jnHxSmU&list=PLBlnK6fEyqRhX6r2uhhlubuF5QextdCSM&index=2
book: https://beej.us/guide/bgc/html/split/hello-world.html#hello-world

# Code Structure

## Preprocessor 

Replaces the text inserted by actual code of a previous library. Replaces before the compilation and the output of the preprocessing is expanded source code.

`source code --(Preprocessor)-> Expanded source code --(Compiler)-> Machine code`

### Examples of preprocessors

- stdio.h: standard input and output. Contains declarations of functions like `printf`, `scanf`, etc;

### Syntax of a function

return_type name_function(parameter_type name_parameter)
{
    set of statements;
}

## Variables

### Variable names 

You can use any characters in the range 0-9, A-Z, a-z, and underscore for variable names, with the following rules:

- You can’t start a variable with a digit 0-9.
- You can’t start a variable name with two underscores.
- You can’t start a variable name with an underscore followed by a capital A-Z.

### Variable types 

| Type| Example | C type |
| ------------- | -------------- | -------------- |
| Integer | 12445 | int |
| Floating point | 12.325 | float |
| Character (single) | 'a' | char |
| String | "good moring!" | char * |

### Especificadores em printf()

A função printf do preprocessing stdio possui especificadores para injetar variaveis em strings, esses especificadores seguem um padrão:

| tipo  | especificador |
|--------------- | --------------- |
| inteiro | %d |
| float | %f |
| char | %c |
| string | %s |

## Operações e aritmética


