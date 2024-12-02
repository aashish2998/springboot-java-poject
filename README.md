To run the cmd  : java -jar target/spring-boot-web.jar 

#But before that please perform  do these steps :
- sudo apt-get update -y
- sudo apt install openjdk-11-jre -y
- sudo apt-get install maven -y

#To check if java and maven are installed :
- java --version  and mvn --version

# git clone this repository 
- cd springboot-java-poject
  
# Steps for maven automation
- mvn validate
- mvn compile
- mvn test
- mvn package
- mvn install
- mvn deploy
- mvn clean ->  to clean the target repo created

# After the mvn install cmd 
-( inside target folder spring-boot-wen.jar is installed in .m2 local repository(all the plugin and dependencies are installed in it)  




