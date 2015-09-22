---
layout: post
title:  "Docker Repos"
date:   2015-09-22 10:23:52
categories: docker repos open source
---

## Active Projects

These are docker containers we are actively keeping up to date.

### [UKHomeOffice/docker-mediawiki: docker-mediawiki](https://github.com/UKHomeOffice/docker-mediawiki)

This is a dockerised version of Media Wiki.

### [UKHomeOffice/docker-selenium-local-server: Docker Selenium Server in the Background](https://github.com/UKHomeOffice/docker-selenium-local-server)

This docker container extends selenium server container and allows you to run processes which require it locally. This 
is useful for tests that require file uploads, which can only be done locally from the selenium server.

### [UKHomeOffice/docker-jenkins-slave-nodejs: Jenkins Slave Docker Container: NodeJS Build Tools](https://github.com/UKHomeOffice/docker-selenium-local-server)

This container is an Jenkins slave with NodeJS Build Tools. It extends the 
[Jenkins Slave Docker Container][jenkins-slave-container] by adding NodeJS build tools.

### [UKHomeOffice/docker-jenkins-slave-docker1.6: Jenkins Slave Docker Container: Docker 1.6.1](https://github.com/UKHomeOffice/docker-jenkins-slave-docker1.6)

This container is an Jenkins slave with Docker 1.6.1. It extends the 
[Jenkins Slave Docker Container][jenkins-slave-container] by adding Docker 1.6.1.

It will also restore your docker authentication from an encrypted file in a S3 bucket.

### [UKHomeOffice/docker-sonarqube: Docker Sonar Qube](https://github.com/UKHomeOffice/docker-sonarqube)

