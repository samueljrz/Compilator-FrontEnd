## Trabalho de LIP(Linguagens de Programação) com intuito de desenvolver um Analisador Léxico(Scanner) e um Analisador Sintático(Parser) de uma linguagem descrita pelo professor, a linguagem escolhida para desenvolver o projeto foi Haskell que é uma linguagem de paradigma funcional. 
### LINGUAGEM:


###	**program()** → *begin* stmt_list() *end*
###	**stmt_list()** → stmt()
###	    | stmt() *;* stmt_list()
###	**stmt()** → *ID* *=* expression()
###	**expression()** → expression() *+* term()
###	    |expression() *–* term()
###	    |term()
###	**term()** → term() * factor()
###	    |term() */* factor()
###	    |factor()
###	**factor()** → exp() ** factor()
###	    |exp()
###	**exp()** → *ID*
###	    |*constante_inteira*
###	    |*constante_inteira.constante_inteira*
###	    |*(*expression()*)*
###

