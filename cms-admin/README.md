# CMS-DAL
## Introduction

This is a utility internal web app to browse CMS and Activiti data 

## Usage

* Browse all CMS classes
* Search CIs based on NS path, Class , CINAME. 
* Browse activiti instances. 

## Documentation
Coming soon

## Contributing

Refer [Contributing][]. 

## Help

Check out the oneops tags on [Stack Overflow][] or [slack-dev][] 

### Requirements

[Maven][]  and [JDK 8  or later][JDK8 build] 

Be sure that your `JAVA_HOME` environment variable points to the `jdk1.8.0` folder
extracted from the JDK download.
 
The project is dependent on [cms-dal][] . 
 

## Building the Source

* git clone https://github.com/oneops/cms-admin.git
* cd cms-admin 
* mvn clean package 

This will build the war deployable on standard java servlet container like tomcat.

### Configuration

cms-admin war would require environment variables to be passed refer [tomcat environment variables][]  

### Installation
For quick setup refer [setup][] 


## License
The project is released under version 2.0 of the [Apache License](http://www.apache.org/licenses/LICENSE-2.0).



[Maven]: http://maven.apache.org/
[Git]: http://help.github.com/set-up-git-redirect
[JDK8 build]: http://www.oracle.com/technetwork/java/javase/downloads
[Apache License]: http://www.apache.org/licenses/LICENSE-2.0
[Stack Overflow]: http://stackoverflow.com/tags/oneops
[slack-dev]:https://oneops.slack.com/messages/devel/messages
[oo-commons]:../../../oo-commons
[cms-dal]:../../../cmsdal
[Oneops UI]:../../../display
[setup]:../../../setup
[Client]:../../../cli
[Contributing]:https://github.com/oneops/developer-doc/blob/master/_contribution/index.md
[tomcat environment variables]:../../../dev-tools/blob/master/setup-scripts/tom_setenv.sh
