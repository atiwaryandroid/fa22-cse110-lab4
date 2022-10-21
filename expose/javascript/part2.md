1) At line 12, the code returns the size of the prices list
2) At line 13, the code returns the discounted price variable. However, this variable is updated 3 times. The value of the last update, i.e, 300*(1 - 0.5) = 150 is returned
3) At line 14, the value of the last finalPrice is returned (as this variable is updated 3 times). The last update was 150*100/100 = 150. 
4) This function returns an array containing all the final prices, however it does not print anything to the console
5) i is defined inside the for loop, therefore it's scope does not exist outside of it
6) As before, discountedPrice's scope is limited to the for loop, therefore it is not defined up till the console log statement
7) finalprice's scope exists for the entire duration of the function therefore it is printed as before when var was used instead of let
8) As before, nothing is returned, but the scope of discounted array exists for te entire duration of the function, so no error
9) Error because i is not defined outside the for loop block
10) Returns the size of the prices list, no error
11) Discounted prices are pushed to the array 3 times,this array is returned, nothing is printed bcoz no console statement
12) A)student.name B)student['Grad Year'] C)student.greeting() D)student['Favorite Teacher'].name E)student.courseLoad[0] 
13) A) '32' Because 3 and 2 are added to each other as stringsB) 1 C) 3 D) '3null' E) 4 F) 0 G) '3undefined' H) NaN
