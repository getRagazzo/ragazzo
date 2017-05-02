# Ragazzo

## Getting Started

### Step 1: Download
Either clone this repository (for Linux) or click a link below to download for the proper OS. Ragazzo is currently functional on Mac, Windows, and Linux.

[Windows Download](https://github.com/getRagazzo/ragazzo/raw/master/ragazzo-Windows.zip)

[Mac Download](https://github.com/getRagazzo/ragazzo/raw/master/ragazzo-mac.zip)

[Linux Download](https://github.com/getRagazzo/ragazzo/raw/master/ragazzo-Linux.zip)

### Step 2: Run
Extract the file you downloaded

Navigate to the Ragazzo directory you now have in a terminal.

Run the `ragazzod` file with the flag `--config-file configs/ragazzo.conf` in order to start the Ragazzo daemon. The blockchain will take a moment to sync, so be patient in this step.

### Step 3: Create a wallet
In another terminal, open the Ragazzo directory and run the `simplewallet` program with flag `--config-file configs/ragazzo.conf`

Press 'G' to generate a new wallet. Give it whatever name you want, and use a password you won't forget.

### Step 4: Mine
If you would like to mine from the wallet, simply type `start_mining` and hit enter. That's it!

If you would like to mine from the daemon, type `start_mining xxxx` where xxxx is replaced with the address you would like to send your earnings to. That's it!

Note: Tested on Linux, expected to work on Mac and Windows but not tested. Precise instructions may vary based on platform.
