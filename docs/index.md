
## Saturn-V TIP

The __Saturn-V__ TIP is a [recommendation](https://trustoverip.github.io/deliverables/process/work_products/#recommendations) of the ToIP Foundation that prescribes a specific **recipe** of technical components that are assembled according to particular design principles and best practices in support of a wide range of use cases.

A _ToIP Interoperability Profile (TIP)_ is a deliverable of the [ToIP Technology Stack Working Group](https://wiki.trustoverip.org/display/HOME/Technology+Stack+Working+Group).

## Convener(s)

* Richard Esplin
* Dan Gisolfi

## Our Recipe
The vendors supporting this TIP have agreed to develop software that supports the following solution components and will be compliant with the associated test suites for these components:

| ToIP Technical Stack Layer | TIP Technology |
| --- | --- |
| Three | Hyperledger Aries |
| Two | Hyperledger Aries with DIDComm |
| One | Hyperledger Indy |

1. Layer 1: Public Identity Utilities that implement the Indy DID Method Specification.

2. Layer 2: Digital Wallet and Agent software that leverage the DIDComm plug-in in Hyperledger Aires which is compliant with the [ToIP TSS0011: Layer 1 Interop Spec](https://trustoverip.github.io/TSS0011-layer1-Interop-spec/).

3. Layer 3: Digital Wallet and Agent software that leverage Hyperledger Aires and is compliant with the [ToIP TSS0012: Layer 2 Interop Spec](https://trustoverip.github.io/TSS0012-layer2-Interop-spec/).
