# Swisstronik x Learn Web 3 Challenge 4 

In this project, there are sample contracts, tests, and scripts that deploy contracts, as well as the Swisstronik blockchain network. This case demonstrates the basic usage of Hardhat.

## Task

1. Deploy an ERC20 token
2. Mint tokens
3. Transfer at least 1 of your ERC20 tokens to 0x16af037878a6cAce2Ea29d39A3757aC2F6F7aac1

## Token Details

```
Name    : LOGOS
Symbol  : LGS
```

## Smart Contract

```
0x763a7a16C0bfc81D6907D494d651c9993892d4cD
```


### Network: Swisstronik


#### `Function Deploy`

```shell
npx hardhat run scripts/deploy.js --network swisstronik
```

#### `Function Mint`

```shell
npx hardhat run scripts/mint.js --network swisstronik
```

```shell
function mint100tokens() public {
 _mint(msg.sender,100*10**18);
}
```

#### `Function Transfer`

```shell
npx hardhat run scripts/transfer.js --network swisstronik
```
<img width="783" alt="image" src="https://github.com/Logosdibta/Swisstronik_LW3_CC4/assets/97156724/62bbd3fe-0ae6-407b-bb24-66885eb45777">

### `Bonus Scripts`

#### `Function Check Balance`

This scripts to validate your token has successfully transfer to 0x16af037878a6cAce2Ea29d39A3757aC2F6F7aac1

```shell
npx hardhat run scripts/balanceOf.js --network swisstronik
```
```
Response:
Decoded response: 111n
```

## Conclusion

Tx hash Deploy
```
https://explorer-evm.testnet.swisstronik.com/tx/0x9d24d625c99de55f32d0ec05f2fca9a10f90dc4b7e89631fee4c9161e9eed1f7
```

Tx hash Mint
```
https://explorer-evm.testnet.swisstronik.com/tx/0x486dd6a68868366dad7f3929c160647dc97036d5d857df442bf1e7a092d05058
```

Tx hash Transfer
```
https://explorer-evm.testnet.swisstronik.com/tx/0x6e972b20a8726fba9c3c22551791b3bd659a3c2130918ab132784f790f3100eb
```

credited : Logosnodos

