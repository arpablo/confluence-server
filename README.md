# confluence-server
This image contains a Docker File for Atlassian Confluence Server using ORACLE JVM

# How to use this image
This image runs the Atlassian Confluence Server. To use it in a prodcution environment you have to
have a database set up and connected to this image.

## Start image using docker command 
To start the latest version of the server use the following command:
```console
$docker run -v ~/confluence:/var/atlassian/application-data/confluence --name="confluence" -d -p 8090:8090 -p 8091:8091 arpablo/confluence-server
```
