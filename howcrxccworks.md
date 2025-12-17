# CRX C Compiler and CRX Barssembler (crx-cc and crx-bar)
CRX C Compiler works like this:
- It has a lexer (obviously), which transforms code into a token.
- Next comes the parser, which creates a tree. 
- And lastly, the bytecode is generated specifically for xx86.

Why is CRX C Compiler so important?
Because there's no point in using bare-metal gcc if it doesn't compile specifically for xx86. And crx-cc compiles code **specifically** for xx86.
The same logic applies to the CRX Barassembler, but with lower-level bytecode.
# Now comes the most important question: how do you use this damn thing?
I don't know, but yes, I do know.
`crx-cc mycode.c -o mycode.bin -nolibstd`
A clear example of how to use the CRX C Compiler.
What about Barassembly?
F*ck it, I don't know.
