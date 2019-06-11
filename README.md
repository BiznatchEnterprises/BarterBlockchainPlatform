# BarterBlockchainPlatform
BATA.io Barter Blockchain Platform

"10 million has been decided to be the first initial max coins set for BTA,
once we approach that amount, we will discuss further with the BTA community
a controlled increase if required. BTA has been designed  to maintain a store
of wealth for the long-term. Barter Tokens MAY not have a maximum supply,
they've been designed for the problem you mentioned above, liquidity constraints.
By allowing the markets to control the rate of exchange between the Barter Trade
Token <-> BTA / Stratis / Bitcoin; They will self-regulate demand/supply within
the platform. By creating an internal exchange that restricts the exchange-ability
to and from external exchanges, this creates a marketplace (Barter Blockchain Platform)
that discourages hoarding. Preventing external use of the Tokens aside for within
the platform itself only. We're attempting to create a digital framework that incorporates
"asset-backing" economics for stability. If all Barter Trade Tokens are worth their
value held in an existing block-chain (Bitcoin/BTA/Stratis) then the Trade Tokens
themselves will not be subject to centralized inflationary and deflationary pressures.
Their exchange-ability to other crypto-coins such as Stratis and Bitcoin will help
diversify external market pressures on the platform. We feel that BTA will not need to
have a large quantity of coins in circulation."

============================================================================================
'''
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
'''
