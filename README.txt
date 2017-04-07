# BarterBlockchainPlatform
BATA.io Barter Blockchain Platform

============================================================================================

$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
BTA-WALLET APIs (Server)  [Connection from Platform]
$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

.........................................................................................
name                      actor (function)         okSafeMode threadSafe reqWallet
.........................................................................................
stop                       &stop                    true      true        false
getblockcount              &getblockcount           true      false       false
getbestblockhash           &getbestblockhash        true      false       false
getconnectioncount         &getconnectioncount      true      false       false
getpeerinfo                &getpeerinfo             true      false       false
addnode                    &addnode                 true      true        false
getaddednodeinfo           &getaddednodeinfo        true      true        false
getdifficulty              &getdifficulty           true      false       false
getnetworkhashps           &getnetworkhashps        true      false       false
getgenerate                &getgenerate             true      false       false
setgenerate                &setgenerate             true      false       true
gethashespersec            &gethashespersec         true      false       false
getinfo                    &getinfo                 true      false       false
getmininginfo              &getmininginfo           true      false       false
getnewaddress              &getnewaddress           true      false       true
getaccountaddress          &getaccountaddress       true      false       true
setaccount                 &setaccount              true      false       true
getaccount                 &getaccount              false     false       true
getaddressesbyaccount      &getaddressesbyaccount   true      false       true
sendtoaddress              &sendtoaddress           false     false       true
getreceivedbyaddress       &getreceivedbyaddress    false     false       true
getreceivedbyaccount       &getreceivedbyaccount    false     false       true
listreceivedbyaddress      &listreceivedbyaddress   false     false       true
listreceivedbyaccount      &listreceivedbyaccount   false     false       true
backupwallet               &backupwallet            true      false       true
keypoolrefill              &keypoolrefill           true      false       true
walletpassphrase           &walletpassphrase        true      false       true
walletpassphrasechange     &walletpassphrasechange  false     false       true
walletlock                 &walletlock              true      false       true
encryptwallet              &encryptwallet           false     false       true
validateaddress            &validateaddress         true      false       false
getbalance                 &getbalance              false     false       true
move                       &movecmd                 false     false       true
sendfrom                   &sendfrom                false     false       true
sendmany                   &sendmany                false     false       true
addmultisigaddress         &addmultisigaddress      false     false       true
createmultisig             &createmultisig          true      true        false
getrawmempool              &getrawmempool           true      false       false
getblock                   &getblock                false     false       false
getblockhash               &getblockhash            false     false       false
gettransaction             &gettransaction          false     false       true
listtransactions           &listtransactions        false     false       true
listaddressgroupings       &listaddressgroupings    false     false       true
signmessage                &signmessage             false     false       true
verifymessage              &verifymessage           false     false       false
getwork                    &getwork                 true      false       true
getworkex                  &getworkex               true      false       true
listaccounts               &listaccounts            false     false       true
settxfee                   &settxfee                false     false       true
getblocktemplate           &getblocktemplate        true      false       false,
submitblock                &submitblock             false     false       false
setmininput                &setmininput             false     false       false
listsinceblock             &listsinceblock          false     false       true
dumpprivkey                &dumpprivkey             true      false       true
importprivkey              &importprivkey           false     false       true
listunspent                &listunspent             false     false       true
getrawtransaction          &getrawtransaction       false     false       false
createrawtransaction       &createrawtransaction    false     false       false
decoderawtransaction       &decoderawtransaction    false     false       false
signrawtransaction         &signrawtransaction      false     false       false
sendrawtransaction         &sendrawtransaction      false     false       false
getnormalizedtxid          &getnormalizedtxid       true      true        false
gettxoutsetinfo            &gettxoutsetinfo         true      false       false
gettxout                   &gettxout                true      false       false
lockunspent                &lockunspent             false     false       true
listlockunspent            &listlockunspent         false     false       true
verifychain                &verifychain             true      false       false

===============================================================================================================

$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
BTA-WALLET APIs (Client) [Connection to Platform]
$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

getmarkets            ARGS: none       RETURNS: [Items for sale]
getmarketinfo         ARGS: none       RETURNS: [Item, Price, seller, date]

