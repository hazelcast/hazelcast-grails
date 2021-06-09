***
> :warning: **REMARK:**
>
> Dear community members,
>
> Thanks for your interest in **hazelcast-grails**! This project has become a Hazelcast Community project.
>
> Hazelcast Inc. gives this project to the developers community in the hope you can benefit from it. It comes without any maintenance guarantee by the original developers but their goodwill (and time!). We encourage you to use this project however you see fit, including any type of contribution in the form of a pull request or an issue.
> 
> Feel free to visit our Slack Community for any help and feedback.
***

# Hazelcast plugin for grails

Update (4/2016): Hazelcast version is upgraded to 3.6.2.

### How to Install Plugin

Just add the following dependency under the dependencies block in your project's build.gradle:

> compile "org.grails.plugins:hazelgrails:1.0.2"

### Configuration

You can configure hazelcast in details:


For available options have a look at:
[http://docs.hazelcast.org/docs/3.6/manual/html-single/index.html#hazelcast-configuration](http://docs.hazelcast.org/docs/3.6/manual/html-single/index.html#hazelcast-configuration)


To use Hazelcast as Hibernate 2nd Level Cache, add the following line to application.groovy:

cache.region.factory_class = 'com.hazelcast.hibernate.HazelcastCacheRegionFactory'

### For more documentation:
See:
[http://blog.hazelcast.com/distribute-grails-with-hazelcast/](http://blog.hazelcast.com/distribute-grails-with-hazelcast/)

### For Grails3 Test application:
See:
[https://github.com/rohitbishnoi/hazelcast-test] (https://github.com/rohitbishnoi/hazelcast-test)
