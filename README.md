# shielded-transaction-


A shielded transaction is essentially a transaction that is between two shielded addresses. This will essentially keep the addresses, transaction amount and the memo field shielded from the public, with an exception of migrating funds between Sprout and Sapling shielded addresses.  

Shielded addresses are ones that use zero-knowledge proofs to allow transaction data to be encrypted by remaining verifiable by network nodes. 


Senders to a shielded address can or can not include an encrypted memo, and the recipients of a shielded or deshielding transaction do not learn about the sender address through the transaction receipt in their wallet. The receivers can only learn the value which is sent to their address and if they receive to shielded addresses, any encrypted memo that has been included by the member.


In Zcash, there are  two types of addresses, transparent addresses and shielded addresses. Transparent addresses on the Zcash protocol are equivalent to public addresses on the Bitcoin protocol for example, and function similarly as a result. All transparent addresses interact with the Transparent Value Pool and this is what publicly reveals transaction data and allows it to be viewed on the Zcash blockchain at any time by anyone. 
