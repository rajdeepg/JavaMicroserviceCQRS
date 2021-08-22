# JavaMicroserviceCQRS
JavaMicroserviceCQRS

There is a lot of concepts here that we should use:
1) Great use of Lombok that uses the following:
    a) @Data \
    b) @AllArgsConstructor \
    c) @NoArgsConstructor \
    d) @Builder
2) Great use of Maven
    a) Parent POM \
    b) Module POM
3) Great use of docker
    a) Docker Network so all the containers can talk to each other. \
    b) Docker Container for Axon \
    b) Docker Container for MongoDB \
    c) Docker Container for MySQL \
    d) Docker Container for MySQL Tools
4) Axon Framework for all the Eventing and managing all the commands.
    a) TODO: Plan to remove this at some point.
