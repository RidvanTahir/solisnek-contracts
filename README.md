# SoliSnek Smart Contracts

## Scripts

deploy/test-token.ts (for testnet only)
deploy/lge.ts
deploy/logics.ts
deploy/deployer.ts
operation/verify-proxy.ts
operation/mine-address.ts
deploy/token.ts
deploy/dex.ts
operation/add-liquidity.ts (for weth/usdc)
operation/verify-pair.ts
deploy/vote-system.ts

## Testnet

### Implementations

| Contract              | Address                                    |
| --------------------- | ------------------------------------------ |
| Snek                  | 0xfF7Dcc26D9a5E24974f27936BEA2895532F373a5 |
| PairFactory           | 0xA15302aECD6C9646AEA06E429Af83d0DFD358501 |
| Pair                  | 0x95171AA21A29A3cFa53BaB78345DD939fBb19802 |
| Router                | 0x62bca03dFc65FfC9c9D96bA1AB6cc2135eFF6b52 |
| SnekLibrary           | 0x991673ca3cD1e0960463bDa7cFC688C2867c080F |
| VeArtProxy            | 0xd09Cffc843710749B550b299243A7ff84b462fd1 |
| VotingEscrow          | 0x270ef8f7364EE60CE0b486e90E5f99Bc2eb9Ea96 |
| FeeDistributorFactory | 0x53B6c760282767dd9F8b5c518a725B91Dc906428 |
| GaugeFactory          | 0x9Dd766Df594D787Bb3f07438d135c4C42d31E4dF |
| Voter                 | 0x4184C04A7f7c8cB002Fe3F067ad570dBfbF64d75 |
| RewardsDistributor    | 0x64088aA4B2876473809fC0fEe2372b554226fe09 |
| Minter                | 0xAeD4184C0e14DD77af0c980bB8DDcA8f0715A581 |

### Deployer

| Contract   | Address                                    |
| ---------- | ------------------------------------------ |
| ProxyAdmin | 0xa9B41ce6BD3F781Ead19d33b142270B392e7A5e2 |
| Deployer   | 0x3C252a188Aa35D5B08Ca141d79CBDC951Bc160F0 |

### Proxies

| Contract              | Address                                    |
| --------------------- | ------------------------------------------ |
| Snek                  | 0xeeee97AC0f417D220dFfA3DCCbf6121C53541513 |
| PairFactory           | 0xeeee175CC85Db8D1245094B0f83e39b0128a8D6B |
| Router                | 0xeeee1b84A9D7F1648ee1537D23E233283B042FA1 |
| SnekLibrary           | 0xeeee107104Dc4Bd4b3339eF6e9081572ac015DF4 |
| VeArtProxy            | 0xeeee22cd7047966eDBE47Ff5698d34159C953cCF |
| VotingEscrow          | 0xeeee3823509dF4819F3D7F4B93D314e9a2fc8d9f |
| FeeDistributorFactory | 0xeeee461cFc20E385891380BC5d4DACc258ff50F5 |
| GaugeFactory          | 0xeeee55A381ca608B45a550A0c261B9ADa9C645f5 |
| Voter                 | 0xeeee674b981F7A0266c099bdD8150B137996cC31 |
| RewardsDistributor    | 0xeeee794A5dd290Eb5CC92598A08EB61fE6D5f261 |
| Minter                | 0xeeee84244DD0A1dE06493A0252dC02A238C04988 |

### Test Tokens

| Token | Address                                    |
| ----- | ------------------------------------------ |
| wavax | 0xd00ae08403B9bbb9124bB305C09058E32C39A48c |
| weth  | 0xB124CD5F735810B3C672A4a0a208f0aAEF861201 |
| usdc  | 0x8530f66241E47eE93dbDd3542455889f9f12FA6E |
| usdt  | 0x3Bb3dA843522f65b18d1E23d63124AA035f9A3D1 |
| mim   | 0x6223D4BF70e5aD440c41F39F3420178a0CF3AC70 |
| dai   | 0x3383791f2C0CCd0f6f8f39043cBBb009DD9d7E21 |

## Mainnet

LGE: 0xe1Fa7CBD4a47B0Ebef5a93a2aa9cE8EEA2694e59

### Implementations

07:12:44 INFO FeeDistributorFactory: 0xD605DAfDFffd7Db34022639a18a5A113f1E0B045
07:12:44 INFO GaugeFactory: 0x8A125D994d655C7f1dd527282A1F3888C9Ed1Cd9
07:12:44 INFO PairFactory: 0x0fC46a8Fc906F026E2cBE6a259A70D493fcC9D17
07:12:44 INFO Minter: 0x70C8173Ba11e22cd3Dd104484c5A362b3042728E
07:12:44 INFO Pair: 0x5AeF491b234Ce47CAD75f917C242610Ae994f581
07:12:44 INFO RewardsDistributor: 0x960588b21ab1693A6F76F3c693019798cCb8988C
07:12:44 INFO Router: 0xB5116Bc84125E7685b84EA22e9243c5C2E821eae
07:12:44 INFO Snek: 0xD716fd6763355Faee2615Ac878064f907A456cDd
07:12:44 INFO SnekLibrary: 0x4390aDF0C2Eb0494D251a49c0435f06F1762D8bE
07:12:44 INFO VeArtProxy: 0xd377b09E4313c079Dc2aB17a2C1ab58F11e6d819
07:12:44 INFO Voter: 0x1865051a62Bb670A2b0Df330764990d16D2B3019
07:12:44 INFO VotingEscrow: 0x7C3623a1C6284EcdBb6B0a63c18ba487a202a45c

### Deployer

proxy admin: 0xCa6F5401C608d0E8242c638bd30af0F594A97118
deployer: 0x0EC828edd906CD602D619a78e02c66CaeDF61440
