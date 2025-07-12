---
aliases
  - raid
---

# Redunannt Array of Independnt Disks 

> "RAID is fault tolerence, not a backup"

## Overview

**Striping**: Data is split into blocks (stripes) and written across multiple drives in the array. This configuration allows a single file to be distributed across several drives, allowing parallel reads and writes, improving performance.
- Used in: raidO, raid5, raid6, raid10

Generalliy smaller array [1, 4]
Generalliy large array [6, 1] (enterprise grade)

A hot spare is something that can be used in raid1, 3, 5, 6, 10, z1, z2, Z3... but it is not needed in any raid.

**Implemenation**
- Raid card:
- Native filesystem implementaion: [btrfs](btrfs.md) [zfs](zfs.md)

## RAID 01

Mirroring

**Use case**: Smaller arrays (4-6 disks)

## RAID 5

## RAID 6

**Premise** More useable space with drives compared to raid 10 while still having two-point-failure redundancy.

**Use case**: When array has more than 4 drives 

## RAID 10

**Minimum drives**: 4

**Example scenario**: In a 4-drive array, after one drive fails, there is a 33% chance that a second drive failure will result in total data loss.
