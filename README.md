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

<h5>1-Installation of Jenkins on all PCS: <a href="https://github.com/kaido89/Jmeter-HA/wiki/2.-Installation-Jenkins">Link</a></h5>

<h5>2-Installation of Gitlab on one of the PCS (In my case: on Slave 2 Centos): <a href="https://github.com/kaido89/Jmeter-HA/wiki/3.-Installation-Gitlab">Link</a><br></h5>
<h5>3-Installation of Jmeter on all PCS <a href="https://github.com/kaido89/Jmeter-HA/wiki/4.-Install-Jmeter">Link</a></h5>
<h5>4-Configure the Network <a href="https://github.com/kaido89/Jmeter-HA/wiki/5.-Configure-the-Network">Link</a></h5>
