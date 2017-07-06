## Libraries.io's Curent Metrics

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
| Version | Dependents | Array of repositories | - |
| Version | Commits | Array of commit | Actually called contribution in Libraries.io | 
| Commit | SHA | String | The SH string id of the commit | 
| Commit | Datetime | Datetime | - |
| Commit | Contributor | Contributor | - | 
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

## Proposed Metrics

| Entity | Name | Description (if not obvious) | Source |
|----------|----------|-------------|------|
| Project | deployers | The set of people able to deploy a new version of a project |  |
| Project | distributors | The set of people able to distribute new versions of a project |  |
| Project | documentaiton | url of documentation |  |
| Project | faq | url of faq |  |
| Project | donate | url for donations |  |
| Project | chat | url for project chat |  |
| Project | supporters | an array of supporters sponsoring the project in cash or kind |  |
| Project | has_ci | does the project use a CI env. to automate its build/test/deployment process? |  |
| Repository | branches | array of braches |  | 
| Branch | id | | | 
| Branch | created | | | 
| Branch | last commit | | | 
| Branch | total commits | | | 
| Version | changelog | project changelog |  |
| Version | changelog_updated | last update on changelog |  |
| Version | cves | number of CVEs disclosed for this version |  |
| Version | code_quality | external measure of code quality (i.e. code climate) |  |  
| Version | downloads | # downloads | 
| Version | download_reqests | # download requests (i.e. direct dependencies) |  |
| Version | build_errors | # reported build errors |  |
| Version | test_status | pass/fail (you'd hope always pass) |  |
| Version | citation | link to citation file |  |
| Issue | comments | An array of comments |  |
| Comment | id |   |
| Comment | author | A user |
| Comment | created |  |
| Comment | updated |  |
| Contributor | organisation |  The organisational affiliation of the contributor |  |