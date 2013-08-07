使い方

下記のように、pom.xmlに repositoryタグとdependencyタグを加えてください。

<pre>
  <repositories>
    <repository>
      <id>ucchy-github</id>
      <name>ucchy github repository</name>
      <url>https://raw.github.com/ucchyocean/mvn-repo/master</url>
    </repository>
  </repositories>
</pre>

LunaChatの参照
<pre>
    <dependency>
      <groupId>com.github.ucchyocean</groupId>
      <artifactId>LunaChat</artifactId>
      <version>2.3.1</version>
    </dependency>
</pre>

NicoLiveAlertの参照
<pre>
    <dependency>
      <groupId>com.github.ucchyocean</groupId>
      <artifactId>NicoLiveAlert</artifactId>
      <version>1.5.0</version>
    </dependency>
</pre>
