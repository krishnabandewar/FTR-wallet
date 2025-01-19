# Future Wallet (FTR) Blockchain Wallet

A blockchain wallet application for generating, importing, and managing Bitcoin wallets. This project demonstrates the integration of React.js for the frontend and Node.js for the backend using the BitcoinJS library.

## Features
- Generate a Bitcoin wallet (address and private key).
- Import an existing wallet using a private key.
- Check the balance of a wallet.
- Generate QR codes for wallet addresses.

## Tech Stack
- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Libraries**: 
  - `bitcoinjs-lib` for wallet generation and validation.
  - `axios` for API communication between the frontend and backend.
  - `qrcode` for generating QR codes.
  - `body-parser` for handling JSON requests.

## Project Structure
future-wallet/ │ ├── ftr-wallet-backend/ # Backend server │ ├── app.js # Main server file │ ├── package.json # Backend dependencies │ └── node_modules/ # Installed backend modules │ ├── ftr-wallet-frontend/ # Frontend application │ ├── src/ # React source code │ │ ├── App.js # Main React component │ │ ├── components/ # Custom React components │ │ │ ├── WalletGenerator.js │ │ │ ├── WalletImporter.js │ │ │ ├── BalanceChecker.js │ │ │ └── QRCodeGenerator.js │ │ └── index.js # React entry point │ ├── package.json # Frontend dependencies │ └── node_modules/ # Installed frontend modules │ ├── README.md # Project documentation └── .gitignore # Git ignored files

markdown
Copy
Edit

## Installation and Setup

### Prerequisites
- Node.js and npm installed.
- Basic knowledge of React.js and Node.js.

### Steps to Run

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd future-wallet
Set up the backend:

cd ftr-wallet-backend
npm install
node app.js
The backend server will start at http://localhost:5000.

Set up the frontend:

cd ../ftr-wallet-frontend
npm install
npm start
The frontend will open in your browser at http://localhost:3000.

API Endpoints
POST /wallet/generate: Generates a new Bitcoin wallet.
POST /wallet/import: Imports a wallet using a private key.
GET /wallet/balance/:address: Retrieves the balance for the specified Bitcoin address.
POST /wallet/qr: Generates a QR code for a given address.
Known Issues
The balance checker does not fetch live balances due to incomplete backend functionality.
Ensure all required npm packages are installed before running the project.
Future Improvements
Integrate a blockchain API for live balance retrieval.
Enhance error handling and form validation in both frontend and backend.
Add unit tests for React components and Express routes.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Note: If you face issues or have questions, feel free to raise them in the repository.
This concise version includes all the key information in a readable format! Let me know if you’d like more tweaks!






