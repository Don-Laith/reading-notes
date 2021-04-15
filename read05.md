## comparison operators evaluating condition 
#### you can evalute a sitation by comparing one valus in the script to what you expect it might be . The result will be a Boolean : true OR false
##### == is equal to : This opoerator compare two values (number ,string ,boolean ) if they the same 
##### != : is not equal : this operator compare two vvalues if they are not same
##### === : strict equals to : this operator compares two values to check that both the data type and valus are the same 
##### !== : strict not equals to : this operator comapres  two values to check that both the data type and the value are not the same 
- (>) greater than :
- (<) less than 
- (<=) less than or equal 
- (>=) greater than or equal 


### LOGICAL OPERATORES
##### comparison operator usually return single values of true or false , Logical operator allow you to compare the result of more than one comparision operator 
### example of logical operator :
- && : logical AND : this operator test more than one condition , if both true it will be true , otherwise it will be false 
- || logical or : this operator tests t least one condition ,if one of them true it will be  true 
- ! logical not: this operator takes a single boolean value and inverts it ,this reverse the state of an expression , if it was false it will return to true 
### SHORT-CIRCUIT EVALUATION 
- Logical expressions are evaluated left to right
- If the first condition can provide enough information to get the answer, then there is no need to evaluate the second condition. 
- There is no point continuing to determine the other result. 
- They cannot both be true. 
true II anything it has found a true 
- There is no point continuing because at least one of the values is true. 

<<<<<<< HEAD
## LOOP
#### Loops check a condition. If it returns true, a code block will run. Then the condition will be checked again and if it still returns true, the code block will run again. It repeats until the condition returns fal se. There are three common types of loops: 
- FOR If you need to run code a specific number of times, use a for loop. (It is the most common loop.) In a for loop, the condition is usually a counter which is used to tell how many times the loop should run. 
- WHILE If you do not know how many times the code should run, you can use a while loop. Here the condition can be something other than a counter, and the code will continue to loop for as long as the condition is true. 
- Do While loop is very similar to the while loop, but has one key difference: it will always run the statements inside the curly braces at least once, even if the condition evaluates to false. 


