# avault-multichain-web-static

## `/api/vault_base_config.json`

- chain
- dapp
- status 0 close 1 online 2 waiting
  - vaultType: 1 stablecoin 2 single 3 lp_token

```json
[
  {
    "status": 1,
    "chain": "Astar",
    "dapp": [
      {
        "dappName": "AAVE",
        "contract": [
          {
            "vaultAddress": "",
            "vaultType": 0
          }
        ]
      }
    ]
  },
  {
    "status": 1,
    "chain": "Ethereum",
    "dapp": ["AAVE"]
  },
  {
    "status": 1,
    "chain": "Arbitrum",
    "dapp": ["AAVE"]
  }
]
```
