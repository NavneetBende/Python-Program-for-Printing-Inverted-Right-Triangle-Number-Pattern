Print Inverted Right Triangle Number Pattern
In this Python Program, we will be discussing about how to write a program to print Inverted Right Triangle Number Pattern. In this pattern, there are n numbers of rows are present which is entered by user. We will use ‘count’ variable for printing number decreasing order. First increase the count variable to the max value.Then, With every iteration of for loop, we will decrease the count variable by 1. So, User have to enter a single value, that will be determine as a number of rows and columns of the pattern. With the help of “for loop”, we will print the Inverted Right Triangle Number Pattern.

Python Program for Printing Inverted Right Triangle Number Pattern
Working:
Step 1. Start

Step 2. Take number of rows as input from the user and stored it into num.

Step 3. Take a variable ‘count’ and initialize it as 0.

Step 4. Run a Reverse for loop starting from num to 0 value.

Step 5. Inside above for loop, increase count variable by i.

Step 6. Run a loop ‘i’ number of times to iterate through all the rows which is Starting from i=0 to num.

Step 7. Run a nested loop inside the main loop for printing spaces which is starting from j=0 to num-i.

Step 8. Print ‘count’ inside the nested loop for each row.

Step 9.Inside above Nested for loop, Decrease count variable by i.

Stop 10. Move to the next line by printing a new line using print() function.

Step 11. Stop

Python Program:
num = int(input("Enter the Number: "))

count = 0
for i in range(num, 0, -1):
    count = count + i

for i in range(0, num):
    for j in range(0, num-i):
        print(count, end="")
        count = count-1
    print()

