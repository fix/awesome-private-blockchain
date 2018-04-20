# private-blockchain
demonstrate powerful features of private blockchains

# FAQ

## What can i do with a private blockchain
Basically anything related to your database logic. Private blockchain is here to help you control your database content update in a non disputable way by thhird part.

## why should i use a private blockchain instead of a normal database
The advantage of using a blockchain is that you can have more control on the integrity of the data you include in your system. You can see it as a smarter way to index your database where you can check later that nobody has changed thhe database content without your consent

## how can i secure my private blockchain
There are several ways to secure your private blockchain
- protect from illegal access, making firewall between your servers network and public internet, using VPN for instance
- maintain a whitelist of public keys allowed to create blocks
- maintain a whitelist of public keys allowed to send transaction
- keep your master private key safe and offline

## how can i prevent a offensive transaction from being included in the blockchain
Further securisation can be needed if you don't want to maintain a whitelist. In this case you can add some extra rules to prevent tx from being included in your blockchain:
- the account is not 'rich' enough: they need to buy your token in order to be allowed to create a transaction with enough fees. You can also make the price of the token higher for people you don't know enough yet making incentive to behave well.


## how can i remove a transaction if i have made an error
In case of error, blockchain is not the best to remove transactions since it needs some more complex management, but there are several techniques to achieve this:
- maintain a list of exceptions you need to sign with your master key. These exceptions are basically a pair of `block id`/`block signature` where the transaction is removed with the new valid block signature. This list is maintained by your master node to be accessed by all nodes to keep consensus.
- rebuild the blockchain from the invalid block. This is a bit more complex but have the advantage of leaving no trace. Basically you reuse all subsequent transactions and reinclude thhem in the new created blocks you sign with your master key.


## how can i be sure only good actors
The best way to favour good actors is to be the main seller of the tokens, in order to be able to control the price, and sell at highher price to the potential bad actors.

## how can i make money with my blockchain
- most incomes is useally done by selling tokens to third part accessing your private blockchain.
- it is also possible to make it closed source so you can resell the technology to third part. The pricing can be automated with the capability to implement at the blockchain level: you can audit the tokens in circulation ad ask for a percentage of the price thhey have been sold.


