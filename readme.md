---


---

<h1 id="simple-navigation-component">Simple Navigation Component</h1>
<p>Di dalam Projek Ini Saya Mencontohkan penerapan android <strong>Android Jetpack Navigation Component</strong></p>
<h1 id="gradle-module">Gradle (Module)</h1>
<p>plugins {</p>
<pre><code>  id 'androidx.navigation.safeargs.kotlin'  																
</code></pre>
<p>}</p>
<p>dependencies {</p>
<pre><code>  implementation "androidx.navigation:navigation-fragment-ktx:2.3.1"  
  implementation "androidx.navigation:navigation-ui-ktx:2.3.1"  
  implementation 'androidx.navigation:navigation-fragment-ktx:2.3.1'  
  implementation 'androidx.navigation:navigation-ui-ktx:2.3.1'
</code></pre>
<p>}</p>
<h1 id="gradle-project">Gradle (Project)</h1>
<p>dependencies {</p>
<pre><code>def nav_version = "2.3.1"  
classpath "androidx.navigation:navigation-safe-args-gradle-plugin:$nav_version"  
</code></pre>
<p>}</p>
<pre><code></code></pre>

