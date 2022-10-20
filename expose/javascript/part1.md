1) Line 9 is supposed to print result. However, because of an unnecessary extra semicolon, the code returns an error.
2) Line 13 prints out the result again, only if input 3rd argument is set to true and if the extra semicolon is removed
3) Code returns an error because reult's scope is limited to the if block and not outside yet
4) Line 9 will be able to print out the right value of result because scope of if exists inside this if block
5) Code returns an error because result cannot be reassigned after assignment
6) Code retuns an error because line 13 is outside of scope of result which exists only inside the if block 
