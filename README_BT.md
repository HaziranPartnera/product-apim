export MAVEN_OPTS="-Xmx2048M -XX:MaxPermSize=1024m" 
export JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk-11.jdk/Contents/Home/
java -version

java version "11.0.21" 2023-10-17 LTS
Java(TM) SE Runtime Environment 18.9 (build 11.0.21+9-LTS-193)
Java HotSpot(TM) 64-Bit Server VM 18.9 (build 11.0.21+9-LTS-193, mixed mode)

nohup mvn clean install & 

mvn clean install -Dmaven.test.skip=true

cd modules/distribution/product/target
zip wso2am-4.2.0-SNAPSHOT.zip --out Split-wso2am-4.2.0-SNAPSHOT.zip -s 50m