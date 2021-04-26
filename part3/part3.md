1. The bug is that the data type of result is `string`, which will results in `num1` and `num2` being concatenated not added.
2. I would convert `num1` and `num2` to numbers before adding them and assigning the sum to `result` (see fix.png screenshot).
3. citylots.json
4. part2.js
5. 11.7 MB
6. 1.84 s
7. Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/90.0.4430.85 Safari/537.36
8. Apache
9. Tue, 26 Jan 2021 22:14:13 GMT
10. application/json 
11. `fetchData()`