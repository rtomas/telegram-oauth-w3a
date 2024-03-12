# Telegram OAuth Server for Web3Auth

This project is a demonstration of integrating Web3Auth with Telegram OAuth for authentication. Web3Auth is a decentralized authentication protocol that allows users to sign in to applications using their Ethereum wallets. In this demo, Telegram OAuth is used to authenticate users, and Web3Auth is employed to provide Ethereum private key access.

## Getting Started

Follow these steps to set up and run the project:

1. Clone the repository:
`git clone https://github.com/rtomas/telegram-oauth-w3a.git`

2. Install dependencies:
```
cd web3auth-byoa/github-oauth-connection
npm install
```

3. Create a `.env` file in the project root and set the following variables:

```env
TELEGRAM_APP_TOKEN=
TELEGRAM_APP_NAME=
TELEGRAM_REDIRECT_URI=
PRIVATE_KEY_FILE_NAME=privateKey.pem
WEB3AUTH_VERIFIER_ID=w3a-telegram-oauth-demo #create a verifier at https://dashboard.web3auth.io
```

4. Run the application:

   ```bash
   npm start
   ```

5. Open your browser and navigate to `http://localhost:5005/telegram/login` to initiate the Telegram OAuth flow. (TODO: does not work on localhost, must use ngrok)





