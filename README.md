# Future Blockchain Wallet

A simple blockchain wallet for generating addresses, managing private keys, checking balances, and generating QR codes.

## Features
- Generate new wallet addresses and private keys.
- Import existing wallets using private keys.
- Check wallet balances.
- Generate QR codes for easy sharing.

## Technologies Used
- **Frontend**: React.js, Axios, TailwindCSS
- **Backend**: Node.js, Express, bitcoinjs-lib

## Installation

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd ftr-wallet-backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the server:
   ```bash
   node app.js
   ```
   Backend will run on `http://localhost:5000`.

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd ftr-wallet-frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the React app:
   ```bash
   npm start
   ```
   Frontend will run on `http://localhost:3000`.

## Usage
1. Open the frontend in your browser.
2. Generate a wallet or import an existing one.
3. Check wallet balance or generate QR codes for transactions.

## Notes
- Ensure the backend server is running before using the frontend.
- Both frontend and backend should run simultaneously for proper functionality.

---

