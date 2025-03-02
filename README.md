# about

learning compilers by building one

# goals

frontend:

- scanner (lexical analysis)
- parser (syntax analysis with ast construction; supports recursive descent, pratt, shunting yard, peg)
- error reporter (context-sensitive error messages)
- semantic analyzer (basic semantic checks and runtime type checking)

backend:

- ir/bytecode generator (code generation for a stack-based vm)
- optimizer (constant folding, dead code elimination, loop unrolling)
- virtual machine (bytecode execution engine with control flow, memory, and state management)
- llvm integration (llvm ir, clang, llvmlite for advanced code generation)

features/explorations

- modular compiler architecture with distinct components for each phase
- implementation of a simple procedural language
