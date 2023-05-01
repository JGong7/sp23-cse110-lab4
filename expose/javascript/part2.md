1. Line 12 will print "3" because the variable i was declared with var, which gave it function scope.
2. Line 13 will print "150" because the variable discountedPrice was declared with var, and it will have the value that the for loop assigned at the last iteration.
3. Line 14 will print "150" because the variable finalPrice was declared with var and will have the value that the for-loop assigned lastly.
4. This function will return an array [50, 100, 150] because line 16 says return discounted, which was an array declared with var.
5. The code throws an error at line 12 because i was declared with let inside the for-loop.
6. The code throws an error at line 13 because discountedPrice was declared with let inside the for-loop.
7. Line 14 will print 150 because the variable finalPrice is declared within the function block.
8. The function will return an array [50, 100, 150], and it is essentially the same as question 4, as the difference of variable scopes don't make a difference in this case.
9. The code will throw an error because the scope of variable i is only within the for-loop.
10. At line 12, the console will print "3" because length is a const variable that recorded the length of [100, 200, 300], which is 3.
11. The function will print [50, 100, 150] because the for-loop cut each entry in the array prices by half and then put them in the output array.
12.
  A. student['name']
  
  B. student['Grad Year']
  
  C. student.greeting()
  
  D. student['Favorite Teacher']['name']
  
  E. student['courseLoad'][0]
  
13. 
  A. Output is '32'. It is because when a string is concatenated with a number, JavaScript converts the number to a string and concatenates them.
  
  B. Output is 1. This is because when Javascript subtracts a number from a string, it tries to convert the string to number and then subtract.
  
  C. Output is 3. This is because Javascript converts null into 0.
  
  D. Output is '3null'. This is because Javascript read + as concatenation, and then converts null into string.
  
  E. Output is 4. This is because true gets converted to 1.
  
  F. Output is 0. This is because both false and null get converted to 0.
  
  G. Output is '3undefined'. This is because JavaScript reads + as concatenation and converts undefined into 'undefined'
  
  H. Output is NaN. This is because both '3' and undefined are not numbers.
  

14. 
  A. Output is true. This is because JavaScript converts '2' into integer.
  
  B. Output is false. This is because JavaScript compares strings lexicographically.
  
  C. Output is true. This is because '2' gets converted to 2.
  
  D. Output is false. This is because === is strict on type comparisons.
  
  E. Output is false. This is because true is converted to 1.
  
  F. Output is true. This is because Boolean(2) converts to true.
 
15. The difference is that === returns false strictly if two sides are not the same type, while == will convert the types first.

17. The result is that the array [1, 2, 3] will become [2, 4, 6]. This is because doSomething(num) takes in an integer and multiplies it by 2. It is being passed into modifyArray and will be executed on every entry of the array, hence multiplying every entry of [1, 2, 3] by 2.

19. The output is:\
1\
4\
3\
2
