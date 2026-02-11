Experiment 6: Python program to understand the basics of conditional statements 
Aim:To understand the basics of conditional statements in python 
Theory:
  if statement is the starting point and the simplest form of a conditional. It executes its code block only if its condition is True. 

  elif allows you to check multiple conditions sequentially if the preceding if or elif conditions were all False.

  else statement is a "catch-all" or fallback option that executes its code block if none of the preceding if or elif conditions are True. An else block does not take a condition. 
Algorithm:

I-->Algorithm to Check if a Number is Positive, Negative, or ZeroStartInput: 
1)Ask the user to "Enter the value of x" and store it in integer variable x.

2)Check 1: If x is greater than 0 ($x > 0$):Output: Print "number is positive".

3)Check 2: Else, if x is exactly equal to 0 ($x == 0$):Output: Print "number is 0".

4)Default: Else (if x is less than 0):Output: Print "number is negative".

5)Stop


II-->Algorithm to Check if a Number is Even or Odd:
1)Start

2)Input: Ask the user to "Enter the value of x" and store it in integer variable x.

3)Condition: Calculate the remainder of x divided by 2 (x % 2).

4)True Case: If the remainder is equal to 0:

5)Output: Print "number is even".

6)False Case: Else (if remainder is not 0):

7)Output: Print "number is odd".

8)Stop




III-->Algorithm to Identify the Greatest of Three Numbers
1)Start

2)Input: Read three integer values into variables a, b, and c.

3)Check A: If a is greater than or equal to b AND a is greater than or equal to c:

4)Output: Print "A IS GREATER".

5)Check B: Else, if b is greater than or equal to c AND b is greater than or equal to a:

6)Output: Print "B IS GREATER".

7)Check C: Else (if neither A nor B is the greatest):

8)Output: Print "C IS GREATER".

9)Stop



IV-->Algorithm to Print Grade (Single Subject)
1)Start

2)Input: Read the marks for one subject into variable sub1.

3)Check Grade A: If sub1 is greater than or equal to 90:

4)Print "a grade".

5)Check Grade B: Else, if sub1 is greater than or equal to 75:

6)Print "b grade".

7)Check Grade C: Else, if sub1 is greater than or equal to 60:

8)Print "c grade".

9)Check Grade D: Else, if sub1 is greater than or equal to 40:

10)Print "d grade".

11)Check Grade F: Else (if marks are below 40):

12)Print "f grade".

13)Stop



V-->Algorithm to Calculate Average and Overall Grade
1)Start

2)Input: Read marks for three subjects into variables sub1, sub2, and sub3.

3)Calculation: Calculate the average: $average = (sub1 + sub2 + sub3) / 3$.

4)Output: Print the value of average.

5)Determine Grade:If average >= 90: Print "a grade".Else, 
if average >= 75: Print "b grade".
Elif average >= 60: Print "c grade".
Elif average >= 40: Print "d grade".
Else: Print "f grade".

6)Stop



VI-->Algorithm to Check for Leap Year
1)Start

2)Input: Read the year to be checked into integer variable year.

3)Logical Condition: Check if the year meets the leap year criteria:

Is the year divisible by 4 AND NOT divisible by 100?

OR, is the year divisible by 400?

4)True Case: If the condition is true:

Print "The year is a leap year".

5)False Case: If the condition is false:

Print "tHE YEAR IS NOT A LEAP YEAR".

6)Stop



VII -->Algorithm to Check Date Validity and Increment Date
1)Start

2)Input: Read a date string (e.g., "10/12/2007"), split it by '/', and convert parts to integers dd, mm, yy.

3)Determine Max Days in Month (max1):

If month (mm) is 1, 3, 5, 7, 8, 10, 12: Set max1 = 31.

Else, if mm is 4, 6, 9, 11: Set max1 = 30.

Else (February): Check if yy is a leap year. If yes, max1 = 29; otherwise max1 = 28.

4)Validate:

If mm < 1 OR mm > 12: Print "Date is invalid".

If dd < 1 OR dd > max1: Print "Date is invalid".

5)Increment Logic:

  Month Change: If dd equals max1 AND mm is not 12:

  Set day dd to 1.

  Increment month mm by 1.

  Year Change: If dd equals 31 AND mm equals 12:

  Set day dd to 1.

  Set month mm to 1.

  Increment year yy by 1.

  Day Change: Else (normal day):

  Increment day dd by 1.

6)Output: Print the new incremented date (dd, mm, yy).

7)Stop



VIII-->Algorithm to Check if a Character is a Vowel
1)Start

2)Input: Read a character from the user into variable ch.

3)Search: Check if ch exists inside the list of vowels: ('a','e','i','o','u','A','E','I','O','U').

4)True Case: If ch is found in the list:

5)Print "The character is a vowel".

6)False Case: If ch is not found in the list:

7)Print "The character is a consonant".

8)Stop



IX-->Algorithm to Calculate Salary with Allowances
1)Start

2)Initialize: Set HRA = 0 and DA = 0.

3)Input: Read the basic salary.

4)Determine Slab:
    Slab 1: If basic <= 10,000:
            HRA = 20% of basic.
            DA = 80% of basic.
    Slab 2: Elif basic $\le$ 20,000:
            HRA = 25% of basic.
            DA = 90% of basic.
    Slab 3: Else (if basic > 20,000):
            HRA = 30% of basic.
            DA = 95% of basic.

5)Calculate Gross: gross_salary = HRA + DA + basic.

6)Output: Print the calculated values for HRA, DA, and Gross Salary.

7)Stop



X-->Algorithm to Calculate Income Tax
1)Start

2)Input: Read annual income into variable income.

3)Determine Tax Bracket:
    a)No Tax: If income < 250,000: Set tax = 0.
    b)Bracket 1 (5%): Elif income >= 250,000 and < 500,000:Calculate tax on amount exceeding 250k: tax = (income - 250000) x 0.05.
    c)Bracket 2 (20%):Elif income >= 500,000 and < 1,000,000:Calculate fixed tax for first bracket + 20% on amount exceeding 500k: tax = (250000 \times 0.05) + (income - 500000) \times 0.2$.
    d)Bracket 3 (30%): Else (if income >= 1,000,000):Calculate fixed tax for previous brackets + 30% on amount exceeding 1M: tax = (250000 x 0.05) + (500000 x 0.2) + (income - 1000000) x 0.3.

4)Output: Print the calculated tax.

5)Stop


Conclusion:With this one can understand The fundamentals of conditional loop in python
