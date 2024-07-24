# PlentiFi - Blockchain Made Easy 🔗

Welcome to PlentiFi!  
PlentiFi is designed to simplify the implementation and usage of blockchain technology. This solution addresses the barriers to entry for both developers and end-users, aiming to make blockchain as accessible and user-friendly as Web2 applications. PlentiFi is a non-custodial Account Abstraction solution powered by biometrics and session keys, enabling seamless interaction with blockchain protocols.

## ⌚️ State of the Art

Onboarding in the blockchain space has been a significant challenge due to complex security measures like 12-word recovery phrases. Existing solutions often require trust in third parties or have not yet achieved a Web2-like user experience. PlentiFi enhances the state-of-the-art by integrating WebAuthn, allowing transactions to be signed using biometric data. This approach improves security and user-friendliness while adhering to decentralized principles.

## ✅ Key Features

### For Developers and Businesses:
- **TypeScript Toolkit**: Simplifies Web3 integration without requiring specialized knowledge. The platform handles all blockchain aspects, from generating functions to managing wallets 🛠️
- **Easy Integration**: Developers register on the platform, receive a business ID, and can start with just five lines of code 🚀
- **Module Connection**: Connect any module to user accounts (smart wallets) to enable specific features and delegate capacities, utilizing ERC-7579 🔗

### For Users:
- **Quick Onboarding**: Requires only a username, email, and password initially, with plans for username-only registration in the future 📝
- **Non-custodial Wallet**: Provides an instantly functional wallet across all supported EVMs with the same address 💼
- **Biometric Authentication**: Transactions are authorized via biometrics (webAuthn), eliminating the need for seed phrases 🔐
- **Multi-device Compatibility**: Use the same account across multiple devices 💻
- **Privacy Features**: Includes burner wallets and ring signatures, with an optional app for managing you account 🔒

