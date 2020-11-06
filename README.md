# Decentralized NGO (D-NGO) 
> This is an [Ethereum](https://ethereum.org/en/) based [Decentralized application](https://blockchainhub.net/decentralized-applications-dapps/) that helps NGOs and Donors maintain accountability and [increase efficiency](index.png) .

### Problem
In almost every country in the world, there’s a profound desire for positive social change, but individuals feel disempowered to do anything to make progress towards it. What stops them?
* Financial leakage
* Middleman organizations
* Politization of NGOs
* Lack of Feedback and Social Support Suppresses Enthusiasm
* Lack of Commitment

### solution
* We are going to cut out the middleman organizations who are a relic of pre-internet days.
* People will no longer need to give money to a non-transparent intermediary when they could give it directly to groups on the ground who are ready to take direct action.
* We uses decentralized curation of proposals, and proposals that are approved have to show proof that they’ve taken the actions they outlined in their submission for funding, as well as reporting on the results. 
* Users will be able to track the proposal funding through the blockchain, and see concrete evidence of exactly what results their support achieved.



 > The donations can be used by community service, civil structure restoration and gadget building. 
 
 > Any NGO over the internet can create a project to raise donations.
 
 > The NGOs can receive donations from anyone on the internet, with an Ethereum wallet and the proper usage of
   these funds are then moderated by volunteers on the website called, Moderators.
   
 > Moderators validate completed withdrawals by the NGOs and award reputation tokens to the respective NGOs.
 
 > The NGOs are incentivized by tokens to keep submitting proof and perform valid transactions so that 
   they can do more withdrawals and of larger amounts.
   
 > The Moderator are incentivized by tokens for validating the NGOs



### Usage of [ERC20 Tokens](https://cointelegraph.com/explained/erc-20-tokens-explained)
   - Reputation Token (rep) - For NGOs to their work
   - Verifiers Token (vep)  - For Modatators to validating projects work
   
### Technology Stack
   - [HTML,CSS,Javascript](https://www.w3.org/standards/webdesign/htmlcss.html)
   - [Smart Contracts](https://www.ibm.com/blogs/blockchain/2018/07/what-are-smart-contracts-on-blockchain/)
   - [Web3 package](https://github.com/ethereum/web3.js/)
   - [Metamask Wallet](https://medium.com/@seanschoi/what-is-metamask-really-what-is-it-7bc1bf48c75)
   - [Ganache](https://www.trufflesuite.com/docs/ganache/quickstart)



### How it works
 - Project creation will happen by NGOs.
 - Donors will donate.  
 - NGOs will spend money accordingly with valid proof.
 - Modarators will validate the NGOs proof.
 
 ### Steps to install 
 1. Clone files
 
 2. Install nodemodules(NPM) in currect working directory
 
 ```shell
 $ sudo npm install
 ```
 
 3. [Install ganache and press Quickstart](https://youtu.be/3PBR4r9aKSg)
 
 4. [Install Solidity compiler](https://solidity.readthedocs.io/en/v0.5.3/installing-solidity.html)
 
 5. [Install Web3 package](https://www.npmjs.com/package/web3)
 
 6. Compile and migrate solidity code
 
 ```shell
 $ sudo truffle migrate
 ```
 7. Runing in lite server
 
 ```shell
 $ sudo npm run dev
 ```




