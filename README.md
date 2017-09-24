# solidity_problem_debug.md

##### Contract migration error: The contract code couldn't be stored, please check your gas amount
It looks like you're deploying an abstract contract (with functions that have no definition).
You can't deploy **abstract** contracts to the Ethereum blockchain.
https://github.com/trufflesuite/truffle/issues/476
