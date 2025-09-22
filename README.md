Blockchain E-Commerce Platform

This project is a decentralized e-commerce application built on blockchain technology. 
It provides a secure, transparent, and tamper-proof system for online transactions.

------------------------------------------------------------
Features
------------------------------------------------------------
- Secure product listing and purchase using blockchain.
- Decentralized transactions without third-party intermediaries.
- Transparent order and payment history.
- Enhanced data integrity and fraud prevention.
- Simple and user-friendly interface.

------------------------------------------------------------
Tech Stack
------------------------------------------------------------
Frontend:
- React.js (or other frontend framework if used)
- Tailwind CSS / Bootstrap
- JavaScript (ES6+)

Backend:
- Node.js / Express.js
- Smart Contracts (Solidity)
- Blockchain: Ethereum (Sepolia Testnet)

Database / Storage:
- Firebase (cloud database option)
- Ganache (local blockchain simulation for testing)

------------------------------------------------------------
Project Structure
------------------------------------------------------------
Blockchain-Ecommerce/
    frontend/               User interface code
    backend/                Server and API code
    contracts/              Smart contracts
    migrations/             Deployment scripts
    package.json            Dependencies

------------------------------------------------------------
Installation & Setup
------------------------------------------------------------
1. Clone the Repository
   git clone https://github.com/your-username/blockchain-ecommerce.git](https://github.com/sidd0710/E-commerce-using-blockchain.git
   cd E-commerce-using-blockchain

2. Install Dependencies
   npm install

3. Start Local Blockchain (for development using Ganache)
   ganache-cli --deterministic

   OR configure Firebase for cloud storage.

4. Compile and Deploy Smart Contracts
   truffle compile
   truffle migrate --network sepolia   (for Sepolia Testnet)

5. Run the Application
   npm start

------------------------------------------------------------
Usage
------------------------------------------------------------
- Open the application in your browser.
- Browse products, add items to cart, and checkout.
- Payments and order records are secured on the Ethereum Sepolia Testnet.
- Use Ganache for local testing or Firebase for online storage.

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Landing page
![alt text](https://github.com/Soul-Coders/ecommerce-dapp-media/blob/main/LANDING-PAGE.png?raw=true)

##### On clicking Start Shopping the user gets two options
![alt text](https://github.com/Soul-Coders/ecommerce-dapp-media/blob/main/Login-Option.png?raw=true)

Either login in as **Seller** or as **Buyer** (or both!)
| Page | Seller | Buyer |
| ---------------------- | ---------------------- | ---------------------- |
| Login As | ![alt text](https://github.com/Soul-Coders/ecommerce-dapp-media/blob/main/Buyer-Login.png?raw=true) | ![alt text](https://github.com/Soul-Coders/ecommerce-dapp-media/blob/main/Seller-Login.png?raw=true) |
| Dashboard | ![alt text](https://github.com/Soul-Coders/ecommerce-dapp-media/blob/main/seller.gif?raw=true) | ![alt text](https://github.com/Soul-Coders/ecommerce-dapp-media/blob/main/buyer.gif?raw=true) |
| Products | ![alt text](https://github.com/Soul-Coders/ecommerce-dapp-media/blob/main/addProduct.gif?raw=true) | ![alt text](https://github.com/Soul-Coders/ecommerce-dapp-media/blob/main/buyProduct.gif?raw=true) |
| Buyer Cart | N/A | ![alt text](https://github.com/Soul-Coders/ecommerce-dapp-media/blob/main/AddToCart.gif?raw=true) |
| Orders | ![alt text](https://github.com/Soul-Coders/ecommerce-dapp-media/blob/main/SellerOrders.png?raw=true) | ![alt text](https://github.com/Soul-Coders/ecommerce-dapp-media/blob/main/Orders.gif?raw=true) |
| Transactions | ![alt text](https://github.com/Soul-Coders/ecommerce-dapp-media/blob/main/SellerTransactions.png?raw=true) | ![alt text](https://github.com/Soul-Coders/ecommerce-dapp-media/blob/main/BuyerTransactions.png?raw=true) |
| Warranties | ![alt text](https://github.com/Soul-Coders/ecommerce-dapp-media/blob/main/SellerWarranties.png?raw=true) | ![alt text](https://github.com/Soul-Coders/ecommerce-dapp-media/blob/main/BuyerWarranties.png?raw=true) |
| Seller Statistics | ![alt text](https://github.com/Soul-Coders/ecommerce-dapp-media/blob/main/SellerStats.png?raw=true) | N/A |
| Profile Settings | ![alt text](https://github.com/Soul-Coders/ecommerce-dapp-media/blob/main/BuyerProfile.png?raw=true) | ![alt text](https://github.com/Soul-Coders/ecommerce-dapp-media/blob/main/SellerProfile.png?raw=true) |

