This is a sample to see how the Dockerfile creates a server to run Java App base on Ubuntu OS and create a JVM & JDK 11 (openJDK 11)

1. Dockerfile-server => create a repository docker. It's use to create a server build on Ubuntu OS and JVM 11
2. Dockerfile-app => use a repository docker which created by Dockerfile-server and add config SpringMVC war file to tomcat
3. springmvc-docker.war => java project
