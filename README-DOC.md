## HTML FUND ME CU 
- The project is a DApp that has an HTML frontend and uses an ABI of a smart contract to help interact with the contract functions from the frontend.

- The aim is to:
    - understand how frontend functions are written within the Javascript file as we call the contract together with the HTML file which helps us interact with the contract through local host after serving.
    - understand how to use Metamask by installing (if you don't have), adding the testnets (Anvil or ETH Sepolia) using the RPC URL, etc. Once setup trying to connect wallet and interact with contract
    - read through the functions and understanding them since they're common Web3 functions used in dApps e.g `connect`, `withdraw`, `getBalance` and `fund`
    - the HTML file has button that call the Javascript functions i.e `connect`, `withdraw`, `getBalance` and `fund`


## Summary Quiz
1. When developing a simple web page locally, which method best simulates how the page would be served by a real web server? `Using a local development server tool or extension.`
2. What core security principle ensures that a web application cannot arbitrarily spend a user's cryptocurrency or execute unauthorized blockchain transactions via a browser wallet? `The wallet requires explicit user confirmation before signing and broadcasting any transaction.`
3. Within JavaScript libraries like `ethers.js`, what function does a 'Provider' primarily serve when initialized with `window.ethereum`?
`It acts as an abstraction layer to communicate with the blockchain network selected in the user's wallet via its RPC connection.`
4. How is the unique identifier used to call a specific smart contract function generated? `By taking the first few bytes of the Keccak-256 hash of the function's signature.`
5. When a user clicks a 'Connect Wallet' button on a website designed for blockchain interaction, what action does the website's code typically initiate through the wallet's provider API? `Request access to the user's public wallet address(es).`
6. To interact with smart contracts deployed on a local development blockchain like Anvil using MetaMask, what setup steps are required?`Manually add the local blockchain's network configuration (RPC URL, Chain ID) to MetaMask and import an account funded on that local chain.`
7. Which type of interaction with a blockchain generally does *not* require a cryptographic signature from the user's wallet? `Querying the current balance of an account or reading data from a smart contract.`
8. What is a function selector in the context of Ethereum smart contracts? `A short identifier derived from a function's signature, used to specify which function to call in the compiled contract bytecode.`
9. What does 'calldata' contain in an Ethereum transaction that interacts with a smart contract function? `The function selector followed by the ABI-encoded arguments for that function.`
10. How can command-line tools like Foundry's `cast` help in understanding the arguments being passed in a transaction's calldata? `By using a decoding command (like `cast --calldata-decode`) along with the function signature and the raw calldata.`
11. How does a decentralized application (dApp) usually gain the ability to request transaction signatures for a specific user account via a browser wallet? `By obtaining a 'signer' object, derived from the provider.`









