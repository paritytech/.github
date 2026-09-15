# Security Policy

Unless a specific release states otherwise, these repositories have not received a full security audit.

Use of this repository in production or production-like deployments should only happen after an independent security review of the relevant code, configuration, generated output, and deployment environment.

Parity Technologies is committed to resolving security vulnerabilities in our software quickly and carefully. We take the necessary steps to minimize risk, provide timely information, and deliver vulnerability fixes and mitigations required to address security issues.

## Reporting a vulnerability

There are two routes. Use the one that fits.

**Parity's Bug Bounty Program** is for findings that may be eligible for a reward. Scope, eligibility, rewards and terms are published at [parity.io/bug-bounty](https://parity.io/bug-bounty). Submissions to the programme are only considered through the form linked there.

**security@parity.io** is for everything else, including reports from downstream projects and from anyone who does not want to participate in the bounty programme. We accept reports here whether or not the repository is in bounty scope.

If you are unsure which applies, use security@parity.io and we will route it.

We encourage the use of encrypted communication. Include a description of the issue, its potential impact, and steps to reproduce.

### What to expect

- **Bug Bounty acknowledgement**, which we aim to send within two business days, confirming we have the report and who is handling it.
- **An initial assessment** telling you whether we consider it a security issue, and if so our view of its severity.
- **Updates** as the work progresses, and notice before any advisory is published.
- **Credit** in the advisory unless you ask us not to.

We will tell you if we decide not to act on a report, and why.

Organisations that distribute or operate software built on Parity code can request access to a triaged reporting route with a shorter acknowledgement commitment. It is intended for reports that arrive with the failing component and version identified, working reproduction steps, and the mechanism established. Contact security@parity.io to request access.

## Scope

This policy covers code in the `paritytech` GitHub organization.

Parity authors and maintains open source software. We are not the operator of the networks, wallets, or services that others build and deploy with it. If you have found an issue in a deployed product or service rather than in this code, report it to whoever operates it. If you are not sure, tell us and we will help you find the right party.

The presence of this file does not mean a repository is in scope for the Bug Bounty Program. Check the programme scope.

## Supported versions

Security fixes are applied to the latest release of an actively maintained repository. Older releases are not routinely backported. Where a fix is backported, this is stated in the advisory.

## Responsible investigation and reporting

This includes, but is not limited to:

- Report the issue to us first, and give us reasonable time to fix it before disclosing it elsewhere.
- Do not make repeat submissions of low quality, rejected, or automated vulnerability reports.
- Do not defraud or harm Parity Technologies, Polkadot, or their users during your research. Make a good faith effort not to interrupt or degrade our services or the network's.
- Do not target our physical security measures, or use social engineering, spam, or denial of service attacks.
- Do not violate the privacy of other users or destroy data.

Research conducted in line with this policy is research we welcome. We will not pursue action against anyone who follows it in good faith.

## Sourcing security information

The [Polkadot Security Hub](https://security.parity.io/) is a resource for all things security in the Polkadot ecosystem. It holds [security vulnerability disclosures](https://security.parity.io/disclosures), detail on [common security vulnerabilities](https://security.parity.io/top), guidance on [how to securely test your Polkadot project](https://security.parity.io/tools), and the [audits](https://security.parity.io/audits) that have been conducted.
