# About this Repo

This is a forked Docker image from the official Docker image for [SonarQube](https://registry.hub.docker.com/_/sonarqube/). See the Hub page for the full readme on how to use the Docker image and for information regarding contributing and issues.

The full readme is generated over in [docker-library/docs](https://github.com/docker-library/docs), specifically in [docker-library/docs/sonarqube](https://github.com/docker-library/docs/tree/master/sonarqube).

The only difference from original one is I put volumn on `$SONARQUBE_HOME/conf` for put customized `sonar.properties` for your needs, for example, connect to your LDAP service.
