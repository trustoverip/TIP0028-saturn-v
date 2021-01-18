## Plans of Record
The vendors supporting this TIP have outlined test plan milestones to help interested parties to understand the state of interoperability testing.

### Wave 1
Our initial plan milestone will be for each vendor to demonstrate interoperability against the following:

1. Validation against Aries Protocol Test Suite for Aries Interop Profile v. 1.0
2. Core Aries Interop Profile v. 1.0 - See Aries RFC 302
  1. DIDComm (did:sov)
  2. Connection
  3. Credentials
  4. Proofs
3. Ephemeral Proofs: receive only
  1. Service decorator
  2. Needed for VC-Authn-OIDC (used by BC.gov)
4. Transition Message Type to HTTPs: receive
  1. Aries RFC 348: Can receive messages with protocol definition of type http://didcomm.org

### Wave 2
Our second milestone will be for each vendor to tackle the goals of AIP 2

* [Aries PR 579 for RFC 302 - AIP 2.0 ](https://github.com/hyperledger/aries-rfcs/pull/579/commits)
* [Notes AIP 2.0](https://docs.google.com/document/d/1Gvv0VNEfnYjJXgscxYRJ38f_KRrojNKv5hrF2t-oESM/edit)
* [Slide deck with current thinking](https://docs.google.com/presentation/d/1trbAnVLomRr5TjUBC0U9N8bbiaahmPmTBeIYzWaDBj8/edit#slide=id.p)
* [Discussion in Aries WG B 2020-12-02](https://wiki.hyperledger.org/pages/viewpage.action?pageId=41587389)
* [Discussion in Aries WG B 2020-12-09](https://wiki.hyperledger.org/pages/viewpage.action?pageId=41588229)

#### User Stories
* Able to provide a proof without creating a persistent connection.
  * Out-of-Band Protocol

#### Other Technical Requirements
* Transition Message Type to HTTPs: send/receive
  * Aries RFC 348: http://didcomm.org

#### Further Ideas
* Core Aries Interop Profile v. 2.0 (TBD)
  - Out Of Band
  - DID Exchange
  - Credential Exchange Protocols (v2)
  - feature discovery v2
  - mime-types (to help transition to didcomm v2)
  - Signed attachments
* New MIME Types
* BC-Gov Test Suite
