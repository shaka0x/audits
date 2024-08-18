|||
|-|-|
|🐺|Code4rena|
|🕵|Sherlock|
|🦅|CodeHaws|
|🪐|Cantina|
|🅿️|Pashov Audit Group|

# 2024
- [Nabla](https://github.com/pashov/audits/blob/master/team/md/Nabla-security-review.md) 🅿️
- [Reya Network](https://github.com/pashov/audits/blob/master/team/md/ReyaNetwork-security-review.md) 🅿️
- [Karak](https://github.com/pashov/audits/blob/master/team/md/Karak-security-review.md) 🅿️
- [Ion](https://github.com/pashov/audits/blob/master/team/md/IonProtocol-security-review.md) 🅿️
- [Sharwa Finance](https://github.com/pashov/audits/blob/master/team/md/SharwaFinance-security-review.md) 🅿️
- [HoneyJar](https://github.com/pashov/audits/blob/master/team/md/HoneyJar-security-review.md) 🅿️
- [Serious Market](https://github.com/pashov/audits/blob/master/team/md/Serious-security-review.md) 🅿️
- [Euler](#euler-0524-) 🪐
- [Axis Finance](#axis-finance-0324-) 🕵
- [Revert Lend](#revert-lend-0324-) 🐺
- [Rio Network](#rio-network-0224-) 🕵
- [Opal](#opal-0224-) 🪐
- [AI Arena](#ai-arena-0224-) 🐺
- [ZeroLend](#zerolend-0124-) 🪐
- [Flat Money](#flat-money-0124-) 🕵
- [Ubiquity](#ubiquity-0124-) 🕵

# 2023
- [Revolution](#revolution-1223-) 🐺
- [Badger eBTC](#badger-ebtc-1023-) 🐺
- [DittoETH](#dittoeth-0923-) 🦅
- [Tokemak](#tokemak-0723-) 🕵
- [PoolTogether](#pooltogether-0723-) 🐺
- [Symmetrical](#symmetrical-0623-) 🕵
- [Iron Bank](#iron-bank-0523-) 🕵
- [USSD](#ussd-0523-) 🕵
- [DODO](#dodo-0523-) 🕵
- [Footium](#footium-0523-) 🕵
- [Teller](#teller-0423-) 🕵
- [Caviar](#caviar-0423-) 🐺
- [Contest 225](#contest-225-0323-) 🐺
- [Asymmetry](#asymmetry-0323-) 🐺
- [Y2K](#y2k-0323-) 🕵
- [Taurus](#taurus-0323-) 🕵
- [Surge](#surge-0223-) 🕵

## [Euler (05/24)](https://cantina.xyz/competitions/41306bb9-2bb8-4da6-95c3-66b85e11639f) 🪐

|Type|Issue|
|:--:|--|
|L|[Cash amount can overflow on repayment](https://cantina.xyz/code/41306bb9-2bb8-4da6-95c3-66b85e11639f/findings/161)|
|L|[`repayWithShares` does not allow to repay partial debt](https://cantina.xyz/code/41306bb9-2bb8-4da6-95c3-66b85e11639f/findings/159)|
|L|[Using a nested vault as a collateral in the underlying vault will revert on the `calculateLiquidity` function due to reentrancy](https://cantina.xyz/code/41306bb9-2bb8-4da6-95c3-66b85e11639f/findings/157)|

## [Axis Finance (03/24)](https://audits.sherlock.xyz/contests/206) 🕵

|Type|Issue|
|:--:|--|
|H|[`Auctioneer.auction` stores always the `Routing` data for new auctions using `lotId` 0](https://github.com/sherlock-audit/2024-03-axis-finance-judging/issues/238)|
|M|[Settlement of batch auction can exceed the gas limit](https://github.com/sherlock-audit/2024-03-axis-finance-judging/issues/237)|
|M|[DoS for EMPAM `refundBid`](https://github.com/sherlock-audit/2024-03-axis-finance-judging/issues/235)|

## [Revert Lend (03/24)](https://code4rena.com/audits/2024-03-revert-lend) 🐺

|Type|Issue|
|:--:|--|
|M|[Daily limits are calculated incorrectly](https://github.com/code-423n4/2024-03-revert-lend-findings/issues/329)|
|M|[`V3Vault` does not implement correctly `maxDeposit` and `maxMint`](https://github.com/code-423n4/2024-03-revert-lend-findings/issues/332)|
|M|[Liquidations can be DoSed by repaying minimum amount](https://github.com/code-423n4/2024-03-revert-lend-findings/issues/333)|
|M|[Loans can be liquidated in the block after their creation](https://github.com/code-423n4/2024-03-revert-lend-findings/issues/336)|

## [Rio Network (02/24)](https://audits.sherlock.xyz/contests/176) 🕵

|Type|Issue|
|:--:|--|
|H|[Assets for withdrawal can be locked](https://github.com/sherlock-audit/2024-02-rio-network-core-protocol-judging/issues/315)|
|H|[The operator utilization heap is not updated correctly when a operator is deactivated](https://github.com/sherlock-audit/2024-02-rio-network-core-protocol-judging/issues/316)|
|M|[Restaking tokens are not priced correctly when there are withdrawals queued](https://github.com/sherlock-audit/2024-02-rio-network-core-protocol-judging/issues/314)|
|M|[Rebalance DoS due to errors in allocation calculations](https://github.com/sherlock-audit/2024-02-rio-network-core-protocol-judging/issues/318)|

## [Opal (02/24)](https://cantina.xyz/competitions/28425672-ce54-4c66-b188-c4d5650d6790) 🪐

|Type|Issue|
|:--:|--|
|H|[Incorrect USD price returned for price feeds that are not normalized to 8 decimals](https://cantina.xyz/code/28425672-ce54-4c66-b188-c4d5650d6790/findings/f832074d-7942-4bcd-95ad-62ba5a59524a)|

## [AI Arena (02/24)](https://code4rena.com/audits/2024-02-ai-arena) 🐺

|Type|Issue|
|:--:|--|
|H|[Non-transferable game items can be transferred](https://github.com/code-423n4/2024-02-ai-arena-findings/issues/1915)|
|H|[The `_ableToTransfer` check can be bypassed for fighter NFTs](https://github.com/code-423n4/2024-02-ai-arena-findings/issues/1918)|
|H|[Minting fighters will fail after generation 0](https://github.com/code-423n4/2024-02-ai-arena-findings/issues/1919)|
|H|[`FighterFarm.reRoll` does not check for fighter type](https://github.com/code-423n4/2024-02-ai-arena-findings/issues/1895)|
|H|[Users can use mint passes for champions to mint dendroids](https://github.com/code-423n4/2024-02-ai-arena-findings/issues/1906)|
|H|[Fighters can engage in battles with barely no downside risk](https://github.com/code-423n4/2024-02-ai-arena-findings/issues/1913)|
|M|[DoS for `RankedBattle.updateBattleRecord`](https://github.com/code-423n4/2024-02-ai-arena-findings/issues/1901)|
|M|[Users can mine dna values to generate fighters with specific properties](https://github.com/code-423n4/2024-02-ai-arena-findings/issues/1912)|
|L|[Wrong calculation of probabilities for attributes](https://github.com/code-423n4/2024-02-ai-arena-findings/issues/1903)|
|L|[`MergingPool:getFighterPoints` reverts when called with `maxId` greater than 1](https://github.com/code-423n4/2024-02-ai-arena-findings/blob/main/data/shaka-Q.md#l-01-mergingpoolgetfighterpoints-reverts-when-called-with-maxid-greater-than-1)|
|L|[The value of `RankedBattle.totalBattles` will be doubled](https://github.com/code-423n4/2024-02-ai-arena-findings/blob/main/data/shaka-Q.md#l-02-the-value-of-rankedbattletotalbattles-will-be-doubled)|
|L|[Signature verification in `FighterFarm.claimFighters` will always pass if `_delegatedAddress` is set to address zero](https://github.com/code-423n4/2024-02-ai-arena-findings/blob/main/data/shaka-Q.md#l-03-signature-verification-in-fighterfarmclaimfighters-will-always-pass-if-_delegatedaddress-is-set-to-address-zero)|
|L|[Signature in `FighterFarm.claimFighters` can be replayed in other chains](https://github.com/code-423n4/2024-02-ai-arena-findings/blob/main/data/shaka-Q.md#l-04-signature-in-fighterfarmclaimfighters-can-be-replayed-in-other-chains)|


## [ZeroLend (01/24)](https://cantina.xyz/competitions/a83eaf73-9cbc-495f-8607-e55d4fdaf407) 🪐

|Type|Issue|
|:--:|--|
|H|[`ZLRewardsController:claim()` will revert due to lack of token approval](https://cantina.xyz/code/a83eaf73-9cbc-495f-8607-e55d4fdaf407/findings/7bf440cb-56c3-4273-8d94-1995541eaef6)|
|H|[`ZLRewardsController` is not compatible with ZeroLend ATokens](https://cantina.xyz/code/a83eaf73-9cbc-495f-8607-e55d4fdaf407/findings/3959ec82-64f3-40d4-a15c-68928cde537e)|
|H|[DOS for `StakingEmissions:distrubute()`](https://cantina.xyz/code/a83eaf73-9cbc-495f-8607-e55d4fdaf407/findings/1357ddec-d5cf-4a01-98fa-b9340c4cfb0d)|
|L|[`ZeroLocker` signals support for ERC721Metadata incorrectly](https://cantina.xyz/code/a83eaf73-9cbc-495f-8607-e55d4fdaf407/findings/f7578b4a-47b4-4258-bfa5-a0d1d88508a5)|


## [Flat Money (01/24)](https://audits.sherlock.xyz/contests/132) 🕵

|Type|Issue|
|:--:|--|
|H|[Trade fees can be avoided in limit orders](https://github.com/sherlock-audit/2023-12-flatmoney-judging/issues/212)|
|H|[`LeverageModule` NFT can be unlocked when there is a pending order](https://github.com/sherlock-audit/2023-12-flatmoney-judging/issues/211)|
|H|[Accounting error for `marginDepositedTotal` in `settleFundingFees()`](https://github.com/sherlock-audit/2023-12-flatmoney-judging/issues/214)|
|M (SOLO)|[Oracle can return different prices in same transaction](https://github.com/sherlock-audit/2023-12-flatmoney-judging/issues/216)|
|M|[DoS for functions with invariant modifiers](https://github.com/sherlock-audit/2023-12-flatmoney-judging/issues/222)|

## [Ubiquity (01/24)](https://audits.sherlock.xyz/contests/138) 🕵

|Type|Issue|
|:--:|--|
|M|[The depegging of the collateral token from the USD could result in the Ubiquity Dollar token being undercollateralized](https://github.com/sherlock-audit/2023-12-ubiquity-judging/issues/19)|

## [Revolution (12/23)](https://code4rena.com/audits/2023-12-revolution-protocol) 🐺

|Type|Issue|
|:--:|--|
|H|[Ether will get stuck in ERC20TokenEmitter](https://github.com/code-423n4/2023-12-revolutionprotocol-findings/issues/651)|
|M|[`VerbsToken.tokenURI` does not comply with ERC-721 specification ](https://github.com/code-423n4/2023-12-revolutionprotocol-findings/issues/660)|
|M|[Auction settlement can be DOS's](https://github.com/code-423n4/2023-12-revolutionprotocol-findings/issues/657)|
|M|[`CultureIndex.sol:_verifyVoteSignature` does not comply with EIP-712](https://github.com/code-423n4/2023-12-revolutionprotocol-findings/issues/658)|
|L|[Edge case bug in `SignedWadMath.wadMul`](https://github.com/code-423n4/2023-12-revolutionprotocol-findings/blob/main/data/shaka-Q.md#l-01-edge-case-bug-in-signedwadmathwadmul)
|L|[Incorrect `require` statement in `VerbsToken.sol:getArPieceById`](https://github.com/code-423n4/2023-12-revolutionprotocol-findings/blob/main/data/shaka-Q.md#l-02-incorrect-require-statement-in-verbstokensolgetarpiecebyid)|
|L|[Incorrect calculation in `ERC20TokenEmitter.sol:getTokenQuoteForPayment`](https://github.com/code-423n4/2023-12-revolutionprotocol-findings/blob/main/data/shaka-Q.md#l-03-incorrect-calculation-in-erc20tokenemittersolgettokenquoteforpayment)|

## [Badger eBTC (10/23)](https://code4rena.com/audits/2023-10-badger-ebtc-audit-certora-formal-verification-competition) 🐺

|Type|Issue|
|:--:|--|
|M|[`fetchPrice` can return different prices in the same transaction](https://github.com/code-423n4/2023-10-badger-findings/issues/310)|
|L|[Misleading comments for protocol integrations](https://github.com/code-423n4/2023-10-badger-findings/blob/main/data/shaka-Q.md#l-01-misleading-comments-for-protocol-integrations)|

## [DittoETH (09/23)](https://www.codehawks.com/contests/clm871gl00001mp081mzjdlwc) 🦅

|Type|Issue|
|:--:|--|
|H|[Collateral is not returned to the creator of an order when it is cancelled with `cancelOrderFarFromOracle`](https://www.codehawks.com/submissions/clm871gl00001mp081mzjdlwc/454)|
|H|[All orders can be cancelled once `Asset.orderId` reaches 65,000](https://www.codehawks.com/submissions/clm871gl00001mp081mzjdlwc/452)|
|H|[Short flagger can be overwritten while it is still active](https://www.codehawks.com/submissions/clm871gl00001mp081mzjdlwc/450)|
|H|[Cancelled order can be cancelled again and break the linked list](https://www.codehawks.com/submissions/clm871gl00001mp081mzjdlwc/449)|
|M|[Lack of price deviation check for assets different from `USD`](https://www.codehawks.com/submissions/clm871gl00001mp081mzjdlwc/465)|
|M|[The liquidation process is open for one hour less than expected](https://www.codehawks.com/submissions/clm871gl00001mp081mzjdlwc/455)|
|L|[DoS in primary margin call](https://www.codehawks.com/submissions/clm871gl00001mp081mzjdlwc/456)|
|L|[Changes in `dittoShorterRate` affect retroactively to accrued Ditto yield shares](https://www.codehawks.com/submissions/clm871gl00001mp081mzjdlwc/446)|

## [Tokemak (07/23)](https://audits.sherlock.xyz/contests/101) 🕵

|Type|Issue|
|:--:|--|
|H|[`AbstractRewarder:queueNewRewards()` might try to pull too many reward tokens from caller](https://github.com/sherlock-audit/2023-06-tokemak-judging/issues/451)|
|H|[It is not possible to liquidate rewards](https://github.com/sherlock-audit/2023-06-tokemak-judging/issues/456)|
|M|[Users will not be able to withdraw assets on oracle price decrease](https://github.com/sherlock-audit/2023-06-tokemak-judging/issues/455)|
|M|[`redeem` function can return less assets than expected](https://github.com/sherlock-audit/2023-06-tokemak-judging/issues/452)|

## [PoolTogether (07/23)](https://code4rena.com/contests/2023-07-pooltogether) 🐺

|Type|Issue|
|:--:|--|
|H|[Anyone can claim `Vault` yield fees](https://github.com/code-423n4/2023-07-pooltogether-findings/issues/88)|
|M (SOLO)|[Transfer of `Vault` tokens can cause accounting errors in other contracts](https://github.com/code-423n4/2023-07-pooltogether-findings/issues/91)|
|M|[Griefing attack on `Vault.claimPrizes`](https://github.com/code-423n4/2023-07-pooltogether-findings/issues/90)|
|M|[`LiquidationPair` can mint less tokens than expected](https://github.com/code-423n4/2023-07-pooltogether-findings/issues/89)|

## [Symmetrical (06/23)](https://audits.sherlock.xyz/contests/85) 🕵

|Type|Issue|
|:--:|--|
|H|[`LibMuon` verifications hash collisions](https://github.com/sherlock-audit/2023-06-symmetrical-judging/issues/180)|
|H|[`depositAndAllocateForPartyB` allocates the wrong amount](https://github.com/sherlock-audit/2023-06-symmetrical-judging/issues/183)|
|H|[Party A can be liquidated with outdated price data](https://github.com/sherlock-audit/2023-06-symmetrical-judging/issues/188)|
|H|[Users can DOS liquidation process by increasing their nonce](https://github.com/sherlock-audit/2023-06-symmetrical-judging/issues/186)|
|H|[No check for expired `priceSig` in `setSymbolsPrice`](https://github.com/sherlock-audit/2023-06-symmetrical-judging/issues/179)|
|M (SOLO)|[`partyA` can inflate the uPnL with no cost](https://github.com/sherlock-audit/2023-06-symmetrical-judging/issues/181)|
|M (SOLO)|[Wrong calculation of solvency after request to close and after close position](https://github.com/sherlock-audit/2023-06-symmetrical-judging/issues/184)|
|M|[Position can fall below minimum acceptable quote value after partial closing](https://github.com/sherlock-audit/2023-06-symmetrical-judging/issues/185)|
|M|[The liquidation process can get stuck if the liquidators do not submit the symbol prices in the given time](https://github.com/sherlock-audit/2023-06-symmetrical-judging/issues/182)|

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
