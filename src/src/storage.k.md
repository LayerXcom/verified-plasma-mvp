## RootChain
```
syntax Int ::= "#RootChain.operator" [function]
// -------------------------------------
// doc:
// act:
rule #RootChain.operator => 0

syntax Int ::= "#RootChain.currentChildBlock" [function]
// -------------------------------------
// doc:
// act:
rule #RootChain.currentChildBlock => 1

syntax Int ::= "#RootChain.currentDepositBlock" [function]
// -------------------------------------
// doc:
// act:
rule #RootChain.currentDepositBlock => 2

syntax Int ::= "#RootChain.currentFeeExit" [function]
// -------------------------------------
// doc:
// act:
rule #RootChain.currentFeeExit => 3
```