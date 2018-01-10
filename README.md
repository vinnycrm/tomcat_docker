Tomcat Dockerfile
==================

Based on OpenJdk 9 Tomcat Dockerfile...

This repo contains a recipe for making Docker container for Tomcat on OpenJdk.

Setup
-----

Check your Docker version

    # docker version

Perform the build

    # docker build --rm --tag <yourname>/tomcat .

Check the image out.

    # docker images

Launching Tomcat
-----------------

### Recommended start ###

To run the tomcat docker here is run command

    # docker run --name=tomcat -d -p 8080:8080 <yourname>/tomcat