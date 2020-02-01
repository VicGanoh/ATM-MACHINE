# Java-Exercise
ATM Machine Outline
a. The system should show the following top menu. Write a function that simply displays this menu
1.Sign in
2.Balance
3.Deposit
4.Withdraw
5.Exit

b. We assume that this ATM machine hold accounts for 10 people. So, use an array to store client's account balance. Suppose all accounts start with initial balance of $1000.
With this structure in mind we use array indices(0,1,2,3,4,5,6,7,8,9) as user's account number(a single digit) and array values as balances.The user must first sign in to use the machine by entering their account number(0,1,2,3,4,...9). If the user enters an incorrect account number the system should give a warning message and display the menu again.

c. User can request account Balance by entering option 2. Write a function to complete the ff task: 
The system displays the current balance

If balance is below $100, the system should display the message "Low Balance".

Then go back to the Top menu.

d. If option menu 3, which is deposit is selected, write a function to complete the task: 
the system should propmt the user to enter the amount. The ATM machine valiadates the input by verifying that the input is positive.

If not, a warning message is displayed "invalid amount", and the user is prompted to try again, if amount is negative again, the deposit operation is terminated and the top menu is dispplayed again

if amount is positive, the Balance is updated.

e.If option 4 , which is Withdraw is selected, write a function to complete the task: 
the ATM machine prompts the user to enter an amount, then checks if user has sufficient balance.

if the balance is insufficient, then a warning message along with user's balance is displayed.

The user is prompted to enter a new amount for the second time, if amount is OK, withdraw operation is completed and balance is updated and menu is displayed.

if balance is still insufficient, withdraw operation is terminated and the top menu is displayed.

f. For option exit, write a function that displays a "Goodbye" message and exits/log out from user's account. The ATM machine's menu is displayed, however this time the next user must sign in by entering his account number(0,1,2,...9).
