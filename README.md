# NoDevFee - Disable the commission in the cryptocurrency miners. 

GitHub developers have brought this idea to life by writing a simple program. Into which wallets of developers are sewn and which easily searches for them in the miner. After it changes them to yours (which you specify in the config file).


The program is suitable for most popular miners, regardless of their version. Because the commission collection algorithm remains the same. The changes concern only the work of the miner itself:

    Claymore’s Dual Ethereum+Decred_Siacoin_Lbry_Pascal AMD+NVIDIA GPU Miner;
    Claymore’s CryptoNote AMD GPU Miner;
    Zec miner;
    ccminer;
    XMR;
    ewbf;
    Cast XMR;
    SRBMiner;
    dstm’s ZCash / Equihash Nvidia Miner;
    Excavator;
    JerryMiner;
    Claymore’s BTG AMD GPU Miner;
    Claymore’s ZCash/BTG GPU Miner;
    BTG nVidia miner;
    MOD lbry;
    Bminer;
    RAVECOIN (X16R);
    PhoenixMiner (added in 9.84);
    T-REX;
    CryptoDredge. 

How to disable the commission in the cryptocurrency miner 
----------------------------------------------------------

In this article, we will look at how to disable commission in the miner using the NoDevFee (NoFee) program.

    Attention! The commission is absolutely on all miners, even where NoFee is written, 0% Fee and so on!
    We decrypt the source code of the miner.
    We insert our wallet instead of the developer’s wallet.
    We encrypt back.
    Now all the commission that was supposed to go to the developer goes to our wallet.



Instruction manual
------------------

1. Download the latest version of NoDevFee. Winrar or 7zip may be required to unpack.
2. Unpack it into the folder with the miner. Turn off mining.
3. Open config.cfg with notepad ++ / sublime text (https://notepad-plus-plus.org/) and change the wallet of the desired algorithm to your >>> Save config.cfg
4. Run Nofee.exe, if we did everything right, a window will appear: Done!
5. We start mining.
    Now DevFee (commission) is mining on you, that is, 100% of your capacities work for you!
