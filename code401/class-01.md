#  Java Basics

## Tutorial

### Variables 

The Java programming language defines the following kinds of variables:

1. Instance Variables (Non-Static Fields) : fields declared without the static keyword.

2. Class Variables (Static Fields) : any field declared with the static modifier.

3. Local Variables : local variables are only visible to the methods in which they are declared.

4. Parameters : ex. *`args`* in *`public static void main(String[] args)`*

### Data Types


| Data Type            | bits   |Default Value (for fields)| info |
|----------------------|--------|--------------------------|------|
|byte                  | 8-bit  |	0                      | min.value=-128 max value= 127 (inclusive) |
|short	               | 16-bit |  0                       | min.value=-32,768 max value= 32,767 (inclusive) |
|int	               | 32-bit |  0                       | min.value=-2^31 max value= 2^(31)-1 |
|long	               | 64-bit |  0L                      | min.value=-2^(63) max value= 2^(63)-1 |
|float	               | 32-bit |  0.0f                    |  if you need to save memory in large arrays of floating point numbers. |
|double	               | 64-bit | 0.0d                     | for decimal values |
|char	               | 16-bit |  '\u0000'                | min.value='\u0000'(or 0) max value='\uffff' (or 65,535 inclusive)|
|boolean	           |not precisely defined | false      | for simple flags that track true/false conditions  |
|String (or any object)|    | 	null  (not exactly a data type) |   immutable(values can not be changed) |

### Operators 


|Operators            |	Precedence
|---------------------|-----------
|postfix              |	expr++ expr--
|unary                |	++expr --expr +expr -expr ~ !
|multiplicative       |	* / %
|additive             |	+ -
|shift                |	<< >> >>>
|relational           |	< > <= >= instanceof
|equality             |	== !=
|bitwise AND          |	&
|bitwise exclusive OR |	^
|bitwise inclusive OR |	\|
|logical AND	      | &&
|logical OR           |	\|\|
|ternary              |	? :
|assignment           |	= += -= *= /= %= &= ^= |= <<= >>= >>>=

### Statements

* if-then Statement
* switch Statement
* while and do-while Statements
* for Statement
* break, continue and return Statements


## What Does It Mean To Compile A Code

Compile means to make the code executable(convert human language ***java*** to machine language ***1's and 0's***

## Making sense of a Java API Documentation

If you check out the last reference you'll find out how to understand the documentation , and learn how to use it and how to get the information from it.

References:

* [Check this JAVA Tutorial](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/index.html)

* [EL15](https://www.reddit.com/r/explainlikeimfive/comments/233dq5/eli5_what_does_it_mean_to_compile_code/)

* [xkcd Compiling](https://xkcd.com/303/)

* [JAVA Documentation](https://www.dummies.com/programming/java/making-sense-of-javas-api-documentation/)