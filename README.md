# Joint Savings on Ethereum Blockchain

This solidity file establishes two joint savings accounts, the smart contract accepts two user addresses that are then able to control a joint savings account.


---

## Technologies

This project uses the Solidity Programming language in a solidity file (.sol)
    
    - solidity
    - Remix IDE

---

## Installation Guide

To install you will want to pull the entire Joint_Savings folder from github. Then follow the next steps
  1. Import joint_savings.sol into the Remix IDE
  2. Compile joint_savings.sol using Remix IDE
  3. Deploy the contract 



---

## How it works / Results

1) First the user will open the Remix IDE and import the joint_savings.sol file
2) Then the user will simply compile and deploy the contract using the Remix IDE


Here I used the ``` setAccounts ``` function to establish the two accounts that we join. 

![set accounts](https://user-images.githubusercontent.com/84096312/137646112-0a34ee47-d19c-4b8c-8aad-ce3a2d7a8d18.png)

Then I used the ```Deposit``` function to deposit ether (in units of wei) into the contract and used the ```contractBalance``` function to make sure the deposit worked

  Transaction 1: Deposit 1 ether as wei 
  
  ![transaction 1](https://user-images.githubusercontent.com/84096312/137646176-c8d06532-16f1-4977-8002-79a3a8764156.png)
  
  ![contract balance 1](https://user-images.githubusercontent.com/84096312/137646186-6cb78eaf-a029-4ee5-9a9b-49df57b6db6e.png)
  
  ![transaction 1 balance](https://user-images.githubusercontent.com/84096312/137646198-7d942e4c-b515-47a3-909d-12b71875d804.png)
  

  Transaction 2: Deposit 10 ether as wei
  
  ![transaction 2](https://user-images.githubusercontent.com/84096312/137646219-d4d5eb52-f788-42af-96ca-d4d2c41dcf76.png)
  
  ![contract balance 2](https://user-images.githubusercontent.com/84096312/137646224-81f37362-e383-4af0-b039-dcee3305f0b6.png)
  
  ![transaction 2 balance](https://user-images.githubusercontent.com/84096312/137646232-91252ccd-897e-4777-83e6-d6d0fb55a3e0.png)
  
  
  Transaction 3: Deposit 5 ether 
  
  ![transaction 3](https://user-images.githubusercontent.com/84096312/137646247-fdd668b2-37cb-4e09-b054-b8010a371afb.png)
  
  ![contract balance 3](https://user-images.githubusercontent.com/84096312/137646250-ed9d3d72-5867-4676-872c-155779f375bd.png)
  
  ![transaction 3 balance](https://user-images.githubusercontent.com/84096312/137646257-345ce5c5-0251-4d8b-a94a-ef86301d8711.png)
  


Next I used the ```Withdraw``` function to withdraw ether from the contract balance and put it into one of the two approved accounts. I used the ```contractBalance``` function to confirm the withdraw happened as well as ```lastToWithdraw``` and ```lastWithdrawAmount``` to confirm the correct amount went to the correct account

  Withdraw 1: Sending 5 ether to accountOne
  
  ![withdraw 5 account 1](https://user-images.githubusercontent.com/84096312/137646356-0f29986f-9439-4a2f-8a8f-fbd3ecb7f4c4.png)
  

  Withdraw 2: Sending 10 ether to accountTwo
  
  ![withdraw 10 account 2](https://user-images.githubusercontent.com/84096312/137646371-7a65f1af-c82b-4a03-8682-0461900e8e23.png)
  



---

## Usage

Overall it should be a very simple application to use, all you need to do is import the .sol file into the Remix IDE, compile and then deploy the contract. 

---

## Contributors

Colin Benjamin

Linkedin: [Colin Benjamin](https://www.linkedin.com/in/colinbenjamin/)
    
email: cbenjamin33@gmail.com

---

## License

(c) Copyright 2021 Colin Benjamin

Licensed under the MIT license:

    http://www.opensource.org/licenses/mit-license.php


Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
