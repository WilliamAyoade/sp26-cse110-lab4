1. values added:  20
2. final result:  20
3. var should not be used because it allows the variable to be accessed out side 
   its block, which can cause issues. 
4. values added:  20
5. line 13 returns an error as we are trying to access the results variable outside
   the if block, but we are using the let variable type so this is not allowed
6. Line 9 is never reached as we get an error on line 7, as we attempt to reassign
   a value to the result vairble, but this is not allowed as const gives immutable variables(for primatives)
7. Line 13 is never reached for the same reason given above. 