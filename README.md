Note:
1. Copy from https://github.com/NomicFoundation/hardhat-boilerplate
2. Modify package.json: hardhat 2.11.0->2.11.1

1. Installation
'''
git clone https://github.com/github167/demo-hardhat.git
cd demo-hardhat
npm install
'''
2. Start teminal1
'''
npx hardhat node
'''

3. Deploy contract
'''
npx hardhat --network localhost run scripts/deploy.js
'''

4. Metamask
a. launch metamask: localhost:8454
b. transfer eth and token to the Account 1
'''
npx hardhat --network localhost faucet 0x7b38b0b624a29f0115ee118dd010129e68b5df56
'''

5. Start terminal2
'''
cd frontend
npm install
npm start
'''
