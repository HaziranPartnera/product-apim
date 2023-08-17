https://github.com/wso2/product-apim/issues/11674


mvn install:install-file \
-Dfile=<path-to-file> \
-DgroupId=<group-id> \
-DartifactId=<artifact-id> \
-Dversion=<version> \
-Dpackaging=<packaging> \
-DgeneratePom=true


mvn org.wso2.carbon.am.integration.test:4.2.0-SNAPSHOT:install-file  \
-Dfile=/Users/bulenttokuzlu/Documents/PartneraCloud/product-apim/org.wso2.carbon.am.integration.benchmark.test-4.2.0.jar \
-DgroupId=org.wso2.am -DartifactId=org.wso2.carbon.am.integration.test \
-Dversion=4.2.0-SNAPSHOT -Dpackaging=jar 

-DlocalRepositoryPath=${master_project}/local-maven-repo

    <parent>
        <artifactId>org.wso2.carbon.am.integration.test</artifactId>
        <groupId>org.wso2.am</groupId>
        <version>4.2.0-SNAPSHOT</version>
        <relativePath>../pom.xml</relativePath>
    </parent>
