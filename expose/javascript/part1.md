# Part 1:
1. line 9 would print "values added:  20"
2. Since variable declared with var has no block scope, line 13 still would print "final result:  20"
3. line 9 would print "value added:  20"
4. code returns an error at line 13. Since let variable has block scope, when outside of if statement, result doesn't defined.
5. Code returns an error, since const variable couldn't be reassigned after initialization, which the addition in line 4 would produce an error
6. Code returns an error, since const variable has been reassigned and use out of block scope.
   
# Part 2:
1. Line 12 would print "3", as var does not have block scope limit and outside of for loop, i add up to prices's size and exit loop, which is 3.
2. Print "150", which is the last discountedPrice added, price[2] * (1 - discount) = 300 * (1 - 0.5) = 150.
3. Print "150", which is the round up integer value of last discountedPrice.
4. Function will return an array containing discounted prices, [50, 100, 150].
5. Code causes an error. Since i is a let variable, and let variable has block scope. When outside of for loop, i isn't defined and program output error.
6. Code causes an error, same reason as question 5, let variable has block scope.
7. Printed "150", which is the last discounted value. Since finalPrice let variable is declared outside of for loop, value gets printed.
8. Print [50, 100, 150] the array containing discounted values
9. Code returns error, as i is declared only inside for loop.  
10. Print "3", which is the input array prices's size.
11. Printed [50, 100, 150], which is the 50% discounted price array. Since const variables don't reassigned in code, code function as expected.