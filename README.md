# avault-multichain-web-static

## `/api/vault_base_config.json`

- chain
- dapp
- status 0 close 1 online 2 waiting
  - vaulttype: 1 stablecoin 2 single 3 lp_token
  - eventtype: 0 normal 1 active 2 addNew

```json
[
  {
    "status": 1,
    "chain": "Astar",
    "dapp": [
      {
        "dappname": "AAVE",
        "contract": [
          {
            "vaultAddress": "",
            "vaulttype": 0
          }
        ]
      }
    ]
  },
  {
    "status": 1,
    "chain": "ethereum",
    "dapp": ["AAVE"]
  },
  {
    "status": 1,
    "chain": "arbitrum",
    "dapp": ["AAVE"]
  }
]
```
