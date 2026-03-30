# Interstellar Vault 🚀

Welcome, spacefarer, to the Interstellar Vault! This is a competitive, level-based smart contract challenge designed to test your Solidity skills.

## How to Play

1. **Fork this repository** to your own GitHub account.
2. Clone your fork locally to begin your journey:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Contract-battle.git
   cd Contract-battle
   ```
3. Initialize the development environment. You will need [Foundry](https://book.getfoundry.sh/getting-started/installation):
   ```bash
   # Initialize git submodules for forge-std
   git submodule update --init --recursive
   ```
4. Read your current mission and implement your solution in `src/`.
5. Run the local tests to ensure your baseline logic is correct:
   ```bash
   forge test
   ```
6. **Local Push:** `git push` your changes to your fork. This will trigger a public Action verifying your local tests pass.
7. **The Judge (Submit):** Once ready, open a **Pull Request** from your fork to the original Master repository! This awakens the Central Judge, which will run **secret edge-case tests** against your code.
   - If you pass, the Central Judge will leave an "Access Granted" comment on your PR and automatically push the **next level's challenges** to a new branch (`level-2`) directly onto your fork! You can then `git fetch` and checkout the new branch locally.
   - If you fail, the Central Judge will comment "Access Denied" and summarize the failure. Examine your code for security vulnerabilities, push updates to your fork, and the Judge will re-evaluate your PR automatically!

---

## Current Objective: Level 1 - The Galactic Registry

**Mission:** Register your ship in the interstellar database. Every pilot must register before entering the vault.

**Your Task:**
Complete the `register` function inside `src/Level1.sol` for the `GalacticRegistry` contract.

Requirements:
1. Ensure the name is not empty.
2. Prevent a single address from registering more than once.
3. Record the data in the mappings and emit the `Registered` event.

Good luck, commander. The Judge is watching!
