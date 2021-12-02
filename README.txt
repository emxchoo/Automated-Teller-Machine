Emily Ming Li Choo
README file 

CLASS DOCUMENTATION
Description of the class: Automated Teller Machine (ATM)
Class AutomatedTellerMachine contains data variables name and balance. 
User are able to deposit,withdraw, view the account balance. 

Description of the data variables:
- name are set to private variable self.__username
- balance are set to private variable self.__balance

Description of each methods:
- random.randint() returns an integer number selected element from the specified range. 
I need random.randint() in this program to generate the transaction number.

- append() adds a single item to the existing list. It does not return a new list of items but will modify
the original list by adding the item to the end of the list. 
I need append() in this program to append the accounts. 

DEMO PROGRAM DOCUMENTATION
Description of the demo program:
The program allows user to access their bank account with their ID number.
They will be able to withdraw, deposit, view balance and exit the program. 
Each selection will lead to different output.

Instructions on how to run the demo program:
First, program will ask user to input their ID number. It can be any ID number between 1000 to 9999. 
If the ID number is out of range, it will ask user to re-enter their ID number again.

Secondly, program will show a list of selection. 
User can enter their selection depending on what they intend to do. 
The selections are 1 - View Balance, 2 - Withdraw, 3 - Deposit and 4 - Exit.

If user choose 1 - View Balance:
Program wil show the user's balance. 

If user choose 2 - Withdraw:
Program will ask how much they want to withdraw.
It will ask to verify the withdrawal amount. 
If the withdrawal amount is greater than the balance they have in their account, it will pop out an error message. 
If not, user will be able to withdraw the amount smoothly and show the remaining balance. 

If user choose 3 - Deposit:
Program will ask how much they want to deposit.
It will ask to verify the deposit amount. 
It will show the deposit money and the total balance. 

If user choose 4 - Exit:
Program will have a farewell note, show their transaction number and exit the program. 

If user choose other options, other than 1 to 4, it will have an error message. 









