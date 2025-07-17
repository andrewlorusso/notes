# Biscyn

**Data model**

2025+ (The "Distributed State" Paradigm)

**Description**: This is the state-of-the-art for distributed systems applied to personal computing. It acknowledges that both the cloud (SSOT) and the local device (working replica) have their own valid states that must be reconciled. It's a peer-to-peer relationship mediated by the cloud.

**Purity**: Very Pure. It models the problem correctly as a distributed system with two nodes (local, cloud) that need state reconciliation. It avoids the simplification of a main/worker (one-way) relationship. Its logic is based on deltas and history, akin to Git.

**Confidenilaity**: Excellent. With rclone crypt, data is secure at rest and in transit. The persistent local replica is the main point of difference/risk compared to the Library model.

**Integrity**: Excellent. Integrity is a first-class citizen. cryptcheck provides end-to-end cryptographic verification. The use of file hashes (--compare) and history files makes the reconciliation process robust against silent corruption.

**Avalibility**: Excellent. This is its greatest strength. The local replica provides 100% offline availability for all files. You can work on a plane for 8 hours, and bisync will reconcile the changes when you land.

**Distrubted systems**: Excellent. This is a true distributed system model, where two nodes maintain and reconcile state. It correctly models the real-world scenario of multiple active endpoints. It's the most accurate model for multi-device personal computing.
