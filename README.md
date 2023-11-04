# **ERROR_HANDLING**
The smart contract has been created using the Solidity programming language, which is essentially responsible to represent all sort of erorr handling in solidity.

# Description

This is a smart contract written using solidity (a high-level programming language primarily used for developing smart contracts on the Ethereum blockchain), which is basically responsible to showcase all different types of erorr handling in solidity. This contract has been developed utilizing a variety of functions, which have been documented and listed below.

This Solidity contract `ErrorHandling` demonstrates different error handling mechanisms. Here's a brief explanation of each function:

1. `call_require()`: This function uses the `require` statement to check if the `msg.sender` is the owner of the contract. If the condition is not met, it will revert the transaction, and any remaining gas will be returned to the user, while consumed gas will not be refunded.

2. `call_assert()`: In this function, the `assert` statement is used to check if `msg.sender` is not the owner. If the condition is false, the transaction will be reverted, and no gas will be refunded to the user.

3. `call_revert()`: This function checks if the input `_x` is greater than 10. If it's not, the function will revert with an error message, returning any remaining gas to the user but not refunding the consumed gas.

This contract demonstrates the use of `require`, `assert`, and `revert` for error handling in Solidity, each with its own characteristics regarding gas refund and transaction behavior.

## Authors

- [@raiyan-fr](https://www.github.com/raiyan-fr)

## License

The project is License under [MIT License](https://choosealicense.com/licenses/mit/).
