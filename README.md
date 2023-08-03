# Metacrafter_Polygon_Module_3
This is project of Polygon Module 3
# Description of Project
In this project, I designed a circuit which is deployed to Mumbai Network

# Circuit and Question
Check the circuit.png file in repository; you will get the circuit image!
![Uploading Assessment_b05f6ed658.png…](https://authoring.metacrafters.io/assets/cms/Assessment_b05f6ed658.png?updated_at=2023-02-24T00:00:37.278Z)

Imagine that you wake up, check your email, and you see an interesting task: Polygon is asking you to design a new zkSNARK circuit that implements some logical operations. You need to implement the circuit and deploy a verifier on-chain to verify proofs generated from this circuit

For this project, you will create a circuit using the circom programming language that implements the following logical gate:
Your goal is to prove you know the inputs A (0) & B (1) that yield a 0 output.

# Explaination of What I did.
I formulated the code according to circuit
## Code:
Use https://github.com/shrutinarad16/Metacrafter_Polygon_Module_3/blob/main/circuits/multiplier/circuit.circom this link for accessing code.

Or, Access circuits folder where you have to go in multiplier and finally visit circuits.

## Installations and commands on Terminal
I used gitpod.io for this project
Commands are mentioned below!!
Follow below order
1) npm i
2) npx hardhat clean (any artifact file is generated then it shouuld be deleted as we are generating new solidity file for compilation)
3) npx hardhat circom (this will install circom)
4) npx hardhat compile (this will generate solidity file)
5) npm install dotenv (install environment for your private info)
6) npx hardhat run scripts/deploy.ts --network mumbai  (this will deploy your contract on mumbai network)

 ## Precaution
  1) Create env file which will store private keys as some information should be hidden from public.
  2) First deploy your circuit on local network
  3) For deployment on local host, use following command: npx hardhat run scripts/deploy.ts
  4) if your logic is deployed properly then definitely it will deploy on mumbai network

### Connection with metamask
1) https://chainlist.org/chain/80001 (this site will connect your metamask to mumbai network).
2) https://mumbaifaucet.com/ (this will give you faucet for transaction)

# Result
It will give you **TRUE** as output on terminal

# Loom Video

   
   
 
