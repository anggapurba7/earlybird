# earlybird
Register Smart Contract Creation and Deployment Task
 


Create a smart contract called “Register”.


The contract must have:


Deployment & Verification:

The state variables must be public and have the same order and names.
The contract must be deployed and verified in Sepolia testnet


State variables:

“github”: a public string variable.
“owner”: a public address variable
“Referral”: a struct containing:
Address
String
“referrals”: an array of type “Referral” called which will contain your future referrals.

Functions:

Constructor: Initializes the contract with the following steps:
Initialize your GitHub name to the github state variable.
Initialize your address as the owner of the contract.
Optional (If you want to participate in the referral campaign):
Function “addReferral”:
External or Public
Only the owner of the contract can call this function
Create a new struct “Referral”  and add the “Referral” to the array of referrals.
Function “totalReferrals”:
Public view or External view
Return the total number of referrals in this contract.

Once the task is completed, please leave the link to the verified contract on Sepolia Etherscan, in your Early Bird Application form.




 
