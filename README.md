# Dummycontract
// SPDX-License-Identifier: MIT pragma solidity ^0.8.0;  contract DummyContract {     string public data;      constructor(string memory _initialData) {         data = _initialData;     }      function updateData(string memory _newData) public {         data = _newData;     } }
