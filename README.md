---
title: DeFi Toolkit by @gweicz
tags: defi, ethereum, eth, smart-contract
description: Curated list of best tools and resources for user of Ethereum (DeFi) ecosystem.
image: https://i.imgur.com/r48kTSf.png
---

# DeFi Toolkit by [@gweicz](https://twitter.com/gweicz)

[![hackmd-github-sync-badge](https://hackmd.io/m_QNVHFmSreR8Dttw50Fyg/badge)](https://hackmd.io/m_QNVHFmSreR8Dttw50Fyg)

Curated list of best tools and resources for user of Ethereum (DeFi) ecosystem.

Updates in [this thread on our forum](https://forum.gwei.cz/t/defi-toolkit-seznam-uzitecnych-nastroju/96) (in Czech language).

## Legend

| Link | Legend |
| -------- | -------- |
| :star:Item | must-have |
| ==Item== | newly added |

## Table of Contents

[TOC]

## Documentation
- :star:[`docs.ethhub.io`](https://docs.ethhub.io/)
- [Ethereum Whitepaper](https://ethereum.org/en/whitepaper/)
- [Ethereum Yellow Paper](https://ethereum.github.io/yellowpaper/paper.pdf) - formal protocol specification

## Security
- [`defiscore.io`](https://defiscore.io/) - risk score of DeFi platforms
- [`defiwatch.net`](https://defiwatch.net/) - admin keys, project reviews
- [`defisafety.com`](http://defisafety.com/) - safety ranking
- [`crypto51.app`](https://www.crypto51.app/) - 51% attack cost
- [Blockchain Security DB by ConsenSys Diligence](https://consensys.github.io/blockchainSecurityDB/)

## Network & Nodes
- [`ethstats.io`](https://ethstats.io/)
- [`forkmon.ethdevops.io`](https://forkmon.ethdevops.io/) - fork monitor (nodes and latest consensus)
- [`ethernodes.org`](https://ethernodes.org/) - node statistics
- [`ethereumnodes.com`](https://ethereumnodes.com) - list of public nodes
- [`chainid.network`](https://chainid.network/) - A list of EVM networks (for clients like Metamask)


## Blocks & Transactions
- :star:[`etherscan.io`](http://etherscan.io/)
- [`ethviewer.live`](http://www.ethviewer.live/)
- [Transaction visualizer @ `TxStreet.com`](https://txstreet.com/v/eth)
- [Transaction Reverts @ `duneanalytics.com`](https://explore.duneanalytics.com/public/dashboards/1dzncvBWwkFYvbYSMXbubJNCupAGFWU9hJmxja7r)
- [`ethtx.info`](https://ethtx.info/)

## Wallets
- ["Ethereum Wallet Comparison" article](https://github.com/shanefontaine/ethereum-wallet-comparison)
- [`sweeposaurus.com`](https://sweeposaurus.com/) - He'll make it easy to sweep all your tokens to a new address

<!-- ## Supply
- [ethsupply](https://github.com/madumas/ethsupply) - calculates the total amount of Eth ever issued[^ethsupply-source]
- [supply.go](https://gist.github.com/karalabe/4cc4bb89a32a93a194803654753c3fac) -->

## Fees (gas)

### Current Gas

- :star:[`ethgasstation.info`](https://ethgasstation.info/)
- [Gas Tracker @ `etherscan.io`](https://etherscan.io/gastracker)
- [`gasnow.org`](https://www.gasnow.org/) - forward-looking gas estimates (SparkPool)[^gasnow-src]
- [`ethgas.watch`](https://ethgas.watch/) - agreggator
- [`dethgasstation.eth.link`](http://dethgasstation.eth.link/) - gas estimator thru web3 provider

### Historic Gas
- [Ethereum Gas Charts @ `ethereumprice.org`](https://ethereumprice.org/gas/)
- [`txpool.zengo.com`](https://txpool.zengo.com/) - Ethereum TxPool Statistics
- [Gas Prices Dashboard @ `duneanalytics.com`](https://explore.duneanalytics.com/public/dashboards/qswVMdzbyiiZFdnCDSwx1jfYLOjdaokM4CSGNxsH)[^gas-dashboard-source]

### Gas Tools
- [Cancel Ethereum Transaction](https://cancel-ethereum-transactions.web.app/) ([source](https://github.com/mds1/Cancel-Ethereum-Transactions)) - micro dapp
- [`fees.wtf`](https://fees.wtf/) - calculate how much gas you spend
- [`txn.finance`](https://txn.finance/) - spend gas statistics[^txn-finance-src]
- [`ethgas.watch`](https://ethgas.watch/) - get notified when gas prices drop below the threshold[^ethgaswatch-src]
- [GasPriceTRackerBot @ `telegram.org`](https://t.me/GasPriceTRackerBot)

### Gas Tokens
- :star: [Chi Gastoken](https://medium.com/@1inch.exchange/everything-you-wanted-to-know-about-chi-gastoken-a1ba0ea55bf3) - everything you wanted to know
- [GasToken Miner](https://forum.saturn.network/t/how-to-use-gastoken-miner/2433) - script for mining GST1, GST2, CHI
- [Automated buying of Chi Tokens @ `hal.xyz`](https://9000.hal.xyz/recipes/1inch-buy-chi-token)
- [Liquid Gas Token ($LGT) Exchange](https://lgt.exchange/) ([whitepaper](https://github.com/matnad/liquid-gas-token/blob/master/thesis/LiquidGasToken_Nadler2020.pdf))


## Private Key & Address
- [`iancoleman.io/bip39`](https://iancoleman.io/bip39/) - BIP39 derivation (mnemonic)
- [profanity](https://github.com/johguse/profanity) - high performance vanity generator (incl. GPU)
- [`vanity-eth.tk`](https://vanity-eth.tk/) ([source](https://github.com/bokub/vanity-eth)) - web variant
- [Vanity Eth generators @ `github.com`](https://github.com/search?q=eth+vanity)

## Recovery
- [`findeth.io`](https://findeth.io/) - find your lost Ether or address

## Meta Transactions
- [`furucombo.app`](https://furucombo.app/) - transaction "combo"
- [`disperse.app`](https://disperse.app/) - distribute ether or tokens to multiple addresses
- [`bulksender.app`](https://bulksender.app/)
- [erc20-meta-token](https://github.com/arcadeum/erc20-meta-token) - wrapper for meta-transaction with any ERC-20

## Custom Transactions
- [Send Offline Helper](https://www.myetherwallet.com/send-offline-helper)
- [Broadcast Raw Transaction @ `etherscan.io`](https://etherscan.io/pushTx)
- [Get Raw Transaction Hex @ `etherscan.io`](https://etherscan.io/getRawTx?tx=0xeb20185d7be6012b4753d17707b0f776511c4db3ecf65ad7dbdc660964e0864f)
- [Eth Tx Decoder](https://antoncoding.github.io/eth-tx-decoder/) ([source](https://github.com/antoncoding/eth-tx-decoder)) - decode raw transaction
- [Ethereum input data decoder](https://lab.miguelmota.com/ethereum-input-data-decoder) ([source](https://github.com/miguelmota/ethereum-input-data-decoder))

## Automation
- [`hal.xyz`](https://www.hal.xyz/)

## Allowances
- [Token Approvals @ `etherscan.io`](https://etherscan.io/tokenapprovalchecker)
- [`tac.dappstar.io`](https://tac.dappstar.io/) - Token Allowance Checker
- [`revoke.cash`](https://revoke.cash/)
- [`approved.zone`](https://approved.zone/)

## Portfolio Trackers
- :star:[`zapper.fi`](https://www.zapper.fi/)
- :star:[`zerion.io`](https://app.zerion.io/)
- [`debank.com`](https://debank.com/)

## Financial Metrics (Dashboards)
- [`ethdashboard.com`](https://ethdashboard.com/)
- [DeFi Insight @ `intotheblock.com`](https://app.intotheblock.com/insights/defi/charts)
- [`ethereumprice.org`](https://ethereumprice.org/) - Blockchain cap, ETH leveraged/dominance
- [`duneanalytics.com/dex`](https://duneanalytics.com/dex)

## TVL (Total Value Locked)
- [`defipulse.com`](https://defipulse.com/)
- [`defillama.com`](https://defillama.com/home)
- [`defimarketcap.io`](https://defimarketcap.io/)

## Token Swaps
- [`1inch.exchange`](https://1inch.exchange/)
- [`matcha.xyz`](https://matcha.xyz/)
- [`debank.com/swap`](https://debank.com/swap)
- [`dexindex.io`](https://dexindex.io/)

## Communication
- [`ethmail.cc`](https://ethmail.cc/) - mailbox for all people who have Ethereum wallet

## Mempool Data
- [`Blocknative.com`](https://blocknative.com/) - a composable mempool data platofrm. Watch any address for real-time status updates

## Prediction Markets
- [`predictions.exchange`](https://www.predictions.exchange/) - list of markets (Augur, Omen, Flux in future)
- [`predictionexplorer.com`](https://predictionexplorer.com)

## Oracles
- [`oracles.club`](https://oracles.club/) - overview of all oracles (Maker, Chainlink, ..)

## DAOs
- [`deepdao.world`](http://deepdao.world/) - overview of all DAOs (Aragon, Moloch, ..)
<!-- - [`daometrics.com`](https://daometrics.com/) -->

## BTC on Ethereum
- [`btconethereum.com`](https://btconethereum.com/)
- [BTC on ETH Graph @ `predictions.exchange`](http://www.predictions.exchange/ethbtc/)
- [BTC on Ethereum @ `dunenalytics.com`](https://explore.duneanalytics.com/public/dashboards/ffM8FLsAcRYLcGc0JdaoU6oLOk8ThGXZ9cJ1XKJn)

## Yield Farming
- [Yield Farms @ `coingecko.com`](https://www.coingecko.com/en/yield-farming)
- [Yield Farms @ `etherscan.io`](http://etherscan.io/yieldfarms)
- [`yieldfarming.info`](https://yieldfarming.info/)
- [`yieldfarmingtools.com`](https://yieldfarmingtools.com/)
- [`vfat.tools`](https://vfat.tools/)

## Layer 2
- ==[`l2beat.com`](https://www.l2beat.com/) - list of L2s, TVL statistics==
- ["Evaluating Ethereum L2 Scaling Solutions: A Comparison Framework"](https://medium.com/matter-labs/evaluating-ethereum-l2-scaling-solutions-a-comparison-framework-b6b2f410f955)

## Social Money
- [List of social tokens @ `forefront.news`](https://forefront.news/market/)[^forefront-src]

## Contract Inspection
- [Ethereum Contract DiffChecker](https://yieldfarming.info/tools/diff/)[^diffchecker-src]

## Contract Interaction
- [`ethcontract.watch`](https://ethcontract.watch/) - generates the UI from ABI

## Governance
- [`snapshot.page`](https://snapshot.page/) - yEarn and YAM governance

## NFTs
- [`cryptoart.io`](http://cryptoart.io/) - top artists and artworks
- [`cryptoartpulse.com`](https://cryptoartpulse.com/)
- [`nftfi.com`](https://nftfi.com/) - use your NFTs as loan collateral
- [`pumpmygas.xyz`](https://pumpmygas.xyz/) - Live estimates of gas fees on all major NFT marketplaces for creators, buyers, and sellers Fuel pump

## Token Claims (Airdrops)

- [`earni.fi`](https://earni.fi/) - Find which airdrops and POAPs are waiting for you to claim
- ==[Airdrops @ `etherscan.io`](https://etherscan.io/airdrops)==

## MEV (Miner Extractable Value)
- ==[`flashbots.net`](flashbots.net)==
- ==[`explore.flashbots.net`](https://explore.flashbots.net/) - Flashbots MEV statistics==

## Protocols

### 0x
- [`0xtracker.com`](https://0xtracker.com/)

### Aave
- [`aavewatch.now.sh`](https://aavewatch.now.sh/)
- [`aave-futuristic-dashboard.now.sh`](https://aave-futuristic-dashboard.now.sh/)
- [`governance.aave.com`](https://governance.aave.com/) - Governance forum
- ["The Aavesome List"](https://github.com/marczeller/Aavesome-list)

### Aragon
- [List of Aragon DAOs](https://apiary.1hive.org/orgs)
<!-- - ["Awesome Aragon"](vhttps://github.com/lkngtn/awesome-aragon) -->

### Balancer
- [`pools.vision`](http://pools.vision/)

### Bancor
- [Dashboard @ `duneanalytics.com`](https://explore.duneanalytics.com/public/dashboards/kkvyor52spBBLRWpTDswfafl2uRDhMOaErhNHGoU)

### Compound
- [`stat.farm`](https://stat.farm/) ([source](https://github.com/Anish-Agnihotri/stat.farm))
- [`divided.house`](https://divided.house/) - governance proposals
- [`deflast.finance`](https://deflast.finance/) - Instantly swap your collateral

### CryptoKitties
- [`kittysales.herokuapp.com`](https://kittysales.herokuapp.com/)

### Curve
- [Dashboard @ `duneanalytics.com`](https://explore.duneanalytics.com/public/dashboards/RTH47mNjQcoLv5oG0HMDdI0iDq7BHxk1PzCRdwQB)[^curve-source]

### dYdX
- [Dashboard @ `duneanalytics.com`](https://explore.duneanalytics.com/public/dashboards/AU7ZSx67NOEwqELtIDyzpPlpAGNJJnW0hmeuwwO9)[^dydx-da-src]

### Indexed Finance
- [Dashboard @ `duneanalytics.com`](https://duneanalytics.com/0xBoxer/indexed-finance_3)

### Keep
- [`explorer.keep-grants.info`](https://explorer.keep-grants.info/)

### Kleros
- [`kleroscan.com`](http://kleroscan.com/)

### MakerDAO / DAI

- [`daistats.com`](https://daistats.com/) - basic metrics (capitalizations, fees etc.)
- [`catflip.co`](https://catflip.co/) - system params, changelog, voting
- [Collateralization graphs @ `decipher.io`](http://makervaults.descipher.io/)
- [`makerburn.com`](https://makerburn.com/)

#### DAI Peg
- [`daipeg.com`](https://daipeg.com/) - DAI Trading charts
- [DAI graphs @ `descipher.io`](http://dai.descipher.io/)

#### Auctions
- [`daiauctions.com`](https://daiauctions.com)
- [`maker-auctions.io`](https://maker-auctions.io/)
- [`flops.live`](https://flops.live/) - Debt Auctions Tracker

#### Tools & others
- [`makerburn.com`](https://makerburn.com/)
- [`collateralswap.com`](https://collateralswap.com/)
- ["Awesome MakerDAO"](https://github.com/makerdao/awesome-makerdao)

### Matcha
- [Dashboard @ `duneanalytics.com`](http://duneanalytics.com/matcha)

### Nexus Mutual
- [`nexustracker.io`](https://nexustracker.io/)
- [wNXM Wrap/Unwrap](https://je45e4c2q4x52s66qenp5aeyfonfsvkvupkf4ipefkzs364gbera.arweave.net/STnScFqHL91L3oEa_oCYK5pZVVWj1F4h5CqzLfuGCSI/#/)[^wnxm-source]

### Nuo
- [`nuoscan.io`](https://nuoscan.io/)

### Omen
- [`omenfarming.com`](https://omenfarming.com/)
- [Omen Stats @ `duneanalytics.com`](https://explore.duneanalytics.com/dashboard/omen-stats) [needs login]

### Opyn
- [`opynmonitor.xyz`](https://opynmonitor.xyz/)

### Ren
- [Dashboard @ `duneanalytics.com`](https://explore.duneanalytics.com/public/dashboards/hXk0g5BaYNrIfqKwuqXTiRDTqD4UAszmoGzebIlV)

### SushiSwap
- [`sushi.zippo.io`](https://sushi.zippo.io/)

### Synthetix
- [snx.link](https://snx.link/) - cheaper trading thanks to [Gas Tokens](#Gas-Tokens)
- [`snx.tools`](https://snx.tools/)
- [`synthetixstats.com`](https://synthetixstats.com/)
- [`sips.synthetix.io`](https://sips.synthetix.io/) - Synthetix Improvement Proposals
- [`synthetix.community`](https://synthetix.community/) - docs, guides

### THORChain
- [`thorchain.help`](https://thorchain.help/)
- [`leaderboard.thornode.org`](https://leaderboard.thornode.org)
- [`bepswapsimulator.info`](https://www.bepswapsimulator.info/)

### TokenSets
- [`tokenviz.io`](https://tokenviz.io/)

### Uniswap
- [`uniswap.vision`](https://uniswap.vision/) - TradingView interface
- [`chartex.pro`](https://chartex.pro/?symbol=UNISWAP:DIA) - TradingView interface for low-caps
- [`dextools.io`](https://www.dextools.io/app/uniswap/pool-explorer) - Pool/Pair Explorer
- [`pools.fyi`](https://pools.fyi/)
- [`tokenscan.xyz`](http://tokenscan.xyz/) - Discover trending pools[^tokenscan-src]
- [`duneanalytics.com/uni`](https://duneanalytics.com/uni) - UNI token claims
- [Lost $UNI statistics @ `duneanalytics.com`](https://explore.duneanalytics.com/dashboard/uni-lost-tokens) [needs login]
- [Permanent Loss™](https://permanentloss.app//)
- [Impermanent Loss Calculator](https://chitty27.pythonanywhere.com/)
- ["A short history of Uniswap" article](https://uniswap.org/blog/uniswap-history/)

### YAM
- [`yam.zippo.io`](https://yam.zippo.io/)[^yam-zippo-src]
- [`yam.tools`](https://yam.tools/)
- [`yam.chainwiki.dev`](https://yam.chainwiki.dev/)
- [`duneanalytics.com/yam`](http://duneanalytics.com/yam)
- [`treasury.vision`](https://treasury.vision/)

### Yearn
- [`yfi.fyi`](http://yfi.fyi) - Index of services
- [`py-earn.herokuapp.com`](https://py-earn.herokuapp.com/)
- [`gov.yearn.finance`](https://gov.yearn.finance/) - Governance forum
- [`learnyearn.finance`](https://www.learnyearn.finance/)

## Flippening
- [`flippening.watch`](https://www.flippening.watch/)
- [`ratiogang.com`](https://ratiogang.com/)
- [`money-movers.info`](https://money-movers.info/)

## Books
- ["Mastering Ethereum" by Andreas M. Antonopoulos and Gavin Wood](https://ethereumbook.info/)
- ["The Infinite Machine" by Camila Russo](https://www.harpercollins.com/products/the-infinite-machine-camila-russo)

## Newsletters
- [The Daily Gwei](https://thedailygwei.substack.com/) ([Youtube](https://www.youtube.com/channel/UCvCp6vKY5jDr87htKH6hgDA))
- [Today in DeFi](https://todayindefi.substack.com/)
- [Week In Ethereum](https://weekinethereum.substack.com/)
- [Bankless](http://bankless.substack.com/)
- [The Defiant](https://thedefiant.substack.com/) ([Youtube](https://www.youtube.com/channel/UCL0J4MLEdLP0-UyLu0hCktg))

## Programming
- [ETH.Build](https://eth.build/)

## Research

### EIP-1559
- [Projected Daily ETH Issuance @ `duneanalytics.com`](https://explore.duneanalytics.com/public/dashboards/zrSKhqUarjkKrvfCgYjuPcUvW39R4ewxXZ3pwpWG)

## Ethereum 2.0
- :star: [`beaconcha.in`](https://beaconcha.in/)
- [`beaconscan.com`](https://beaconscan.com/)
- [`eth2stats.io`](https://eth2stats.io/)
- [Ethereum 2.0 @ `ethhub.com`](https://docs.ethhub.io/ethereum-roadmap/ethereum-2.0/eth-2.0-phases/)
- [Ethereum 2.0 clients @ `ethhub.com`](https://docs.ethhub.io/ethereum-roadmap/ethereum-2.0/eth2.0-teams/teams-building-eth2.0/)
- [`eth2-fork-mon.stokes.io`](https://eth2-fork-mon.stokes.io/) - Eth2 fork monitor


## Fun
- [`feedvitalik.com`](https://feedvitalik.com/) ([source](https://github.com/bford21/FeedVitalik))


---

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

Created by [Gwei.cz](https://gwei.cz) Community ([@gweicz](https://twitter.com/gweicz))

Curator: @treecz ([twitter](https://twitter.com/treecz))

Most important sources:
- [Ethereum community @ Twitter](https://hive.one/ethereum)
- <https://github.com/denisnazarov/awesome-crypto-trackers>
- <https://github.com/colekennelly1/awesome-defi-trackers>


[^wnxm-source]: https://twitter.com/BatmanDeFi/status/1284206337165910016
[^ethsupply-source]: https://twitter.com/marcandu/status/1291840343047118854
[^curve-source]: https://twitter.com/CurveFinance/status/1243327941091577856?s=20
[^gas-dashboard-source]: https://twitter.com/alex_kroeger/status/1294093017901670411
[^forefront-src]: https://twitter.com/carlosecgomes/status/1293215171729530880
[^yam-zippo-src]: https://twitter.com/zippoxer/status/1293342696531255302?s=2
[^dydx-da-src]: https://twitter.com/DuneAnalytics/status/1237752192267882496
[^gasnow-src]: https://twitter.com/sparkpool_eth/status/1293739552197103616
[^tokenscan-src]: https://twitter.com/0xdev0/status/1296724941287563264
[^diffchecker-src]: https://twitter.com/Weeb_Mcgee/status/1296189359650209795
[^ethgaswatch-src]: https://twitter.com/wslyvh/status/1298274040574930945
[^txn-finance-src]: https://twitter.com/tansawit/status/1308374889082974208