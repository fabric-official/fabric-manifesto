Contributing to Fabric Manifesto

🔑 Governance-Driven Contributions

The Fabric Manifesto is not altered through normal open-source pull requests.
All modifications are governed by Fabric DAO on-chain proposals to ensure decentralized and transparent evolution of this document.

📜 Contribution Rules

DAO Proposal Required
Any changes to FABRIC_MANIFESTO.md, governance docs, or roadmap diagrams must be tied to a Fabric DAO proposal ID.
Submit proposals via:
fab dao submit --proposal <path_to_proposal.yaml>
Proposals include:
Rationale for change
Impact on governance or protocol
Manifesto section references
Voting and Approval
DAO members vote on proposals using:
fab dao vote --proposal <proposal_id> --choice yes/no
A majority vote and quorum are required for approval.
Merging Changes
Approved proposals trigger a GitHub Action that merges associated PRs automatically.
PR commits must reference:
Proposal ID
On-chain transaction hash
Immutable Historical Archive
Previous manifesto versions are permanently stored:
In this repository under /archive/
On-chain within DAO state for auditability

✅ Contribution Workflow
Fork the repository and create your branch.
Draft proposed changes.
Submit DAO proposal referencing your branch and PR link.
Await community discussion and vote.
Once approved, Fabric’s GitHub Action will merge your branch.

🔒 Security
All commits must be GPG-signed for authenticity.
External code of conduct follows Fabric DAO governance standards.
Unauthorized merges will be reverted automatically.
💬 Community Discussion
Join discussions about proposed manifesto changes on:
Fabric DAO Forum (coming soon)
GitHub Discussions
“Every change must be earned, verified, and approved—not by a company, but by the community.”
