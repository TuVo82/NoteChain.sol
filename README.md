# NoteChain.sol
NoteChain.sol6
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract NoteChain {
    string public message;

    constructor(string memory _message) {
        message = _message;
    }

    function setMessage(string memory _newMessage) public {
        message = _newMessage;
    }
}
Add setMessage function
Clean unused variables
Update function visibility
Refactor storage logic
Add require for safety
Remove unused imports
