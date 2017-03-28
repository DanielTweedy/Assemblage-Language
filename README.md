# Assemblage-Language
Ideas for an esoteric programming language that is designed from the name "Assemblage". The repo will only contain ideas for the language until I learn how to implement compilers.

## Idea 1: Assemble All the Worst Ideas
Take some of the worst syntactic sugar from common programming languages and throw them together like the Assemblage Art Movement in the 1950's. An example could be using the '->' reference operator and the strict assignment structure of Bash, e.g. 'var=value' would be valid syntax and 'var = value' would not be valid.

### Problems and Possible Pitfalls
Since the language would implement many different features from many different programming langauges that would have no common thread except in their obtuseness, the compiler might be difficult to implement (from my limited knowledge of compilers.) This might also mean that the compiler will not be easily ported and probably faily large and complex.

## Idea 2: High Level Assembly
Make a "high level" assembly language that compiles directly into the instruction set assembly language of the machine and has none of the benefits of high level languages. Consider implementing the assembly in weird ways like being in trinary, poor design structure (look into x86 achitecture and maybe make it worse.)

Example: `ADD &input1 &input2 &output`
