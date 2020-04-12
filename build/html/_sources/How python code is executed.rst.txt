===========================
How python code is executed
===========================

At the command line::

    a = "hello“

There are four steps that python takes when you hit return lexing, parsing, compiling, and interpreting

* **Lexing** is breaking the line of code you just typed into **tokens**
* The **parser** takes those **tokens** and generates a structure that shows their relationship to each other (in this case, an **Abstract SyntaxTree**).
* The **compiler** then takes the **AST** and turns it into one (or more) **code objects**. (function objects, code objects, and bytecode)
* Finally, the **interpreter** takes each code object (It contains information that this interpreter needs to do its job) executes the code it represents

|
|

to understand how Lexing,prasar & AST work `a link`_.

.. _a link: http://www.jayconrod.com/posts/37/a-simple-interpreter-from-scratch-in-python-part-1
