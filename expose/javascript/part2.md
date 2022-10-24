# Part 2
12.  
    1. student.name
    2. student['Grad Year']
    3. student.greeting()
    4. student['Favorite Teacher'].name
    5. student.courseLoad[0]
13. 
    * '32', since integer 2 is converted to string '2'
    * 1, since stirng '3' is converted to integer 3 in here 
    * 3, since null is converted to 0 in numeric conversion
    * '3null', since null is converted to string 'null' in string conversion
    * 4, since true is integer 1 in numeric conversion
    * 0, since false is 0, and null is also 0 in numeric conversion
    * '3undefined', since variable undefined converted to string 'undefined'
    * NAN, since undefined converted to number NAN in numeric conversion
14. 
    * true, since '2' string is converted to 2
    * false, since string '2' first character is bigger than string '12'
    * true, since string '2' is converted to 2
    * false, since === is strict equality operator, which compare variables without type conversion, and string '2' is not the same type as integer 2
    * false, since true is converted to 1 in numeric conversion
    * true, since Boolean(2) return boolean true, which is the same data with LHS.
15. == is non-strict check, which allows conversion between different type data in comparison, while === is strict check, which does not allow conversion.
16. See js code.
17. Function return an array [2, 4, 6]. Since function also is a type of variable, when doSomething function pass in, it gets initialized and executed inside the for loop, which double the input array values.
18. See js code.
19. Print 1 4 undefined 3 2 accordingly.
