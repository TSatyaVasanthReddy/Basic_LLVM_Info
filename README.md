AST structure: Use the options provided with Clang to view the LLVM/Clang-AST for some non-trivial

programs. Understand the design of LLVM-AST to some level. Report your findings.

• AST traversals: Read the tutorial to write AST visitors at http://clang.llvm.org/docs/RAVFrontendAction.

html. Write a short note about the visitor mechanism to traverse the AST and do semantic analysis.

(The visitor pattern is design pattern, a paradigm from software engineering which you are using in your

ANTLR.)

• Error messages: Do a study of how the error messages are handled in LLVM source code, primarily the

assert mechanism of LLVM. Report on the handling of some specific error messages.

• LLVM-IR: Do a study of the LLVM-IR. Print the IR for some non-trivial programs and study them.

Report on your study.

• Assembly language: Generate the assembly language codes of some simple C/C++ programs. Under-
stand how the C/C++ compilers mangle the names of various entities. Report your findings.

• Compiler toolchain and options: For a set of programs, go all the way; print the AST, print the

LLVM-IR, print the assembly code. Play with the various compiler frontend/middle-end/optimizer options.

Report your findings.

• Kaleidoscope: Read the Kaleidoscope at documentation http://llvm.org/docs/tutorial/index.html.

Extend the language in a minor way, like adding binary operators, adding more syntax flavors etc. Report

your findings.
