# releases

Updated : 8/17/2018

The Mac, Windows linux-cli and linux catocoin-qt wallets now show this additional information in the 'getinfo' command from the debug window or through 'catocoin-cli getinfo'

    "MN collateral" : nnnn,
    "MN reward" : n.nnnnnn,
    "Staking reward" : n.nnnnnnn

Please note: cato-linux.tar.gz file now contain catcoin-qt for linux

Port: 33888
RPC Port: 6082
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
IMPORTANT NOTE FOR MAC USERS:
You must install boost using these commands in Terminal.

xcode-select --install

ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

brew doctor

brew install boost

Then your App will launch.
