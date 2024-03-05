# Changelog

## 1.1.0
* Merged changes up to go-ethereum Archanes (v1.13.4), which covers the Ethereum Shanghai network upgrade.
  - Support for Solidity compiler up to 0.8.23 version
  - Support for EIP-3855: PUSH0 instruction
  - Support for EIP-3860: Limit and meter initcode
  - Support for EIP-3651: Warm COINBASE


## 1.0.0
* First version, based on go-ethereum Paravin (v1.10.26)
* Updated Go version to 1.21
* Module names changed from `ethereum` to `HorizenOfficial`
* Added EON Native <> Real smart contract interoperability support 
  by modifying following files:
  - `core/vm/errors.go`
  - `core/vm/evm.go`
  - `core/vm/instructions.go`
  - `core/vm/interpreter.go`