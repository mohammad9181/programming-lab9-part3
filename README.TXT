Questions - part3 - lab 9

22. "Testing the addition operation.
The result is: 7
Testing the subtraction operation.
The result is: 5
All tests passed." is the message given. i don't really believe it really
passed though.

23. In the concol, it gives a semi-red text saying "calcEngi1.testPlus()
returned int 1". It also gives a pop-up stating that the result of
calculating 3+4, then shows the returned value of int 1. After calling
the method once more, the returned value shifts from 1 to 7, with 7 being
the correct answer to 3+4. 7 thus should always be the value of that
operation.

24. the first call to testMinus gives out the right answer for an
operation of 9-4, 5. However, after the second call, the returned value
shifts from 5 to -13. -13 being an incorrect value for 9-4.

25. when looking at the testMinus method code, I did get some questions 
about the methods and the way of calculating. The method TestMinus seemed
a little enifficient, so I was wondering if there was a way to make better.
Checking each method and how to make it less naive.

26. 

Initial State:      0   0   ' '
clear:              0   0   ' '
numberPressed(3);:  3   0   ' '
numberPressed(4);:  4   0   ' '
equals();:          4   4   ' '
getDisplayValue();: 4   4   ' '

Since there is no operator, the equal value is the latest number pressed
(numberPressed(4))

27. Yes, because previousOperator method doesn't do anything wrong when
the operator is null.

28. No, it doesn't clear everything, it only clears dysplayValue.
Consequently, the calculation is false on the second call.

29. Changes in the clear method should be made, it should now clear
the previousOperator to ' ' and the leftOperand to 0 in addition.

30. The result should be 6. Yes, the engine does everything correctly. 


