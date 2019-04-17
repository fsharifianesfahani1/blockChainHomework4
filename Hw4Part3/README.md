# Homework 4

By: Farnoosh Sharifian Esfahani 

Step on How to Run the Program: 
1) Using the Remix using this link provided: http://remix.ethereum.org/#optimize=false&version=soljson-v0.5.0+commit.1d4f565a.js

2) open my Course.Sol file onto the remix IDE platform or copy paste it onto existing one, and name it Course.sol

Note: My code has been programmed to meet the Slodity 0.50 requirment. 
3) After opening the Courses.sol onto the IDE, you need to choose the compiler version 0.5.0+commit.1d4f565a so that it would match the program and run successfully. 
4) Compile the code

Steps in defining parameters with results obtained: 
	
    	You CLick to the run tab. 
    
    
Exercise 1) Run with parameters on setInstructor and getInstructors
- Deploy the code
- Copy the contract address from the account tab. 
- Under Deployed contracts, paste the address as string, along with integer and two names as strings like this example on setInstructor tab: 

On setInstructor (paste copied address as the first string): 
		
        "0xca35b7d915458ef540ade6068dfe2f44e8fa733c", 34, "Gary", "Simon"
        
- Click on getInstructors button and copy the provided address.
- Paste copied address onto the getInstructor tab 
- RESULTS: 

		Will show results like below: 
		0: uint256: 34
		1: string: Gary
		2: string: Simon
        
Exercise 2) Repeat by adding another instuctor with DIFFERENT account
- Deploy the code
- Choose a different on the accounts tab. (lets say second one) 
- Copy the contract address from the account tab. 
- Under Deployed contracts, paste the address as string, along with integer and two names as strings like this example on setInstructor tab: 

On setInstructor (paste copied address as the first string): 
		
        "0x14723a09acff6d2a60dcdf7aa4aff308fddc160c", 34, "Robert", "Smith"
        
- Click on getInstructors button and copy the provided address.
- Paste copied address onto the getInstructor tab 
- RESULTS: 

		Will show results like below: 
		0: uint256: 34
		1: string: Robert
		2: string: Smith

Exercise 3) Repeat by adding another instuctor but this time using countInstructors
- Deploy the code
- Choose a different on the accounts tab. (lets say second one) 
- Copy the contract address from the account tab. 
- Under Deployed contracts, paste the address as string, along with integer and two names as strings like this example on setInstructor tab: 

On setInstructor (paste copied address as the first string): 
		
        "0x14723a09acff6d2a60dcdf7aa4aff308fddc160c", 34, "Jackie", "Smith"
        
- Click on getInstructors button and copy the provided address.
- Paste copied address onto the getInstructor tab 
- RESULTS: 

		Will show results like below: 
		0: uint256: 34
		1: string: Jackie
		2: string: Smith
        
- Click on countInstructor button and you will see the result
			
            0: uint256: 1

