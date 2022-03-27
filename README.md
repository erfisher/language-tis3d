# Tis3d language package

Provides syntax highlighting for code files for the [TIS-3D](https://github.com/MightyPirates/TIS-3D/) minecraft mod.

A TIS-3D file consists of any number of program blocks. Any line outside of a program not starting with `#!` (editor directives) will be completely ignored. Each program block is delimited with `#!BEGIN PROGRAM` and `#!END PROGRAM`, as such:

```
#!BEGIN PROGRAM
LP: MOV DOWN ACC
SUB 15
JEZ LP #Ignore inputs of 15
...
#Additional code goes here
...
MOV ACC UP
#!END PROGRAM
```

Within a program block, the grammar is defined by the TIS-3D manual.
