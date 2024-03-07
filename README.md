
![icons8-hare-64](https://github.com/Amamitoken/amamicontract/assets/162604718/a53547d3-cb05-4dcc-a888-9ed8a1157d79)

# <span style="color:#0000EE">Amami ERC20 Token Contract</span>

The Amami ERC20 token contract is a modified version of a standard ERC20 token, tailored to suit the specific requirements of the Amami project. In this README, we'll outline the modifications made to the standard ERC20 contract and the additional features implemented.

## <span style="color:#0000EE">Modifications and Features</span>

### <span style="color:#0000EE">1. Standard ERC20 Compliance</span>

The Amami ERC20 token contract adheres to the ERC20 standard.

### <span style="color:#0000EE">2. Fee System Implementation</span>

#### <span style="color:#0000EE">Transaction Taxation</span>

- A fee system has been implemented to tax users for each transaction they perform, with the exception of token transfers.
- This fee is deducted automatically from the sender's balance during transactions.

#### <span style="color:#0000EE">Tax Collection</span>

- Tokens acquired from transaction taxes are stored in the contract's balance.
- These tokens will be liquidated for ETH when a swap threshold of 0.5% tokens has been reached.

#### <span style="color:#0000EE">Distribution of Liquidated Tokens</span>

- Upon reaching the swap threshold, 0.25% of the tokens will be liquidated for ETH.
- The remaining 0.25% of tokens will be transferred to the "AmamiCollector" wallet.

### <span style="color:#0000EE">3. Code Optimization and Compliance</span>

- The ERC20 contract has been thoroughly audited and optimized for efficiency and security.
- Compliance with ERC20 standards has been ensured, with any necessary improvements implemented.


For more details on the contract implementation and usage, please refer to the contract source code.

- Contract address:
