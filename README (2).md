# Experiment 8
# Aim of Experiment: Study of For loops in Python
# Theory:
- A for loop in Python is a control statement used to repeat a block of code multiple times.  
- It is mainly used when the number of iterations is known or when you want to iterate over a sequence.    
- A for loop executes a group of statements for each item in a sequence.
- It works as-Python takes the first value from the sequence, Assigns it to the loop variable.    
   Moves to the next value and Repeats the process until the sequence is finished.  
- Important Features of for Loop-Used for sequences (list, tuple, string, range, etc.  
-  No need to manually update loop variable and Makes code simple and readable.
- For Loop with else-Python allows an else block with a for loop.
- Advantages of for Loop-Easy to use, Less chance of infinite loop, Clean and readable code and Works directly with collections.
## Algorithm 1: To print numbers from 1 to 5.
1.Start.  
2.Initialize a loop variable i to iterate from 1 to 5 using range(1,6).  
3.Repeat the following steps for each value of i.  
4.Print the value of i.  
5.Stop when the loop ends (after i = 5).  
6.End.  
## Algorithm 2: To print even numbers from 2 to 10 using for loop.
1.Start.  
2.Use a for loop along with the range function to generate numbers from 2 to 10 with a step of 2.  
3.Assign each generated number to a variable.  
4.Display the value.  
5.Continue until the range is exhausted.  
6.Stop.  
## Algorithm 3: To print Sum of first N numbers:
1.Start.  
2.Input a number n from the user.  
3.Initialize a variable total = 0.  
4.Start a loop from i = 1 to n (using range(1, n+1)).  
5.For each value of i add i to total, total = total + i.  
6.Repeat step 5 until the loop ends.  
7.Display the value of total as the sum.  
## Algorithm 4: 3x3 matrix display.
1.Start.  
2.Define a 3×3 matrix A with given elements.  
3.Initialize outer loop with i = 0 to 2 (for rows).  
4.For each row i, do the following:Initialize inner loop with j = 0 to 2 (for columns).  
5.Print the element at position A[i][j] with a space.  
6.Repeat until all columns of that row are printed.  
7.After finishing each row, print a new line.  
8.Repeat steps 4–5 until all rows are completed.  
9.End.  
## Algorithm 5: Multiplication of two 3x3 matrices
1.Start.  
2.Define matrix A (3×3).  
3.Define matrix B (3×3).  
4.Initialize result matrix Result with all elements as 0 (3×3 matrix).  
5.Use three nested loops:  Outer loop i from 0 to 2 (rows of A), Middle loop j from 0 to 2 (columns of B) and 
inner loop k from 0 to 2 (for multiplication and addition).  
6.For each position (i, j) in Result:Multiply corresponding elements→ A[i][k] * B[k][j].  
7.Add to Result[i][j] Result[i][j] = Result[i][j] + A[i][k] * B[k][j].  
8.Repeat until all rows and columns are processed.  
9.Print each row of the Result matrix.  
10.End.  
## Algorithm 6: To print all Prime numbers in given range.
1.Start.  
2.Set the range of numbers from 2 to 49 (using range(2, 50)).  
3.For each number num in this range, do the following:Check divisibility of num by all numbers from 2 to num-1.  
4.For each value i in range(2, num):If num % i == 0 num is not prime and Exit the inner loop using break,  
If the inner loop completes without finding any divisor (i.e., no break occurred), then:num is a prime number.  
5.Print num and display result.  
6.Repeat steps for all numbers in the range.  
7.End.  
## Algorithm 7: Printing a Right-Angled Triangle Star Pattern using for loop:
1.Start.  
2.Initialize a loop variable i from 5 down to 1(using range(5, 0, -1)).    
3.For each value of i, do the following:  
Print "" repeated i times "" * i.    
Move to the next value of i (decrease by 1 each time).    
4.Stop when i becomes 0.  
5.Display the result.  
6.End.    
## Algorithm 8a: Printing inverted triangle using for loop:
1.Start the program.  
2.Initialize a for loop using range(1,6) to control the number of rows.  
3.The loop variable i starts from 1.  
4.In each iteration, print "* " multiplied by i using print("* " * i).  
5.After printing each row, increase the value of i by 1 automatically.   
6.Repeat the process until i becomes 5.  
7.Stop the program.  
## Algorithm 8b: Printing non-inverted triangle of 7 lines using for loop:
1.Start the program.  
2.Initialize a for loop using range(1,8) to control the number of rows.  
3.The loop variable i starts from 1.  
4.In each iteration, print spaces " "*(7-i) to align the pyramid.  
5.Then print stars "* "*i using print(" "*(7-i) + "* "*i).  
6.Increase the value of i by 1 after each iteration until it becomes 7.  
7.Stop the program.  
## Algorithm 8c: Printing pryramidal triangle using for loop:
1.Start the program.  
2.Initialize a for loop using range(1,6) to control the number of rows.  
3.The loop variable i starts from 1.  
4.In each iteration, print spaces " "*(5-i) to align the pyramid.  
5.Then print stars "* "*i to form the pyramid pattern.  
6.Increase the value of i by 1 after each iteration until it becomes 5.   
7.Stop the program.  

# Conclusion:
A for loop in Python is used to iterate over sequences and execute a block of code repeatedly. It is simple, efficient, and widely used for processing data collections.
