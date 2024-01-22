# Compound Interest Calculator
Here is an explanation of what this Python code in a README file is doing:

1. `p = float(input("How much do you want to deposit?:")`

- It is taking user input for deposit amount as a float (decimal number). The input prompt asks "How much do you want to deposit?"

2. `n = 12  # months in a year`  

- Sets n to 12 to represent 12 months in a year for use in monthly compound interest calculations

3. `r = 0.08 # interest rate of 8%`  

- Sets the annual interest rate r to 0.08 (8%) 

4. `t = int(input("How many years do you want to store your bread: ")`  

- Prompts user for input on years money will be stored/invested, converts to integer

5. `(1 + (r/n))`  

- Calculates the monthly interest rate by dividing the annual rate r by number of months n

6. `monthly_compound = n * t`  

- Calculates number of total months money will be invested for based on years input by user 

7. `amount = p * float(inside) ** int(monthly_compound)`

- Calculates final amount after compound interest by raising the monthly interest to power of number of months and multiplying the initial deposit

8. `final_amount = print(f"Your amount is: £{amount:,.2f}.")`

- Prints out final amount formatted with £, commas, and 2 decimal places.

Overall, it allows a user to input a deposit amount, years, and calculates the final amount earned after monthly compound interest. The comments explain what each variable represents.
