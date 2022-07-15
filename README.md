# beezk
bee zero knowledge proofs boilerplate

forked from https://github.com/ConsenSys/gnark-tests

## beezk boilerplate features

- Write, debug and compile `gnark` circuits using Go tooling
- Write, debug and compile solidity using `Hardhat`
- Output gnark circuit to solidity

## Project structure

### /build

Circuits are compiled inside build directory, where a solidity artifact is created.

### /circuits - gnark circuits

There are two examples from gnark library, the default cubic equation circuit and a MiMC circuit called `age18orOlder`. Additional helper functions are `EdDSA signatures`, `Merkle proofs` and `zk-SNARK verifier`

### /contracts

Solidity contracts

### /test

Solidity tests

## gnark compilation npm command

### npm run compile:circuit

Compiles `build/contract/main.go`, outputs a proof and verifier. Builds a Solidity contract verifier ready to use.


Maintainers
----

- @molekilla

License
---

MIT
