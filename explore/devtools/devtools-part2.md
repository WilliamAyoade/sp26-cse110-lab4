1. The bug is that num1 and num2 are being read as strings, 
   so result = num1 + num2 is doing string concatination. 
2. I would convert num1 and num2 to numbers before adding them together