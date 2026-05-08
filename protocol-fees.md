# Metaplex Protocol Fees

Last Updated: April 21, 2026

This file summarizes the current Metaplex Protocol fee schedule for transparency and public reference. Fees may change over time based on ecosystem needs and governance decisions. Users and developers should always verify the latest schedule

------------------------------------------------------------
## 1. GENESIS
------------------------------------------------------------

### Bonding Curve

| Instruction      | Fee (SOL) |
|------------------|-----------|
| Protocol fee     | 0.50%     |
| Creator revenue  | 0.60%     |

### Post Bond Trading

| Instruction      | Fee (SOL) |
|------------------|-----------|
| Protocol fee     | 0.40%     |
| Creator revenue  | 0.60%     |
| LP fees          | 0.17%     |
| Raydium fee      | 0.08%     |

### Launch Pool

| Instruction           | Fee (SOL) |
|-----------------------|-----------|
| User deposit fee      | 0%        |
| User withdraw fee     | 0%        |
| Creator withdraw fee  | 5%*       |

*This fee only applies when creators withdraw liquidity

### Launch Pool Trading

| Instruction            | Fee (SOL) |
|------------------------|-----------|
| Liquidity requirement  | 20%*      |
| Protocol fee           | 0.50%     |
| LP fees                | 0.42%     |
| Raydium fees           | 0.08%     |

*Subject to a 1 year unlock schedule with quarterly unlocks.

------------------------------------------------------------
## 2. MPL-CORE
------------------------------------------------------------

Paid by the minter. Includes all instructions that "create" an NFT, including print editions.

| Instruction | Fee            |
|-------------|----------------|
| Create      | 0.0015 SOL     |
| Execute     | 0.00004872 SOL |


------------------------------------------------------------
## 3. BUBBLEGUM v2
------------------------------------------------------------

| Instruction | Fee          |
|-------------|--------------|
| Create      | 0.00009 SOL  |
| Transfer    | 0.000006 SOL |

------------------------------------------------------------
## 4. TOKEN METADATA
------------------------------------------------------------
Paid by the minter, which is typically individual collectors minting new digital assets.

| Instruction | Fee      |
|-------------|----------|
| Create      | 0.01 SOL |


------------------------------------------------------------
## 5. BUBBLEGUM v1 (Legacy)
------------------------------------------------------------

| Instruction | Fee  |
|-------------|------|
| Create      | Free |


------------------------------------------------------------
## 6. MPL-HYBRID
------------------------------------------------------------

| Instruction | Fee       |
|-------------|-----------|
| Swap        | 0.005 SOL |


------------------------------------------------------------
## 7. FUSION (TRIFLE)
------------------------------------------------------------

| Instruction      | Fee       |
|------------------|-----------|
| Combine          | 0.002 SOL |
| Split            | 0.002 SOL |
| Edit Constraint  | 0.01 SOL  |

------------------------------------------------------------
## HOW PROTOCOL FEES ARE USED
------------------------------------------------------------

Metaplex protocol fees support the objectives of the Metaplex Foundation,
including research, development, ecosystem growth, governance, security,
and long-term sustainability of the Metaplex Protocol.

Currently:
- 50% of protocol fees are converted to MPLX and contributed to the DAO treasury
- 50% are retained by the Foundation to support ecosystem development
