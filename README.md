# CrowdNotifier - Decentralized Privacy-Preserving Presence Tracing

This repository puts forward a proposal for a secure, decentralized,
privacy-preserving presence tracing system. Our proposal aims to simplify and
accelerate the process of notifying individuals that shared a semi-public
location with a SARS-CoV-2-positive person for a prolonged time without
introducing new risks for users and locations. Existing proximity tracing
systems (apps for contact tracing such as SwissCovid, Corona Warn App, and
Immuni) notify only a subset of these people: those that were close enough for
long enough. Current events have shown the need to notify _all_ people that
shared a space with a SARS-CoV-2-positive person. The proposed system aims to
provide an alternative to increasing use of apps with similar intentions based
on invasive collection or that are prone to abuse by authorities. Our
design aims to minimize privacy and security risks for individuals
and communities, while guaranteeing the highest level of data protection and
good usability and deployability.

With this proposal, we seek feedback from a broad audience on the high-level
design, its security and privacy properties, and the functionality it offers, so
that the merits of the design can be discussed, and protection mechanisms can be
added to correct weaknesses. We feel it is essential that designs be made public
so the community as a whole can discuss the proposal and verify the claimed
privacy guarantees before applications are deployed.

## Changes with respect to v1.0

The current version of the white-paper contains several improvements with respect to version v1.0 that we published here earlier. The cryptographic protocol has been changed significantly to avoid the need to reprint a new QR code after triggering a notification. The white paper itself contains a more structured analysis of the security and privacy properties, as well as a more extensive comparison with other deployed systems.

## Implementations of CrowdNotifier

The [reference implementation of CrowdNotifier](https://github.com/CrowdNotifier/crowdnotifier-ts/) implements the cryptographic schemes as described in the white paper. The proof-of-concept SDKs 
for [Android](https://github.com/CrowdNotifier/crowdnotifier-sdk-android) and [iOS](https://github.com/CrowdNotifier/crowdnotifier-sdk-ios) implement the core cryptographic operations 

## Who we are

We are a international consortium of technologists, legal experts, engineers and
epidemiologists with a wide range of experience who are interested in ensuring
that any presence tracing technology does not result in governments obtaining
surveillance capabilities which will endanger civil society.

The following people are behind this design:

**EPFL**: Prof. Carmela Troncoso, Prof. Marcel Salathé, Prof. Edouard Bugnion, Dr. Wouter Lueks  
**ETH**: Prof. Kenneth G. Paterson
**TU Delft**: Prof. Seda Gürses  
**University College London**: Dr. Michael Veale

This consortium overlaps with [the DP3T
consortium](https://github.com/DP-3T/documents), but we stress that these are
separate projects.

## Contributing

Everyone interacting on the CrowdNotifier projects codebases, issue trackers, etc. is expected to follow the [code of conduct](CODE_OF_CONDUCT.txt).

### Thanks!

We are grateful for the feedback, questions, suggestions and fixes of everyone that commented on earlier versions of this white paper:
Paul-Olivier Dehaye,
Daniel Kahn Gillmor,
Teo Goddet,
Andreas Greulich,
Matthias Payer,
Thusid,
Christian Paul,
Trond Arve Wasskog,
and Peter Wells.
