# Avalanche_Subnet
## Overview
The Vault contract allows users to deposit ERC-20 tokens and receive shares in return. These shares represent ownership in the vault and can be used to withdraw tokens later.

## Features
- ERC-20 Compatible: Works with any standard ERC-20 token.
- Minting/Burning Shares: Users receive shares when depositing tokens and burn shares when withdrawing tokens.
- Token Accounting: Tracks total supply and individual balances.

## Usage
### Deploy
Deploy the contract with the address of an existing ERC-20 token.

function deposit(uint _amount) external

### Withdraw

function withdraw(uint _shares) external

### Internal FUnctions
_mint
Mints shares for a specified address.
function _mint(address _to, uint _shares) private

_burn
Burns shares from a specified address.
function _burn(address _from, uint _shares) private



