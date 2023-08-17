|||
|-|-|
|🐺|Code4rena|
|🕵|Sherlock|

## [PoolTogether (06/23)](https://code4rena.com/contests/2023-07-pooltogether) 🐺

TBD

|Type|Issue|
|:--:|--|
|H||
|M (SOLO)||
|M||
|M||

## [Symmetrical (06/23)](https://audits.sherlock.xyz/contests/85) 🕵

TBD

|Type|Issue|
|:--:|--|

## [Iron Bank (05/23)](https://audits.sherlock.xyz/contests/84) 🕵

|Type|Issue|
|:--:|--|
|M|[Chainlink price feed data not validated properly](https://github.com/sherlock-audit/2023-05-ironbank-judging/issues/261)|
|M|[It is not checked whether the sequencer is down when fetching the price from Chainlink](https://github.com/sherlock-audit/2023-05-ironbank-judging/issues/262)|
|M|[Wrong price returned by oracle if asset's price drops below `minAnswer`](https://github.com/sherlock-audit/2023-05-ironbank-judging/issues/265)|

## [USSD (05/23)](https://app.sherlock.xyz/audits/contests/82) 🕵

|Type|Issue|
|:--:|--|
|H|[The calculations of DAI price in `StableOracleDAI.sol:getPriceUSD()` are incorrect](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/66)|
|H|[Spot price of USSD/DAI pool can be manipulated](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/175)|
|H|[No slippage protection for swaps](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/73)|
|H|[Anyone can mint and burn tokens for/from the USSD contract](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/68)|
|H|[Wrong address for `ethOracle` in `StableOracleDAI.sol`](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/64)|
|H|[Wrong address for `DAIEthOracle` in `StableOracleDAI.sol:DAIEthOracle` and `StableOracleWBGL.sol:staticOracleUniV3`](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/65)|
|H|[Wrong address for `BTC/USD` Chainlink aggregator contract](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/63)|
|M|[Removing collateral token changes order in array](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/72)|
|M|[Chainlink price feed data could be stale](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/62)|
|M|[Lack of Chainlink price feed data validation](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/71)|

## [DODO (05/23)](https://app.sherlock.xyz/audits/contests/78) 🕵

|Type|Issue|
|:--:|--|
|H|[Flash loan callback can be used to steal tokens](https://github.com/sherlock-audit/2023-05-dodo-judging/issues/76)|

## [Footium (05/23)](https://app.sherlock.xyz/audits/contests/71) 🕵

|Type|Issue|
|:--:|--|
|H|[Approvals for `FootiumEscrow` remain active after the club owner changes](https://github.com/sherlock-audit/2023-04-footium-judging/issues/211)|
|M|[Return value of ERC20 transfer not checked](https://github.com/sherlock-audit/2023-04-footium-judging/issues/212)|
|M|[`maxGenerationId` + 1 players can be minted per cohort](https://github.com/sherlock-audit/2023-04-footium-judging/issues/219)|

## [Teller (04/23)](https://app.sherlock.xyz/audits/contests/62) 🕵

|Type|Issue|
|:--:|--|
|H|[`CollateralManger.sol:setCollateralEscrowBeacon` can be called by anyone](https://github.com/sherlock-audit/2023-03-teller-judging/issues/236)|
|H|[Committed collateral can be updated by any user at any time](https://github.com/sherlock-audit/2023-03-teller-judging/issues/233)|
|M|[Admin can update `LenderManager` address in `TellerV2`](https://github.com/sherlock-audit/2023-03-teller-judging/issues/240)|
|M|[Fee-on-transfer token collateral will lock deposits in escrow](https://github.com/sherlock-audit/2023-03-teller-judging/issues/235)|

## [Caviar (04/23)](https://code4rena.com/contests/2023-04-caviar-private-pools) 🐺

|Type|Issue|
|:--:|--|
|M|[Incorrect calculation of flash loan fee](https://github.com/code-423n4/2023-04-caviar-findings/issues/477)|
|M|[`change` fails for tokens with less than 4 decimals](https://github.com/code-423n4/2023-04-caviar-findings/issues/473)|
|M|[Royalties recipient can make `buy` and `sell` revert](https://github.com/code-423n4/2023-04-caviar-findings/issues/470)|

## [Contest 225 (03/23)](https://code4rena.com/contests/2023-03-contest-225-contest) 🐺

Private contest

|Type|Issue|
|:--:|--|
|H|H-1|
|M|M-1|

## [Asymmetry (03/23)](https://code4rena.com/contests/2023-03-asymmetry-contest) 🐺

|Type|Issue|
|:--:|--|
|H|[First staker can get ETH from other stakers](https://github.com/code-423n4/2023-03-asymmetry-findings/issues/523)|
|H|[Error in calculations of total deposits of rETH](https://github.com/code-423n4/2023-03-asymmetry-findings/issues/909)|
|H|[It is assumed that the price of ETH-stETH is 1](https://github.com/code-423n4/2023-03-asymmetry-findings/issues/519)|
|M|[It is not checked if Rocket Pool deposits are enabled](https://github.com/code-423n4/2023-03-asymmetry-findings/issues/520)|
|M|[Rocket Pool withdrawals can be timelocked](https://github.com/code-423n4/2023-03-asymmetry-findings/issues/522)|

## [Y2K (03/23)](https://app.sherlock.xyz/audits/contests/57) 🕵

|Type|Issue|
|:--:|--|
|H|[`enlistInRollover()` stores wrong index for receiver](https://github.com/sherlock-audit/2023-03-Y2K-judging/issues/104)|

## [Taurus (03/23)](https://app.sherlock.xyz/audits/contests/45) 🕵

|Type|Issue|
|:--:|--|
|M|[TAU `currentMinted` amount is not updated when tokens are burned from vault](https://github.com/sherlock-audit/2023-03-taurus-judging/issues/142)|
|M|[`UniswapSwapAdapter.swap()` only works for paths formed by two tokens](https://github.com/sherlock-audit/2023-03-taurus-judging/issues/141)|

## [Surge (02/23)](https://app.sherlock.xyz/audits/contests/51) 🕵

|Type|Issue|
|:--:|--|
|M (SOLO)|[Users can borrow all loan tokens](https://github.com/sherlock-audit/2023-02-surge-judging/issues/106)|
