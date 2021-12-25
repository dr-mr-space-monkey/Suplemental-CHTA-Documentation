CHTA miner in Termux:
=====================
### Created by: "reflex⛏#8729" (Discord CHTA user)


## Install Ubuntu 18.04 Bionic Beaver
    pkg update -y && pkg install wget curl proot tar -y && wget https://raw.githubusercontent.com/AndronixApp/AndronixOrigin/master/Installer/Ubuntu/ubuntu.sh -O ubuntu.sh && chmod +x ubuntu.sh && bash ubuntu.sh

    ./start-ubuntu.sh
    
    apt update && apt install wget ssh

    wget https://github.com/ShorelineCrypto/cheetahcoin/releases/download/v1.9.1.2/cheetahcoin_v1.9.1.2_android_userland_arm.tgz && tar xvfz cheetahcoin_v1.9.1.2_android_userland_arm.tgz && cd Android_Userland_App/ubuntu/armhf/

> Then delete all (sudo) words from prepare_userland.sh and prepare_neng.sh using nano editor: nano prepare_userland.sh
> Then run these 2 files one by one, *same for arch64*.
> Don't forget to change rpc user and pass for wallet and miner and ready to go, then move cheetahcoin.conf

    cp cheetahcoin.conf ~/.cheetahcoin/ 
