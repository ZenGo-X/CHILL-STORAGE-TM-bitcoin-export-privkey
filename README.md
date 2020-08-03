# CHILL-STORAGE™-bitcoin-export-privkey
Export BTC private key & address pair for Zengo server recovery

## Getting started
Installation:
```
$ yarn install
``` 
Use the Command-Line Interface:
```
$ chmod +x ./index
$ ./index --help
Usage: index [options] [command]

Options:
  -h, --help              display help for command

Commands:
  export <privateKey>     Export a private key into a WIF (Wallet Import Format). Private key expected to be 32 bytes hex.
  address|a <privateKey>  Get the ZenGo BTC address given a private key. Private key expected to be 32 bytes hex.
  help [command]          display help for command
```
Example:
```
$ ./index export 89e14df060ee50b4ca60ab46fbdae193eff62a0f233b34f9c46473f7366401a0
L1qjPvgEg3jfEPBqjXdkdZVhT6q32ZMPPm6owfegUxdCP6gJF64G
$ ./index address 89e14df060ee50b4ca60ab46fbdae193eff62a0f233b34f9c46473f7366401a0
3DEyPLmPAx1RsugmiNX9EG2J7Kgp2ZGwuZ
```
