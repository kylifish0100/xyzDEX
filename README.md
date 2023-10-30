# xyzDEX written in Cairo v2.0

Clone of Uniswap V2 to Cairo. AMM for StarkNet.

## Development and Testing 

- We used [Scarb](https://docs.swmansion.com/scarb/) for our Cairo contracts compilation and [Starkli](https://book.starkli.rs/) for contranct deployment on StarkNet.<br>
Run ```scarb build``` to build the contracts.


- [Starknet Foundry](https://foundry-rs.github.io/starknet-foundry/index.html) is used for our contract testing.<br>
Run ```snforge``` to perform test using the test contracts.


## Directory Structure
- src folder contains all the contracts that made up the DEX
- target/dev folder contains Sierra files and Cairo Assembly(CASM) files automatively generated Scarb as the build result
- test folder contains all the test written in Cairo for the contracts (starknet foundry will automatically perform test cases for us)



