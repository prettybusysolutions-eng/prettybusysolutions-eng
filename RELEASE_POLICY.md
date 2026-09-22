# Release policy

## Versioned software

Installable packages, protocols, libraries, and deployable services use
Semantic Versioning (`vMAJOR.MINOR.PATCH`). A release requires:

1. a clean default branch;
2. passing required checks;
3. a changelog or generated release notes;
4. a tag that matches the shipped artifact version; and
5. a GitHub release created from that tag.

`0.x` means the public contract can still change. `1.x` means compatibility is
part of the release contract; it does not imply production suitability.

## Presentation and data surfaces

Profile repositories and static sites use deploy history instead of artificial
package releases. Dataset/catalog repositories may use dated snapshots when a
snapshot has independent consumer value.

## Claim discipline

A tag records a version. It does not prove third-party validation, production
deployment, security certification, adoption, revenue, or performance. Those
claims require their own evidence.
