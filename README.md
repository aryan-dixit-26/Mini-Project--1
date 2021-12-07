                                            Step to be followed to develop the website: 
1. First we need to write the smart contracts for the web application. Then we have to compile it using the Truffle. 
2. After compiling we need to perform the moderation, so that over smart contracts can be transferred to the local blockchain. 
3. After migrating we start the local deployment server and perform the development process on that very server. 
4. i) First we write the smart contract, for adding a candidate then, casting a vote, then deploying the standings of the candidates. 
ii) After this we need to call the artifacts of the solidity file that we just wrote, so that migrations can be performed on the blockchain. 
iii) Having done all this the last task in hand is to connect the blockchain with the frontend User Interface for which we use Web3 Js. 
5. i) A basic HTML boilerplate is used to develop the skeleton of the front end. The skeleton consists of the landing page, action page and finally the provider page.
ii) After this we add the necessary CSS for the aesthetic of the website. 
iii) Necessary Javascript for interaction with the user can also be generated. 


                                             Step to be followed by the user. 
       
 The user has to follow all these prerequisites and install all this into their system. 

                    Prerequisites: 
1.Install truffle.

2.Install Ganache.

3.Install Solc@5.0.16.


                    Running Commands: 
1.cd Election-dApp.

2.npm install.

3.npm run dev.

After this user will be faced with very UI friendly page, where user it will be easily understandable, how to use the webpage.



                                                  MODULES AND FUNCTIONALITIES 
▪ MetaMask: This will be used for ethereum transactions, Meta Mask will allow a user to create an account so that user can access ethereum amount and its transactions.

▪ Home Page: This will be the only page required for whole process, this page will be user friendly, and will direct the user directly to the voting section.

▪ Voting Section: This section provides an interface to select the candidates upto user’s will and further vote for the candidate selected after proper ethereum transaction.

▪ Standings Table : This will display the results of polling/elections. Users will be able to watch the result once he/she casts their vote.

▪ Web3 Js: This is a javascript library which allows us to interact with ethereum wallets on the MetaMask manipulative browser.

