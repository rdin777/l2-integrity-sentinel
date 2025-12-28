# l2-integrity-sentinel# L2 Integrity Sentinel 🛡️

A specialized diagnostic utility designed for **Arbitrum Nitro** and other L2 node stacks to ensure database integrity and prevent state corruption during network reorgs.

### 🚀 Motivation
Inspired by my core contributions to the **Offchain Labs / Nitro** stack ([PR #4163](https://github.com/OffchainLabs/nitro/pull/4163)), this tool automates the validation of block state existence before complex state transitions.

### 🛠 Features (In Development)
- **State Validation**: Pre-reorg checks to ensure the target block exists in the local database.
- **Corruption Detection**: Monitors for "silent errors" in database writes.
- **Go 1.25 Optimized**: Built using the latest toolchain for maximum performance.

### 💻 Stack
- **Language**: Go
- **Libraries**: go-ethereum/rpc, PebbleDB/LevelDB wrappers
