# SRBMiner-MULTI cryptocurrency miner

Cryptocurrency miner supporting AMD, NVIDIA and Intel GPUs, as well as CPU mining.

**Mine up to 4 different algorithms/coins at the same time!**

## DOWNLOAD

- [Official website](https://www.srbminer.com/download.html)
- [GitHub repository](https://github.com/doktor83/SRBMiner-Multi)

## ALGORITHMS

- `C` — CPU
- `A` — AMD GPU
- `N` — NVIDIA GPU
- `I` — Intel GPU

```text
[0.85%]   [ C  A  -  - ]   argon2d_16000
[0.85%]   [ C  A  -  - ]   argon2d_dynamic
[3.00%]   [ C  A  N  - ]   argon2id_exfer
[1.00%]   [ -  A  N  I ]   autolykos2
[2.00%]   [ -  A  N  I ]   blake3_an
[1.00%]   [ -  A  N  I ]   blake3_decred
[0.85%]   [ C  -  -  - ]   cpupower
[0.85%]   [ C  A  N  I ]   cryptonight_gpu
[0.85%]   [ C  A  N  - ]   cryptonight_turtle
[0.85%]   [ C  A  -  - ]   curvehash
[0.65%]   [ -  A  N  I ]   etchash
[0.65%]   [ -  A  N  I ]   ethash
[0.85%]   [ -  A  N  I ]   evrprogpow
[0.85%]   [ -  A  N  I ]   firopow
[0.85%]   [ -  A  N  I ]   fishhash
[2.00%]   [ C  -  -  - ]   flex
[0.85%]   [ C  -  -  - ]   ghostrider
[0.85%]   [ -  A  N  I ]   heavyhash
[0.85%]   [ -  A  N  I ]   kawpow
[0.85%]   [ C  A  N  - ]   lyra2v2_webchain
[0.85%]   [ -  A  N  I ]   meowpow
[0.85%]   [ C  -  -  - ]   mike
[0.85%]   [ C  -  -  - ]   minotaurx
[2.00%]   [ -  A  N  - ]   noid
[0.85%]   [ -  A  N  I ]   oggpow
[0.85%]   [ C  -  -  - ]   panthera
[2.00%]   [ -  A  N  - ]   pearlhash
[0.85%]   [ -  A  N  I ]   phihash
[0.85%]   [ -  A  N  I ]   progpow_epic
[0.85%]   [ -  A  N  I ]   progpow_zano
[1.50%]   [ -  A  N  I ]   qhash
[2.00%]   [ -  A  N  - ]   quantus
[1.00%]   [ C  -  -  - ]   randomalpha
[0.85%]   [ C  -  -  - ]   randomarq
[0.85%]   [ C  -  -  - ]   randomc64
[0.85%]   [ C  -  -  - ]   randomdrgx
[0.85%]   [ C  -  -  - ]   randomepic
[0.85%]   [ C  -  -  - ]   randomjuno
[0.85%]   [ C  -  -  - ]   randompcn
[0.85%]   [ C  -  -  - ]   randomscash
[0.85%]   [ C  -  -  - ]   randomsnap
[0.85%]   [ C  -  -  - ]   randomvirel
[0.85%]   [ C  -  -  - ]   randomx
[1.00%]   [ C  -  -  - ]   randomy
[0.85%]   [ C  -  -  - ]   randomyada
[0.85%]   [ C  -  -  - ]   randomzqvx
[1.00%]   [ C  -  -  - ]   rinhash
[1.00%]   [ -  A  N  I ]   sha256d_csd
[1.00%]   [ -  A  N  I ]   sha3t
[1.00%]   [ -  A  N  I ]   verthash
[0.85%]   [ C  -  -  - ]   verushash
[1.50%]   [ C  A  N  I ]   xelishashv3
[3.00%]   [ -  A  N  I ]   xhash
[0.85%]   [ C  A  N  - ]   yescrypt
[0.85%]   [ C  A  N  - ]   yescryptr16
[0.85%]   [ C  A  N  - ]   yescryptr32
[0.85%]   [ C  A  N  - ]   yescryptr8
[0.85%]   [ C  -  N  - ]   yespower
[0.85%]   [ C  -  -  - ]   yespower2b
[0.85%]   [ C  -  -  - ]   yespoweradvc
[2.00%]   [ C  -  -  - ]   yespowereqpay
[0.85%]   [ C  -  -  - ]   yespowerinterchained
[0.85%]   [ C  -  -  - ]   yespowerltncg
[0.85%]   [ C  -  -  - ]   yespowermgpc
[0.85%]   [ C  -  -  - ]   yespowermwc
[0.85%]   [ C  -  -  - ]   yespowerr16
[0.85%]   [ C  -  -  - ]   yespowersugar
[0.85%]   [ C  -  N  - ]   yespowertide
[0.00%]   [ C  -  -  - ]   yespowerurx
```

## DUAL MINEABLE ALGORITHMS

- `fishhash` + `qhash`
- `fishhash` + `blake3_decred`
- `autolykos2` + `qhash`
- `autolykos2` + `blake3_decred`
- `autolykos2` + `heavyhash`
- `etchash` + `blake3_decred`
- `etchash` + `heavyhash`
- `ethash` + `blake3_decred`
- `ethash` + `heavyhash`
- `xhash` + `qhash`
- `xhash` + `blake3_decred`

Additionally:

- `randomepic` + any algorithm
- `progpow_epic` + any algorithm


## SUPPORTED GPUs

### AMD

- RX 9xxx
- RX 7xxx
- RX 6xxx
- RX 5xxx
- VEGA 56/64/FE/VII
- RX 470/480/570/580/590
- BC-250

### NVIDIA

- Blackwell
- Hopper
- Ada Lovelace
- Ampere
- Turing
- Pascal

### INTEL

- Battlemage
- Alchemist


## SUPPORT

- [Discord](https://discord.gg/zXY23De)
- [BitcoinTalk](https://bitcointalk.org/index.php?topic=5190081.0)


## LICENSE

Copyright © **doktor83**. All rights reserved.

This software may be used only for lawful cryptocurrency mining on hardware or systems that you own or are authorized to use. You are solely responsible for complying with all applicable laws, regulations, network rules and third-party terms.

All embedded or precompiled GPU binaries and machine code distributed with SRBMiner-MULTI are proprietary. They may be executed only as part of an official or otherwise expressly authorized SRBMiner-MULTI release.

Extracting, copying, modifying, reverse engineering, decompiling, disassembling, redistributing, sublicensing, selling, publishing, incorporating into another product or otherwise using these binaries without prior written permission from the copyright holder is prohibited, except where applicable law provides otherwise.

Third-party components remain subject to their respective licenses.

THIS SOFTWARE IS PROVIDED **“AS IS”**, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR ITS USE.
