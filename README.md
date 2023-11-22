# TJ-Tasks-2023-Sheetal-Asthana
This Repository consists of my tasks of DSA.
I attempted tasks from DSA domain and i attempted six of them.

EASY

Question 1
1. In this task firstly I accepted an array from the user.
2. Then I created an empty array of the same size.
3. I took a variable and initialized it with the last index of the array.
4. After that I started a for loop from 0 to length and reversily stored the elements of the original array in the new array.
5. Then I printed the new array.

Question 2
1. I started this task by accepting an array from the user and the sum.
2. Then I used nested for loops, wherein i=0 and i<length-1 and j=i+1 and j<a.
3. Within the nested loops I checked if a[i]+a[j]==sum.
4. And if yes,then printed the values of a[i] and a[j] together in the form of pairs.

Question 3
1. I started off by accepting the array and the size from the user.
2. Then I used nested for loops, wherein i=1 and i<=n and within i I initialised f=0. j=0 and j<n-1.
3. Then I checked if from 1 to the size every number is present in the array or not using the above nested loops.
4. When a number isn't found in the array,
5. I printed it with the statement "Missing number".

MEDIUM

Question 2
1. Firstly I accepted two numbers from the user and then accepted the operation to be performed.
2. Using Switch case, I checked the operation.
3. Then I performed the following Operation and stored the result in a variable.
4. I printed the result.
5. In case the user inputs an operation that does not exists, the program by default returns "Wrong Choice".

HARD

Question 1
1. I started off this task by creating a function isPrime(int x) that checks and returns true if a number is prime and false if a number is composite.
2. Then I accepted the interval range from the user.
3. I started a for loop from the start to the end of the range.
4. I created an object of a class and then called the function isPrime(int x) to check whether the number is prime or not.
5. If the function returned true, then I printed the number.

Question 2
1. In this task I accepted a number from the user.
2. Then I converted the number to its reversed Binary form using a for loop by continuously adding the remainder of the number while diving it by 2 and adding it using the condition r*=10+d.
3. This way we received the reversed binary form of the given number.
4. Now we converted the received binary form into its respective decimal form by starting a loop and adding it using sum+=d*(Math.pow(2,c)), wherein d contains the extracted digits of the binary form and c consisted of power.
5. I updated c by 1 each time the loop executes.
6. Then I printed the number.
