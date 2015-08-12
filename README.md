# docker-tomcat
Tomcat instance for running web applications in the Deloitte VA systems

## Usage instructions
* For usage as a dependency, add <pre>FROM deloitteva/docker-tomcat:version</pre>, replacing the word "version" with the version that you would like to use.  For a list of possible versions, please check out the [versions on DockerHub](https://registry.hub.docker.com/u/deloitteva/docker-tomcat/tags/manage/)
* For execution instructions, please visit [DockerHub](https://registry.hub.docker.com/u/deloitteva/docker-tomcat/)

## Release instructions
* Create a branch of the version that matches the tomcat version you are attempting to release.  This would be something like "8.0.23".  
* Go to [DockerHub](https://hub.docker.com/r/deloitteva/docker-tomcat/) and add an automated build for this new branch/version.
* Once it has completed building, it should be available for use.
