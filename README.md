# SPLITIT
This source code is of a application which will help you to split the expenses within your   family, friends or group of people.
###################################################---SPLITIT---###################################################



How to Use:-
1. Add the all the group members with their names.
2. Start putting the expenses details.(The one who is spending money and the amount).
3. This will add the 1 transaction in the data.
4. Point 3 will be repeated multiple times and may be by all users.
5. Final calculate the expenses button will help you to get the "who owes how much money to whom".


Techincalities :-

- This is the first version of the SPLITIT.
- Contains 2 tables. viz. Members and Calculations.
- Members will contain only the list of the Memebers who are in a group.
- Calculations will contain the transactions which will be taking place as the members start addin the expenses.

--------------
Members Table
--------------
ID		Name
--------------
1		A
2		B
3		C
4 		D	
-------------


-------------------------------------------
Calculations Table
-------------------------------------------
Trans ID	Name	Amount	Owes_to_User
1			B		25			A
2			C		25			A
3			D		25			A 	
-------------------------------------------

#Above table depicts one example how the data will be added.
- Suppose there are 4 group memebers (A, B, C, D)
- And the memeber A spneds 100rs for some item for all other users.
- Then in the Calculations table 3 entries will be addded.
- Which will tell that all three memebers A, B , C owe 25rs to A.
- In similar manner when B will spend money on behlf of others then, A, C and D will owe respective calculated amount
  and that will be added accordingly. 
- And, when at the end of certain time period all the transactions in the Calculations table will be parsed and then by calculating 
  the diffference amount the final amount will be calculated that who owes how much money to whom
  
###################################################---SPLITIT---###################################################






