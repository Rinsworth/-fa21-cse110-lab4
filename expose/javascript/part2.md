# Part 2. A Little More of a Challenge...

1. Line 12 will print "3" as it is the value of "var i", which is incremented three times, as the lenght of prices.length is 3. 
2. Line 13 will print "150", as the last element in prices is 300 and we multiply it by (1-discount) or (1-0.5) or 0.5. Because it's a var, it is global, we keep the value from inside the loop.
3. Line 14 will also print "150" for the same reason as question 2. We just take the last value of discountedPrice, which is 150, multiply it by 100, round it to the nearest integer, and then divide it by 100. I assume this is to round to the nearest cent. 
4. Line 16 will return the array "[50,100,150]". As the loop iterates through the elements of prices, it pushes the resulting finalPrice to array discounted. The array push function in javascript appends the element to the end of the array. This gives us the final array in discounted. 
5. There is a reference error because "i" was declared using "let" in the for loop. Once the for loop is completed, "i" is no longer in scope and calling it results in a reference error.
6. There is a reference error because "discountedPrice" is declared using "let" in the for loop. Once the for loop is completed, "discountedPrice" is no longer in scope and calling it results in a reference error.
7. Line 14 will print "150" for the same reason as question 3. This does not result in a reference error because "finalPrice" is declared at the start of the function and is still in scope at line 14.
8.  Line 16 will return the array "[50,100,150]" for the same reasons as in question 4. This does not result in a reference error because "finalPrice" is declared at the start of the function and is still in scope when returning the value.
9.  There is a reference error because "i" was declared using "let" in the for loop. Once the for loop is completed, "i" is no longer in scope and calling it results in a reference error.
10. Line 12 will print "3" because the length of the array "prices" is 3. It is then set to a const in line 4, and that value is then called in line 12 when printing.
11. Line 16 will return the array "[50, 100, 150]" for the same reasons as in question 4. This does not result in an error when we push to discounted even while it is a const. This is because we are not reassigning the list.
12. 

    A.  student['name']

    B.  student['Grad Year']

    C. student['greeting']()

    D. student['favorite teacher']['name']

    E. student['courseLoad'][0]

13.

    A. 32. We are concatenating the string '3' with the int 2, which is cast to '2'. This gives us the string 32.
    
    B. 1. As there is no operators to subtract strings, the string '3' is cast into an int, giving us int 3 - int 2, which gives us the integer 1. 

    C. 3. Null is considered to be a 0, so 3+0=3.

    D. 3null. Because '3' is a string, javascript attempts to concatenate the two, which casts null to the string 'null'.

    E. 4. The integer value of true is 1, which gives us 1+3=4.

    F. 0. The integer values of false and null are both 0, so 0+0=0.

    G. 3undefined. Because '3' is a string, javascript attempts to concatenate the two, which casts undefined to the string 'undefined'.

    H. NaN. As there is no operator to subtract strings, the string '3' is cast to the int 3, and undefined is cast to NaN. The subtraction of 3 and NaN defaults to NaN.

14.
    
    A. True. The string '2' is cast into a integer 2. 2>1 is true.
	
    B. False. When comparing two string, the first characters are compared. Thus this comparison turns to '2'<'1', which is false. 

    C. True. The string '2' is cast into the integer 2, and 2==2 is true.
	
    D. False. The '==' operator uses type coercion to convert the variables to the same type before comparing. The '===' operator does not do this type conversion, and thus, we are comparing an int to a string, which are not the same. 

    E. False. The numerical value of true (1) is used, and we now compare 1==2, which is false.

    F. True. The function Boolean() returns true if any positive integer is given. This turns into true===true, which is true.

15. The '==' operator uses type coercion to convert the variables to the same type before comparing. This essentially means that the '==' operator attempts to cast the variables to types that are valid for comparison. The '===' operator does not do this type conversion, so comparisons between different types are false. 

17. This returns '[2,4,6]'. In modifyArray, we are essentially using a map function to apply some function to each element of the array. modifyArray iterates through each element in the array and runs it through doSomething. The result is then appended to newArr, which is returned after the for loop.


19. Output:
    
        1

        4

        3

        2
    