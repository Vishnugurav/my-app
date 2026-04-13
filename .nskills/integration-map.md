# Integration Map

How components connect and what data flows between them.

### Erc721-stylus --> Frontend-scaffold

- **Source**: Erc721-stylus (`79893bea`)
  - Output ports: NFT Contract (contract)
- **Target**: Frontend-scaffold (`d672ee32`)
  - Input ports: Contract ABI (contract), Network Config (config)

### Frontend-scaffold --> Wallet-auth

- **Source**: Frontend-scaffold (`d672ee32`)
  - Output ports: App Context (config)
- **Target**: Wallet-auth (`66a4446e`)
  
