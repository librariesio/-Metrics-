## Code
* What scale is this project? - Looking at things like novel LoC, #dependencies and LoC in dependencies perhaps. 
*  How many dependencies are included (inc. transisitve dependencies) - Simple count of dependencies vs. transisitvie dependencies (as we do now) 
* Are dependencies 'pinned' or open?
* Does the project have any implicit dependencies (i.e. 'Elastic is expected to be running on port X') - This one is going to be very difficult, requiring some readme/documentation scanning 
* Does the project have tests?
* Are those tests passing? - Some integration with CI provider perhaps?
* What's the test coverage like? Is it improving? - using external code checking tool for instance
*  Does the project use a CI process or tool? - Detecting configuration file and/or badged in readme.md files
* Is the code linted? Does it have many warnings?
* Is the code readable? Does the project use standard code style? Does it follow it?  - Check for code style in readme.md, contributing.md or styleguide.md or simialr. Apply a standard, external provider scroe like code climate.
* Is the project 'performant'? Does it include any performance tests?

## Documentation
* Is the code documented?
* What's the code comment coverage like? Is it improving?
* Is there a readme?
* IS there a wiki?
* Is there a website?
* Is there a installation document?
* Is there an architectural diagram or other 'architecture-type docuemnt?'
* Are these documents up to date?

## Security
* Does the project have any open CVEs listed against it directly?
* Does the project have any open CVEs listed in its dependency tree?
* How quickly are CVEs patched?
* How quickly are dependency updates patched?
* Does the project execute any code?
* What priv's does the project require?
* Does the project communicate with any external service?
* Does the porject whitelist or blacklist those services?
* Does the project communicate using secure connections?
* Does the project cleanse and validate all inputs form external sources?
* Does the project show any evidence of a security review (attacker model, risk assesment, thread/library safe checks etc)?

## Distribution
* Is the project distributed via a package manager?
* Has the project been *removed* from its package manager?
* Does that package manager have adequate measures to protect users of that distribution?
* Does the distibution include a link to source? 
Is that source validated as the correct source for this project?
* Does the project use semantic versioning?
* Is there a regualr release cycle?
* Has that cycle become longer or shorter?
* Has there been a release in the last 3/6/12 months?
* Is there a changelog? Is it updated? 
* What size is the diff of releases relative to the size of the project? i.e. how consistent is the project in its evolution
* Are releases freuently breaking or non-breaking changes?

## Community

### Contributors
* Are there many or few? 
* How many are there relative to the number of 'users' of this project? 
* Are they likely to be over-stretched or can they cover that demand? 
* What kind of redundancy is built into the community's structure? 
* How many contributors are there with a commit bit?
* How many contributors are permitted to distribute a new patch or release?
* Is the contirbutor 

### Contributions
* How many contributors are actively working on the project versus the number of contributors over time?
* How distributed is the workload (i.e. are there 1-2 people contributing 80-90% of the work?)
* What proportion of contributions are code versus documentation, new issues, comments or PRs?
* Are the number of issues being managed effectively? Are they increaseing, decreasing or staying the same?
* What proportion of contributions are accepted within the exsting community versus outside?
* What's the proportion of issues that are new, old and 'legacy'?
* What's the average time to close an issue? Or accept a PR?

### Principles and practices
* Does the project have good guidance for contributors (code of conduct, readme.md, issue and PR templates)
* Is there good guidance for getting a local instance up and running? A vagrant install? Test fextures etc?
* Does the project have good guidance for contributing? (issue labels, code style, architecture, strategy, key features, decisions)
* Does the project manage and distribute its knowledge well (project website, wiki, FAQ, stackexchange)
* Are issues labelled, is there guidance on how to label?
* Are these documents maintained?
* Is deployment, testing, documentation, reviewing etc. automated?

### Academic
* Is there a citations file? 

### Ecosystem
* Which projects would be at risk if certain factors changed? (orgs removing support, maintianers leaving, project yanked)
* Can we use graph theory to create a stronger open source ecosystem, so that changes to not avalance. 

### Support 
* What's the turnover of support requests to answers like on sites like stack exchange? 
* Are support responses from a wide or narrow group? 
* Does the project have a readme.md, a installing.md or other installation document?
* Is that/are those documents maintained? 

### FAILS
* Data flow dependency
* Static analysis 
* Implicit dependencies 
* Process/data/workflow dependencies/complements