# NFT-mint-Vault-and-Swap
This is a project submission for the Talent Olympics Hosted by SuperteamDAO. 

Prerequisites to begin with-:
1. Install Rust and Cargo: You must have Rust and Cargo installed.
2. Install Solana CLI: Follow the installation instructions from the official documentation.
3. Install Anchor: Follow the installation instructions from the official Anchor documentation.

Step-by-Step Guide
Step 1: Initialize an Anchor Project

Step 2: Define the Program in Rust
Edit the lib.rs file inside the programs/nft_minting/src directory:

Step 3: Update the Cargo.toml file
Add dependencies for Anchor and SPL Token:

Step 4: Configure the Anchor.toml file
Update the Anchor.toml file to specify the program ID and other details:

Step 5: Build and Deploy the Program

Step 6: Create a Client Script
You can create a simple JavaScript client using @project-serum/anchor to interact with your smart contract. Create a new file 'mint_nft.js':

Final Step: Run the Client Script

This is a simplified example. In a production scenario, you would add error handling, validation, and possibly more advanced features such as metadata for the NFTs.

Make sure to replace YourProgramId with the actual program ID generated when you deploy your Anchor program.



