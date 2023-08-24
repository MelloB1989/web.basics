**JavaScript (JS) Exercises:**

1. **Alert**
   - *Question:* Display an alert with the message "Hello, World!".
   - *Solution:* 
     ```javascript
     alert("Hello, World!");
     ```

2. **Console Log**
   - *Question:* Log the message "This is a log message" to the console.
   - *Solution:* 
     ```javascript
     console.log("This is a log message");
     ```

3. **Variables**
   - *Question:* Declare a variable named "myName" and assign it the value "John".
   - *Solution:* 
     ```javascript
     var myName = "John";
     ```

4. **String Concatenation**
   - *Question:* Concatenate two strings "Hello" and "World" and display the result.
   - *Solution:* 
     ```javascript
     var result = "Hello" + " " + "World";
     alert(result);
     ```

5. **Conditional**
   - *Question:* Display "Adult" if the age is 18 or over, and "Minor" if under 18.
   - *Solution:* 
     ```javascript
     var age = 20; // example age
     if (age >= 18) {
       alert("Adult");
     } else {
       alert("Minor");
     }
     ```

6. **Array**
   - *Question:* Create an array with 3 colors: "Red", "Green", and "Blue".
   - *Solution:* 
     ```javascript
     var colors = ["Red", "Green", "Blue"];
     ```

7. **Loop**
   - *Question:* Display numbers 1 through 5 using a loop.
   - *Solution:* 
     ```javascript
     for (var i = 1; i <= 5; i++) {
       console.log(i);
     }
     ```

8. **Function**
   - *Question:* Create a function that adds two numbers and returns the result.
   - *Solution:* 
     ```javascript
     function addNumbers(a, b) {
       return a + b;
     }
     ```

9. **Events**
   - *Question:* Display an alert when a button is clicked.
   - *Solution:* 
     ```javascript
     document.querySelector("button").addEventListener("click", function() {
       alert("Button was clicked!");
     });
     ```

10. **DOM Manipulation**
   - *Question:* Change the text of a paragraph with the id "demo" to "New Text".
   - *Solution:* 
     ```javascript
     document.getElementById("demo").textContent = "New Text";
     ```

11. **Math Object**
   - *Question:* Generate a random number between 0 and 1 and display it.
   - *Solution:* 
     ```javascript
     var randomNumber = Math.random();
     alert(randomNumber);
     ```

12. **ParseInt**
   - *Question:* Convert the string "123" into a number.
   - *Solution:* 
     ```javascript
     var number = parseInt("123");
     console.log(number);
     ```

13. **Array Length**
   - *Question:* Determine the number of elements in the array ["apple", "banana", "cherry"].
   - *Solution:* 
     ```javascript
     var fruits = ["apple", "banana", "cherry"];
     console.log(fruits.length);
     ```

14. **String Methods**
   - *Question:* Convert the string "HELLO" to lowercase.
   - *Solution:* 
     ```javascript
     var str = "HELLO";
     var lowerCaseStr = str.toLowerCase();
     console.log(lowerCaseStr);
     ```

15. **Date Object**
   - *Question:* Get the current year using the Date object.
   - *Solution:* 
     ```javascript
     var currentDate = new Date();
     var currentYear = currentDate.getFullYear();
     console.log(currentYear);
     ```
