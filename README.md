# erc20-token-crowdfund-project

In this project we are creating an ERC20 token for crowdsale their named PupperCoin token in order to help fund the network development.
This network will be used to track dog breeding activity across the globe in a decentralized way, and allow humans to track the genetic trail of their pets. We have already worked with the necessary legal bodies and obtained the green light on creating a crowdsale open to the public. However, we are required to enable refunds if the crowdsale is successful and the goal is met, and we are only allowed to raise a maximum of 300 ether. The crowdsale will run for 24 weeks.
We will need to create an ERC20 token that will be minted through a Crowdsale contract that we can leverage from the OpenZeppelin Solidity library.
This crowdsale contract will manage the entire process, allowing users to send ETH and get back PUP (PupperCoin).
This contract will mint the tokens automatically and distribute them to buyers in one transaction.
It will need to inherit Crowdsale, CappedCrowdsale, TimedCrowdsale, RefundableCrowdsale, and MintedCrowdsale.
We will conduct the crowdsale on the Kovan or Ropsten testnet in order to get a real-world pre-production test in.

![alt text](https://github.com/victorlfreire/erc20-token-crowdfund-project/blob/main/Images/crowd.jpg)
