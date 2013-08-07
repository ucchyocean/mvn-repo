使い方

下記のように、pom.xmlに repositoryタグとdependencyタグを加えてください。

<pre>
  &lt;repositories&gt;
    &lt;repository&gt;
      &lt;id&gt;ucchy-github&lt;/id&gt;
      &lt;name&gt;ucchy github repository&lt;/name&gt;
      &lt;url&gt;https://raw.github.com/ucchyocean/mvn-repo/master&lt;/url&gt;
    &lt;/repository&gt;
  &lt;/repositories&gt;
</pre>

LunaChatの参照<br />
Vaultとdynmapが間接参照されています。<br />
なお、dynmapはリポジトリがないので、各自ローカルリポジトリへのインストールをお願いします。
<pre>
    &lt;dependency&gt;
      &lt;groupId&gt;com.github.ucchyocean&lt;/groupId&gt;
      &lt;artifactId&gt;LunaChat&lt;/artifactId&gt;
      &lt;version&gt;2.3.2&lt;/version&gt;
    &lt;/dependency&gt;
</pre>

NicoLiveAlertの参照
<pre>
    &lt;dependency&gt;
      &lt;groupId&gt;com.github.ucchyocean&lt;/groupId&gt;
      &lt;artifactId&gt;NicoLiveAlert&lt;/artifactId&gt;
      &lt;version&gt;1.5.0&lt;/version&gt;
    &lt;/dependency&gt;
</pre>
