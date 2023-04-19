# PI16_DependencyCheck
mvn dependency:resolve-plugins dependency:resolve dependency:sources dependency:resolve -Dclassifier=javadoc
~/Downloads/apache-maven-3.9.1/bin/mvn dependency:resolve-plugins > spring-boot-3.0.5-plugins.txt
~/Downloads/apache-maven-3.9.1/bin/mvn dependency:resolve >  spring-boot-3.0.5-deps.txt
~/Downloads/apache-maven-3.9.1/bin/mvn dependency:resolve -Dclassifier=sources  > spring-boot-3.0.5-src.txt
~/Downloads/apache-maven-3.9.1/bin/mvn dependency:resolve -Dclassifier=javadoc > spring-boot-3.0.5-doc.txt
