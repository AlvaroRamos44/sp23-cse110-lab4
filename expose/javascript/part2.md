# Part 2. A Little More of a Challenge...
+ Question 1: outputs 3, which is the value of for var loop variable 'i' after the loop ends. This is possible outside for block because 'i' is a declared as var.
+ Question 2: outputs 150, which is the value of of discountedPrice when for loop ends (computation of (300 * (1 - 0.5)). This is possible outside for block because discountedPrice is declared as a var. 
+ Question 3: outputs 150, from the last computation of finalPrice and since 150 is an integer, the computation is the same. finalPrice is declared in the same block and function, so it would be in scope even if it was not declared as var.
+ Question 4: returns array discounted consisting of [50, 100, 150]. The values finalPrice are pushed into array in the for loop. 
+ Question 5: error because for loop variable 'i' is declared as a let, which has a block level scope and line 12 is outside of that scope.
+ Question 6: error because discountedPrice declared as a let inside for loop, and line 13 is outide of for block.
+ Question 7: outpus 150 because finalPrice is declared at top of function outside of for loop block, and line 14 is in the same scope.
+ Question 8: returns array discounted containing [50, 100, 150]. This is possible because discounted is declared outside for loop and so has same scope as the return statement.
+ Question 9: error, because 'i' is declared as a let withing for loop block and line 11 is outside this scope.
+ Question 10: outputs 3, because length of the argument 'prices' passed to function is array of length 3
+ Question 11: returns array discounted containing [50, 100, 150]. discounted is declared in same scope as return statement and the variable is pushed 'discountedPrice' is pushed into it in the for loop. Despite discountedPrice being initialized as a const, each loop iteration initializes a new instance of discountedPrice, which allows this.

## Data Types
+ Question 12:
  + A: console.log(student.name);
  + B: console.log(student['Grad Year']);
  + C: student.greeting();
  + D: console.log(student['Favorite Teacher'].name);
  + E: console.log(student.courseLoad[0]);

## Basic Ooperators & Type Conversion
+ Question 13 (Arithmetic):
  + A: outputs '32' because 2 converted to string '2' and concatenated (+ operator is overloaded for concatenation and addition)
  + B: outputs 1 because '3' converted to integer representation 
  + C: outputs 3 because null is converted to integer 0
  + D: outputs '3null' because null is converted to string 'null' and concatenated
  + E: outputs 4 because true is converted to integer 1
  + F: outputs 0 because false is converted to integer 0 and null is converted to integer 0
  + G: outputs '3undefined' because undefined is converted to string 'undefined' because of the concatenation operator (+)
  + H: outputs undefined because undefined is converted to NaN and the resulting operation is also NaN
+ Question 14 (Comparison):
  + A: outputs true because string '2' is converted to number 2
  + B: outputs false because strings '2' and '12 converted to numbers 2 and 12
  + C: outputs true because string '2' converted to number 2
  + D: returns false because === checks equality without type conversion
  + E: returns false because true converted to 1 
  + F: returns true because Boolean(2) returns boolean value true
+ Question 15: === checks for equality without converting the types of the things being compared. == does type conversion before checking for equality.
## Loops
+ Question 16: -- in part2-question16.js -- 

## Functions
+ Question 17: The result would be the array newArr containing [2,4,6]. It would arrive at this because inside the for loop in modifyArray, we call function in callback that was passed as a argument in modifyArray. The function doSomething is the callback function and it gets the current element at index i of the array passed to modifyArray and multiplies it by 2. 

## setInterval(), setTimeout(), clearTimeout()
+ Question 18: -- in part2-question18.js --
+ Question 19: Prints out 1 then 3 then 4 then 2. This happens because there is a delay of 1 second for 2 to be printed, despite it being in line 3 before 3 and 4.

