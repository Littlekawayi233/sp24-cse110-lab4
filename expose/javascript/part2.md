1. It prints out the value of i which is 3. The value of i is also eqaul to the prices.length .

2.It prints out 150. Because at the last iteration of for loop, discountedPrice = 300*(1-0,5) = 150

3. It prints out 150. Because at the last iteration of for loop, finalPrice = math,round(150*100)/100 which is also equal to 150.

4.It returns [ 50, 100, 150 ], because at each itertation, it pushes the finalprice to the discounted array. 

5. ReferenceError: i is not defined.  i is outside of the for block.

6.ReferenceError: discountedPrice is not defined. discountedPrice is outside of the for block.

7. It prints out 150. for the same reason as question3. And it has been defined in the same block.

8. [ 50, 100, 150 ], because at each itertation, it pushes the finalprice to the discounted array. 

9. ReferenceError: i is not defined. i is outside of the for block.

10. It prints out 3 which is the prices.length that has already been assigned at top of the function with the keyword const.

11. [ 50, 100, 150 ], because at each itertation, it pushes the discountedPrice to the discounted array. 

12. A:student.name 
    B:student['Grad Year']
    C: student.greeting()
    D: student['Favorite Teacher'].name
    E:student.courseLoad[0]

13. A:'32' since integers map to their exact string representation
    B: 1 since it converts string '3' into integer
    C: 3 since null maps to 0
    D: '3null' since  the concatenation, and null is converted into string 'null'
    E: 4 since true maps to 1
    F: 0 both false and null map to 0
    G: '3undefined' since  the concatenation, and undefined is converted into string 'undefined'
    H: NaN since undefined can not be converted into a num 

14  A: true since '2' is converted into num 2
    B: false since JavaScript uses lexicographic order to compare string
    C: true since  '2' is converted into num 2
    D: false since 2 and '2' are different  data types and === operator always return false when 2 data type are not the same.
    E: false  since true maps to 1
    F: true since Boolean(2) returns true 

15.  For the == operator, since javascript is able to map the value of a variable from one data type to another and we can use it to compare two different data types. However for the === operator, comparing between two different data type will always return false as it's strict equality propety.

17. It retruns [ 2, 4, 6 ]  as the dosomething function take a num as parameter and multiply by two, then in the modifyArray function it takes both the array and callback as the parameters. It first create a newArr with const keyword and then in the for loop it iterates array.length times and push the result of dosomething(num) into the newArr which is the input num multiply by two. After all the iterations, it will return an array with all the num multiply by two from the original array.

19. 1 4 3 2