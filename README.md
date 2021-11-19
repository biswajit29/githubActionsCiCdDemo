# github Actions CICD Demo
This project is used to show a demo fo the Github actions for a CICD pipeline with a Java app that is getting built and deployed to docker hub


##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t java-app .
    
##### push image to repo 

    docker tag java-app demo-app:java-1.0