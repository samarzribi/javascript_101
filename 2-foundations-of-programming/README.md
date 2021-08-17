# Part II: Foundations of Programming

*Note: Before getting started on these exercises, please be certain that you've read through the root [README.md](../README.md) file in this repository.*

## Exercises

### Basic Requirements

#### Numbers

1. Enter the following expressions into your console.

   ```js
   1 + 2
   3 * 5
   5 / 4 - 13
   5000 * 234
   1073 / 57 + 200
   ```

2. Why are the values produced by the following two expressions different? What
   are they?

   ```js
   <!-- the secande inside parenthèses , every operation calculated by itself first  -->
   3 + 2 * 4 - 1
   (3 + 2) * (4 - 1)
  
 ```js

5. Try the following expressions in the console:

   ```js
   6 % 2
   42 % 10
   5 % 2
   6 % 3
   7 % 4
   100 % 12
   ```

   What is the significance of the result? How does the `%` (modulus) operator
   work?
 <!-- for exemple %2 it still devide the number by 2 until the number reach 0 or 1 then it return the rest  -->
6. Try the following:

   ```js
   3 % 2
   4 % 2
   5 % 2
   6 % 2
   ```
 ```js
   What do the results tell you about the first operand to the modulus operator?
// when we divide the 3 by 2 the rest is 1 so the result it will be 1
#### Strings

1. Write a string that represents your full name.
   'Samar  Zribi'
2. Write a string that represents your favorite food.
 'Pizza'
3. Use the `+` operator to combine (known as *concatenation*) two or more
   strings, *e.g.*:
"Name :" +" "+ "samar zribi" +" "+ "best food :" +" "+ 'Pizza'
   ```js
   // Your first and last names
   "John" + " " + "Doe"
   ```js

   // + Your first and last names (as shown above)
"Samar" + " " + "Zribi"
   // + Your best friend's full name
    "Haifa" + " " + "oueslati"
   // + Your home town, state and country


// 4. Fix the errors in the following strings:

   'Where are all the quotes?'
   'hmm something is not right'
   'Do other  * operators work with string concatenation?'
