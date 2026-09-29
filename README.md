##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t java-deployment .
    
##### push image to repo 

    docker tag java-deployment demo-app:java-1.0
    
