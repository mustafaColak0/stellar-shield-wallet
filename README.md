# 🌌 Stellar Shield Wallet

Stellar Shield Wallet, *It is a modern, fast, and user-friendly Web3 wallet and transaction interface that integrates seamlessly with Soroban smart contracts. The project is designed to manage financial workflows on the Stellar network in the most transparent and secure manner.

---

## 🎬 Project Demo Video


👉 <img width="800" height="360" alt="videoconnet-ezgif com-video-to-gif-converter" src="https://github.com/user-attachments/assets/13163f64-ba36-4f00-900b-1c237b1b2109" />


> 💡 **Want to see the full, uncut workflow?** > If you would like to watch the complete step-by-step wallet connection, multi-asset transfer processes, and live network confirmations in full detail, you can watch our comprehensive video here:  
> 👉 **[Click Here to Watch the Full Detailed Project Demo Video]()**(https://drive.google.com/file/d/1II4ByR4UaOZgnzGMrpXjZFrx0AV5reQe/view)

---

## 🚀 Features

* 🔐 **Multi-Wallet Integration:** Full integration with the official **Freighter** wallet, along with ecosystem simulation models for Albedo and xBull in a sandbox environment.
* 🛡️ **Smart Security Detector (Security Audit):** A native module performing real-time `SSL/TLS Connection Status` checks and running a `Wallet Injection Interceptor` shield to mitigate malicious extension exploits.
* 🔒 **Advanced Transaction & Risk Confirmation:** A two-stage confirmation modal triggered before signing transactions, presenting the user with a dedicated security risk analysis agreement checkbox.
* 💰 **Dynamic Balance & Base Fee Tracking:** Fetches the connected wallet's live Testnet XLM balance and the network's current minimum gas fee (Base Fee) dynamically via API.
* 🌌 **Soroban Smart Contract Deposit Workflow:** Full implementation of dynamic input fields and multi-stage transaction modals tailored for interacting with Soroban smart contract `deposit()` methods.
* 📊 **Live Contract Event Stream Timeline:** Real-time monitoring of emitted smart contract events, utilizing auto-updating layouts and specialized **`DEPOSIT`** badges to visualize historical and live blockchain operations smoothly.
* 🛑 **Jury Soroban Error Detail Window:** An advanced error handling boundary that captures contract failures (`FAILED` transaction status) and displays raw `jurySorobanError` stack traces inside a monospaced, highly readable, and responsive debug container.
* 📈 **Live Asset Flow Chart (Recharts):** An interactive dynamic Area Chart enabling users to track asset fluctuations and balance changes immediately after transfers.
* 💸 **Multi-Asset Transfer Panel:** Easily switch between `XLM`, `USDC`, and `EURC` token supports to execute secure Testnet transfers using the recipient's Public Key.
* 📇 **Integrated Address Book:** Save frequently used addresses, secure vaults, or jury test wallets to initiate accurate transfers with a single click.
* 🔍 **Instant Search & Filtering:** Case-insensitive, real-time query filter within the Transaction History tab using wallet addresses or Transaction Hashes (Tx Hash).
* 📏 **Pixel-Perfect Responsive Layout:** Fully optimized with tailored layout spacing, component padding, and precise pixel dimensions (`px dimensions`) leveraging Tailwind CSS animations (`animate-in fade-in slide-in-from-bottom-2`) to ensure absolute layout stability and cross-device smoothness.
* 🔲 **Dynamic QR Code Engine:** Generates a custom QR code matching the connected user's Public Key for error-free, quick peer-to-peer payment requests.

---

## 🛠️ Installation & Local Setup

Follow these steps to run the project locally on your machine:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/mustafaColak0/stellar-shield-wallet.git
   cd stellar-shield-wallet
    ```

2.  **Install Dependencies:**
    ```bash
    npm install
    ```

3.  **Start the Development Server:**
    ```bash
    npm start
    ```
    Your browser will automatically open the project at http://localhost:3000 .

---

## 📸 Submission Proofs

💡 Jury Evaluation Note: The mandatory visual proofs requested in the Seviye 2 Submission Checklist are mapped directly below.

1. Wallet Connected State & Live Dashboard (Dashboard Overview)
Proof of successful Freighter extension connection showing the active account state, real-time simulated network load, gas metrics, and the dynamic asset flow area chart tracking historical Testnet balances:
<img width="1918" height="873" alt="dashboard2" src="https://github.com/user-attachments/assets/6ccda133-b401-409b-8856-d72e2b9442d1" />
<img width="872" height="722" alt="dashboard3" src="https://github.com/user-attachments/assets/7ad42cde-e9c2-45f3-b2cc-148504f98e5b" />



2. Multi-Asset Transfer Engine with Compliance Filters
The cross-asset ecosystem panel (supporting XLM, USDC, EURC) equipped with real-time compliance network logs, integrated quick contacts, and the automated "Sign & Send Transaction" interface:
<img width="1918" height="876" alt="transfer2" src="https://github.com/user-attachments/assets/43b7ae37-7d09-40a3-b898-143e9f2d9036" />
<img width="423" height="377" alt="sorobanauthmatrix" src="https://github.com/user-attachments/assets/a4063688-8369-4caa-9e2f-08d0788ba859" />
<img width="845" height="503" alt="transfer_enforced" src="https://github.com/user-attachments/assets/5d5bb9ba-56a0-4eb6-8bcd-751bdb10152d" />




3. Dynamic QR Code Peer-to-Peer Payment Request Engine
A real-time payment address sharing layout that auto-generates a high-contrast verifiable QR code corresponding directly to the connected user's Public Key, including options for custom amounts and memos:
<img width="1918" height="861" alt="qrkod2" src="https://github.com/user-attachments/assets/3cb5ae92-b2a2-44d5-8f06-80d5f5d80300" />



4. Level 2 Security Audit & Soroban Interaction Matrix
The centralized simulation sandbox showing automated code scans, cryptographic binding logs, a custom transaction monitor, and live exception/abort test handlers:
<img width="1918" height="870" alt="security audit 2" src="https://github.com/user-attachments/assets/e595a182-4b41-4496-b91a-4dd7bd9d838b" />



5. Soroban Contract Interface & Emitted Event Timeline
The core Smart Contract execution window containing real-time crowdfunding progress bars, a direct `deposit()` execution method, and an isolated live ledger contract event stream listing verifiable asset badges:
<img width="886" height="700" alt="security_audit_deposit" src="https://github.com/user-attachments/assets/edbbb585-91fc-4e0b-93b5-b70b9ad23c14" />



6. Integrated Address Book for Verified Test Accounts
A secure, custom local registry allowing users to manage, save, and launch quick-transfer triggers (`Send Money`) directly to designated jury test wallets or secure vaults:
<img width="1918" height="863" alt="adressbook2" src="https://github.com/user-attachments/assets/4728197a-e93b-4d24-8bd8-cc3f5d34488b" />



7. Optimized Transaction Ledger (Transaction History UI)
A real-time query-filtered interface mapped out with clean responsive constraints, designed to trace case-insensitive searches for transaction hashes and target addresses:
<img width="1912" height="863" alt="Transaction History 2" src="https://github.com/user-attachments/assets/c1704740-fa60-474b-9c6a-6de623887d84" />
<img width="881" height="312" alt="transaction_history_process" src="https://github.com/user-attachments/assets/6766b6f6-642f-40c4-86b5-dee11bb8c7ff" />


--

🗺️ Future Roadmap

### 🔄 Phase 1: Soroban Optimization & Verification (Short-Term)
*   **Soroban Auth Next-Gen Integration:** Migrate from standard invocations to Soroban's advanced `isValidSignature` and multi-signature authorization frameworks for institutional vault workflows.
*   **Automated Contract Unit-Testing:** Embed an isolated client-side WebAssembly (WASM) simulation boundary allowing developers to test Soroban contract custom exceptions and gas limits directly inside the dashboard.

### 🌐 Phase 2: Mobile Ecosystem & Deep Linking (Medium-Term)
*   **WalletConnect v2 & Deep Linking Architecture:** Expand the Multi-Wallet panel by integrating native WalletConnect infrastructure, letting mobile users trigger instant biometric transaction sign requests on **LOBSTR**, **Vibrant**, or **xbull mobile**.
*   **Dynamic QR Intent Protocol (SEP-0007):** Upgrade the QR Code Engine to generate dynamic, compliant `stellar:` URI payment intents, embedding asset types, exact amounts, and memo hashes natively into the matrix.

### 🛡️ Phase 3: Advanced Compliance & Security AI (Long-Term)
*   **Real-Time Decentralized Phishing Registry:** Connect the native Security Audit detector to open-source Stellar phishing APIs and blacklist databases to throw high-severity UI alerts before broadcasting transactions to flagged malicious endpoints.
*   **Automated Fee-Bump Enabler:** Implement a smart transaction relayer that automatically attaches fee-bumps to critical Soroban contract interactions during heavy Testnet/Mainnet network congestion states.

--

🧬 Tech Stack
Frontend: React.js (JavaScript / JSX)

Styling: Tailwind CSS (Fully Responsive Layout)

Icons: Lucide React

Charts: Recharts

Stellar SDK: @stellar/freighter-api
