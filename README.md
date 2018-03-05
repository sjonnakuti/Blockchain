geth --datadir=./chaindata/ init ./genesis.json

geth --datadir ./chaindata/

geth attach /path_to_.ipc/geth.ipc

personal.newAccount() /to create a new account/ /enter passphrase/

personal.unlockAccount(eth.accounts[0]) /or/ personal.unlockAccounts($address) /replace $address with the address that was given when account is created/

miner.start() /will start mining/

eth.getBalance(eth.accounts[0]) /or/ eth.getBalance($address)

miner.stop() /stop mining/