This is a [Sonar Qube](http://www.sonarqube.org/) Docker container.

### [UKHomeOffice/jenkins-docker-aws: DOCKER JENKINS](https://github.com/UKHomeOffice/jenkins-docker-aws)

Features include:
- Backing up and restoring of config from Amazon S3
- Includes docker, git, awscli
- Includes kubectl and restoration of corresponding config from encrypted file in Amazon S3
- Includes restoration of encrypted config for docker logins from encrypted file in Amazon S3

### [UKHomeOffice/docker-postfix: Postfix in a Service](https://github.com/UKHomeOffice/docker-postfix)
                              
A Postfix container with TLS support

### [UKHomeOffice/docker-mysql: Docker MySQL Container](https://github.com/UKHomeOffice/docker-mysql)

Docker MySQL Container that extends the official home office docker base image.

### [UKHomeOffice/docker-ngx-openresty: OpenResty Docker Container](https://github.com/UKHomeOffice/docker-ngx-openresty)

This container aims to be a generic proxy layer for your web services. It includes OpenResty with Lua and NAXSI filtering compiled in.

It will also pass A UUID as an additional query parameter to the URL

### [UKHomeOffice/docker-nodejs: Node.JS On Build Container](https://github.com/UKHomeOffice/docker-nodejs)

This is an onbuild container for Node.JS Projects.

### [UKHomeOffice/docker-redis: docker-redis](https://github.com/UKHomeOffice/docker-redis)

Docker image for redis. This image is designed to be used with kubernetes, it may work outside kubernetes as well.

### [UKHomeOffice/docker-gitlab](https://github.com/UKHomeOffice/docker-gitlab)

Dockerfile to build a [GitLab](https://about.gitlab.com/) container image.

### [UKHomeOffice/docker-jenkins-slave-openjdk8: Jenkins Slave Docker Container: OpenJDK8 Build Tools](https://github.com/UKHomeOffice/docker-jenkins-slave-openjdk8)

This container is an Jenkins slave with OpenJDK8 Build Tools. It extends the 
[Jenkins Slave Docker Container][jenkins-slave-container] by adding Java build tools.

### [UKHomeOffice/docker-jenkins-slave: Jenkins Slave Docker Container](https://github.com/UKHomeOffice/docker-jenkins-slave)

This container is a basic jenkins slave that contains only the information required to get a jenkins node up an running. The reason behind this image is to give you somewhere to put language specific build tools and dependencies (which may even conflict with differing library version, for example) without having an overly complicated jenkins master.

### [UKHomeOffice/docker-openjdk8-gradle: docker-openjdk8-gradle](https://github.com/UKHomeOffice/docker-openjdk8-gradle)

Builds upon ukhomeoffice/docker-centos-base by adding openjdk8 and running gradlew.

### [UKHomeOffice/docker-dropwizard: Docker Dropwizard](https://github.com/UKHomeOffice/docker-dropwizard)

This is an onbuild container for Dropwizard (using Maven)

### [UKHomeOffice/docker-centos-base: Docker Base Image for the Home Office](https://github.com/UKHomeOffice/docker-centos-base)

This is a base image to ensure that all home office containers are starting from a known state. This allows us to monitor for security problems in only one operating system, rather than 5 or 6. It also gives us a place to insert fixes.

### [UKHomeOffice/docker-jira](https://github.com/UKHomeOffice/docker-jira)

This docker container provides a JIRA installation. As far as possible it's configurable through environment variables. The initialization and setup scripts are largely inspired by the superb gitlab container from sameersbn.

### [UKHomeOffice/docker-oracle-database-express-edition-11g: Oracle Database Express Edition 11g Container](https://github.com/UKHomeOffice/docker-oracle-database-express-edition-11g)

This provides a docker container for Oracle XE 11g.

### [UKHomeOffice/docker-mysql-java: Docker MySQL Java Container](https://github.com/UKHomeOffice/docker-mysql-java)

Docker MySQL Container that also includes Open Java 8 JRE install.

### [UKHomeOffice/docker-openjdk8-jre: docker-openjdk8 JRE Only](https://github.com/UKHomeOffice/docker-openjdk8-jre)

Standard Open JDK 8 built on standard base image.

JRE Only.

### [UKHomeOffice/docker-openjdk8: docker-openjdk8](https://github.com/UKHomeOffice/docker-openjdk8)

Standard Open JDK 8 built on standard base image.

Includes JDK.

### [UKHomeOffice/docker-selenium-standalone-server: Docker: Selenium Server with Firefox and Google Chrome](https://github.com/UKHomeOffice/docker-selenium-standalone-server)

Docker container containing Selenium Server

### [UKHomeOffice/docker-jenkins-slave-ruby: Jenkins Slave Docker Container: Ruby Build Tools](https://github.com/UKHomeOffice/docker-jenkins-slave-ruby)


This container is an Jenkins slave with Ruby Build Tools. It extends the 
[Jenkins Slave Docker Container][jenkins-slave-container] by adding Ruby build tools.

### [UKHomeOffice/docker-mysql-sonarqube: docker-mysql-sonarqube](https://github.com/UKHomeOffice/docker-mysql-sonarqube)

The docker MySQL container plus a single SQL file that creates a sonar db. For use with the sonarqube docker container

### [UKHomeOffice/docker-go-gb: docker-go-gb](https://github.com/UKHomeOffice/docker-go-gb)

For using gb build and fetch for go applications

### [UKHomeOffice/docker-vault: docker-vault](https://github.com/UKHomeOffice/docker-vault)

Dockerised vault server, useful for testing tools that interact with vault

### [UKHomeOffice/docker-mongonodejava8: docker-mongonodejava8](https://github.com/UKHomeOffice/docker-mongonodejava8)

Image that has Sun Java 8, mongodb and node installed.

### [UKHomeOffice/docker-mysql-java-jdk: docker-mysql-java](https://github.com/UKHomeOffice/docker-mysql-java-jdk)

Docker MySQL Container that also includes Open Java 8 *JRE* install.

[jenkins-slave-container]: https://github.com/UKHomeOffice/docker-jenkins-slave "Jenkins Slave Docker Container"

## Retired/Incomplete

### Depreciated

#### UKHomeOffice/docker-aws-drupal

Broken, no plans to fix.

#### UKHomeOffice/docker-gradle

Depreciated in favour of UKHomeOffice/docker-openjdk8-gradle

#### UKHomeOffice/docker-fedora-baseservices

Depreciated in favour of UKHomeOffice/docker-centos-base

### No unclear/documentation
* UKHomeOffice/docker-php-fpm
* UKHomeOffice/docker-gitlab-tools
* UKHomeOffice/docker-nginx-gateway
* UKHomeOffice/docker-crond
* UKHomeOffice/docker_s3registry
* UKHomeOffice/docker-confluence
* UKHomeOffice/docker-logstash-s3