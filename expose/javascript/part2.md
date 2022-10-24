1. 3 is printed because i is a var variable so it can be accessed anywhere within the function. Since the loop ends when i is equal to the length of prices, i is equal to 3.
   
2. 150 is printed because discountedPrice is a var variable so it can be accessed anywhere in the function. The last thing discountedPrice is assigned to before loop end is 300 * 0.5 = 150, so 150 is printed after the loop.
   
3. 150 is printed because the last thing it was assigned to was Math.round(150 * 100) / 100. Math.round rounds 1500 to the nearest integer which is still 1500. Divided by 100 is 150.
   
4. Returns the Array [50, 100, 150] because each of the initial values in the prices array is discounted by 50%, then rounded, then pushed onto the discounted array.
   
5. Error because i is a let variable and since it was declared in the for loop block it cannot be accessed outside of the loop.
   
6. Error because discountedPrice is a let variable declared in the for loop so it cannot be printed outside of the loop.
   
7. 150 is printed out because console.log is called in the same block as where let finalPrice is declared so there is no error. It prints out 150 specifically for the same reason as Answer 3 above.
   
8. Returns the Array [50, 100, 150] for the same reason as Answer 4. Changing var to let makes no difference in functionality.
   
9.  Error because i is a let variable so it can't be printed outside of its declaration block (the for loop)
    
10. 3 is printed out because length is assigned to the length of prices, which is 3.
    
11. The Array [50, 100, 150] is returned because each of the initial values in prices array is discounted by 50%, then pushed onto discounted array. No error is caused by having discounted being a const variable since it is not reassigned, but the array itself is being changed which is fine.
    
12. (a) student.name
    (b) student["Grad Year"]
    (c) student.greeting()
    (d) student["Favorite Teacher"].name
    (e) student.courseLoad[0]

13. (a) "32" since "3" is string, + is interpreted as concatenation, so 2 becomes "2"
    (b) 1 since - is math operator, so "3" becomes 3, and 3 - 2 = 1
    (c) 3 because null is coerced into 0, and 3 + 0 = 3
    (d) "3null" since "3" is string, + is concatenation, and null becomes "null"
    (e) 4 since true is coerced into 1, and 1 + 3 = 4
    (f) 0  since + is interpreted as addition, so false is coerced into 0 and null is coerced into 0
    (g) "3undefined" since "3" is string, + is interpreted as concatenation, so undefined becomes "undefined"
    (h) NaN since - is math operator, '3' becomes 3 and undefined becomes NaN, so 3- NaN = NaN

14. (a) true because "2" turns into 2, and 2 > 1
    (b) false because string comparison of first characters: '2' is not less than '1'
    (c) true because loose equality converts '2' to 2, and 2 == 2
    (d) false because strict equality does not type convert so 2 !== "2"
    (e) false because loose equality converts true to 1, and 1 != 2
    (f) true because Boolean(2) is true, and true === true

15. Loose equality == first converts to numerical type and compares, whereas strict equality === does not, immediately returning false if types not equal and then comparing values

17. It returns Array [2, 4, 6]. First you call modifyArray with args [1, 2, 3] and doSomething. An empty array is created to store the results. The for loop iterates 3 times, since length of input array is 3. Each element of input array is passed to doSomething (which doubles them). This is pushed onto the result array, which is returned after loop end.

19. 1 4 3 2