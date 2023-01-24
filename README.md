# CHANGE TO docker-compose.yaml

 open docker-compose.yaml and make the following changes:

---

change the value of the environment variable **ncwmspassword** from "customncwmspassword" to the password you want to use for the ncWMS service

---

change the path on the line: 

<pre>- source: C:\ETT\github\docker-ncwms-install\deployfiles\entrypoints\ncWMS_entrypoint.sh</pre>

to the actual folder where you have deployed the ncWMS_entrypoint.sh file

---

change the path on the line: 

<pre>- source: C:\ETT\github\docker-ncwms-install\deployfiles\configs\ncWMS.xml</pre>

to the actual folder where you have deployed the ncWMS.xml file 

---

change the path on the line: 

<pre>- source: C:\ETT\github\docker-ncwms-install\volumes\ncwmsData</pre>

to a folder where you want to store ncWMS configuration files

---

change the port on the line:

<pre>- published: 12083</pre>

to the port you want to use for the ncWMS service


# HOW TO RUN

execute the command

<code>docker-compose up -d </code>

on the folder where you have deployed the docker-compose.yaml file
 


