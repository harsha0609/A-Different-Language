# A-Different-Language

The language is created using parse tree,lexical generators like `Bison` and `Lex`.<br>

features such as  `evaluating an expression` , `basic arithmetic operations(+,-,*,/)` , `if ` condition , `while` loop

It considers context free grammar(CFG)

The CFG used in this language is :<br>
```
    <expr> := [ <op> <expr> <expr> ] | 
                 <symbol> | <value>
    <symbol> := [a-zA-Z]+
    <value> := [0-9]+
    <op> := ‘+’ | ‘*’ | ‘==‘ | ‘<‘
    <prog> := [ = <symbol> <expr> ] |
              [ ; <prog> <prog> ] |
              [ if <expr> <prog> <prog> ] |
              [ while <expr> <prog> ] |
              [ return <expr> ]
```
##  Running the program
To  run this program use:<br>
```
 bash run1
 
 ./runit
```
```
To clear all the object files and the other generated files use:
 ./clear
```
