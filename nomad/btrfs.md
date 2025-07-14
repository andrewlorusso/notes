# BTRFS

## Overview

**Complementary Packages**
- List: snapper, grub btrfs
- [install](https://www.youtube.com/watch?v=b4vTKg-qW_0)
- [page](https://www.youtube.com/@stephenstechtalks5377/videos)
- [opensuse install](https://www.youtube.com/watch?v=b4vTKg-qW_0)
- [debain stress test](https://www.youtube.com/watch?v=A1JzSgZ3EBg)
- [tumbleweed configuration](https://www.youtube.com/watch?v=ttG2NFkKPRM)
- [timeshift install debain](https://www.youtube.com/watch?v=MoWApyUb5w8)
- [another timeshift debain](https://www.youtube.com/watch?v=9htEaXAXfdg)
- [arch btrfs](https://www.youtube.com/watch?v=maIu1d2lAiI)


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
