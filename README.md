<h2>Investigation - Defaced</h2>


<h2>Scenario:</h2>

Mike is a young entrepreneur that recently started a pharmaceutical company online that supplies personal health products. As the business is growing at a rapid pace, Mike pressured the developers to create a website as quickly as possible and disregarded time-consuming security measures. Unsurprisingly, after the website went live it was defaced by a threat actor that also stole all the database records. Learning from this incident Mike took down the server and began security testing and investigation. He setup a forwarder to send server logs to a SIEM and used a file integrity monitoring solution to get alerts when files are modified on the server. You are provided with the alerts generated from the file integrity monitoring tool, stored on the Desktop as FIM1.JPG and FIM2.JPG. You also have screenshots of the website homepage before and after the compromise, saved as; Before.JPG and After.JPG.

Access the link that is bookmarked in your browser [Discover - Elastic] to hunt
The root cause of the compromise by analysing logs between Feb 17 to Feb 18, 2021. Alternatively you can paste this URI into the lab’s browser:

http://localhost:5601/app/discover#/?_g=(filters:!(),refreshInterval:(pause:!t,value:0),time:(from:'2021-02-16T10:17:54.500Z',to:now))&_a=(columns:!(_source),filters:!(),index:'350867a0-729c-11eb-9d3d-8583953ebd4a',interval:auto,query:(language:kuery,query:''),sort:!())


<br />

<p align="center">
  
<h2>Questions:</h2>
   
Q1. As an analyst, you need to submit details to the CTI team. What is the signature left by the threat actor that compromised the website? (2 points)
- I go to investigate after.jpg file. At the bottom right hand side me can see the answer.
<img src="https://imgur.com/2HxuPKQ" height="80%" width="80%" alt="after.jpg"/>

Answer: Team ApashKirikiri2.0
<br />
<br />



<h2>Post-Lab lessons learnt</h2>

First ever lab (I have ever shared) DONE. I think learning how to navigate Github, creating a repository as well as learning how to use markdown text was probably the most challenging bit. Windows Anti-virus is definitely a great option to ensure your computer data is safe asssuming its configured properly. Learnt how to update threat definitions and perform a custom scan on a specific folder. Learnt how to accept and block traffic using firewall rules.

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
