# notaryDapp [WIP]

Proof of concept of notary Dapp using qtum based technology

The concept of notary to test is based in bitcoin private-public key pairs to sign the proof of ownership of the file. The owner of the file creates an sha-512 hash  of the file and signed it with their private key, which creates a signature. Then, stores this signature and file hash in the smart contract deployed in the blockchain.

The signature is composed of the file hash and owner address fields. 


The dapp deployed as smartcontract can be called to show if the owner is the rightfull of the file. This is simple done calling a smartcontract method with the owner public key, address and the file hash to verify identity. This call is done off chain and it doesn´t have any cost to the person to verify

# References

https://searchsecurity.techtarget.com/definition/digital-signature
