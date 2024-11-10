# **Armour E-Vault Decentralized Blockchain Storage System**

This project facilitates **decentralized image upload and sharing** on the blockchain using **Solidity** for the smart contract and **React** for the front-end interface. It enables users to securely upload images to **IPFS** (InterPlanetary File System) and share access with specified users through smart contract functionality. Not only can files be uploaded, but applications can also be shared based on the server.

---

## **Pinata Server**

- **Pinata Blockchain server** is used for handling transactions and ensuring **secondary hashing** for enhanced security, particularly for sensitive documents.

---

## **Hardhat**

- **Hardhat version v.23** is used for the generation of hash values. We leverage **SHA hashing** algorithms to ensure more secure transactions.

---

## **Solidity**

- Basic **Solidity** code for **smart contract transactions**, enabling users to interact with the blockchain and manage file uploads securely.

---

## **Metamask**

- **Metamask** is a Chrome extension used as a **crypto wallet**. It allows users to perform blockchain transactions directly, bypassing the need for third-party sandbox versions.

---

## **Research on How Polygon Works**

- Developers using **Polygon Mumbai** are encouraged to migrate to **Amoy** for continued testing and development. The **Amoy testnet** promises **improved scalability** and **lower gas fees**, offering benefits for developers working on blockchain applications.
- **Migration steps**: Developers must create a new app on the **Amoy network** via the **Alchemy dashboard**, update their **API URLs**, deploy test contracts, and adjust their **testing environments** accordingly.

---

## **ALCHEMY - WEB3, AGGREGATED**

- **Alchemy** provides a platform to interact with blockchain applications easily, helping developers to scale and manage decentralized applications (dApps).

---

## **Usage**

1. Install dependencies:
   ```bash
   npm install
2.Deploy HardHat 
   ```bash
   npx hardhat run scripts/deploy.js --network <network-name> #Your Network Name
