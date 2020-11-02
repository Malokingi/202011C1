## 202011C1
# Challenge 1

### Build a Jenkins CI/CD pipeline for a Dockerized Spring/Node/DotNet microservice on a Kubernetes environment on AWS using Jenkins.

I make a Jenkins Folder and `cd` into it and use these to populate it:
```curl https://raw.githubusercontent.com/revaturelabs/Auto-CI-Server/master/Jenkins/Dockerfile -o Dockerfile```
```curl https://raw.githubusercontent.com/revaturelabs/Auto-CI-Server/master/Jenkins/plugins.txt -o plugins.txt```
```curl https://raw.githubusercontent.com/200803-java-devops/mwg-JeKuDo/master/jenkins.yaml -o jenkins.yaml```

I go back to my root folder and run this:
```curl https://raw.githubusercontent.com/Malokingi/sample-spring-boot/main/kubernetes.yml -o k8s.yml```

### Set up your cloud infrastructure using `awscli`, register a GitHub hook to trigger a Jenkins build, and validate code quality with SonarCloud before publishing a Docker image to DockerHub.

### Use `kubectl` to deploy the image to both a testing and staging environment. Report build, test, and deployment results via Slack/Discord or email message.


## Features
- [ ] GitHub repository for all pipeline scripts
- [ ] Documentation on setting up AWS infrastructure with `awscli`
- [ ] Dockerfiles, Jenkinsfile, and Kubernetes deployments
- [ ] SonarCloud style, code smells, and bug analysis
- [ ] Tagged Docker images published to DockerHub
- [ ] Continuous Delivery with `kubectl`
- [ ] Build, Test, and Staging servers on Kubernetes pods
- [ ] Reports vis Slack/Discord or email

## Tech Stack
- [ ] GitHub
- [ ] Jenkins
- [ ] Docker
- [ ] AWS EKS
- [ ] Kubernetes
- [ ] Slack/Discord/Email

## Presentation
- [ ] 5 minute live demonstration
- [ ] 5 minute questions & answers