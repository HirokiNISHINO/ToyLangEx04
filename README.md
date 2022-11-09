# ToyLangEx03
Toy Programming Language: Ex03

整数の(expr)をサポート．

現状の文法．

\<Program\> ::= \<AdditiExp\>

\<AdditiExpr\>　:: = \<MultiplicativeExpr\> [ ( '+' | '-' ) \<MultiplicativeExpr\> ]\*

\<MultiplicativeExpr\> :: = \<Primary\> [ ( '\*'  | '/' ) \<Primary\> ]\*

\<Primary\> :: = ( \<expr\> ) | \<Integer\>
