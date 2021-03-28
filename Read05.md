## Comparision Operators ( < , > , == , != , >= , etc...)

1. Results *True* or *False* , ' I will refer to True as *T* and to False as *F* ' .
2. Comparing two values ( numbers, strings, booleans).
3. ' === ' & ' !== ' compare the value and the data type *preferable tto use* , for eg ' (3 === "3") ' will result F.
4. ' == ' & ' != ' compare only the value. for eg ' (3 == "3") ' will result T.

## Logical Operators 

1. Comparing results for more than one comparison operator.
2. ' && ' is the logical *AND* operator.
   **T && T** RESULTS T  - **T && F** RESULTS F  - **F && T** RESULTS F  - **F && F** RESULTS F  
3. ' || ' is the logical *OR* operator.
   **T || T** RESULTS T - **T || F** RESULTS T - **F || T** RESULTS T - **F || F** RESULTS F  
4. ' ! ' is the logical *NOT* operator.
   **!T** RESULTS F  - **!F** RESULTS T

*Expresions are evaluated from left to right*.

## Loops

There are three common types of loops:

1. *For* Loop, a counter condition.
2. *While* Loop, loop will continue looping as long as the condition results T.
3. *DO...WHILE* Loop, similar to the while loop but every statement runs at least one time even if it's condition results F.



*Note that: for the variable x , the expression 'X += ' means that I identify x with the new resulted value*.