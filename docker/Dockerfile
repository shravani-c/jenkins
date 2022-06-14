FROM jenkins/jenkins:jdk11

COPY plugins.txt /usr/share/jenkins/plugins.txt
RUN  jenkins-plugin-cli --plugin-file  /usr/share/jenkins/plugins.txt    

USER jenkins
