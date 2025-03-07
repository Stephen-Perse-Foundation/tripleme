Haskell has built-in functions, but you can write your own. Function names must start with a lowercase letter because names that start with an uppercase letter are reserved for constructors.
Copy in the following code into a new Haskell .hs file:
tripleMe x = x * 3
You have created a function called “tripleMe”.
Load the file by typing :l <filename>.hs  into the GHCi prompt (see Appendix for examples).
Then, test the tripleMe function with the argument 10 like so: tripleMe 10

Q1. Write a function doubleAdd that takes two values, doubles each of them, and adds them together.
Start with: doubleAdd x y = 

Write it above and then test it in the interpreter.

Here is an example of a recursive function to add up the numbers from 0 to n:
sumTo n
  | n == 0 = 0
  | otherwise = n + sumTo (n-1)

Q2. Write a function factorialMe that takes a value and find the factorial of it (i.e., n!). Write it on the lines below then test it in the interpreter with the value 100. 
