#Plata Ethereum Blockchain DApp

This is an Ethereum-based DApp on the Ropsten test network. With this application users are able to sell and buy data using "ether". Data itself is stored on the InterPlanetary File Server (IPFS), a decentralized cloud storage platform.

## In order for local development first execute the fol

1. In order for local development first execute the fol
    ```javascript
    npm install -g truffle
    ```

2. Download the box. This also takes care of installing the necessary dependencies.
    ```javascript
    truffle unbox chainskills/chainskills-box
    ```

3. Run the development console.
    ```javascript
    truffle develop
    ```

4. Compile and migrate the smart contracts. Note inside the development console we don't preface commands with `truffle`.
    ```javascript
    compile
    migrate
    ```

5. Run the `liteserver` development server (outside the development console) for front-end hot reloading. Smart contract changes must be manually recompiled and migrated.
    ```javascript
    // Serves the front-end on http://localhost:3000
    npm run dev
    ```
