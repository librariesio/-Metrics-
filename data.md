# Data

The data below should support [measures](/measures.md) which in turn provide answers to [questions](/questions.md).

## Currently gathered

| Entity |   Name   |      Type      |  Description (if not obvious) |
|----------|----------|:-------------:|------|
| Project | name |  String | - |
| Project | description | String | - |
| Project | homepage | URl | - |
| Project | keywords | Array of String | - |
| Project | language | String | - |
| Project | platform | array of string | List of distribution sources for this project e.g. npm, rubygems etc |
| Project | repository url | URI | - |
| Project | deprecated | Bool | Is the project marked as deprecated* |
| Project | unmaintained | Bool | Is the project marked as unmaintained* |
| Project | deleted | Bool | If every distribution is removed |
| Project | latest stable release | Version | - | 
| Project | latest release | Version | - | 
| Repository | Host | String | The provider for the repo (Github, GitLab, BitBucket, Trac, Sourceforge, etc) |
| Repository | Owner | User or Organisation | - |
| Repository | Issues | Array of Issue | - |
| Repository | Contributors | Array of contributor | - | 
| Repository | Stars | Int | - |
| Repository | Subscribers | Int or Array of users | watchers  |
| Repository | Forks | Array of repository | - |
| Version | Version or release | SemVer | The version number or tagged release for this update |
| Version | Release date/time | Datetime | - | 
| Version | Licence | Array of licences | The SPDX-normalised licence or set of licences |
| Version | ReadMe | Document | - | 
| Version | Dependencies | Nested array of project versions | - |
| Version | Dependent_repositories | Array of repositories | - |
| Version | Dependent_projects | Array of projects | - |
| Version | Commits | Array of commit | Actually called contribution in Libraries.io | 
| Issue | number | int | - |
| Issue | title | String | - |
| Issue | body | Document | The description of the issue |
| Issue | created | Datetime | - |
| issue | updated | Datetime | - |
| Issue | state | open/closed | - |
| Issue | firstpr | bool | is this issue marked as a good first contribution? |
| Contributor | Name | String | - |
| Contributor | Location | String | - |
| Contributor | Description | - | 
| Organisation | Name | String | - |
| Organisation | Location | String | - |
| Organisation | Description | - | 

* names, descriptions and keywords are searched for words like deprecated or unmaintained. Libraries.io also farms for contributions of this data. 

## Proposed Data to Collect

| Entity | Name | Description (if not obvious) | Source |
|----------|----------|-------------|------|
| Project | deployers | The set of people able to deploy a new version of a project |  |
| Project | distributors | The set of people able to distribute new versions of a project |  |
| Project | documentaiton | url of documentation |  |
| Project | faq | url of faq |  |
| Project | donate | url for donations |  |
| Project | chat | url for project chat |  |
| Project | forum | url for project forum |  |
| Project | supporters | an array of supporters sponsoring the project in cash or kind |  |
| Project | ci_location | url for the ci environment  |  |
| Project | distributors | array of users/organisations |  |
| Project | deployers | array of users/organisations |  |
| Repository | branches | array of braches |  | 
| Repository | subfolder | the location within the repo for this package |  |
| Branch | name | | | 
| Branch | created | | | 
| Branch | last commit | SHA | | 
| Branch | total commits | | | 
| Version | Copyright holders |  copyright holders (Array of users) | |
| Version | changelog | project changelog |  |
| Version | changelog_updated | last update on changelog |  |
| Version | cves | #CVEs disclosed for this version |  |
| Version | code_quality | external measure of code quality (i.e. code climate) |  |  
| Version | test_coverage | external measure of test coverage (i.e. code climate) |  |  
| Version | downloads | # downloads | 
| Version | download_reqests | # download requests (i.e. direct dependencies) |  |
| Version | build_errors | # reported build errors |  |
| Version | test_status | pass/fail (you'd hope always pass) |  |
| Version | citation | link to citation file |  |
| Version | languages | Breakdown of langs and %age breakdown | - |
| Version | size | Byte size of version 
| Version | diff_size | diff size to previous version | - |
| Version | commit | Release commit SHA/tag |  |
| Issue | comments | An array of comments |  |
| Contribution | Type | The type of contribution (issue, creating, labeling, assigning, commenting, reviewing, commiting,  donating, voting, PR) breaking types out, a la commit |  |
| Commit | SHA | The SH string id of the commit |  | 
| Commit | DiffSize | Lines/chars added/removed | 
| Commit | Datetime | Datetime |
| Commit | Author |  |  |
| Commit | Committer |  |  |
| Commit | Message |  |  |
| Commit | ci_status | pass/fail/warn |  |
| Commit | ci_status_message | Log of the CI |  |
| Comment | id |   |  |
| Comment | source | Source of comment (SE/Google Group/GH)  |  |
| Comment | author | A user |  |
| Comment | created |  |  |
| Comment | updated |  |  |
| Contributor | organisation |  The organisational affiliation of the contributor |  |
