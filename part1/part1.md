### Part 1a.
1. values added: 20
2. final result: 20
3. values added: 20
4. The code returns an error because the scope of variable `result` is within the `if` block, unaccessible by line 13.
5. The code returns an error because on line 7 we are reassigning the `const` variable `result` to a new value.
6. The code returns an error because on line 7 we are reassigning the `const` variable `result` to a new value.

### Part 1b.
1. Console prints value of variable `i`, which equals 3 in this case.
2. Console prints value of variable `discountedPrice`, which equals 150 in this case.
3. Console prints value of variable `finalPrice`, which equals 150 in this case.
4. The function will return the `discounted` array, which equals `[50, 100, 150]` in this case. The function `discountPrices()` applies a specified discount, `discount`, to all prices in the `prices` array parameter.
5. The code causes an error because the scope of variable `i` is within the `for` loop, unaccessible by line 12.
6. The code causes an error because the scope of variable `discountedPrice` is within the `for` loop, unaccessible by line 13.
7. Console prints value of variable `finalPrice`, which equals 150 in this case.
8. The function will return the `discounted` array, which equals `[50, 100, 150]` in this case. The function `discountPrices()` applies a specified discount, `discount`, to all prices in the `prices` array parameter.
9. The code causes an error because the scope of variable `i` is within the `for` loop, unaccessible by line 11.
10. Console prints value of variable `length`, which equals 3 in this case.
11. The function will return the `discounted` array, which equals `[50, 100, 150]` in this case. The function `discountPrices()` applies a specified discount, `discount`, to all prices in the `prices` array parameter.
12. <ol type="A">
        <li><code>student.name</code></li>
        <li><code>student['Grad Year']</code></li>
        <li><code>student.greeting()</code></li>
        <li><code>student['Favorite Teacher'].name</code></li>
        <li><code>student.courseLoad[0]</code></li>
    </ol>
13. <ol type="A">
        <li>32 <br> The number 2 gets converted to the string '2' and concatenated with '3' (<code>+</code> operator converts all operands to a string if one operand is a string)</li>
        <li>1 <br> The string '3' gets converted to the number 3 (<code>-</code> operator converts all operands to a number)</li>
        <li>3 <br> <code>null</code> is converted to the number 0</li>
        <li>3null <br> <code>null</code> is converted to the string 'null' and concatenated with '3' (<code>+</code> operator converts all operands to a string if one operand is a string)</li>
        <li>4 <br> <code>true</code> is converted to the number 1</li>
        <li>0 <br> <code>false</code> and <code>null</code> are both converted to the number 0</li>
        <li>3undefined <br> <code>undefined</code> is converted to the string 'undefined'</li>
        <li><code>NaN</code> <br> <code>undefined</code> is converted to the value <code>NaN</code>, which as an operand will cause the expression to evaluate to <code>NaN</code></li>
    </ol>
14. <ol type="A">
        <li><code>true</code> <br> The string '2' is converted to the number 2 (comparing different types converts operands to numbers)</li>
        <li><code>false</code> <br> The strings '2' and '12' are compared lexicographically ('2' > '12')</li>
        <li><code>true</code> <br> The string '2' is converted to the number 2 (comparing different types converts operands to numbers)</li>
        <li><code>false</code> <br> The <code>===</code> operator checks equality without type conversion (the number 2 is not the same as the string '2')</li>
        <li><code>false</code> <br> <code>true</code> is converted to the number 1 (comparing different types converts operands to numbers)</li>
        <li><code>true</code> <br> <code>Boolean(2)</code> evaluates to <code>true</code> which is strictly equal to the value <code>true</code></li>
    </ol>
15. The `==` operator checks equality with type conversion whereas the `===` operator checks equality without type conversion, also known as strict equality. 
16. (see part1b-question16.js file)
17. The function `modifyArray()` will return an array whose content is `[2,4,6]`. The function creates an array, populates it by calling `callback()` on all elements in the parameter `array` and pushing the returned values to the created array, and finally returns the created array. In this case, `callback()` was the function `doSomething()`, which simply returns its argument multiplied by 2, so `modifyArray()` returns a copy of `array` with all elements multiplied by 2.
18. (see part1b-question18.js file)
19. 1 <br> 
    4 <br>
    3 <br>
    2