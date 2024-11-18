# Blockchain Intern Recruitment Requirements

Welcome to our Blockchain Intern recruitment challenge! This project is designed to evaluate your ability to build a simple, user-friendly, and functional interface to interact with a blockchain network. Please read the requirements carefully and complete the challenge as specified.

---

## Objective
Your task is to create a web application with the following features using a framework of your choice (e.g., React, Next.js) and demonstrate your understanding of blockchain concepts, wallet integration, and interaction with a blockchain test network.

---

## Feature Requirements

- [ ] **Connect to Wallet**  
  Implement a simple interface that allows users to easily connect their blockchain wallet. Users should be able to select from a list of available wallets (e.g., MetaMask, WalletConnect, or any wallet supported by your chosen blockchain network).

- [ ] **Show Connected Account (Address)**  
  Display the user's wallet address in a clear and intuitive way. Ensure that this information updates dynamically when the user connects or switches accounts.

- [ ] **Initialize Client to Connect to the Network**  
  Set up a client to connect to the blockchain network, specifically a **testnet**. Ensure that connecting to the network is seamless and provides feedback to the user if the connection is successful or fails.

- [ ] **Fetch & Show Balance for Connected Account**  
  Retrieve and display the account balance of the connected wallet. 
  
- [ ] **Build a Form to Transfer Balance**  
  Create a simple and intuitive form where users can:
  - Enter the **destination address**.
  - Specify the **amount to transfer**.
  
  Include necessary validation to ensure that the input data is correct (e.g., valid address format, sufficient balance).

- [ ] **Check Transaction Status**  
  Provide feedback to the user about the status of their transaction, specifically:
  - **Finalized**: When the transaction is finalized on the blockchain.
  
  This feature should inform the user about the transaction's progress in a user-friendly way.

- [ ] **Check Transaction Result**  
  Clearly show whether the transaction was **successful** or **not**. Include error messages or confirmations for better user understanding.

---
## Implementation Guidelines

1. Fork the repo
![image](https://github.com/user-attachments/assets/f963ae18-0119-4bfd-b5d6-d38c3ba6d8c1)

2. Clone the repo

```shell
git clone https://github.com/<your-github-username>/blockchain-intern-assignment.git
```
- Replace `<your-github-username>` with your actual GitHub username
- For example, if your GitHub username is `phapdev`, the command would be:

```shell
git clone https://github.com/phapdev/blockchain-intern-assignment.git
```

3. Create a folder with your name

```shell
mkdir <your-name>
```
4. Create a your project inside the folder
- Use React, Next.js, or any other framework of your choice
5. Start implementing the requirements
- [ ] Connect to Wallet
- [ ] Show Connected Account (Address)
- [ ] Initialize Client to Connect to the Network
- [ ] Fetch & Show Balance for Connected Account
- [ ] Build a Form to Transfer Balance
- [ ] Check Transaction Status
- [ ] Check Transaction Result

---
## Submission Instructions

1. **Commit & Push your code to your GitHub repository**
```shell 
git add .
git commit -m "Submit Blockchain Intern Assignment"
```

2. **Create pull request**
- Go to your repository on GitHub
- Click on `Pull requests`
- Click on `New pull request`
- Click on `Create pull request`
- Add a title 
    ```shell
    Your Name | Submit Blockchain Intern Assignment
    ```
    - example: `Luong Van Phap | Submit Blockchain Intern Assignment`
- Click on `Create pull request`
![image](https://github.com/user-attachments/assets/5fc0d2a1-ee87-4ec4-ace9-13f03386954c)

---

Thank you for participating in our Blockchain Intern recruitment challenge! We look forward to seeing your work and exploring your potential as part of our team.

**Good luck and happy coding!**
