### Project Title:
Assessment 3 of Poly proof

### Creation of the project:
        * visit https://github.com/gmchad/zardkat ==> it is a template to implement zkSNARK circuit using circom.
        * Fork and clone this repo.
        * Open the terminal and write command npm i
        * paste the code of circuit.circom inside the circuit.circom inside ./circuits/multiplier
        * paste the text inside input.json inside ./circuits/multiplier/input.json
        * compile the circuit using command npx hardhat circom.
        * It will generate the out folder inside ./circuits/multiplier which contains the circuit intermediatories.
        * configure your hardhat.config.js to deploy it on a testnet.
        * After configuration, run npx hardhat run scripts/deploy.ts --network <network name>
        * You will get a contract address and a verification status with respect to your input.json.

