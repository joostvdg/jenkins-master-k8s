# jenkins-master-k8s

[![GitHub release](https://img.shields.io/github/release/joostvdg/jenkins-master-k8s.svg)]()
[![license](https://img.shields.io/github/license/joostvdg/jenkins-master-k8s.svg)]()
[![Docker Pulls](https://img.shields.io/docker/pulls/caladreas/jenkins-master-k8s.svg)]()
[![](https://images.microbadger.com/badges/image/caladreas/jenkins-master-k8s.svg)](https://microbadger.com/images/caladreas/jenkins-master-k8s "Get your own image badge on microbadger.com")

Jenkins Master in Docker for K8s.

Has all the basic plugin for Docker, Jenkins Pipeline, BlueOcean and those related to Kubernetes.

## Build

```bash
docker build --tag jks-m-k8s .
```

## Run as container

```bash
docker run -p 8088:8080 --name jks jks-m-k8s
```

Then open [localhost:8088/jenkins](http://localhost:8088/jenkins).

You can login with ```admin```:```admin```.

## Deploy in K8s

T.B.D.


<a href='https://ko-fi.com/W7W29DSZ' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://az743702.vo.msecnd.net/cdn/kofi2.png?v=0' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>