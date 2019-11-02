# Release-Windows

Use the following instructions to setup a node on Windows Server.

Download the Windows QT wallet from leedcoin and upload the file to your Windows Server.

Note: replace “leedcoin” with the name of your coin.

Extract the zip file leedcoin-qt-windows.zip.

Close your wallet and create the file leedcoin.conf in the folder “%APPDATA%\leedcoin\”.

Paste the following text into leedcoin.conf and save the file.

rpcuser=rpc_leedcoin

rpcpassword=123456789

rpcallowip=127.0.0.1

listen=1

server=1

txindex=1


Your wallet will function as a node when you start your wallet.
