# GiGMint Contracts

## Contracts

### GiGToken
> Deployed at
> - Bsc testnet: 0x9E44c0F56f45FCCB273dD2253B884DBe05a9DACF

### GiGTune
> Deployed at
> - Bsc testnet: 0xF6Bfd7DDF8Bd923dbA5849F1c48c71b9f87bFf07

### GiGCampaign
> Deployed at
> - Bsc testnet: 0xfCDb6dC4E4D83408EEB13D6544b2Bd495CB37B7f

### GiGMint
> Deployed at
> - Bsc testnet: 0x98A423642a02081dDAF78BBeB41Aaa72Ed9Df6d5

## Development

### Environment Setup
.env file
```
PRIVATE_KEY=${YOUR_PRIVATE_KEY}
GIGMINT_TOKEN_ADDRESS=${YOUR_GIGTOKEN_ADDRESS}
GIGMINT_TUNE_ADDRESS=${YOUR_GIGTUNE_ADDRESS}
GIGMINT_CAMPAIGN_ADDRESS=${YOUR_GIGCAMPAIN_ADDRESS}
GIGMINT_ADDRESS=${YOUR_GIGMINT_ADDRESS}
```

### Deployment
- Deploy GiGToken to Bsc testnet
```bash
npx hardhat deploy_gigmint --network bsc_testnet
```

- Deploy GiGTune to Bsc testnet
```bash
npx hardhat deploy_gigtune --network bsc_testnet
```

- Deploy GiGCampaign to Bsc testnet

Warning: Make sure to set the `GIGMINT_TOKEN_ADDRESS` and `GIGMINT_TUNE_ADDRESS` in the .env file
```bash
npx hardhat deploy_gigcampaign --network bsc_testnet
```

- Deploy GiGMint to Bsc testnet

Warning: Make sure to set the `GIGMINT_TOKEN_ADDRESS`, `GIGMINT_TUNE_ADDRESS`, and `GIGMINT_CAMPAIGN_ADDRESS` in the .env file
```bash
npx hardhat deploy_gigmint --network bsc_testnet
```