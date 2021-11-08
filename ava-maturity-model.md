---
title: "Software Maturity Model"
permalink: /maturity-model/
---
# Scope

This document describes and defines Avanade's maturity model for Open-Source and InnerSource, as agreed at any given time by the [Open Source Review Board](https://avanade.sharepoint.com/sites/OpenSource/SitePages/Open-Source-Review-Board.aspx) at Avanade.

This is intended to support Avanade and the broader community, to understand the level of expected quality, and strategic importance for projects that are maintained by Avanade.

Projects on the [Avanade GitHub](https://github.com/avanade) or [Avanade InnerSource](https://github.com/ava-innersource) must follow the standards below.

# Types of Avanade project
Avanade supports multiple project types. InnerSource projects are those which are focussed on internal employees within the [Avanade InnerSource](https://github.com/ava-innersource) GitHub organizaion. Open-Source projects are those which are publicly available to the world on our [Avanade GitHub](https://github.com/avanade).

Our bias is to promote repositories to be open, and unless there is a reason to collaborate internally, we aim to migrate InnerSource projects to our [Avanade GitHub](https://github.com/avanade).

## Shields
Shield URLs for each example are found below - you'll need to take the image URL, and link out to the [maturity model](https://avanade.github.io/maturity-model/) like so:


> [![New Ava InnerSource](https://img.shields.io/badge/New-Ava--InnerSource-%23DC4600?labelColor=%23e5e5e5)](https://avanade.github.io/code-of-conduct/)
```
[![New Ava InnerSource](https://img.shields.io/badge/New-Ava--InnerSource-%23DC4600?labelColor=%23e5e5e5)](https://avanade.github.io/code-of-conduct/)
```


## InnerSource

| Name | Requirements | Description | Badge | Badge URL |
| ---- | ------------ | ----------- | ----- | ---------- |
| Scratch | - none - | Space for employees to test and play around. | ![Scratch Ava InnerSource](https://img.shields.io/badge/Scratch-Ava--InnerSource-%23DC4600?labelColor=yellow) | `https://img.shields.io/badge/Scratch-Ava--InnerSource-%23DC4600?labelColor=yellow` |
| New | - none - | Newly created projects, which will either end up as open source projects, or internal IP. | ![New Ava InnerSource](https://img.shields.io/badge/New-Ava--InnerSource-%23DC4600?labelColor=%23e5e5e5) | `https://img.shields.io/badge/New-Ava--InnerSource-%23DC4600?labelColor=%23e5e5e5` |
| Internal | Executive Sign-off or Business Sponsor assigned | Projects which have been deemed to be internal only at this time. | ![Internal Ava InnerSource](https://img.shields.io/badge/Internal-Ava--InnerSource-%23DC4600?labelColor=%23C80000) | `https://img.shields.io/badge/Internal-Ava--InnerSource-%23DC4600?labelColor=%23C80000` |


## Open-Source

| Name | Requirements | Description | Badge | Badge URL |
| ---- | ------------ | ----------- | ----- | ---------- |
| Incubating | • Community health files (LICENCE.md, CONTRIBUTING.MD, SECURITY.md) included. • Code scans configured for each pull request, and regular scans, including for vulnerabilities, secret keys, and intellectual property. | Proof of concepts and new projects. | ![Incubating Ava Maturity](https://img.shields.io/badge/Incubating-Ava--Maturity-%23FF5800?labelColor=yellow) | `hhttps://img.shields.io/badge/Incubating-Ava--Maturity-%23FF5800?labelColor=yellow` |
| Working | • Everything from Incubating. •  Release candidate or packages available. • Basic setup instructions documentation. | A working concept, but it's early. | ![Incubating Ava Maturity](https://img.shields.io/badge/Incubating-Ava--Maturity-%23FF5800?labelColor=yellowgreen) | `https://img.shields.io/badge/Incubating-Ava--Maturity-%23FF5800?labelColor=yellowgreen` |
| Ready | • Everything from Working. • CI/CD configured. • Mature documentation including sample, setup, and FAQs. | The team self-certify as production ready, but no Avanade official backing. | ![Incubating Ava Maturity](https://img.shields.io/badge/Incubating-Ava--Maturiy-%23FF5800?labelColor=green) | `https://img.shields.io/badge/Incubating-Ava--Maturiy-%23FF5800?labelColor=green` |

#### Avanade Official - Strategic
| Name | Requirements | Description | Badge | Badge URL |
| ---- | ------------ | ----------- | ----- | ---------- |
| Strategic | • Avanade sign-off. •  Maintenance, bug support, long term support - and a notice of retirement in advance of deciding to do so. | Noted as a strategic project for Avanade. | ![Avanade Strategic](https://img.shields.io/badge/Strategic-Avanade-%23FF5800?labelColor=brightgreen) | `https://img.shields.io/badge/Strategic-Avanade-%23FF5800?labelColor=brightgreen` |


# Quality
We aim to amplify the best of what we bring, rather than curate and select winners.

Recognizing this, some projects will necessarily over time become stale.

## Projects with no contributions ever
After a month of being empty, or with no changes to the initial template, repositories will be retired.

Any project with change, such as a commit, or item on a project board, will fall out of scope

## Projects with no contributions after a year
After a year of no contributions - from commit, issue, discussion, or otherwise - the repository will be flagged to the [Open Source Review Board](https://avanade.sharepoint.com/sites/OpenSource/SitePages/Open-Source-Review-Board.aspx) at Avanade.

[Avanade will then either mindfully contribute the project to the community, archive, or remove the repository.](https://avanade.sharepoint.com/sites/OpenSource/SitePages/Shutting-down-an-open-source-project.aspx)