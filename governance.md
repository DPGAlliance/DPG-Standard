# Digital Public Goods Standard Governance

This is a work in progress. 

The purpose of this document is to share how the Digital Public Goods Alliance (DPGA) envisions engaging a growing community of contributors and stakeholders around the Digital Public Goods (DPG) Standard. Our goal is to balance responsiveness to feedback, with stability and predictabilty for the DPG Standard so it can be a framework that people can build for and to.

The DPG Standard leverages frameworks, standards and definitions from specific organizations that have broad market consensus and are facilitating the discovery, development, use of, and investment in digital public goods. Specific organizations the DPG Standard aligns with include: Open Source Initiative (OSI), Creative Commons, and Open Data Commons.

## Principles

The DPGA community adheres to the [OpenStand Principles](openstand.md) when developing the DPG standard.

## Code of Conduct

We have adopted the [Contributor Covenant Code of Conduct v2](CODE_OF_CONDUCT.md), and expect all members of the
community to embrace it. The following is an excerpt on our pledge:

*We as members, contributors, and leaders pledge to make participation in our community a harassment-free experience for everyone, regardless of age, body size, visible or invisible disability, ethnicity, sex characteristics, gender identity and expression, level of experience, education, socio-economic status, nationality, personal appearance, race, religion, or sexual identity and orientation.*

*We pledge to act and interact in ways that contribute to an open, welcoming, diverse, inclusive, and healthy community.*

## Revisions

The following section showcases the processes for:
* proposing modifications to the current version of the DPG Standard 
* reviewing proposed changes 
* incorporating proposed changes in forthcoming revisions

The latest version of the [Digital Public Goods Standard](standard.md) is found in the root folder of this repository. 
The DPG Standard is operationalized through a [questionary](standard-questions.md). This set of questions is used to screen 
projects or products, and validate whether they conform to the DPG Standard, and can thus be classified as digital public goods.

### Priority

Our priority for Q4/2020 and Q1/2021 is to establish a stable version of the DPG Standard. To do so, we ask for all comments and edits to be centered around the DPG Standard 
rather than the associated set of questions. The rationale being if the DPG Standard were to significantly change in the coming
months, so would the questionary, therefore any preliminary work on the questions may need to be discarded.

### Proposing Changes

