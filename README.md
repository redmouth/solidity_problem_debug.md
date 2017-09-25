# solidity_problem_debug.md

##### Contract migration error: The contract code couldn't be stored, please check your gas amount
It looks like you're deploying an abstract contract (with functions that have no definition).
You can't deploy **abstract** contracts to the Ethereum blockchain.<br>
https://github.com/trufflesuite/truffle/issues/476

##### VM Exception while processing transaction: invalid opcode
1. It's possible that contract is not initialized correctly.
2. Don't use uninitialized variable.
3. Remove unnecessary comments ????
