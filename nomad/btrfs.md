# BTRFS

## Overview

### Options
- **Permissions**: `rw` `ro`
- **Compression**
`noatime`
`space_cache=v2`
- defragmentation
compress=zstd (level 3) zstd:1 (level 1)
discard=async


### Options

Swap partition (not idoematic)
Copy on write must be disabled 
Swap can no span across storage devices 
However linux kernel may expect swap 

## Subolvolmes

Parition is pool, allowing flexble subvolumes
