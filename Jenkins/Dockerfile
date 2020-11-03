FROM jenkins/jenkins:lts

ENV JAVA_OPTS "-Djenkins.install.runSetupWizard=false"
# ENV DOCKERVERSION=18.03.1-ce

COPY jenkins.yaml /var/jenkins_home/jenkins.yaml
ENV CASC_JENKINS_CONFIG=/var/jenkins_home/jenkins.yaml

COPY plugins.txt /usr/share/jenkins/ref/plugins.txt
RUN /usr/local/bin/install-plugins.sh < /usr/share/jenkins/ref/plugins.txt