## 🌐 Useful Links
- [Website](https://plentifi.xyz)
- [Demo](https://plentifi.xyz)
- [LinkedIn](https://www.linkedin.com/company/103131730)

## 📑 Litepaper
Coming soon

## PlentiFi on the XRP Ledger: System Design Diagrams and Narrative <img src="https://cryptologos.cc/logos/xrp-xrp-logo.png?v=032" alt="XRP" width="20"/>

### Create a Smart Account on the XRP Ledger
<img src="https://github.com/user-attachments/assets/8592b812-983d-4274-a5b6-0e43dbf9e08c" alt="Screenshot from 2024-07-24 11-18-16" width="500"/>

### Smart Account Transaction on XRPL
<img src="https://github.com/user-attachments/assets/b6c046e6-1824-4f2e-b1ac-1e1960f96faa" alt="Screenshot from 2024-07-24 11-19-32" width="500"/>


**Custom Account Abstraction Mechanism**
Since the XRPL does not support smart contracts in the same way as EVM-compatible blockchains, PlentiFi has developed a custom account abstraction mechanism tailored for the XRP Ledger. This mechanism utilizes the ledger's built-in multi-signature feature to offer robust authentication and account management.

- **Multi-Signature Authentication**: The XRPL's multi-signature feature allows multiple keys to authorize transactions. PlentiFi uses this to secure user accounts, enabling a multi-layered authentication process that enhances security and reduces the risk of unauthorized access.
- **Recovery Options**: Even if a user loses access to one of their devices, the multi-signature setup ensures that they can still recover their account using other authorized devices. This approach eliminates the need for users to store seed phrases or manage private keys, significantly reducing the friction associated with traditional blockchain wallets.

**Developer SDK**
The PlentiFi SDK abstracts the complexities of interacting with the XRPL, allowing developers to integrate blockchain functionalities with minimal effort.
- **Seamless Onboarding**: By simplifying the onboarding process, the SDK enables developers to quickly bring new users onto the XRPL without requiring them to understand the underlying blockchain technology.

**XRPL EVM Sidechain Integration**
PlentiFi also integrates with an EVM sidechain to enhance its offering, leveraging EIP-4337 for advanced account management features.

- **EIP-4337 Deployment**: The deployment of EIP-4337 on the EVM sidechain introduces account abstraction capabilities that are compatible with the XRPL. This includes a public bundler RPC to facilitate user operations and the creation of smart accounts using biometrics (WebAuthn).
- **Smart Account Factory**: PlentiFi's smart account factory utilizes ERC-7579 to allow developers to connect various modules to user accounts. This enables extensive customization and the addition of specific features tailored to user needs.

Additionally, PlentiFi, our non-custodial smart wallet application, plays a crucial role in this ecosystem. PlentiFi allows users to have a single address across all supported EVMs without storing a private key, utilizing biometric authentication (WebAuthn). Users do not need to download an app, enhancing accessibility. For developers, PlentiFi simplifies blockchain integration, enabling any blockchain action with just three lines of code.


## 🌐 Multi-Chain Powered by PlentiFi

### One Account for All Apps and Blockchains

With PlentiFi, users have a single account that works across all supported blockchains. This means the same address can be used on all the supported networks, simplifying account management and interaction with various dApps.

### Cross-Chain Interaction and Auto-Bridging

PlentiFi enables effortless cross-chain interactions and automatic bridging of assets. Users can interact with dApps on different blockchains without the need for manual bridging, making the experience more intuitive and user-friendly.

### Supported Chains

PlentiFi will initially supports a wide range of blockchains, ensuring broad compatibility and flexibility:

<img src="https://cryptologos.cc/logos/ethereum-eth-logo.png?v=024" alt="Ethereum" width="30"/> Ethereum <br>
<img src="https://scrollscan.com/assets/scroll/images/svg/logos/chain-light.svg?v=24.6.3.0" alt="Scroll" width="30"/>  Scroll <br>
<img src="https://cryptologos.cc/logos/optimism-ethereum-op-logo.png?v=024" alt="Optimism" width="30"/> Optimism <br>
<img src="https://cryptologos.cc/logos/arbitrum-arb-logo.png?v=024" alt="Arbitrum" width="30"/> Arbitrum <br>
<img src="https://cryptologos.cc/logos/polygon-matic-logo.png?v=024" alt="Polygon" width="30"/>  Polygon  <br>
<img src="https://cryptologos.cc/logos/xrp-xrp-logo.png?v=024" alt="XRP" width="30"/> XRPL - EVM sidechain  <br>

More will be added in the future

### Non-Custodial Solution

PlentiFi is a non-custodial solution, meaning users have full control over account and assets. This enhances security and ensures that users are the sole owners of their funds.

### Use of Biometrics and Session Keys

To provide a seamless and secure user experience, PlentiFi utilizes biometric authentication (WebAuthn) and session keys. This approach eliminates the need for traditional seed phrases, making the onboarding process straightforward and secure. Users can authorize transactions with biometrics, ensuring ease of use without compromising security.
Session Keys can significantly change the way users interact with dApps (decentralized applications). The idea is to let users create a session key that pre-approves transactions within a dApp for a specific time, up to a certain limit and with particular rules. This means users can use their favorite project without having to repeatedly confirm transactions through their wallet.

#### 🔑​ Key Features of Session Keys:
- **Predefined Actions**: Users predefine the allowed actions, enabling them to interact with a protocol while ensuring their assets remain secure.
- **User Convenience**: Currently, most dApps require users to sign transactions repeatedly, which is inconvenient for users who perform many transactions. Session Keys reduce this inconvenience by allowing predefined approvals.
- **Customizable Limits**: Session Keys can be customized in various ways, such as setting a time limit, maximum gas limit, maximum transaction volume for a specific token, or allowing only certain functions on a specific program.

#### Example Use Case:
For instance, Session Keys could significantly enhance the user experience for derivative exchanges on Solana like Drift, Zeta, or Cypher. A trader could create a session key valid for one hour, allowing them to trade up to $50,000 without needing to confirm each transaction with their wallet. This would create an experience similar to what users enjoy on centralized exchanges like Binance, without the cons of centralization.

By offering tailored “keys” for different purposes and users, protocols can provide a more user-friendly experience while minimizing risks associated with repeated transaction confirmations. This flexibility and enhanced control make Session Keys a powerful tool for improving the overall dApp interaction experience.


### 📚 Our Open Source Contributions

PlentiFi is committed to the open-source community and has made significant contributions to enhance blockchain development. Here are some of our key contributions:

- **Deterministic Smart Contract Deployment Architecture**: Our innovative architecture allows developers to deploy any contracts with the same address on multiple blockchains, requiring only one EOA transaction per blockchain. This is possible even if the contracts do not have the same bytecode. Additionally, the contracts can be upgradable, providing flexibility and future-proofing for decentralized applications.

- **Account Abstraction SDK on the XRPLedger**: We provide an abstraction layer that enables developers to create seamless and non-custodial integrations with ease. The open-source nature of this SDK allows developers from the XRPL community to build more secure, user-friendly wallets and applications. This abstraction simplifies the user experience, making it more intuitive and driving broader adoption of the XRPL ecosystem.


## 📖​ Open Source Libraries we based our work on

PlentiFi leverages several open-source libraries to build a robust and efficient platform. Here are the key libraries we use:

- **Kernel v3.1**: [Kernel v3.1 Repository](https://github.com/zerodevapp/kernel/tree/release/v3.1)

- **ZeroDev SDK**: [ZeroDev SDK Repository](https://github.com/zerodevapp/sdk)

- **SmoothCryptoLib**: [FreshCryptoLib Repository](https://github.com/get-smooth/crypto-lib)

​
<br>
<br>
Thank you for choosing PlentiFi! We are excited to have you on board and look forward to simplifying your blockchain experience.

