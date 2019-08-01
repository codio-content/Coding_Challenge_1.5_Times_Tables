## Skills required
Students will need to be able to:

 - Use while or for loops
 
## Advice
Before asking students to tackle this challenge you could demonstrate how to output the numbers from 1-100 using a loop. Some students should then be able to apply what they learn to this challenge. 

## Extension
The more able students can allow the user to choose the times-table and how many rows are shown. They could also use a delay (sleep) like in the first challenge.

## Solutions

12 times-table, 10 rows

    counter = 1
    while counter <= 10:
      print(counter, "x 12 is", counter * 12)
      counter = counter + 1
      
Improved version

    table = int(input("Enter table"))
    row = int(input("Enter rows"))

    counter = 1
    while counter <= row:
      print(counter, "x", table, "is", counter * table)
      counter = counter + 1