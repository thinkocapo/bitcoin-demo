1. cp https://github.com/bitcoin/bitcoin
2. bitcoind -prune=550 -daemon
3. cd ~/Library/Application\ Support/Bitcoin
4. tail -f debug.log

What's Happening:
#2 runs the bitcoind application. you won't see any output logged
#2 gets you to the directory with the file thats the log
#4 will show you the log
