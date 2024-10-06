### 1. Install Dependencies:
`$ npm install`
![image](https://github.com/user-attachments/assets/45bf04a1-3586-4926-bbf3-7c42d2567fab)

### 2. Setup .env file:
Before running any scripts, you'll want to create a .env file .

You'll need to create an account on [Hugging Face](https://huggingface.co/), visit your profile settings, and create a read access token. 

You'll also need to create an account on [NFT.Storage](https://nft.storage/), and create a new API key.

### 3. Run tests
`$ npx hardhat test`

### 5. Start Hardhat node
`$ npx hardhat node`

### 6. Run deployment script
In a separate terminal execute:
`$ npx hardhat run ./scripts/deploy.js --network localhost`

### 7. Start frontend
`$ npm run start`
