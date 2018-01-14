# Assemblage-Language
Ideas for an esoteric programming language that is designed from the name "Assemblage". The repo will only contain ideas for the language until I learn how to implement compilers.

## Idea 1: Assemble All the Worst Ideas
Take some of the worst syntactic sugar from common programming languages and throw them together like the Assemblage Art Movement in the 1950's. An example could be using the '->' reference operator and the strict assignment structure of Bash, e.g. 'var=value' would be valid syntax and 'var = value' would not be valid.

### Problems and Possible Pitfalls
Since the language would implement many different features from many different programming langauges that would have no common thread except in their obtuseness, the compiler might be difficult to implement (from my limited knowledge of compilers.) This might also mean that the compiler will not be easily ported and probably faily large and complex.

### Things that are annoying about a language or that would be annoying if used in this context
- All variables MUST begin with a captial letter (prolog)
- Free form syntax using '(' and ')' for structure (LISP/Scheme/Racket)
- Tail recursion with "car" and "cdr" (LISP/Scheme/Racket)
- Whitespace matters (Haskell/Python)
- Explicit pointers and memory management (C)
- Standard system functions like printing have to be accessed through a static System class, and make it worse (Java)
- Only a multiline comment (Old C)
- `if` is either only ternary or bash like if: `a && b ? c : d` or `if [a && b]; then c; else d; fi` 

## Idea 2: High Level Assembly
Make a "high level" assembly language that compiles directly into the instruction set assembly language of the machine and has none of the benefits of high level languages. Consider implementing the assembly in weird ways like being in trinary, poor design structure (look into x86 achitecture and maybe make it worse.)

Example: `ADD &input1 &input2 &output`
