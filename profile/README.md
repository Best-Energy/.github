## Best Energy
#### BlockChain Based Energy Trading Platform
Best Energy is a peer-to-peer energy trading platform which can be used to trade energy in a decentralized, secure, efficient and transparent manner over the Ethereum blockchain.
Since the project comprises of different repositories for each component, this is the main Readme file for the project which connects each of these components and demonstrates the use of the application as a whole. 

We have 4 main components/repositories for this project:
 - [Blockchain Smart Contracts](https://github.com/Best-Energy/core)
 - [Oracle Services](https://github.com/Best-Energy/oracles-services)
 - [Trading Bot/User Application Backend](https://github.com/Best-Energy/trade_bot)
 - [Frontend Application](https://github.com/Best-Energy/best-energy-frontend)

### Prerequisites
In this section we demonstrate the prerequisites in order to run the application as a whole. 
Some additional requirements in addition to the ones mentioned below:

 - Node version: v14.8.0
 - npm version: 8.5.5
 - yarn version: 1.22.19

#### Install Ganache
- Download and install Ganache-UI which is a GUI based tool in order to test and simulate Ethereum blockchains locally and we are using it for the purpose of development. You can download it from [here](https://trufflesuite.com/ganache/).

- Once downloaded, follow the installation steps and launch the application and it should like like following <img src="https://github.com/Best-Energy/best-energy/blob/main/images/2.png" alt="MongoDB Configuration" width="600"/>

- After that you can either click on **Quickstart** or **New Workspace** in case you want to persist the blockchain transactions and accounts for later use. We recommend creating a new workspace and saving it.

- Now, you will have a blockchain backend up and running and you should reach to a screen as shown<img src="https://github.com/Best-Energy/best-energy/blob/main/images/3.png" alt="MongoDB Configuration" width="600"/>

#### Install Truffle
Install Truffle on your system globally. You can refer to the instructions for installation [here](https://trufflesuite.com/docs/truffle/getting-started/installation/).

#### Deploy Smart Contract
We now want to deploy our smart contract onto this Ganache blockchain that we set up in the previous step. We need to follow these steps for the same:

- Make sure that truffle is installed on your system globally and it can also be done by the following instructions [here](https://trufflesuite.com/docs/truffle/getting-started/installation/).

- Clone the [contract repository](https://github.com/Best-Energy/core/tree/master) and open a terminal in this repository

- Run the command `truffle migrate` in order to deploy the smart contract onto Ganache and make sure this runs without any errors and the contract is deployed successfully.


**Note**: By default Ganache listens on port 7545 of the sytem and it should automtically be found by Truffle. If this is not the case, you might need to uncomment and modify the ***development*** attribute in the truffle-config.js file and set the correct port and host there.
### How to run complete application?


#### Install MongoDB
-------- Pranav --------


#### Other project related resources:
Project Board:  https://github.com/Best-Energy/best-energy/projects/1