These are the suggested steps for proposing changes to the DPG Standard:
- First, to avoid duplication, review the existing [Pull Requests](https://github.com/DPGAlliance/DPG-Standard/pulls) to see if your proposed change
has already been proposed or not. If it has already been proposed, you are encouraged to add your perspective
to the existing proposed change and argue for or against it with constructive and compelling arguments.
- If none of the open pull requests address the issue you are proposing, 
[edit the standard](https://github.com/DPGAlliance/DPG-Standard/edit/master/standard.md) and open a new pull request with your edits, guided by the "**one issue, one pull request**" guideline.
When opening a new pull request, be very explicit about the changes that you are proposing when making the case for your suggested changes. If your
contribution is commentary or a general opinion, we will still review it, but we will deem it nonactionable and close it.
- Once your pull request has been submitted, follow the discussion that ensues.

### Classification of Modifications

In order to streamline the review of proposals, we will use the following classifications and labelling them accordingly:

* [![](https://img.shields.io/badge/-minor_fix-c5def5)](https://github.com/DPGAlliance/DPG-Standard/pulls?q=is%3Apr+is%3Aopen+label%3A%22minor+fix%22) These 
are mostly stylistic edits that include, but are not limited to: correcting typographical errors, making gramatical edits, adding or removing clarifying
statements with the aim of improving readibility, or facilitating understanding of the DPG Standard to the reader. These proposed changes do not alter the 
intended meaning of the existing indicators, nor introduce or remove key concepts.

* [![](https://img.shields.io/badge/-major_change-FFA500)](https://github.com/DPGAlliance/DPG-Standard/labels/major%20change) These are modifications 
that alter the existing indicators in significant ways that have broader implications, but they do not challenge the purpose or scope of the DPG Standard.
These may also include reorganization of the various sections of the DPG Standard, removing existing sections entirely, or adding new indicators to the DPG Standard.

* [![](https://img.shields.io/badge/-fundamental-b60205)](https://github.com/DPGAlliance/DPG-Standard/labels/fundamental) These involve
fundamental or philosophical changes that challenge the purpose, scope, or very existence of the DPG Standard.

## Proposal Review

The process for reviewing and accepting proposals varies depending on the classification of the proposal:

* [![](https://img.shields.io/badge/-minor_fix-c5def5)](https://github.com/DPGAlliance/DPG-Standard/pulls?q=is%3Apr+is%3Aopen+label%3A%22minor+fix%22) After
leaving a minimum of one week of accepting additional comments from other members of the community, the pull request requires 1 secretariat co-lead and 1 technical
lead (see [Current Roles](#current-roles)) to review and approve the issue in order to accept and merge it. This review will happen on a rolling basis, there 
are monthly meetings to catch and address any outstanding issues.

* [![](https://img.shields.io/badge/-major_change-FFA500)](https://github.com/DPGAlliance/DPG-Standard/labels/major%20change). The moderator will first assign it
to a member of the DPGA for further investigation over a period of up to two weeks. That person will report and comment on the issue, documenting and exploring
the implications of accepting or rejecting that change, and will open another period of up to two weeks for additional input from the community. We will inform
the members of the DPGA's Internal Strategy Group (ISG) giving them an equal opportunity to comment. Reviewing these changes will happen quarterly. Consensus from the 2 co-leads and 2 technical leads 
(see [Current Roles](#current-roles)) will be required to accept or reject these proposals.

* [![](https://img.shields.io/badge/-fundamental-b60205)](https://github.com/DPGAlliance/DPG-Standard/labels/fundamental). After validating the legitimacy of the 
proposal, we will open a consultation process with significant communities and stakeholders throughout the ecosystem, including all [endorsers](endorsement.md).
The findings from this consultation process will be presented to the DPGA's Internal Strategy Group (ISG), who will have a week to veto or ask for more time
(where silence is implied consent). Consensus from the 2 co-leads and 2 technical leads (see [Current Roles](#current-roles)) will be required to  
either accept or reject the proposal. Reviewing these changes will occur twice per year during the first year, and yearly thereafter.

## Versioning

All notable changes to this project will be documented in the [CHANGELOG](CHANGELOG.md) 
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html) using a variation of the `MAJOR.MINOR.PATCH` format (accounting for the fact that this applies to content, not code):

* *MAJOR version when you make incompatible API changes*: [![](https://img.shields.io/badge/-fundamental-b60205)](https://github.com/DPGAlliance/DPG-Standard/labels/fundamental)
* *MINOR version when you add functionality in a backwards compatible manner*: [![](https://img.shields.io/badge/-major_change-FFA500)](https://github.com/DPGAlliance/DPG-Standard/labels/major%20change)
* *PATCH version when you make backwards compatible bug fixes*: [![](https://img.shields.io/badge/-minor_fix-c5def5)](https://github.com/DPGAlliance/DPG-Standard/pulls?q=is%3Apr+is%3Aopen+label%3A%22minor+fix%22)

### Releasing a New Version

Follow these steps to release a new version:

1. Document your upcoming changes in `CHANGELOG.md`. Follow the existing structure and be consistent with the order of subsections: `Added`, `Changed`, `Deleted`. Also be sure to link the version in the diff list at the very bottom of the CHANGELOG.
2. Update the version number in both `standard.md` and `README.md`.
3. Commit all the changes that will be included in the new version.
4. Tag the last commit, for example, for version 1.0.1:
    ```bash
    git tag -a v1.0.1 -m "Version 1.0.1"
    ```
5. Push the tag to the origin:
    ```bash
    git push origin --tags
    ```
6. Visit https://github.com/DPGAlliance/DPG-Standard/releases and click on `Draft a New Release`:
    - Select the version you just tagged above in step 3
    - Enter the `Release title`, for example `v1.0.1` consistent with the preceeding steps.
    - In the `Describe this release`, copy and paste the text from the CHANGELOG for this version in *raw form* (it's markdown after all). Preview and verify that it looks good (you can edit this information again later, no big deal if something is wrong in the description).

# Current Roles

* [Liv Marte Nordhaug](https://github.com/livmarte), Secretariat Co-Lead
* [Lucy Harris](https://github.com/lucyeoh), Secretariat Co-Lead
* [Christer Gundersen](https://github.com/christer-io), Technical Lead
* [Victor Grau Serrat](https://github.com/lacabra), Technical Lead, current moderator.
