---
sip: <to be assigned>
title: Support GHO as LP collateral on Arbitrum
network: Arbitrum
status: Draft
type: Governance
author: TokenLogic (@TokenLogic-com-au)
implementor: TokenLogic (@TokenLogic-com-au)
release: TBD
implementation-date: TBD
discussions-to: TBD
created: 2024-09-18
---

## Simple Summary

This SIP proposes to add support for Aave's GHO Stablecoin (GHO) as LP collateral on Sinthetix v3 on Arbitrum.

## Abstract

Add GHO as a supported collateral type for Arbitrum V3 deployment with minting at 125% C-ratio and a maximum LP cap of $50M.

## Motivation

GHO is a decentralized multi-collateral stablecoin that is fully backed, transparent and native to the Aave Protocol with over [155M](https://aave.tokenlogic.xyz/gho) of circulating supply.

The collateral ratio exceeds [2.20](https://aave.tokenlogic.xyz/collateral) and is consists of by high-quality assets like wstETH and wETH making up [23.67%](https://aave.tokenlogic.xyz/gho) and [20.20%](https://aave.tokenlogic.xyz/gho) respectively of all collateral.

The Aave Liquidity Committee (ALC) is eager to explore integrations that expected to drive GHO's expansion across various protocols and chains.

Further details about GHO can be found [here](https://docs.gho.xyz/).

The Chainlink CCIP bridge was deployed by Aave Governance and has been in production since early July. GHO has also been integrated into Aave v3 on Arbitrum.

With the initial phase of the launch complete, it's time to accelerate GHO's growth on Arbitrum. Integrating GHO as a collateral asset into Synthetix v3 is a strategic move that supports this expansion.

## Specification

### Overview

Implementation of this SIP will be contingent on the availability of a high frequency GHO price oracle on Arbitrum. This is actively being developed by Chainlink.

The below details the GHO LP Configurable Values (Via SCCP)

| Parameter         | Value |
| ----------------- | ----- |
| Maximum LP amount | $50M  |
| Issuance Ratio    | 125%  |
| Liquidation Ratio | 105%  |

### Test Cases

## Copyright

Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
