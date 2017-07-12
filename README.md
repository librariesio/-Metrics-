# Metrics
This repo aims to gather a diverse group of organisations, institutions and individuals to explore how best to measure, classify and otherwise infer infromation from software ecosystems and projects. 

## Goals
* To define a set of useful direct and derivative measures for judging aspects of a project within a number of thematic areas (i.e. code quality, community, documentation).
* To signpost toward sources of data. 
* To define a set of metrics that are missing from Libraries.io that are not provided by another service.

## Process

### [Related work](https://github.com/librariesio/metrics/blob/master/signpost.md)
A place to refrence the significant works of others tackling these issues in industry, academia or as individuals.

### [Questions](https://github.com/librariesio/metrics/blob/master/questions.md)
For me this process begins with a number of framing questions. These questions are user-centred and based on the needs of our users, as defined in our [personas](https://docs.libraries.io/personas.html) from there we can define measures and metrics. 

### [Measures](https://github.com/librariesio/metrics/blob/master/measures.md)
Measures can be direct (a quoted metric i.e. 'released on 1st Jan 2017), derivative (information gleaned from data i.e. 'released more than a year ago') or aggregated (compiled from >1 data i.e. 'all releases we're within the last year'). 

Measures may be broken down into a number of areas. At Libraries.io we have been considering areas for code, community, distribution and documentation. The single, overarching measure in Libraries.io is SourceRank which is defined over [in our documentation](https://docs.libraries.io/overview#sourcerank). 

### [Data](https://github.com/librariesio/metrics/blob/master/data.md)
Data can be 'harvested' (gathered automatically using APIs, data dumps, scraping etc) or 'farmed' (gathered from a community by contribution).

Libraries.io currently focusses on harvesting metrics. It is preferable for a metric to be present in many sources rather than a single source so that we can make like-for-like comparisons across [supported package managers](http://libraries.io/compatibility). 

### [Sources](https://github.com/librariesio/metrics/blob/master/signpost.md#sources)
Sources contain metrics. They may also contain measures themselves.  We think it is important not to rely on proprietary, third party services for measures. 

Reproducibility is the key issue here. An inability to reproduce a measure from the source data (metrics) risks the ability to create a like for like comparison of two pieces of software and ties all users of the classifier to that service. This is [unacceptable](https://www.youtube.com/watch?v=07So_lJQyqw)(🔊).
 
## Contributing 
While there will be no one single approach that is right for everyone our hope is that we can come to consensus about what good measures look like and what metrics they will require, so that Libraries.io can provide them. 

Please feel free to fork and PR additions to any of the documents in this repo, to share your thoughts and ideas in an issue, to propose a draft specifications for areas, measures etc. as a PR or reference. 