# fintech-unit-21-homework-puppercoin-crowdsale
 Using advanced solidity to create a crowdsale

 You can see the solidity contracts I reference below here:
 [PupperCoinSaleDeployer.sol](https://ipfs.io/ipfs/QmerT9oCeNWPw1Y8Va7Hf7rCndBmUK3qkBvTj5Kt1sVRcq)
 [PupperCoin.sol](https://ipfs.io/ipfs/QmVSVSkq6LByfMkisBbhzitAcTDnMAgYc4EGMEhGtEnMJd)
 [Crowdsale.sol](https://ipfs.io/ipfs/QmNPrJ4MWKUAWzKXpUqeyKRUfosaoANZAqXgvepdrCwZAG)

 Feel free to open them in remix and try this as I go along.


The PupperCoinSaleDeployer.sol contract deployment
- It was deployed on the Kovan Test Network
- - You can do it on your local netowkr with Ethereum Accounts from Granache that have test ETH loaded)
- Environment: WebInject3
- This account was used to deploy the PuppercoinSaleDeployer.sol contract: MetaMask Account 1 0x1d92D60Ab708957212849F15cfDAf12C080f7b1D
- The name is: Pupper Coin Sale Deployer
- The Symbol is: PPC
- The payable wallet is: MetaMask Account 2 0x652D8f3677Faa9D859A55752a4e9Ff2061b18447
- The goal is: 50
- When I did this locally, the total transaction cost was: 5900240 gas
- When I did this locally, the total execution cost was: 4360480 gas
- See the published metadata from doing it locally is below for reference. In this case I didn't have the funds to do it on the Kovan Test Network, but the contract clearly works

The PupperCoin.sol contract deployment
- It was deployed on the Kovan Test Nework
- - You can do it on your local netowkr with Ethereum Accounts from Granache that have test ETH loaded)
- Environment: WebInject3
- This account was used to deploy the PupperCoin.sol contract: MetaMask Account 7 0x7Bc43E5d0b8957c89feEBB8611ffEa58bF27258c
- The name is Pupper Coin Token
- The symbol is: PPC
- The initial supply is 

I couldn't deploy the contract because of insufficient funds to pay fees on Kovan (although it worked on local network when I had ETH in my grananch accounts).

The Crowdsale.sol  contract deployment
- It was deployed on the Kovan Test Nework
- - You can do it on your local netowkr with Ethereum Accounts from Granache that have test ETH loaded)
- Environment: WebInject3
- This account was used to deploy the Crowdsale.sol contract: MetaMask Account 3 0x8eCa3aDBC0266FD4bA0207Ce906A9F609Bc80c39
- The rate: 1
- The Wallet was MetaMask Account 4 0xE188D3f232Bcae0aec266fD912d0394582b45337
- The token address: TBD. *NOTE: I would've used the output of the PupperCoin.sol deployment above to put here, and the person doing this themselves locally should do that. When I did this locally with test Ether in Accounts from Granache, I was able to deploy the PupperCoin.sol contract and get a token deployment account number as an output (My Token address: 0xE03C5974D552955a1a8D3B94263d6D0f0150c66e) that I could them put into this field here so that I'd have an account where I could sell the tokens from in the Crowdsale to buy PupperCoins*

Locally on my *8545* custom network I could see in metamask - I was able to deploy each of these contracts and get the outputs. See an example of the published metadata

All three deployments appeared in the remix side bar under "Deployed Contracts" and carried accout numbers. Here's some notes I made while doing these deployments locally. You should try to do the same with these contracts I'd provided.

Once you have the contracts deployed and running - try sending more than 50 ETH to the Crowdsale account that collects the money in the crowdsale (0xE188D3f232Bcae0aec266fD912d0394582b45337) from any wallet except that one.

When that wallet exceeds the goal of 50 ETH, then tokens will be released to those who gave.

You're tokens (I named the token PPC) address with be given to you in the deployed contracts output, during the deployments of the contracts in Remix on your local network. You can also setup whatever custom token you come up with the the account in MetaMask or MyCypto.

GOOD LUCK!

PUPPERCOINSALEDEPLOYER AT 0X1D1...690DF (BLOCKCHAIN)
0:
address: 0x50e12D1706f530673b4a71AE04656580438b0C2e


My Token address: 0xE03C5974D552955a1a8D3B94263d6D0f0150c66e


The address for the block with my PupperCoin Contract: 0x9206e18Fdae8c4c23d5BE32B2725ec8cde9B954c


So when I delayed the Crowdsale.sol which included the PupperCoinSaleDeployer contract, I did the deployment with this account from Granache: 
ADDRESS: 0x68b5e1C3808cb3Cf59cf5a7BbCc3108334A47139
BALANCE: 100 ETH
You'll need you secret key.

Use this address to deploy crowdsale 0xa2D381A64ba7cbe50Ec050B96b7d9315a09eb5Bb


