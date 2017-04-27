# Ragazzo

## Getting Started

### Step 1: Download
Either clone this repository or click [here](http://romaniellolovettseniorproject2017.weebly.com/uploads/1/0/3/0/103055266/ragazzo.tar.gz) to download. Ragazzo is currently functional on Mac and Linux systems.

### Step 2: Run
If you downloaded the .tar.gz file, extract it.

Navigate to the Ragazzo directory you now have in a terminal.

Run `./ragazzod --config-file=ragazzo.conf` in order to start the Ragazzo daemon. The blockchain will take a moment to sync, so be patient in this step.

### Step 3: Create a wallet
In another terminal, open the Ragazzo directory and run `./simplewallet --config-file=ragazzo.conf`

Press 'G' to generate a new wallet. Give it whatever name you want, and use a password you won't forget.

### Step 4: Mine
If you would like to mine from the wallet, simply type `start_mining` and hit enter. That's it!

If you would like to mine from the daemon, type `start_mining xxxx` where xxxx is replaced with the address you would like to send your earnings to. That's it!
