######TWRP BUILD TREE FOR WIKO HIGHWAY SIGNS s4750.[CHIPSET: MEDIATEK MT6592m ]


KERNEL : PREBUILT KERNEL LINUX 3.4.67

TWRP REPO : https://github.com/goayandi/TWRP-manifest

BUILD :

$ cd [TWRP REPO]

$ source build/envsetup.sh 

$ lunch omni_s4750-userdebug 

$ make clean && make -j# recoveryimage [# : no. of cpu core]


