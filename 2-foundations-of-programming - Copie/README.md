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
3
15
-11.75
1170000
218.82456140350877
2. Why are the values produced by the following two expressions different? What
   are they?

   ```js
   3 + 2 * 4 - 1
   (3 + 2) * (4 - 1)
   ```
   due to the basics of math and the () operators the interpertor calculates this 2 expressions differently

3. Calculate 50 years in minutes using the console.
var hour = 60
var day = hour*24
var year = day*365
var years = year*50
console.log(years);
26280000
4. What is the percentage of letters in the english alphabet that are vowels (including y)? Use the
   console to find out.
var letters = 26;
var voy = 6;
var percent = voy/letters*100;
console.log(perccent); 
23.076923076923077
5. Try the following expressions in the console:

   ```js
   6 % 2
   42 % 10
   5 % 2
   6 % 3
   7 % 4
   100 % 12
   ```
   0
   2
   1
   0
   3
   4

   What is the significance of the result? How does the `%` (modulus) operator
   work?
% is the operator which returns the rest of the division operation;
6. Try the following:

   ```js
   3 % 2
   4 % 2
   5 % 2
   6 % 2
   ```
   1
   0
   1
   0

   What do the results tell you about the first operand to the modulus operator?
It reminded me of the boolean operator
#### Strings

1. Write a string that represents your full name.
"maroua beltaief"
2. Write a string that represents your favorite food.
"pasta"
3. Use the `+` operator to combine (known as *concatenation*) two or more
   strings, *e.g.*:

   ```js
   // Your first and last names
   "John" + " " + "Doe"
   ```

   + Your first and last names (as shown above)
   + Your best friend's full name
   + Your home town, state and country
"adem"+ "mrabet"
'ademmrabet'
"zied"+"jlassi"
'ziedjlassi'
"rades"+"ben arous"+"Tunisie"
'radesben arousTunisie'

4. Fix the errors in the following strings:

   ```js
   Where are all the quotes?
   'hmm something is not right"
   'Do other ' * 'operators work with string concatenation?
   ```
"where are all the quotes?"
"hmm something is not right"
"Do other '*' operators work with string concatenation?"