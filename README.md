# 🌞 Onchain GM (Optimism Mainnet)

Un contrat minimaliste pour dire "GM" directement on-chain sur [Optimism](https://www.optimism.io).

## 🚀 Détails du contrat

- **Nom :** OnchainGM  
- **Réseau :** Optimism Mainnet  
- **Adresse :** [`0xFF361E51BE6408aB954088822eD383148BE8A693`](https://optimistic.etherscan.io/address/0xFF361E51BE6408aB954088822eD383148BE8A693)  
- **Licence :** MIT  
- **Compilateur :** Solidity v0.8.24+commit.e11b9ed9  

## 🧠 Description

Le contrat permet à n’importe qui de publier un message “GM” on-chain.
Chaque message est stocké et émet un événement `NewGM` avec :
- l’adresse de l’auteur  
- le timestamp  
- le message

```solidity
function postGM(string calldata message) external
