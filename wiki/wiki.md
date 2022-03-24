---
[[_TOC_]]
<!-- DOCUMENTGENERATION -->

#  Code Release Versions


|Release Version| BranchId | Release Date | Notes | 
|--|--|--|--|
| v1.0.21 (DEV) || TBC | [here](/_WIKI/_Release/V.1.0.18) | N/A |
| v1.0.20 (latest) |**release.v.1.0.20**| 18/12/2020| [here](/_WIKI/_Release/V.1.0.20) | N/A |
| v1.0.19 (latest) |**release.v.1.0.19**| 02/12/2020| [here](/_WIKI/_Release/V.1.0.19) | N/A |
| v1.0.18 (latest) |**release.v.1.0.18**| 04/11/2020| [here](/_WIKI/_Release/V.1.0.18) | N/A |
| v1.0.17 (latest) |**release.v.1.0.17**| 14/10/2020| [here](/_WIKI/_Release/V.1.0.17) |
| v1.0.16 (latest) |**release.v.1.0.16**| 20/08/2020| [here](/_WIKI/_Release/V.1.0.16) |
| v1.0.15 |**release.v.1.0.15**| 13/08/2020| [here](/_WIKI/_Release/v.1.0.15) |
| v1.0.14 |**release.v.1.0.14**| 29/06/2020 | [here](/_WIKI/_Release/v.1.0.14) |
| v1.0.13 |Archived |22/06/2020 | [Archived] |
| v1.0.12 |Archived |15/06/2020 |[Archived] |
| v1.0.11 |Archived |08/06/2020 |[Archived] |
| v1.0.10 |Archived |01/06/2020 |[Archived] |
| [older] |Archived |Archived |[Archived] |

#  Branching Strategy

## Branching Approach and Structure
- Keep the branch strategy simple 
- All branches created from master
- Use feature branches for all new features and bug fixes
- Merge feature branches into the master branch using pull requests

## Bug Fixes
If a defect is found on a release version, a new branch from master is created where the defect is fixed and merged to master. If this fix must be distributed to current clients, the changes from this fix are cherry-picked into the latest release branch. The publish to GitHub pipeline will then be executed to distribute this fix to the public git hub mirror.
