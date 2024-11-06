# Jakarta EE 10 Essentials Web Profile Archetype

This archetype allows you to create a Jakarta EE project 
with the least amount of dependencies and plugins. Includes:

- `web.xml`
- `microprofile-config.properties` (Microprofile Example) 
- `persistence.xml`

```shell
mvn -DarchetypeGroupId=com.apuntesdejava \
    -DarchetypeArtifactId=jakarta-ee-10-essentials-web-profile \
    org.apache.maven.plugins:maven-archetype-plugin:generate 
```