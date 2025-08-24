# PARITY CHECKER
 In this program we can differentiate the input number is even or odd using python.
  
  ## Features
  Feature 1: It is used to find even or odd number.
  Feature 2: Identifying a number is even or odd helps in recognising number patterns,performing arithematic calculation more efficiently,solving problems in mathematics and in daily life by providing a fundamental classification for numbers.
  Feature 3: 
             a).Performance- For determining a number is even or odd efficiently and fastest method is using bitwise AND operator than modulo operator and there is no security issues .
             b).Security- Parity checks for data transmission have limitations. They can detect single-bit errors but fail if an even number of bits are corrupted, which can lead to undetected errors. This is a historical issue with parity bits as an error-detection code, but it is unrelated to determining the parity of a number within a program.
  Feature 4: 
            a).Integration-Nil
            b).Extensibility-The ability to determine a number is even or odd can be extended by encapsulating the logic reusable function as follows:-
               * Function Design: A simple function could take an integer as input and return true if it's even and false if it's odd, or vice versa.
               * Modulus Operator: This is implemented using the modulus operator (%). For a number n, n % 2 will be 0 if n is even, and 1 if n is odd.
               * Applications: This function can then be integrated into larger programs to handle various tasks, such as processing lists of numbers or validating user input, making it a more versatile
## Table of Contents
 An integer datatype is input using varaiable a.
 Conditional operator if is used to check the number a is even or odd using the condition a%2==0
  if true-An output is displayed with message even.(Note-f'{a}- formatted string literals, also known as f-strings)
  else False-An output is displayed with message odd.
  
   ************ THANK YOU ************
   
   # Summation of Natural Numbers from 1 to 50
 In this program we can add every input number from 1 to 50 using python.
  
  ## Features
  Feature 1: It is used to add every number from 1 to 50.
  Feature 2:Firstly, it demonstrates a core concept in arithmetic progression.
            Secondly, this summation is a common problem in educational settings, used to teach students about formulas, sequences, and problem-solving techniques.
            Finally, the concept of summing natural numbers has practical applications in computer science, particularly in algorithm analysis. For instance, calculating the time complexity of nested loops that iterate from 1 to n often involves summing natural numbers, making this calculation relevant for understanding the efficiency of algorithms
  Feature 3: 
             a).Performance- The most efficient and fastest method to find the sum of natural numbers from 1 to 50 is using the mathematical formula for the sum of the first $n$ natural numbers, which is n(n+1)/2.Applying this formula with n = 50, the sum is calculated as (50*51)/2=1275.This approach has a time complexity of $O(1)$, meaning it performs the calculation in constant time regardless of the input size, making it significantly faster than iterative methods like loops or recursion, which have a time complexity of $O(n)$.
             b).Security-However, a significant limitation arises when the sequence does not start from 1. In such cases, the formula must be adjusted.
  Feature 4: 
            a).Integration- Nil
            b).Extensibility-The summation of natural numbers from 1 to 50 can be efficiently calculated using the mathematical formula S=2n(n+1), where n is the last number in the sequence.
            Applying this formula, the sum is (50×51)/2=1275.
            This formula-based method is the most extensible approach as it provides a constant-time O(1) solution, regardless of the size of n, making it highly efficient for large numbers like 50.
            While loops or recursion can also be used to compute the sum, they have a time complexity of O(n), which is less efficient for large values of n
## Table of Contents
  An input value 0 is stored using varaiable sum because Neutral starting point: Zero doesn’t affect the sum. It’s the identity element for addition,Safe and predictable: It ensures the variable has a defined value before you begin adding to it and Avoids garbage values: In some languages (like C or C++), uninitialized variables can contain random data, leading to incorrect results.
  Range function is used and stored in variable n.
 A for loop is control flow statement it is used for iteration from 1 to 50.
 sum+=i or sum=sum+i. In this when i=1 then it get store in sum where initial value was 0.Now sum value is updated to 1 this process follows up until i value reaches to 50.
  An output is displayed with message (The sum of numbers from 1 to 50 is",sum) where  now sum is 1275.
  
 ************ THANK YOU *************
