# CHIA blockchain

## Build

sh install.sh
. ./activate

chia init
chia keys generate
<!-- chia plots create -k 32 -n 2
chia plots check -n 30 -->

## Launch

. ./activate
sh install-timelord.sh
chia start timelord &

(FreeBSD install)[https://github.com/Chia-Network/chia-blockchain/wiki/FreeBSD-Install#build]
https://github.com/Chia-Network/chia-blockchain/wiki/Quick-Start-Guide
https://github.com/Chia-Network/chia-blockchain/wiki
