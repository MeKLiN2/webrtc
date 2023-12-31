### Description
a java based webrtc signaling&amp;room server of [SkyRTC-client](https://github.com/LingyuCoder/SkyRTC-client)

### Run
git clone [https://github.com/Xcorpio/webrtc.git](https://github.com/Xcorpio/webrtc.git)  
cd webrtc  
mvn tomcat7:run  
see [http://127.1.1.1:8080](http://127.1.1.1:8080)

12-31-2023: fixed build code block in pom.xml
```
<build>
    <plugins>
        <plugin>
            <groupId>org.apache.maven.plugins</groupId>
            <artifactId>maven-compiler-plugin</artifactId>
            <version>3.8.1</version>
            <configuration>
                <source>1.8</source>
                <target>1.8</target>
            </configuration>
        </plugin>
    </plugins>
</build>
```
