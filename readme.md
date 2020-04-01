## Programming languages ​​work in order to develop a Scanner and a Parser of a language described by the teacher, the language chosen to develop the project was Haskell, which is a functional paradigm language.

### How

* Haskell

* Compilators

### LINGUAGEM:

####	**program()** → *begin* stmt_list() *end*
####	**stmt_list()** → stmt()
####	    | stmt() *;* stmt_list()
####	**stmt()** → *ID* *=* expression()
####	**expression()** → expression() *+* term()
####	    |expression() *–* term()
####	    |term()
####	**term()** → term() * factor()
####	    |term() */* factor()
####	    |factor()
####	**factor()** → exp() ** factor()
####    |exp()
#### 	**exp()** → *ID*
####	    |*constante_inteira*
####	    |*constante_inteira.constante_inteira*
####    |*(*expression()*)*
####

