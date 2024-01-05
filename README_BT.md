export MAVEN_OPTS="-Xmx2048M -XX:MaxPermSize=1024m" 

java version "11.0.21" 2023-10-17 LTS
Java(TM) SE Runtime Environment 18.9 (build 11.0.21+9-LTS-193)
Java HotSpot(TM) 64-Bit Server VM 18.9 (build 11.0.21+9-LTS-193, mixed mode)


mvn clean install -Dmaven.test.skip=true