<h1>Jmeter-HA Project</h1>

One of the problems, that may occur in huge website is load balacing problem.<br> This errros may occur in bigger environment.
So in the <b>I</b>nformation <b>T</b>echnology world there is a free open source tool.<br>
Named <b>Apache Jmeter</b>, citing from their website: <br>"<i>100% pure Java application designed to load test functional behavior and measure performance.<br> 
It was originally designed for testing Web Applications but has since expanded to other test functions.</i>"<br>

<h3>Initial Requirements:</h3>
<ul>
<li>Master PC (In my case: Centos)<br></li>
<li>Two Slaves PC (In my case: 2 Centos)<br></li>
<li>Apache Jmeter (In my case: Jmeter 3.2v)<br></li>
<li>Gitlab Repositories<br></li>
<li>Jenkins on all machines<br></li>
</ul>

<h4>Instalation Steps:</h4>
<ol>
<li>Installation of Jenkins on all PCS</li>
    <ol>
    <li> <a href="https://jenkins.io/download/">Download Jenkins</a> (In my case it was jenkins-2.7.4-1.1.noarch.rpm)</li>
    <li> 1-Install on Master</li>

    </ol>

  `` Sudo rpm -Uvh jenkins-2.7.4-1.1.noarch.rpm 
`` 
</ol>
