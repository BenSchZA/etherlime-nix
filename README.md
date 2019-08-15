## Resources

1. Nix, The Purely Functional Package Manager: https://nixos.org/nix/
2. Node2Nix, generate Nix expressions to build NPM packages : https://github.com/svanderburg/node2nix
3. Etherlime, Dapp Development framework based on ethers.js: https://github.com/LimeChain/etherlime

## Prerequisites

Install Nix package manager and `node2nix`

## Generate Nix expressions (only if updating)

`node2nix --nodejs-10 -i node-packages.json`

## Installation

`nix-env -f default.nix -iA etherlime --keep-going`
