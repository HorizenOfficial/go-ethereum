# Horizen Go-Ethereum

This project is a fork of [Go-Ethereum (geth)](https://github.com/ethereum/), the official Golang implementation of 
Ethereum protocol.

The Ethereum Virtual Machine is included in [Horizen Sidechain SDK](https://github.com/HorizenOfficial/Sidechains-SDK),
through [libevm](https://github.com/HorizenOfficial/libevm) library.

Current used Go-Ethereum version is 1.13.4 [Archanes](https://github.com/ethereum/go-ethereum/releases/tag/v1.13.4), 
with the following modifications:
- Go version is 1.21
- Module names changed from `ethereum` to `HorizenOfficial`
- Added support for calling Sidechain Native Smart Contracts (a.k.a. external Smart Contracts) from Ethereum smart contracts.
  Modified files:
  - `core/vm/errors.go`
  - `core/vm/evm.go`
  - `core/vm/instructions.go`
  - `core/vm/interpreter.go`

## Build
See [original Go-Ethereum README](./ETHEREUM_README.md)