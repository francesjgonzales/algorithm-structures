# algorithm-structures

Practice activity how to implement conditional and binary decision structures.

## Problem 1: Discount Eligibility

**Scenario:** You are tasked with creating a program to determine if a customer is eligible for a discount. The program should check the total amount a customer has spent and decide if they qualify for a discount.

### Instructions:

- Write a program that takes the total spending amount as input.

- If the customer has spent $100 or more, print `10% discount applied.`

- If the customer has spent less than $100, print `No discount.`

### Define the problem:

Write a program that determines if a customer is eligible for a discount by checking the total amount spent and decide if they qualify for a discount.

### Identify Key Processes:

1. Input the total spending amount.
2. Check the discount condition: The program needs to check if the customer is qualified for a 10% discount if they spent $100 and above on a single receipt.
3. Print a message based on the outcome.

### Decide on the algorithm structure:

**_Are there multiple conditions to check?_** No, there's only 1 condition: whether the customer is eligible for a 10% discount or not.
**Is the decision between 2 outcomes?** Yes, discount applied or not applied
**Does the problem involved classifying items into multiple categories?** No, there's only 2 possibilities

### Chosen Structure:

Use a conditional structure of IF/ELSE statement to check if the statement is true or false and make a decision after.

### Pseudocode for algorithmic structure:

- Step 1: Define a variable to store the customer's total amount spent. The statement `Create variable total_amount and set it to the value of the user input for "Enter the customer's total amount:"`

- Step 2: Use an if statement to check if the amount is $100 or higher. The line `IF amount is greater than or equal to $100 THEN` will check and evaluate based on specific condition.

- Step 3: Provide the output for when the condition is true. If the amount is $100 or higher, the line `DISPLAY to user "10% discount applied.` executes, displaying a message indicating eligibility.

Step 4: Use an else statement to handle the false condition. If the amount is less than $100, the line `OTHERWISE display to user "No discount".` The else statement will provide an alternative action.

### Pseudocode:

```
Create variable total_amount and set it to the value of the user input for "Enter the customer's total amount:
IF amount is greater than or equal to $100 THEN
    Display to user "10% discount applied".
OTHERWISE
    Display to user "No discount".
```

## Problem 2: Book Categorization

**Scenario:** A library needs to categorize books based on their genre. You need to develop a program that helps categorize each book correctly.

### Instructions:

- Write a program that takes the genre of a book as input.

- If the genre is "Fiction," print "Category: Fiction."

- If the genre is "Non-Fiction," print "Category: Non-Fiction."

- If the genre is "Science Fiction," print "Category: Science Fiction."

- If the genre does not match any of these, print "Category: Unknown."

### Define the problem:

Write a program that categorize each book according to genre based on Fiction, Non-Fiction, Science Fiction and Unknown.

### Identify Key Processes:

1. Input the title of the book.
2. Check book category: Multiple categories need to be checked to determine which category it is assigned to.
3. Print the outcome that corresponds to the category assigned.

### Decide on the algorithm structure:

- **Are there multiple conditions to check?** Yes, there are multiple conditions to check
- **Is the decision between 2 outcomes?** No, there's only 1 outcome which is the category of the book.
- **Does the problem involved classifying items into multiple categories?** No, it is a straight-forward check

### Chosen Structure:

Use a multiple conditional structure of IF/ELSE IF/ELSE statements to derive to the appropriate book category.

### Pseudocode for algorithmic structure:

- Step 1: Define a variable to store the customer's total amount spent. The statement `Create variable book_genre and set it to the value of the user input for "Enter the book title:"`

- Step 2: Use an if statement to check if the genre is fiction. The line `"IF the genre is "Fiction" THEN` will check and evaluate the multiple conditions.

- Step 3: Provide the output for each condition. For genre that is Fiction, the line `Display to user "Category: Fiction"` is executed. If the condition is not met, execute the line `"OTHERWISE IF genre is Non-Fiction, display to user "Category: Non-Fiction".` This pattern will be repeated for the remaining categories to ensure that all categories are checked.

- Step 4: Use an else statement to handle the false condition that don't meet the previous statements by executing the line `OTHERWISE display "Category: Unknown"` as the final step before ending the program.

### Pseudocode:

```
Create variable book_genre and set it to the value of the user input for `Enter the book title:`
IF book title is Fiction THEN
    Display to user "Category: Fiction".
OTHERWISE IF book title is Non-Fiction THEN
    Display to user "Category: Non-Fiction".
OTHERWISE IF book title is Science Fiction THEN
    Display to user "Category: Science Fiction"
OTHERWISE
    Display to user > Unknown.
```

## Problem 3: Even or Odd Number

**Scenario:** You need to create a program that determines whether a given number is even or odd.

### Instructions:

- Write a program that takes a number as input.

- If the number is even, print `Even number.`

- If the number is odd, print `Odd number.`

### Define the problem:

Write a program that identify if the number is odd or even.

### Identify Key Processes:

1. Input the number
2. Check if the number is odd or even by dividing the value by 2.
3. Print the outcome.

### Decide on the algorithm structure:

**Are there multiple conditions to check?** No, there's only 1 condition and that is to check if the number is odd or even.
**Is the decision between 2 outcomes?** Yes, there's 2 outcomes.
**Does the problem involved classifying items into multiple categories?** No, it is a straight-forward check

### Chosen Structure:

Use a conditional structure of IF/ELSE statements to derive to the appropriate book category.

### Pseudocode for algorithmic structure:

- Step 1: Define a variable to store a number. The statement `Create variable check_number to store the value of the user input. The line should read as "Enter a number:"`

- Step 2: Use an if statement to check if the number is even. The line `IF number is divisible by 2 THEN` will check if the condition is true.

- Step 3: Provide the output if the number is an even number, the line `Display to user, "Even number"` will be executed to very the value.

- Step 4: If the value don't meet the previous condition, use the line `OTHERWISE and display the output "Odd number"` as the final step before ending the program.

### Pseudocode:

```
Create variable check_number and set it to the value of the user input for "Enter a number:"
IF the number is divisible by 2 THEN
    Display to user "Even number"
OTHERWISE
    Display to user "Odd number".
```
