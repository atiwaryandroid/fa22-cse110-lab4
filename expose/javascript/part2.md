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
13) A) '32' Because 3 and 2 are added to each other as stringsB) 1 because '-' has no meaning in the context of strings, therefore these are treated as numbers C) 3 because 3 is not in quotes, therefore it is treated as a number and null is treated as 0, their sum is 3 D) '3null' because 3 is within quotes and is therefore treated as a string, the 2 strings are concatenated E) 4 because 3 is not within quotes and therefore both 3 and true are treated as numbers where true is the number 1 F) 0 because both false and null are treated as numbers (both equal to 0) G) '3undefined' because 3 is within quotes and therefore both are treated as strings that are concatenated H) NaN because '-' has no meaning in the context of strings, therefore both are treated as numbers, anything minus undefined is also undefined.
14) A) true because both are treated as numbers as 2 is not in quotes B) false because both are treated as strings as both are in quotes, therefore each character is compared, the first character of 12 (1) is lesser than the first character of 2 (2), therefore false is returned C) true because string is converted to integer and 2 is equal to 2 D) false because this is a strong comparison operator that returns false if the type is different, string is not the same as integer E) false because true is converted to integer (1) and 1 is not equal to 2 F) true because Boolean of any number not equal to 0 is true and true is indeed qual to true
15) 
