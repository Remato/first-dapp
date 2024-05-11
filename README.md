<img width="1032" alt="Screenshot 2024-05-11 at 19 18 52" src="https://github.com/Remato/first-dapp/assets/8043534/550432b6-5458-49a9-b3d6-f507f26112b7">

First dApp interaction with Sepolia Network.

Smart Contract:

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.19;

contract MoodDiary {
    string mood;

    function setMood(string memory _mood) public {
        mood = _mood;
    }

    function getMood() public view returns (string memory) {
        return mood;
    }
}
```

Install + Run:

```script
yarn install && yarn lite-server 
```

[Sepolia Ethereum Faucet](https://sepolia-faucet.pk910.de/#/)

