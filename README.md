# TestNetCoin (TST)

TestNetCoin (TST) is a test cryptocurrency designed for educational purposes and blockchain development testing. This coin is not intended to be listed on any exchange and should be used solely in a testnet environment.

## Specifications

- **Algorithm**: SHA256
- **Block Time**: 60 seconds
- **Retarget Interval**: 120 minutes
- **Confirmations for Coinbase**: 60 confirms
- **Confirmations for Transactions**: 6 confirms
- **Halving Interval**: Every 500,000 blocks
- **Block Reward**: 7,500 coins
- **Total Supply**: 7,500,000,000 coins
- **Fractional Unit**: Satoshi (1 TestNetCoin = 100,000,000 Satoshis)

## Ports

- **RPC Port**: 17891
- **P2P Port**: 17892

## Wallet

The wallet for TestNetCoin is built using the free option provided by WalletBuilders. This wallet is intended purely for testing purposes as we couldn't find a decent testnet.

## Warning to Exchange Operators

**Go away! This coin should never end up on an exchange, and if you list it, you'll get what you deserve.**

## Adding Nodes

To add nodes to your TestNetCoin wallet, use the following format in your configuration file:

addnode=xxx.xxx.xxx.xxx
addnode=xxx.xxx.xxx.xxx
addnode=xxx.xxx.xxx.xxx
addnode=xxx.xxx.xxx.xxx


Replace `xxx.xxx.xxx.xxx` with the actual IP addresses of the nodes you wish to connect to.

## License

No lisence at all, your free to do whatever you damn well like with it, although it would be nice if you didnt break it.
