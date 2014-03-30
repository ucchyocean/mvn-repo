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

LunaChatの参照。Vaultとdynmapが間接参照されています。
<pre>
    &lt;dependency&gt;
      &lt;groupId&gt;com.github.ucchyocean&lt;/groupId&gt;
      &lt;artifactId&gt;LunaChat&lt;/artifactId&gt;
      &lt;version&gt;2.5.12&lt;/version&gt;
    &lt;/dependency&gt;
</pre>

NicoLiveAlertの参照
<pre>
    &lt;dependency&gt;
      &lt;groupId&gt;com.github.ucchyocean&lt;/groupId&gt;
      &lt;artifactId&gt;NicoLiveAlert&lt;/artifactId&gt;
      &lt;version&gt;2.0.1pre&lt;/version&gt;
    &lt;/dependency&gt;
</pre>

ColorTeamingの参照
<pre>
    &lt;dependency&gt;
      &lt;groupId&gt;com.github.ucchyocean&lt;/groupId&gt;
      &lt;artifactId&gt;ColorTeaming&lt;/artifactId&gt;
      &lt;version&gt;2.3.3&lt;/version&gt;
    &lt;/dependency&gt;
</pre>

ExpTimerの参照。ColorTeamingが間接参照されています。
<pre>
    &lt;dependency&gt;
      &lt;groupId&gt;com.github.ucchyocean&lt;/groupId&gt;
      &lt;artifactId&gt;ExpTimer&lt;/artifactId&gt;
      &lt;version&gt;2.3.0&lt;/version&gt;
    &lt;/dependency&gt;
</pre>

BattlePointsの参照。VaultとColorTeamingが間接参照されています。
<pre>
    &lt;dependency&gt;
      &lt;groupId&gt;com.github.ucchyocean&lt;/groupId&gt;
      &lt;artifactId&gt;BattlePoints&lt;/artifactId&gt;
      &lt;version&gt;3.2.1&lt;/version&gt;
    &lt;/dependency&gt;
</pre>
