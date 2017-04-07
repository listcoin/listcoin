# listcoin
experiments in ledger using distributed hash table


## financial laws

* universal basic income (UBI), less taxes, can be requested every two weeks
* interest through running a node and verifying the system, should be easier/better than farming multiple wallet UBIs
* extremely progressive tax on incoming coins - ranging from 10% to 100% - based on wallet balance and amount incoming
* maximum wallet balance = MAX\_SAFE\_INTEGER = 2<sup>53</sup> - 1
* smallet payment amount is 256 listcoins = 256 lc

listcoins are denominated in computer powers of two.

|   listcoins    | denomination |
|:--------------:|:------------:|
|      1024      |      Klc     |
|1024<sup>2</sup>|      Mlc     |
|1024<sup>3</sup>|      Glc     |
|1024<sup>4</sup>|      Tlc     |
|1024<sup>5</sup>|      Plc     |

technically more proper, Klc -> Kilc, ok.

maximum wallet size is approximately 8 Plc.


## implementation

need some difficulty in creating users, to avoid farming their UBI for your account;
that is not nice!

naughty people get put on a fake blockchain.  8)
