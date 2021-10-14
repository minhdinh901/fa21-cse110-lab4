1. Line 12 prints `3` because the `for` loop exits after `i` is set to `3` since the length of `prices` was 3 in this case. Also, since `i` was declared as a `var`, it is accessible anywhere in the function `discountPrices`, which allows line 12 to print the value of `i`.
2. Line 13 will print `150` because at the last iteration of the `for` loop, `discountedPrice` is calculated to be `150`, and since `discountedPrice` is a `var`, it can be printed by line 13.
3. Line 14 will also print `150` because at the last iteration of the `for` loop, `finalPrice` is calculated to be `150`, and since `finalPrice` is also a `var`, it can be printed by line 14.
4. The function `discountPrices` will return an array containing the discounted prices of each of the prices given in `prices`. In this case, the function returns `[50, 100, 150]` since each price has a 50% discount applied to it. 
5. Line 12 will throw an error since it is trying to access the value of `i`. However, `i` was declared in the scope of the `for` loop, so accessing `i` outside the `for` loop will cause an error.
6. Once again, line 13 will throw an error since it is trying to access the value of `discountedPrice` when `discountedPrice` was only declared within the scope of the `for` loop. 
7. Line 14 will print the last calculated value of `finalPrice`, which in this case is `150`. Since `finalPrice` is within the scope of line 14, no error is thrown. 
8. The function will return an array of all the discounted prices. Since a 50% discount is applied to `[100, 200, 300]`, the returned value is `[50, 100, 150]`.
9. Line 11 will throw an error since it is trying to access `i` outside of the `for` loop, and the scope of `i` is within the `for` loop only.
10. Line 12 will print the value of `length`, which is `3` in this case since the given `prices` array has 3 elements.
11. The function will return an array containing the discounted prices of `prices`. In this case, a 50% discount is applied to each of the items in `prices`, thus returning `[50, 100, 150]`. Line 8 in the function is acceptable by JavaScript since `discounted` is not being reassigned to a new value, rather an array function is being called. 
12. 
```
    A. student.name
    B. student["Grad Year"]
    C. student.greeting()
    D. student["Favorite Teacher"].name
    E. student.courseLoad[0]
```
13. 
```
    A. '32', the number 2 is concatenated to the string '3' to give 32
    B. 1, the string '3' is converted to the number 3, so 3 - 2 =1 
    C. 3, null is converted to the number 0, so 3 + 0 = 3
    D. '3null', null is converted to 'null' and is then concatenated to '3'
    E. 4, true is converted to 1, so 1 + 3 = 4
    F. 0, false is converted to 0 and null is also converted to 0, so 0 + 0 = 0
    G. '3undefined', undefined is converted to the string 'undefined' and is then concatenated to '3'
    H. NaN, '3' is converted to the number 3 while undefined is converted to the number NaN, so 3 - NaN = NaN
```
14. 
```
    A. true, '2' is converted to the number 2, so 2 > 1 is true
    B. false, in ASCII, '2' is greater than '1', so '2' < '12' is false
    C. true, '2' is converted to the number 2, so 2 == 2 is true
    D. false, 2 is a number while '2' is a string, which means their types are different, so 2 === '2' is false
    E. false, true is converted to the number 1, so 1 == 2 false
    F. true, Boolean(2) converts 2 to true since it is a nonzero number, so both types are the same and true === true gives true
```
15. The `==` operator will convert both values being compared to numbers if the types are different. If both types are strings, then `==` will perform string comparison. The `===` operator, on the other hand, does not perform type conversion. So if the types of the two data values being compared are different, the `===` automatically returns `false`. When `===` is used between two values of the same type, the appropriate method of comparision is used. 
16. See `part2-question16.js`
17. Each iteration of the `for` loop pushes a new element to `newArr`. The pushed element is obtained by calling the function `callback` with the value at `array[i]`. In this case, we pass in the array `[1, 2, 3]`, and the callback function passed in is `doSomething(num)`, which just returns the value of `num` multiplied by 2. Therefore, the returned value of `newArr` will be `[2, 4, 6]`.
18. See `part2-question18.js`
19. The code prints out:
```
1
4
3
2
```