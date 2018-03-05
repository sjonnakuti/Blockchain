#Beta
Note: Add chaindata folder in the same directory

geth --targetgaslimit "994712388" --port 3000 --networkid 23422 --identity node1 --datadir=./chaindata/ --rpccorsdomain '*' --rpc --rpcaddr "localhost" --rpcport="8545"

geth --datadir ./chaindata/

geth attach /path_to_.ipc/geth.ipc

personal.newAccount() /to create a new account/ /enter passphrase/

personal.unlockAccount(eth.accounts[0]) /or/ personal.unlockAccounts($address) /replace $address with the address that was given when account is created/

miner.start() /will start mining/

eth.getBalance(eth.accounts[0]) /or/ eth.getBalance($address)

miner.stop() /stop mining/
