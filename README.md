# MechatronicSystems.Group Member Info

## Purpose

This organisation is used to host **valuable** code and other assets for MS.G affiliated projects. It is the recommended means for staff and students to store and disseminate code, research data and other assets that are well suited for git-based version control.

It is **not** intended to be used as a personal storage space, hosting of proof-of concept, and experimental projects. Please use your own personal GitHub account for such purposes.

## Membership

Membership to this organisation is restricted to MS.G staff and students. Undergraduates and other external collaborators should be added as such to individual repositories as required.

Please refrain from displaying your membership of this organisation on your public GitHub profile unless you are actively contributing to this organisation.

## Code of Conduct

This code of conduct outlines the required practises for data management and repository standards. It also outlines the transfer of ownership of valuable code and data from students to the university.

The scope of this code of conduct is limited to this UCT MS.G GitHub organisation account and its repositories. It does not apply to any other MS.G assets or intellectual property hosted elsewhere.

### Repository Standards

Given that repository-based development a core skill of modern engineering; all repositories in this organisation, in general, should be maintained to an above-average standard.

#### Public Repositories

The MS.G, in the spirit of open collaboration, encourages staff and students to publish their repositories publicly whenever possible. Public repositories will however be held to a very high standard as they are a reflection of the MS.G and the university. They should be **well documented**, have a **clear purpose**, be **reproducible** and be **useful to others**. They should be considered a publication in their own right.

As a bare minimum, public repositories should have the following:

- A `README.md` file that outlines the purpose of the repository, how to use it, and other essential information.
- A `LICENSE.md` file that describes the license under which the repository is released.

  > Please consult with your supervisor and the [UCT Intellectual Property Guidelines](http://www.rci.uct.ac.za/rcips/ip/overview) before choosing a license and publishing publicly.

- An appropriate GitHub Description, Tags, and other GitHub settings to make the repository discoverable.
- Be marked as archived if it is no longer maintained. e.g. After a student has graduated.

> If actively developing in a public repository, the development of which should be of a semi-professional standard with regards to [**continuous integration**](https://aws.amazon.com/devops/continuous-integration/).
>
> Otherwise please develop within your personal GitHub account until [transferring ownership](#transfer-of-ownership) once done.

Any public repository that does not meet these standards will be made private during regular audits.

#### Private Repositories

Private repositories are intended for code and other assets that are valuable but not suitable for sharing publicly. This includes:

- Unpublished research data.
- Code and other assets that are **proprietary**, **confidential**, or in a **patent** process.
- Personal information and other content sensitive to ethical and legal considerations.
- Property co-owned between the ARU and external collaborators.
- Any other information that is valuable but for whatever reason is not suitable for sharing publicly.

Although private repositories are not held to the same standard as public repositories, they should still be well maintained and be useful to future students. Private repositories are still visible to members of the organisation. In order to limit pollution; repositories still in development should only be placed in this organisation if necessary. Otherwise, please develop within your personal GitHub account until [transferring ownership](#transfer-of-ownership) once done.

> You can access most GitHub services through the [GitHub Student Developer Pack](https://education.github.com/pack), which is available to all UCT students and staff, without the need for this organisational account. Please visit [https://education.github.com/pack](https://education.github.com/pack) for more information.

### External Repositories

Any research conducted in collaboration with internal or external partners involving git-based repositories and are hosted outside of this organisation should still be mirrored within this organisation.

> A mirror is a copy of a repository that is always kept up to date with the upstream repository. This can be done manually or automatically using GitHub Actions or similar.
>
> A mirror repository is not a fork. A fork is a copy of a repository that is intended to be developed independently, with changes pushed to the upstream repository via pull requests.

For reference, please see [LawrenceStanton/SISPS-PV-PCB](https://github.com/LawrenceStanton/SISPS-PV-PCB/blob/master/.github/workflows/mirror.yml) as an example for mirroring an external repository.

### Appropriate Contents

Repositories in this organisation should only contain code and other assets that are appropriate for git-based version control. This includes:

- Code.
- Most forms of research and experimental data.
- Documentation, markdown and simple webpages.
- LaTeX documents.
- Other text-based assets.

Repositories should not contain:

- Large binary files (that are frequently modified). e.g. Images, videos, audio, build outputs, etc.
- Personal information and other content sensitive to ethical and legal considerations.
- Word, Excel, PowerPoint, and other proprietary file formats.
- Content with absolute paths or other restraints that tie it to a local file system.
- Extremely large amounts of data.

Please maintain a `.gitignore` file in your repository to exclude inappropriate files from being pushed to the remote.

> Please consider alternative cloud storage services, such as the 1TB OneDrive storage provided by UCT, as an alternative for files not suitable for GitHub.

### Transfer of Ownership

All UCT projects are governed by the [UCT Intellectual Property Policy](http://www.rci.uct.ac.za/rcips/ip/policy). In general, all code and data generated as part of a research project is the property of UCT. The MS.G implements this for valuable GitHub-hosed IP by transferring ownership from the student to the MS.G organisational account before or upon graduation. This ensures that the code and data is maintained and accessible to future researchers.

Not all code and data generated as part of a research project is valuable. This should be determined between the student and their supervisor. If the code and data is not valuable, it should not be hosted in this organisation.

Students may however fork their original work back into their personal GitHub account if they wish to continue working on it. This is a good way to keep a personal copy of the code and data for future reference, especially if the original is made private.

> Forks of private repositories are enabled by default, but may be disabled for repositories containing sensitive content.

