1. As i was declared using var, it can be accessed outside its block. Therefore 
   console.log(i), prints the current value of i, which will be 3 after the loop
   ends(we stop looping once i is greater than or equal to the length of the prices
   array (3))
2. At line 13 we print 150, the last held value of discountedPrice. As it is a var 
   variable type, we can access it outside its block. prices[2] * (1 - 0.5)=300 * 0.5=150
3. finalPrice was was declared in the same scope as line 14 and can be accessed.
    So we we print 150 at line 14, its last held value. 
    Math.round(discountedPrice * 100) / 100 simply rounds to 2 places which does not matter here. 
4. The function returns an new array of prices, all discounted by the given 
   discount percentage. In this instance we get [50, 100, 150] returned(each price reduced by 50%).
5. Line 12 throws an error(if the fuction is ran), as i is declared using let, and thus cannot be accessed
   outside of its for loop block. 
6. Line 13 throws an error, as discountedPrice is declared using let, and thus 
   cannot be accessed outside of the block where it was declared. 
7. Line 14 prints 150 as finalPrice was declared in the same scope as line 14, and thus
   can be accessed. finalPrice holds its last assigned value, which is 150 for the same reasoning 
   given in q3. 
8. The function returns a new array of prices, all discounted by the given 
   discount percentage. In this instance we get [50, 100, 150] returned(each price reduced by 50%).
9. At line 11 we get an error as as i is declared using let, and thus cannot be accessed
   outside of its for loop block. 
10. Line 12 prints 3, as it holds the length of the prices array (3). 
11. The fuction returns an new array of prices, all discounted by the given 
   discount percentage. In this instance we get [50, 100, 150] returned(each price reduced by 50%).
12. 
    A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. 
    A. '32'     since integers map to their string representation with +(concatination)
    B. 1        since '3' maps to 3 for numeric subtraction
    C. 3        since null maps to 0
    D. '3null'  since null maps to its string representation
    E. 4        since true maps to 1
    F. 0        since both null and false map to 0
    G. '3undefined'     since undefined maps to its string representation
    H. NaN      since '3' maps to 3 but undefined maps to NaN for numeric subtraction (3 - NaN -> NaN)
14. 
    A. true     since '2' maps to 2
    B. false    since they are compared lexicographically as strings.('2' < '1' is false)
    C. true     since '2' maps to 2
    D. false    since we check for equal value and equal type, but their types differ
    E. false    since true maps to 1 
    F. true     since Boolean(2) = true, as 2 is nonzero. 
15.  == checks equality after type conversion(can be different types). 
    === checks for check for equal value and equal type
16. code
17. The result will be [2, 4, 6], as we iterate through the array passed in, [1, 2, 3], 
    and for each element of the array we put it through the doSomething function (which multiplies it by 2),
    and push this to a new array that we return. 
18. code
19. 
    1
    4
    3
    2
