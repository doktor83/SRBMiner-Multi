***DUAL MINING***
-------------------------------------------------------------------------------
**Xhash + Qhash :**  
*--algorithm xhash --pool parallax-pool-here --wallet parallax-wallet-here --algorithm qhash --pool qtc-pool-here --wallet qtc-wallet-here*

**Fishhash + Qhash :**  
*--algorithm fishhash --pool ironfish-pool-here --wallet ironfish-wallet-here --algorithm qhash --pool qtc-pool-here --wallet qtc-wallet-here*

**Autolykos2 + Qhash :** 
*--algorithm autolykos2 --pool ergo-pool-here --wallet ergo-wallet-here --algorithm qhash --pool qtc-pool-here --wallet qtc-wallet-here*


***MIXED CPU/GPU MINING***
-------------------------------------------------------------------------------
**Cpu: yespower, Gpu: xelishashv3 :**  
*--algorithm-cpu yespower --pool yespower-pool --wallet yespower-wallet --algorithm-gpu xelishashv3 --pool xelis-pool --wallet xelis-wallet*

   
***PERIODIC MINING***
-------------------------------------------------------------------------------
[Mine second algorithm when no job is available for Epic Cash]

**Epic Cash + Monero [CPU] :**
*--algorithm-cpu randomepic --pool epic-pool-here --wallet epic-wallet-here --algorithm-cpu randomx --pool monero-pool-here --wallet monero-wallet-here*

**Epic Cash + Zano [GPU] :**
*--algorithm-gpu progpow_epic --pool epic-pool-here --wallet epic-wallet-here --algorithm-gpu progpow_zano --pool zano-pool-here --wallet zano-wallet-here*

**Epic Cash [GPU + CPU] :**
*--algorithm-gpu progpow_epic --pool epic-pool-here --wallet epic-wallet-here --algorithm-cpu randomepic --pool epic-pool-here --wallet epic-wallet-here*
