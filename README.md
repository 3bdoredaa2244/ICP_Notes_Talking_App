# ICP Notes Talking App

A decentralized note-taking application built on the Internet Computer (ICP) blockchain.  
This app allows users to create, read, update, and delete encrypted notes securely on-chain with shared access.

---

## Features

- Create encrypted notes  
- Read all owned and shared notes  
- Update encrypted notes  
- Delete notes  
- Share notes securely with other users  
- Decentralized storage using ICP stable memory  
- Authentication with Internet Identity (ICP native auth)  

---

## Tech Stack

- **Backend:** Rust canister on Internet Computer  
- **Frontend:** React (connects to Rust canister)  
- **Storage:** ICP stable memory structures  
- **Authentication:** Internet Identity  

---

## Installation & Running Locally

1. Clone the repo  
   ```bash
   git clone https://github.com/3bdoredaa2244/ICP_Notes_Talking_App.git
   cd ICP_Notes_Talking_App
2. Build and deploy the canister

dfx start --background
dfx deploy

3. Start the frontend

cd frontend
npm install
npm start

Usage

Sign in using Internet Identity

Create and manage your encrypted notes

Share notes with other principals securely

Contributing

Contributions are welcome! Please fork the repo and create a pull request for any improvements or bug fixes.

License

MIT License © 2025 Abdulrahman Reda

Contact

For questions or suggestions, please open an issue or contact Abdulrahman Reda.

Built with ❤️ on the Internet Computer (ICP).


