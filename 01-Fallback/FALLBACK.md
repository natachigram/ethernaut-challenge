# Ethernaut Challenge #01 Fallback

## Ethernaut challenge #01 (Fallback) Solution

Ethernaut is an online platform that provides security challenges for Ethereum smart contracts. The first challenge in Ethernaut is designed to test the user’s knowledge and skills in identifying and exploiting vulnerabilities in smart contracts. In this challenge, users are required to take control of a vulnerable smart contract and modify its behaviour. This article provides a detailed explanation of the vulnerability in the first Ethernaut challenge, as well as a step-by-step guide on how to solve it.

### The Vulnerability:

The vulnerability in the first Ethernaut challenge is a result of poor access control in the smart contract. The contract allows anyone to call the “fallback” function, which is used to modify the state of the contract. This means that anyone can call the “fallback” function and change the behaviour of the contract, without the need for proper authentication or authorization.

### Step-by-Stepq Solution:

* **Step 1: Sign up for Ethernaut**
    
    To participate in the Ethernaut first challenge, you will need to [sign up for an account on the Ethernaut platform.](https://ethernaut.openzeppelin.com/) You can do this by visiting the Ethernaut website and following the instructions to create an account.
    
* **Step 2: Connect to a web3 client**
    
    Once you have created an account, you will need to connect to a web3 client, such as MetaMask, to interact with the Ethereum blockchain. You will also need to have some Ether in your web3 client to participate in the challenge.
    
* **Step 3: Load the challenge contract**
    
    Next, you will need to load the challenge contract into your web3 client (MetaMask). To do this, click on the first Ethernaut challenge on the Ethernaut website, and then click on the “Load” button. This will load the challenge contract into your web3 client.
    
* **Step 4: Examine the contract code**
    
    Before attempting to solve the challenge, it is important to examine the contract code to identify any vulnerabilities. The contract code for the first Ethernaut challenge is available for review on the Ethernaut website.
    
* **Step 5: Transfer the ownership of the contract**
    
    To solve the challenge, you will need to transfer the ownership of the contract to your own Ethereum address. To do this, you will need to call the “fallback” function in the contract, which will allow you to modify the state of the contract and transfer ownership to your address.
    
* **Step 6: Confirm the success of the exploit**
    
    Once you have successfully transferred the ownership of the contract to your address, you can confirm the success of your exploit by checking the contract state. If the contract state has been changed and the ownership has been transferred to your address, then you have successfully solved the first Ethernaut challenge.
    

In conclusion, the first Ethernaut challenge provides a great opportunity to test your skills and knowledge in identifying and exploiting vulnerabilities in smart contracts. By following this step-by-step guide, you can successfully solve the challenge and improve your understanding of smart contract security.
