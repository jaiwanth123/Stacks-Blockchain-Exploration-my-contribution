# CHALLENGE:1
 
## PART A:

### INTRODUCTION TO STACKS:
Stacks is a bitcoin L2 chain ,which leverage  the usage of bitcoin chain by adding extra functionalities to it .
For ex: allowing to execute smartcontracts,Building dapps etcc.

It is a Bitcoin Layer that shares some components with L1s and L2s,Users and developers  call Stacks a Bitcoin L2, since it is a simpler concept to understand REFERENCE FOR FULL EXPLANATION: https://www.stacks.co/faq/is-stacks-a-bitcoin-l2#:~:text=Users%20and%20developers%20organically%20call%20Stacks%20a%20Bitcoin%20L2%2C%20since%20it%20is%20a%20simpler%20concept%20to%20understand

The primary purpose of stacks is to  not to consider bitcoin just as  a storage medium but also to add   programmability over bitcoin chain.

Founded by Princeton University alumni Muneeb Ali and Ryan Shea in 2013, Stacks has positioned itself as a significant player in the Web3 ecosystem by leveraging the security and capital of Bitcoin .


### STACKS GROWTH AND POPULARITY

Stacks has seen a huge growth  and  became a leading protocol  among bitcoin l2 projects, But as a whole in the web3 community ,Stacks is not  as a popular as EVM compatible chains .

### CLARITY: A DOMAIN-SPECIFIC LANGUAGE FOR SMART CONTRACTS:

Stacks uses Clarity, a domain-specific language (DSL) designed for smart contract development. Clarity is known for its safety and predictability, reducing the chances of bugs and making it difficult to write dangerous code. It is a decidable language, which means that developers can know exactly how contracts will execute without the need for a compiler or bytecode. This design choice prioritizes safety over expressiveness, which is a trade-off that benefits the security of smart contracts.

           REFERENCE:https://docs.stacks.co/clarity/overview
                     https://clarity-lang.org

### STACKS VS  COMPETITORS( WITH ALL OTHER NETWORKS ):

When compared to Ethereum and other competitors, Stacks offers a unique proposition by enabling smart contracts on Bitcoin. While Ethereum was the first to support smart contracts, Stacks provides a more secure foundation by leveraging Bitcoin's network. The market cap of Stacks is smaller than Ethereum's, but it is growing rapidly with a dedicated developer community and support for early funding through various initiatives.

### STACKS COMPETITORS WITH OTHER BITCOIN BASED NETWORKS:
examples of some other bitcoin based networks:

      lightnning network-https://lightning.network/
      
      liquid network-https://liquid.net
      
      rootstock(RSK)-https://rootstock.io
      
      bouncebit-https://bouncebit.io/

The main difference between  Stacks from other Bitcoin layers like Lightning is :

Lightning don't add any extra functionality to Bitcoin, it simply helps to scale functionality ,Bitcoin already has and help it operate faster. Lightning has no permanent state that it keeps track of, and so is unsuitable for things like smart contracts that need to keep track of data and maintain state.

RSK also adds functionality to bitcoin but different way compared to stacks.RsK dont have thier own miners and mining process but stacks have all these on own.

Contrast this to Stacks, which adds additional functionality to Bitcoin but still ultimately settles down to Bitcoin .

              
### STACKS's FAMOUS PROJECT

 HIRO SYSTEMS formerly known as (BLOCKSTACKS) is the famous project based on stacks network . Hiro ease the process of building on bitcoin.  It Allows developers to build secure, privacy-focused applications using the Stacks blockchain and associated tools.They provide variuos type of developer tools  for bitcoin layers.It is one of the  core entity within the Stacks ecosystem .   


        REFERENCE:https://www.hiro.so

## PART B:
    
RPC network providers for stacks are very limited compared to othe chains like ethereum or solana,because of limited number of users on stacks network:
         
         
some of the node providers who offer services for stacks are:
                      1)QUICKNODE- https://www.quicknode.com/chains/stx
                      2)HIRO SYSTEMS-https://docs.hiro.so/get-started/stacks-blockchain-api

RPC METHOD DOCUMENTATION LINKS:

                     1)HIRO SYSTEMS-https://docs.hiro.so/stacks-blockchain-api
                     2)QUICKNODE-https://www.quicknode.com/docs/stacks                  
                              


## PART C:

Famous self custody wallets on stacks are :
               
                    1) Leather Wallet-https://leather.io
                    2)xverse-https://www.xverse.app
                    3)OKX-https://www.okx.com/web3
                    4)D'CENT -https://dcentwallet.com

One cannot  add stacks to METAMASK because stacks is not an EVM compatible chain .    

### STEPS TO USE LEATHER WALLET:
                    
step1:
                    
Add leather wallet app chrome extension on any of your browser(also desktop app is available for windows,mac and linux ).

