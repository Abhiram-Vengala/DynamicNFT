# TEALScript Project

## Documentation

For TEALScript documentation, go to https://tealscript.algo.xyz

## Usage

### Algokit

This template assumes you have a local network running on your machine. The easiet way to setup a local network is with [algokit](https://github.com/algorandfoundation/algokit-cli). If you don't have Algokit or its dependencies installed locally you can open this repository in a GitHub codespace via https://codespaces.new and choosing this repo.

### Build Contract

`npm run build` will compile the contract to TEAL and generate an ABI and appspec JSON in [./contracts/artifacts](./contracts/artifacts/) and a algokit TypeScript client in [./contracts/clients](./contracts/clients/).

`npm run compile-contract` or `npm run generate-client` can be used to compile the contract or generate the contract seperately.
### Dynamic NFT smart contract
DNFTLogidtics.algos.ts has the Dynamic NFT logistics smart contract with function like creating an parcel which creates the NFT and maps parcel data to the NFT . you can change the token Uri which will be a link to ipfs storage which contains parcel details . This contract contains functions like creating parcel , updating parcel and getting the parcel details . 

### HelloWorld.test.ts 
contains the test cases to mint the NFT and change token URI .


### Run Tests

`npm run test` will execute the tests defined in [./\_\_test\_\_](./__test__) 

### Lint

`npm run lint` will lint the contracts and tests with ESLint.
