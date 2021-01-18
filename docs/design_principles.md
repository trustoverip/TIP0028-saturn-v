## Core Principles
This TIP provides a set of gGuidelines for how market requirements should be translated into architecture and technology decisions.

Evaluators of this TIP should look at each of these suggested design principles and consider the ramifications for supporting or not-supporting each.

The vendors supporting this TIP have incorporated these design principles into their software solutions.

### Laws of Identity
The seven (7) principles outlined by in 2006 and captured in the ToIP Design Principle Recommendation - [DP0003: Laws of Identity](https://github.com/trustoverip/deliverables/blob/main/recommendations/DP0003-laws-of-identity/DP0003-laws-of-identity.md) are foundational principles for this TIP.

### Privacy by design
The seven (7) principles outlined by in the ToIP Design Principle Recommendation - [DP0004: Privacy by Design](https://github.com/trustoverip/deliverables/blob/main/recommendations/DP0004-privacy-by-design/DP0004-privacy-by-design.md) are foundational principles for this TIP.

### Self-sovereign identity (SSI)
This TIP is purpose built to provide the foundational infrastructure necessary to support the [10 Core Principles](https://docs.google.com/document/d/1WqUOqdTBc3JACIlRviJoWJRcJHTNTNzk9_As9v-jwrY/edit#heading=h.ws45zwyr4hfb) that were adopted by the [Sovrin Foundation](http://sovrin.org) in support of SSI.

| Principle | Description |
| --- | --- |
| Existence | Users must have an independent existence. |
| Control | Users must control their identities. |
| Access | Users must have access to their own data. |
| Transparency | Systems and algorithms must be transparent. |
| Persistence | Identities must be long-lived. |
| Portability | Information and services about identity must be transportable. |
| Interoperability | Identities should be as widely usable as possible. |
| Consent | Users must agree to the use of their identity. |
| Minimization | Disclosure of claims must be minimized. |
| Protection | The rights of users must be protected. |

### Decentralization by Design
The ToIP Design Principle Recommendation - [DP0005: Decentralization by Design](https://github.com/trustoverip/deliverables/blob/main/recommendations/DP0005-decentralization-by-design/DP0005-decentralization-by-design.md) provides a spectrum of considerations to be considered when solution architectures are contemplating the degree of decentralization that is required.

This TIP minimally specifies that the root of trust MUST be managed in a decentralized manner, preferably by one or more decentralized public identity utilities.

When the technology has matured, this TIP will be modified to REQUIRE stronger decentralization technics for the root of trust by combining a decentralized ledger with [Key Event Receipt Infrastructure (KERI)](https://keri.one/). Refer to [advancements in the Indy DID Method](https://hackmd.io/@icZC4epNSnqBbYE0hJYseA/S1eUS2BQw).
