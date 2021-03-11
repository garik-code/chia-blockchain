# CHIA blockchain

---

## Build

### Install node

`cd chia-blockchain`

`sh install.sh`

### Keys generate

```
. ./activate
chia init
chia keys generate
```

### Plots (not necessary)

```
. ./activate
chia plots create -k 32 -n 2
chia plots check -n 30
```
---

## Launch

```
. ./activate
sh install-timelord.sh
chia start timelord &
```

---

[FreeBSD install](https://github.com/Chia-Network/chia-blockchain/wiki/FreeBSD-Install#build) •
[Wiki](https://github.com/Chia-Network/chia-blockchain/wiki) •
[Quick start guide](https://github.com/Chia-Network/chia-blockchain/wiki/Quick-Start-Guide)
