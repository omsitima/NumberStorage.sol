# NumberStorage.sol
How to deploy a contract on Base Chain NumberStorage.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract NumberStorage {
    uint public number;

    function setNumber(uint _num) public {
        number = _num;
    }
}
