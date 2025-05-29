# Mars-small-Bank
The project demonstrates a short bank that stores 5 users with their passwords.
The users’s usernames, passwords, checking balances, and saving balances
are each stored on their respective arrays, and all share a common index based on
where they are positioned in the array. First, the user will be given a choice to
take, representing one of those functions. After selecting the create account
option, the user is prompted to create a username and a password that are 8
characters. Additionally, Their checking account and savings account balances will
be respectively initialized to $20 and $0. After creating an account, the user is
then able to use functions such as adding money, removing money, etc. When adding
money to an account, the user is prompted to log in with the username and password
they created. So will also be the case for removing money, transferring money, or
viewing account info. Two of the most common mini-functions used are
account_accessed, account_Type_Check. Account_accessed is used to check the user’s
entered username and password as they are logging in and compare it to their saved
credentials in memory, while account_Type_Check is used to figure out which type of
account the user desires to manipulate. Finally, the user can stop the program when
entering the exit code, 0 in the main menu.
