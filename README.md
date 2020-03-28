Dropwizard Helloworld Example
-
To run application, you must have installed java and gradle
1. git clone https://github.com/lf-kiranpariyar/dropwizard-helloworld.git
2. cd dropwizard-helloworld
3. ./gradlew shadowJar
4. java -jar build/libs/dropwizard-helloworld-1.0-SNAPSHOT-all.jar server hello-world.yml
5. goto the browser and request http://localhost:8080/hello-world?name=yourname

    - {"id":1,"content":"Hello, yourname!"} 