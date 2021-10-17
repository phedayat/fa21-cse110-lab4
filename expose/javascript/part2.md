1. 3
2. 150
3. 150
4. The function returns a list of discounted prices, i.e. each entry is the discounted price of the corresponding entry in the original argument list.
5. Returns an error because we're trying to access `i` but it only has block-scope. It isn't accessible outside of the for-loop.
6. Returns an error because we can't access `discountedPrice` outside of the for-loop.
7. 150
8. The function returns a list of discounted prices, i.e. each entry is the discounted price of the corresponding entry in the original argument list.
9. Returns an error because `i` only has block-scope.
10. 3
11. The function returns a list of discounted prices, i.e. each entry is the discounted price of the corresponding entry in the original argument list.
12. Based on `student`
    1. `student.name`
    2. `student["Grad Year"]`
    3. `student.greeting()`
    4. `student["Favorite Teacher"].name`
    5. `student.courseLoad[0]`
13. Arithmetic
    1. '32', because the first operand has type string and + is a supported operation.
    2. 1, because - isn't a supported string operation but it is a supported number operation
    3. 3, because `null` is nothing
    4. '3null', because + treats the second operand as a raw string
    5. 4, because `true` is treated the same as integer 1
    6. 0, because `false` is treated the same as integer 0 and `null` is nothing
    7. 3undefined', because + treats the second operand as a raw string
    8. `NaN`, because - is not a supported string operation, but it is a number operation. It's expecting that the second operand is a number, but it's not, so `NaN`
14. Comparison
    1. true, because 2 > 1 regardless of whether they're strings or integers
    2. false, because it's comparing the operands lexicographically. 2 > 1 which means 2 > 12 lexicographically
    3. true, because the values are the same (2)
    4. false, because despite the values being the same, the types are not the same
    5. false, because `true` is treated the same as integer 1 and 1 =/= 2
    6. true, because the Boolean object has value `true` when a value that isn't false (or equivalent) is passed
    7. == changes the types of the operands to be the same, essentially only checking the values of the operands. === keeps both operands exactly the same, checking if the operands are identical
17. The result will be `[2, 4, 6]`. The function `modifyArray` creates a new array where every entry is double the corresponding original, doing so using the function `doSomething` as a callback function
19. 1 4 3 2, as the logs get called first before the function passed `setTimeout` (as they have timeouts)

