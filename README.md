# Awesome Private Blockchain
Curated list of powerful features and project for private blockchains

# FAQ

## What can I do with a private blockchain?
Basically anything related to your database logic. Private blockchain is here to help you control your database content update in a non disputable way by third party.

## Why should I use a private blockchain instead of a normal database?
The advantage of using a blockchain is that you can have more control on the integrity of the data you include in your system. You can see it as a smarter way to index your database where you can later check that nobody has changed the database content without your consent.

## How can I secure my private blockchain?
There are several ways to secure your private blockchain:
- Protect from illegal access, making firewall between your servers network and public internet, using VPN for instance.
- Maintain a whitelist of public keys allowed to create blocks.
- Maintain a whitelist of public keys allowed to send transaction.
- Keep your master private key safe and offline.

## How can I prevent a offensive transaction from being included in the blockchain?
Further securisation might be needed if you don't want to maintain a whitelist. In this case you can add some extra rules to prevent tx from being included in your blockchain:
- The account is not 'rich' enough: they need to buy your token in order to be allowed to create a transaction with enough fees. You can also make the price of the token higher for people you don't know enough yet making incentive to behave well.


## How can I remove a transaction if I have made an error?
In case of an error, blockchain is not the best to remove transactions since it needs some more complex management, but there are several techniques to achieve this:
- Mintain a list of exceptions you need to sign with your master key. These exceptions are basically a pair of `block id`/`block signature` where the transaction is removed with the new valid block signature. This list is maintained by your master node to be accessed by all nodes to keep consensus.
- Rebuild the blockchain from the invalid block. This is a bit more complex but have the advantage of leaving no trace. Basically you reuse all subsequent transactions and reinclude thhem in the new created blocks you sign with your master key.


## How can I be sure only good actors?
The best way to favour good actors is to be the main seller of the tokens, in order to be able to control the price, and sell at higher price to the potential bad actors.

## How can I make money with my blockchain?
Most of the income is usually done by selling tokens to third parties accessing your private blockchain. However it is also possible to make it closed source so you can resell the technology to a third party. The pricing can be automated with the capability to implement it at the blockchain level: you can audit the tokens in circulation and ask for a percentage of the price they have been sold for.


# Projects
- Hyperledger https://github.com/hyperledger
- Ripple https://github.com/ripple

# Articles
- The difference between public and private blockchain https://www.ibm.com/blogs/blockchain/2017/05/the-difference-between-public-and-private-blockchain/
- Public Vs Private blockchain protocols: What's the difference?
https://bravenewcoin.com/news/public-vs-private-blockchain-protocols-whats-the-difference/


