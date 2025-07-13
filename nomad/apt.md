## Adding ISO as repo

**Purpose**: Read and install packages from Debain iso, providing access to packages without internet.

1. Mount usb partition containg iso `/media/ISO`

**RELEASE-NAME**
- Correct: `bookworm`, `trixie`
- Incorrect: `BookWorm `, `TRIXIE`

```shell
echo 'deb [trusted=yes] file:///media/ISO <RELEASE-NAME> main contrib non-free-firmware' | sudo tee /etc/apt/sources.list

sudo apt update
```
