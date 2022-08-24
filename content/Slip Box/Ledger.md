> [!SUMMARY]+
> A ledger is a publicly visible history of transactions. This note is about ledgers in [[Cryptocurrency]]

Protocol:
1. Anyone can add entries to the ledger
2. Only signed transactions are valid
3. Overspending is impossible
4. Proof of work
5. Blockchain

As *anyone* can add entries to the ledger (Protocol 1) , some entries can be made such as "Alice pays Bob $250" without the consent of Alice in this case. To prevent this from occurring, [[Digital signatures]] are used.

If the transaction "Alice pays Bob $250" has been verified, it is possible for Bob to repeat the same transaction which has already been "approved". To prevent this exploit, each [[Digital signatures]] *must* include the ID of the transaction taking place (Protocol 2).

Overdrawing money from the ledger is impossible (Protocol 3) as a transaction where a person spends more than they have is as invalid as if they never signed it. This also means that to verify a transaction, the full transaction history of that particular person must be known.

An interesting point to note is that if everyone used the ledger, there would be no need for physical cash as ledger entries could be used as proof of payment. Hence, the money listed in the ledger can be put under a different name such as [[Bitcoin]]. ==*The currency is the list of transactions made.*==

To decentralise the [[Cryptocurrency]], rather than keeping a central ledger, each person maintains their own ledger. When a new transaction takes place, it is broadcast to all other users who then add the entry to their own ledger. The ledger with the most computational work put into it will be agreed upon as the "correct" ledger.

The ledger is grouped into "blocks" of transactions. Each block includes a hash which is unique to a particular message or file (i.e. unique to a particular [[Digital signatures]]) and is near impossible to reverse engineer. The hash also completely changes when even a small piece of information is changed so no pattern can be found. Hence when a hash is generated and attached to a block, it can be considered to be a stamp of authenticity and is known as a proof of work. The next block contains the hash of a previous block and forms a chain, creating the term "blockchain". The longest blockchain is agreed as the correct one. (Protocol 5)

If a transaction or the order of blocks is altered, all the subsequent hash functions will change causing the proof of works for all blocks to be recomputed. This means that to include a fraudulent transaction, a particular entity must be able to generate new blocks (and hence maintain the longest blockchain) than all other block creators (known as miners) combined. As such, fraud is only possible when one entity owns around 50% of *all* computing power dedicated to finding a proof of work. (Protocol 4)

Miners are allowed to include a transaction within the block which gives them a set quantity of that currency to incentivise them to help maintain the credibility of the blockchain and to prevent the concentration of computing power.

---
- Index:: [[Cryptocurrency]]
- Related:: [[Bitcoin]], [[Digital signatures]]
---