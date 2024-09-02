# **Customer Banking System**


## **Overview:**

This project is a simple customer banking system that allows users to calculate and track interest earned on Savings and Certificate of Deposit (CD) accounts. The program prompts the user to enter their account details, calculates the interest earned over a specified number of months, and displays the updated account balance along with the interest earned.

**Features**

Savings Account Interest Calculation: Users can enter their savings account balance, annual interest rate, and the number of months to calculate the interest earned.

CD Account Interest Calculation: Users can enter their CD account balance, annual interest rate, and the number of months to calculate the interest earned.

Updated Balances: The program displays the updated account balances after interest is applied.


## **Getting Started:**

**Prerequisites**

Python 3.x installed on your local machine.

**Running the Program**

Clone the Repository

Navigate to the Project Directory

Run the Program by typing python customer_banking.py on your terminal

**Follow the Prompts:**

The program will ask for the balance, interest rate, and duration in months for both Savings and CD accounts.

After entering the details, the program will calculate the interest and display the updated balances.

**Code Source and Location:**

Account.py: Contains the Account class, which provides methods to set and manage account balances and interest.

Savings_account.py: Contains the create_savings_account function, which handles interest calculation and balance updates for savings accounts.

Cd_account.py: Contains the create_cd_account function, which handles interest calculation and balance updates for CD accounts.

Customer_banking.py: This is the main script that interacts with the user. It imports the necessary functions from savings_account.py and cd_account.py, and manages the program flow.

**All code files are located in the root directory of the repository.**

