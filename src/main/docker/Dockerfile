FROM eclipse-temurin:17-jre

LABEL maintainer="michael.theis@msg.group"
LABEL ${project.groupId}.${project.artifactId}.project="CloudTrain"
LABEL ${project.groupId}.${project.artifactId}.version="${project.version}"
LABEL ${project.groupId}.${project.artifactId}.description="${project.description}"

COPY *.crt /usr/local/share/ca-certificates/

RUN echo "Update packages, install required packages and update trust store" && \
    apt-get update && \
    apt-get install --yes --no-install-recommends ca-certificates && \
    apt-get clean && \
    update-ca-certificates



