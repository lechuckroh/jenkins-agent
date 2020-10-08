# jenkins-agent

Custom jenkins agent docker images with `docker` installed.

## Tags

| Directory |          Base Image          |                      Tag                       |
| :-------: | :--------------------------: | :--------------------------------------------: |
|  `jdk8`   | `jenkins/agent:latest`       | `lechuckroh/jenkins-agent-docker:latest-jdk8`  |
|  `jdk11`  | `jenkins/agent:latest-jdk11` | `lechuckroh/jenkins-agent-docker:latest-jdk11` |


### Caveat

* default user is `root`, not `jenkins`
  