# Simple Blockchain Implementation in Python

This project is a basic implementation of a blockchain in Python. It has functionalities for creating blocks, mining them using proof-of-work, and maintaining the integrity of the blockchain. Users can add blocks with custom transactions and validate the chain to ensure its consistency.

## Features
- *Genesis Block*: Automatically creates the first block of the blockchain.
- *Block Mining*: Uses proof-of-work with a customizable difficulty level.
- *Transaction Support*: Enables adding transactions to new blocks.
- *Blockchain Validation*: Verifies the integrity of the blockchain.
- *Interactive CLI*: It is an interactive loop for adding new blocks with user-defined transactions.

## How It Works
1. *Genesis Block*: The blockchain starts with a predefined genesis block.
2. *Adding Blocks*: Users can input transactions for a new block, which is then mined and appended to the chain.
3. *Proof-of-Work*: Blocks are mined by finding a hash that meets the difficulty criteria.
4. *Chain Validation*: Validates that all blocks are correctly chained and their hashes are legitimate.

## Example Inputs
These are example inputs for the program:

### Input Example 1
Alice pays Bob 10 BTC,Charlie pays Dave 5 BTC
Result: A block with transactions:
["Alice pays Bob 10 BTC", "Charlie pays Dave 5 BTC"]

### Input Example 2
Alice pays Carol 20 ETH
Result: A block with a single transaction:
"Alice pays Carol 20 ETH"


# How to Run the Program

## Clone the repository:
** git clone <repository-url>

## Navigate to the project directory:
** cd <repository-directory>

## Run the program:
** python blockchain.py
Input transactions, mine blocks, and build your blockchain as prompted.
