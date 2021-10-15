# Part 2

1. 
```
It will print 3 because i is declared with var, which is function scope meaning it can be accessed after the for loop. And there are 3 elements in the array, and thus i is 3
```

2. 
```
It will print 150 because discountedPrice is declared with var, which is function scope meaning it can be accessed after the for loop. And with the calculation, the last iteration gives the formula of: 300 * (1-0.5) = 150. 
```

3. 

```
It will print 150 because finalPrice is declared with var, which is function scope and it is declared outside the for loop meaning it can be accessed after the for loop. And with  the calculation, the last iteration gives the formula of: round(300*100)/100 which is 150. 
```

4. 

```
It will return an array values with: [50, 100, 150]. With the parameters given in the function, each value is discounted by 0.5 (50%) which is the second parameter, and thus with the initial price at [100, 200, 300], the corresponding result will be [50, 100, 150].
```

5. 
```
Error, i is a block scope variable, which means it does not exist outside of the for loop. Therefore, accessing it at line 12 will cause an error bc it is not defined there. 
```

6. 
```
Error, discountedPrice is declared with let, which is a block scope variable, which means it does not exist outside of the for loop. Therefore, accessing it at line 13 will cause an error bc it is not defined there. 
```

7. 
```
It will print 150 because finalPrice although is a block scoped variable, it was declared outside of the for loop, so accessing it after/outside the for loop is ok. And with the calculation, the last iteration gives the formula of: round(300*100)/100 which is 150. 
```

8. 
```
It will return an array values with: [50, 100, 150]. With the parameters given in the function, each value is discounted by 0.5 (50%) which is the second parameter, and thus with the initial price at [100, 200, 300], the corresponding result will be [50, 100, 150]
```

9. 
```
Error, i is a block scope variable, which means it does not exist outside of the for loop. Therefore, accessing it at line 11 will cause an error bc it is not defined there. 
```

10. 
```
It will print 3 because although length is a const variable, it was declared outside of the for loop, therefore, accessing its value on line 12 is ok. The prices array has a length of 3, which is why it will print 3. 
```

11. 
```
It will return an array values with: [50, 100, 150]. With the parameters given in the function, each value is discounted by 0.5 (50%) which is the second parameter, and thus with the initial price at [100, 200, 300], the corresponding result will be [50, 100, 150]
```

12. 
- 
```
student.name
```
- 
```
student['Grad Year']
```
- 
```
student.greeting()
```
- 
```
student['Favorite Teacher'].name
```
- 
```
student.courseLoad[0]
```

13. 
A. '32' Since javascript automatically convert 2 to '2'
B. 1 since javascript automatically convert '3' to 3
C. 3 since null is automatically converted to 0
D. '3null' since null is automatically convert ot the string 'null'
E. 4 since true is converted to number 1
F. 0 since javascript converts false and null to 0
G. 3undefined since javascript converts undefined to the string
H. NaN, a string cannot subtract undefined

14. 
A. True since '2' is converted to 2
B. False, with string comparison, javascript compares the first letter of the string, and if one is bigger, the comparison finishes, and 2 is greater than 1 so it returns false. 
C. True, '2' gets converted to number 2 for comparison
D. False, because === takes type into account. they are different types, so they are different. 
E. False, because true turns into 1 and 1 is not equal to 2. 
F. True, Since Boolean(2) is evaluated to true because Boolean(0) results in false. 

15. 
== is the regular comparison, and === is the strict comparison, where the regular comparison automatically converts type, and strict comparison does not convert type automatically. 

16. See `part2-quesion15.js`

17. The result will be `array [2, 4, 6]`, the callback function takes in a parameter `num`, and returns a value with `num*2`. In the `modifyArray` function, we saw an array being passed in, and for each element of that array, we call the callback function which multiplies the current value by 2, and the result of that is pushed into a `newArr`. Thus, the `modifyArray` returns an array where each element is each element from the original array times 2. Therefore `[1, 2, 3]` with `doSomething` returns: `[2, 4, 6]`

18. See `part2-quesion18.js`

19. 
```
1
4
3
2
```
