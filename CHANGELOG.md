# Changelog

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