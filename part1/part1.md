1. The value of `prices.length` will be printed since `i` was declared as `var` and so is the same throughout the scope of the function.
2. It will print the last calculated `discountedPrice`, namely `prices[prices.length-1]*(1-discount)` for the same reason that `discountedPrice` was declared as var or undefined if `prices` is empty. This is because "Declarations are hoisted, but assignments are not".
3. It will print the last `finalPrice` calculated using the last value of `discountedPrice` (the same as in part 2) or 0 if `prices` is empty
4. [ 50, 100, 150]  
   It is the list of the prices to which the discount was applied.
5. It will throw an ReferenceError excpetion since `i` is visible only in the loop.
6. It will throw an ReferenceError excpetion since `discountedPrice` is visible only in the loop.
7. It will print the last `finalPrice` calculated using the last value of `discountedPrice` or 0 if `prices` is empty.
8. [ 50, 100, 150]  
   It is the list of the prices to which the discount was applied.
9. It will throw an ReferenceError excpetion since `i` is visible only in the loop.
10. It will throw an ReferenceError excpetion since `discountedPrice` is visible only in the loop.
11. It will print the last `finalPrice` calculated using the last value of `discountedPrice` or 0 if `prices` is empty.
12. [ 50, 100, 150]  
13.  
    * A. `student.name`
    * B. `student['Grad Year']`
    * C. `student.greeting()`
    * D. `student['Favorite Teacher'].name`
    * E. `student.courseLoad[0]`
14.   
    * A. `'3' + 2 = '32'` since it just concatinates 2 to string '3'
    * B. `'3' - 2 = 1` strings do not have a subtraction operation so 3 is converted to a number instead
    * C. `3 + null = 3` because null becomes 0 when converted to a number
    * D. `'3' + null = '3null'` since null converts to 'null' when converted to a string
    * E. `true + 3 = 4` since true is converted to a 1 when converted to a number
    * F. `false + null = 0` since both operands do not have + operation so they are interpreted as number which makes both 0
    * G. `"3" + undefined` = "3undefined" since undefined converts to 'undefined' when converted to a string
    * H. `"3" - undefined` = NaN since math operations on undefined produce `NaN` and "3" gets interpreted as number as strings do not have - operation 
15.  
    * A. `'2' > 1 = true` since "when comparing values of different types, JavaScript converts the values to numbers" 
    * B. `'2' < '12' = false` since when comparing the first characters, `'2' > '1'`
    * C. `2 == '2' = true` since when comparing values of different types with regular equality check, JavaScript converts the values to numbers  
    * D. `2 === '2' = false` since when comparing values of different types with strict equality check it always returns false
    * E. `true == 2 = false` since `true` gets interpreted as `1`
    * F. `true === Boolean(2) = true` since both equate to `true`
16. `==` does conversion when diferent types are compared and is not as strict as `===` which returns true only if the two operands are absolutely equal.
17. `How are you?` gets printed. Even though `true == 2` doesn't evaluate to true but numbers greater than `0` are still "truthy" 
18.  See the code
19.  The result will be `[4, 6, 8]`. We see that `modifyArray` iteraters through the array and passes each element to callback which we specified to be `doSomething`. `doSomething` in turn calls a callback, which `modifyArray` specifies to be a function mutliplying numbers by 2, and add 2 to the result. Thus, the end results is `array[i]*2+2` for each `array[i]`
20.  See the code
21.  1   
    4   
    3  
    2
