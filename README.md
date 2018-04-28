@@ -4,6 +4,18 @@ It is recommended that you upgrade your wallets (local or MasterNode ones) as so
This ensures that the consensus across the decentralized network and improvements. These are crucial for the success of the project. Non upgraded wallets will be banned by the other nodes in the network at certain block thresholds. This will eliminate the node from the network and cause lost rewards and ban expire delays.


## Backup your wallet

It's a good practice to stop the wallet and backup your `wallet.dat`, `zSub1x.conf` and `masternode.conf` files regularily, before upgrades or other operations.

These are the default directories for the data directory where these files are stored:
 * Windows: `~\AppData\Roaming\zSub1x`
 * Linux: `~/.zSub1x/`
 * Mac: `~/Library/Application Support/zSub1x`

where `~` represents the home directory of the login user.


## Check existing wallet version

Depending on the type of wallet you are running, here are a few ways to check the version that is currently running:
@ -27,18 +39,8 @@ Compiled wallets and source code archives will be available here for every release. 

https://github.com/SuB1X-Coin/zSub1x/releases


## Upgrade your wallet to a newer version

It's a good practice to stop the wallet and backup your `wallet.dat`, `zSub1x.conf` and `masternode.conf` files regularily, before upgrades or other operations.

These are the default directories for the data directory where these files are stored:
 * Windows: `~\AppData\Roaming\zSub1x`
 * Linux: `~/.zSub1x/`
 * Mac: `~/Library/Application Support/zSub1x`

where `~` represents the home directory of the login user.

[Download]() the archive with the new wallet. We are not covering compiling from sources in this guide to keep it short and sweet.

### Windows and OSX GUI wallets
