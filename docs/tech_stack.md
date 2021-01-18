### Technical Stack Proposal
<font color='cyan'>Identify the technologies associated with each layer of the ToIP Stack that will help to define this TIP.</font>

| ToIP Technical Stack Layer | TIP Technology |
| --- | --- |
| Three | Hyperledger Aries |
| Two | Hyperledger Aries with DIDComm |
| One | Hyperledger Indy |

![tech-stack](./images/tech-stack-concepts.png)

The vendors supporting this TIP have agreed to support the following solution components:

1. Layer 1: Public Identity Utilities that implement the Indy DID Method Specification.

2. Layer 2: Digital Wallet and Agent software that leverages the DIDComm plug-in in Hyperledger Aires which is compliant with [ToIP TSS0011: Layer 1 Interop Spec]().

3.  Layer 3: Digital Wallet and Agent software that leverages the Hyperledger Aires which is compliant with [ToIP TSS0012: Layer 2 Interop Spec]().
