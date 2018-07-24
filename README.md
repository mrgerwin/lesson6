# lesson6
List, Tuples, For Loops

We are going to make a prime factorization program.  The user should be able to type in an integer and the program will go through a list of prime numbers and see if it is divisible by any of the prime numbers.  It will store the prime numbers and at the end display them as the prime factors of the user’s number.

In PrimeFactorization.py you will find a tuple called primeNumbers which contains the set (2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47, 53, 59, 61, 67, 71, 73, 79, 83, 89, 97, 101, 103, 107, 109, 113, 127, 131, 137, 139, 149, 151, 157, 163, 167, 173, 179, 181, 191, 193, 197, 199)

Use an input statement to ask the user for their number.  Hard type the input as an integer.

Make an empty list that will store the factors.

Make a for loop that will run for each number in primeNumbers.  It will:
1. Use modular division (%) to check to see if there is any remainder when you take the user’s number divided by number from the primeNumbers.
2. If userNumber % primeNumber == 0 then you want to append that number to the factors list.
3. If userNumber % primeNumber is not 0 then you want to do nothing and keep looping through the for loop.
4. Once the for loop finishes, you will want to print all of the numbers that are factors of the user’s number.

### Debug the program and make sure that it works for these user numbers:
* User Number 10,  Factors = 2 and 5
* User Number 216, Factors = 2 and 3
* User Number 14527, Factors = 199 and 73
* User Number 1814263, Factors = 11, 23, 71, 101
* User Number 41, Factor = 41
* And any other number should work as well

Keep in mind that this program is limited in that it only contains the primes between 0 and 200.  Also if a user doesn’t enter an integer, then it will crash.

###Discussion Questions:

1. Why might the programmer choose to use a tuple for primeNumbers but a list for the factors list?
2. Describe how many times the for loop has to loop.  Why does it have to loop that many times?
3. For the first test case 10, 10 is smaller than most of the prime numbers.  What will the modular division return when the prime number is bigger than 10?  Why?
4. Humans might be faster in some cases than this program.  In what case would a human be faster?  Why?
