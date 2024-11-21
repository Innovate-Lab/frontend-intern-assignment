# Frontend Intern Recruitment Requirements

Welcome to our Frontend Intern recruitment challenge! This project is designed to evaluate your ability to build a simple, user-friendly, and functional interface to interact with a blockchain network. Please read the requirements carefully and complete the challenge as specified.

---

## Objective
Your task is to create a web application with the following features using a framework of your choice (e.g., React, Next.js) and demonstrate your understanding of blockchain concepts, wallet integration, and interaction with a blockchain test network.

---

## Feature Requirements

### Must Have
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

### Nice to Have
- [ ] **Transaction History**  
  Display a history of past transactions for the connected account, including details like transaction hash, amount transferred, and timestamp.

- [ ] **Network Switching**  
  Allow users to switch between different testnets and update the application accordingly. Handle any necessary network changes and notify the user.

- [ ] **Enhanced UI/UX**  
  Implement a polished and responsive user interface. Use animations, tooltips, and progress indicators to improve the overall user experience.

- [ ] **Dark Mode**  
  Add a toggle for dark mode, allowing users to switch between light and dark themes seamlessly.

- [ ] **Notifications**  
  Provide notifications for important events, such as when the wallet is connected, when a transaction is submitted, and when a transaction is confirmed or fails.

- [ ] **Gas Fee Estimation**  
  Show an estimated gas fee before users confirm their transactions. Allow them to adjust the gas fee settings if needed.

- [ ] **Localization**  
  Support multiple languages, enabling users to switch to their preferred language.

- [ ] **Testing**  
  Write unit tests and integration tests to ensure that the core features work as expected. Use a testing framework of your choice (e.g., Jest, React Testing Library).

---

## Technical Requirements
- Use React.js, Next.js, or any other framework of your choice.
- Use Tailwind CSS for styling, but you can use any other CSS framework if you prefer.
- Use wallet-adapter to connect to the wallet.( MetaMask, WalletConnect, SuiWallet, etc.)

## How to Submit

Time to complete: **3 days**.
After you complete the challenge, please submit your code to the following link:
- Do not forget to clearly state the instructions on how to run your application in the README.md file
- Video demo your project.
  
**Submit** 👉 [Here](https://vbiacademy.typeform.com/intern)

---
**Good luck and happy coding!**
