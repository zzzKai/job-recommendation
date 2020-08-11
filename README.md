# Job Recommendation Website

Recommend jobs for you with your location and favorites.

## Prerequisites

* [Apache tomcat 9.0.31](http://tomcat.apache.org/download-90.cgi) - Server
* [Maven](https://maven.apache.org/) - Dependency Management
* [MySQL] - Database

## External

External APIs used to build the project.

### GitHub Job API

[Official Documentation](https://jobs.github.com/api)

GitHub Job API is a web-based API provided by GitHub so that clients can get real jobs data from the GitHub server. Although they do not provide much jobs, it is enough for this website to build, and it is free. With the document we can easily call the API with Java code and many other kinds of language.

### Monkey Learn API

Monkey Learn provides a lot different kinds of NPL APIs, and it is also free for very little usage. For job recommendation we need to extract the key words for the job discription, and that can also be used as labels for the job.<br> 
Monkey Learn is very good, because they provide detail [documentation](https://monkeylearn.com/api/v3/#java) APIs for different langauges.<br>
The API for key word extraction is 300 times for a month. This is enough for testing and demo, but it can not handle load test or large usage.

## Demo
<img src="https://github.com/zzzKai/job-recommendation/demo1.png">
<img src="https://github.com/zzzKai/job-recommendation/demo2.png">
<img src="https://github.com/zzzKai/job-recommendation/demo3.png">
<img src="https://github.com/zzzKai/job-recommendation/demo4.png">
