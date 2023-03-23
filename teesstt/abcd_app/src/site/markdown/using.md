# Using

This component is available via maven.  Include in your pom.xml file the following :-

```
    <project>
        ...
        <dependencies>
            <dependency>
                <groupId>com.example</groupId>
                <artifactId>abcd_app</artifactId>
                <type>application-archive</type>
            </dependency>
            ...
        </dependencies>
        ...
        <dependencyManagement>
            <dependencies>
                <dependency>
                     <groupId>com.example</groupId>
                     <artifactId>abcd_app</artifactId>
                     <version>0.0.1-SNAPSHOT</version>
                 </dependency>
                 ...
             </dependencies>
        </dependencyManagement>
        ...
    </project>
```
