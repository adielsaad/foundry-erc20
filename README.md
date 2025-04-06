# Foundry ERC20 Token Project

This project implements ERC20 tokens using Foundry, featuring both a manual implementation and an OpenZeppelin-based implementation.

## Project Structure

```
├── src/
│   ├── ManualToken.sol    # Manual ERC20 implementation
│   └── OurToken.sol       # OpenZeppelin-based ERC20 implementation
├── script/
│   └── DeployOurToken.s.sol  # Deployment script
├── test/
│   └── OurTokenTest.t.sol    # Token tests
└── lib/
    └── openzeppelin-contracts/  # OpenZeppelin dependencies
```

## Features

### ManualToken.sol
- Basic ERC20 implementation
- Features:
  - Name and symbol
  - Total supply
  - Balance tracking
  - Transfer functionality with balance validation

### OurToken.sol
- OpenZeppelin-based ERC20 implementation
- Features:
  - Standard ERC20 functionality
  - Initial supply minting
  - Full OpenZeppelin security features

## Getting Started

### Prerequisites
- Foundry
- Git

### Installation
1. Clone the repository:
```bash
git clone <repository-url>
cd foundry-erc20
```

2. Install dependencies:
```bash
forge install
```

### Testing
Run the test suite:
```bash
forge test
```


### Deployment
Deploy the token using the deployment script:
```bash
forge script script/DeployOurToken.s.sol
```

## Development

The project uses:
- Foundry for development and testing
- OpenZeppelin contracts for secure token implementation
- Solidity 0.8.18