(step1 is common for both new wallet creation and for importing old wallet ).
                    
### FOR NEW WALLET CREATION:
                    
step2:

Click on NEW WALLET option and it will ask to backup our 24 phrase backup key(private key for whole wallet).

step3:

Now ,it will ask us to set a password,after completing it, the wallet creation process is over!! with a default account(1)created with all its keys and  with account  balance (0).

step4 :

For a new account creation ,click on account1 (above of our balance) or two bar dropdown button and click on add new account
and another account with its own private key will be created !!

### FOR IMPORTING EXISTING WALLET:

step2:

After installing wallet ,click on existing key button for importing our already craeted wallet and type down your 24 phrase private key.

step3:

Type your password and your wallet will be successfully imported .


### GETTING FUNDS FROM FAUCET:

step1:
One can use both HIRO faucet or LEARNWEB3 faucet for getting funds for stacks network.,but lets go with HIRO(the famous one).

step2:

one can go with HIRO's web application(HIRO EXPLORER SANDBOX) or using api ,we will go with web application.

                    webapp link:https://explorer.hiro.so/sandbox/faucet?chain=testnet

                    api docs link(for programmatic creation):https://docs.hiro.so/api#tag/Faucets

step3:
After opening web page ,click on connect stacks wallet button,and  already installed wallet application will pop up ,choose the account you want to add funds,or create another acount.now your wallet will be connected to the webapp,And we can see our account address showing on webpage.

step4:
                    
Now click on request stx buttton,



                    
## PART D :

   
WIDELY USED STACKS EXPLORERS:

                 1)stackexplorer by HIRO-https://explorer.hiro.so

                 2)stackexplorer by blockscout https://explorer.stack.so

DEX ON STACKS:

                 1)ALEX-https://alexlab.co
                 2)Stackswap-https://app.stackswap.org
                 3)Arkadiko-https://arkadiko.finance

NFT MARKET PLACE ON STACKS:

                 1)STX-20-https://stx20.com/Explore
                 2)Gamma- https://stacks.gamma.io


  ## part E:

### STACKS WALLET(ACCOUNT) ADDRESS ENCODING DETAILS:

In stacks account Address contains 2 or 3 fields: 1 byte version, 20 byte public key hash (RIPEMD160(SHA256(input))), optional name (variable length, max 128 bytes).20 byte public key hash is  generated by  the RIPEMD-160 hash of the SHA256 of the public key.The optional name field is used for contract accounts, which are created when a smart contract is instantiated. 

so what is contract accounts?,there are two types of accounts in stacks network,
Two types of accounts: 
1)standard accounts are owned by one or more private keys.
2)contract accounts are materialized when a smart-contract is instantiated (specified by the optional name field above) RFERENCE:https://docs.stacks.co/stacks-101/accounts.



A normal mainnet address starts with SP, and a testnet address starts with ST. e.g. SP3FGQ8Z7JY9BWYZ5WM53E0M9NK7WHJF0691NZ159(mainnet), ST2F4BK4GZH6YFBNHYDDGN4T1RKBA7DA1BJZPJEJJ(testnet) .REFERENCE:https://docs.hiro.so/stacks.js/learn-the-basics#anchor-mode--block-type
While the exact length of a Stacks address can vary due to the optional name field, the base address (without the optional name) is typically 41 characters long, as seen in the provided examples.


### STACKS PRIVATE KEY ENCODING:


In stacks 24 phrase secret key of  wallet is by  BIP 39 standard.
private keys are generated according to the BIP32 and BIP44 standards.
the length of the private key is not explicitly mentioned in any offcial docs.

        REFERENCE:https://stacks.js.org/modules/_stacks_wallet_sdk#:~:text=Secret%20Keys%20conform%20to%20the%20BIP%2039%20standard


  
            

## STACKS  ROLL UP:

            

Stacks is a unique layer that provides smart contract functionality to Bitcoin, effectively acting as a Bitcoin layer for smart contracts 
Unlike traditional rollups, Stacks does not roll up to Ethereum but instead to Bitcoin. The Nakamoto release of Stacks will integrate even more closely with Bitcoin, eliminating a separate security budget and following Bitcoin finality with 100% of Bitcoin's hashpower 
This means that Stacks L2 relies entirely on Bitcoin L1 for its operation and security .


Stacks publishes only the hashes of data to Bitcoin, rather than the full data, which helps to maintain efficiency while leveraging Bitcoin's robust security 
There is ongoing research and development to integrate rollup technology with the Stacks layer, which could further enhance its scalability and functionality .


The integration of rollup technology into the Stacks ecosystem could provide several benefits, including increased throughput, reduced transaction costs, and enhanced security 
However, adding rollups also introduces complexity to the transaction lifecycle and the overall blockchain process.


                        

             REFERENCE:https://docs.stacks.co/stacks-101/bitcoin-connection








                       
               




