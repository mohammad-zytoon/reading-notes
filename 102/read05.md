comaprison operators:
evaluating conditions
We were able to assess the situation by comparing one value in the script to what we
 expect it might be and the result will be boolean:(true or false).

-(==), equal to: this operator compares two values( numbers, string and booleans) to see if they are the same.

-(!=), is not equalto: this operator compares two values( numbers, string and booleans) to see if they are not the same.

-(===), strict equal to: this operator compares two values to check that both the data type and value are the same.

-(!==), stric not equal to: this operator compares two values to check that both the data type and value are not the same.

Exceptions notes: 

- every value can be treated as true or false even if it is not boolean.
- in short-circuit evaluation, a condition might not need to run.


-(>) GREATER THAN
-(<) LESS THAN
-(>=) GREATER THAN OR EQUAL TO
-(<= LESS THAN OR EQUAL TO)

Logical Operators:
-Comparison operators usually return single values of true or false and it is also allow to compare the results of more 
than one comparison operator.

-(&&)logical AND.
-(||)logical OR.
-(!)Logical not.

-Logical expression are evaluated left to right.


Loops are handy, if you want to run the same code over and over again, each time with a different value.
-for: loops through a block of code a number of times.
   for (statement 1; statement 2; statement 3) {// code block to be executed}.

-While Loops: The while loop loops through a block of code as long as a specified condition is true.
     while (condition // code block to be executed}

-The Do/While Loop:The do/while loop is a variant of the while loop. This loop will execute the code block once, before checking if
 the condition is true, then it will repeat the loop as long as the condition is true.
   do {// code block to be executed}
       while (condition); .