# Here's the Published PupperCoinSaleDeployer's Metadata
Metadata of "puppercoinsaledeployer" was published successfully.
browser/Crowdsale.sol : 
dweb:/ipfs/QmerT9oCeNWPw1Y8Va7Hf7rCndBmUK3qkBvTj5Kt1sVRcq
browser/PupperCoin.sol : 
dweb:/ipfs/QmVSVSkq6LByfMkisBbhzitAcTDnMAgYc4EGMEhGtEnMJd
https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/GSN/Context.sol : 
dweb:/ipfs/QmNPrJ4MWKUAWzKXpUqeyKRUfosaoANZAqXgvepdrCwZAG
https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/access/Roles.sol : 
dweb:/ipfs/QmTEwDbjJNxmMNCDMqtuou3dyM8Wtp8Q9NFvn7SAVM7Jf3
https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/access/roles/MinterRole.sol : 
dweb:/ipfs/QmP5aMkvFwMJyuQjKE8ADh5tkWYqonb4KjgkAjgYEVVFAv
https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/Crowdsale.sol : 
dweb:/ipfs/QmWZF4DnkWZZYzVHz8pAxbLFRxmNiKWE2n1Chd4w2rXWYh
https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/distribution/FinalizableCrowdsale.sol : 
dweb:/ipfs/QmUur1SjJ4yyRTDELyfMZSqjkgBUjLzK8iRVx8YKuZiciz
https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/distribution/PostDeliveryCrowdsale.sol : 
dweb:/ipfs/QmPWqHtVJ7bZd6iBy5LD23ZctsZfv6qehLDzGFodCs1xTY
https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/distribution/RefundableCrowdsale.sol : 
dweb:/ipfs/QmPHK5aM8Eg5HEML427S2iAdqtcgpSUH1tQaEfXqx4X1ow
https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/distribution/RefundablePostDeliveryCrowdsale.sol : 
dweb:/ipfs/QmPRTXVzjZzALro3nQWphyJgpLCdBSFa9Ncg5UGMdEDumz
https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/emission/MintedCrowdsale.sol : 
dweb:/ipfs/QmdyGt7hjQ3D6JFr1HRaqa2xjS3EZGFomnwsqfjKHckcqx
https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/validation/CappedCrowdsale.sol : 
dweb:/ipfs/QmQXSQcJeASMyDFm81CvodBP2vdDBKqVd7aT6vqTvVVNSP
https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/validation/TimedCrowdsale.sol : 
dweb:/ipfs/QmQ6npy1tbtRT6g8NR7gRryu4VYYejVvdnSjgdjG8Z4qAc
https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/math/SafeMath.sol : 
dweb:/ipfs/QmbZaJyXdpsYGykVhHH9qpVGQg9DGCxE2QufbCUy3daTgq
https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/ownership/Secondary.sol : 
dweb:/ipfs/Qme7K9o8sEYRcwUfe5VNnpbGGiTyPYbrSxZNUkm2qXJ9VK
https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/payment/escrow/ConditionalEscrow.sol : 
dweb:/ipfs/QmWqKyw2xk3Fw7wzLyeV8Z4r3HVitT4pmDDwhVcM2aJnEP
https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/payment/escrow/Escrow.sol : 
dweb:/ipfs/QmWtspuNDKZt9EAqXJCQELpufj6NV5L6czokqnVNdb3Yu4
https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/payment/escrow/RefundEscrow.sol : 
dweb:/ipfs/Qmaqm1gtFRdBGCujGazMjwmk2SaciqQxSFCnHTAf7Xv32e
https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/token/ERC20/ERC20.sol : 
dweb:/ipfs/QmP5spYP8vs2jvLF8zNrXUbqB79hMsoEvMHiLcBxerWKcm
https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/token/ERC20/ERC20Detailed.sol : 
dweb:/ipfs/Qmb9iW7yNuYehB2NfhRMs9TakqbLVQhBhmGMkaDZ5g1Eb4
https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/token/ERC20/ERC20Mintable.sol : 
dweb:/ipfs/QmcSBRdFwVvy2wFZrBwo5cvqNP4UHh9Eyzf8jnxBgnPqfe
https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/token/ERC20/IERC20.sol : 
dweb:/ipfs/QmQMvwEcPhoRXzbXyrdoeRtvLoifUW9Qh7Luho7bmUPRkc
https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/token/ERC20/SafeERC20.sol : 
dweb:/ipfs/QmTDkFzKnrpiV1UKnSoiZAHPuguWzokrr4pFbSPvyaSo56
https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/utils/Address.sol : 
dweb:/ipfs/Qmebp4nzPja645c9yXSdJkGq96oU3am3LUnG2K3R7XxyKf
https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/utils/ReentrancyGuard.sol : 
dweb:/ipfs/QmWj9g8X1hxkXRre2kwkEjLBetjuzmSbWHD81bsSojnBkS
metadata.json : 
dweb:/ipfs/QmSaKgsH5oBat9ai2Y2GfjukMDbh5RxH2xMdQZ7LQ4wA3K


