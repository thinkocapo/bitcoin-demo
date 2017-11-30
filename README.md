# Bitcoin Demo

The bitcoin program itself is called **bitcoind**. These are instructions on how to obtain bitcoind, run it, and view its activity going on.

## Getting Started

1. Install the bitcoind code repository into your projects directory on your computer
```
git clone https://github.com/bitcoin/bitcoin
```
2. Run the bitcoind (bitcoin) application in pruning mode
```
bitcoind -prune=550 -daemon
```
3. Go to the directory where the bitcoin program's activity is being logged
```
cd ~/Library/Application\ Support/Bitcoin
```
4. Log the tail end (i.e. latest) data from bitcoind's log file
```
tail -f debug.log
```
