# SimpleMapping.sol
SimpleMapping.sol7
pragma solidity ^0.8.20;

contract SimpleMapping {
    mapping(address => uint) public balances;

    function setBalance(uint _amount) public {
        balances[msg.sender] = _amount;
    }
}
Improve validation
Improve naming consistency
Update state variable
Add comments for clarity
Remove debug code
Remove unused imports
Refactor contract layout
