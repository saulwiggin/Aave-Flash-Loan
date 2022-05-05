# Intro to Defi - Aave Flash Loan Lab

![Aave Banner](aave-defi-protocol-platform.png)

## Development

In order to communicate with the Moralis Server, we need to include the Moralis code in our dApp. Open your favorite text editor. We recommend Visual Studio Code with the "Live Server" extension to make running the web page super easy.

## What's next

Smart contracts emit so-called events when something meaningful happens within the smart contract that the smart contract wants to communicate to dapps and other smart contracts. The developers of the smart contract decide when these events are emitted. For example - when somebody sends an ERC20 token - the token contract will emit a Transferevent containing all of the data about the transfer.
When you are building dapps it's very important for you to be able to listen to these events in real time. For example, if you are building an NFT Marketplace, your dapp needs to know when somebody creates a new auction or when somebody bids on an item - the smart contract will communicate these events by emitting events.
With Moralis you can listen to smart contract events in real-time and also get all historic occurences of a specific event.
