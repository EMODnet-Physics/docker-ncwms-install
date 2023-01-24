# CHANGE TO docker-compose.yaml

 open docker-compose.yaml and make the following changes:

---

change the value of the environment variable **ncwmspassword** from "customncwmspassword" to the password you want to use for the ncWMS service

---

change the path on the line: 

\- source: C:\ETT\github\docker-ncwms-install\deployfiles\entrypoints\ncWMS_entrypoint.sh

to the actual folder where you have deployed the ncWMS_entrypoint.sh file

---

change the path on the line: 

\- source: C:\ETT\github\docker-ncwms-install\deployfiles\configs\ncWMS.xml

to the actual folder where you have deployed the ncWMS.xml file 

---

change the path on the line: 

\- source: C:\ETT\github\docker-ncwms-install\volumes\ncwmsData

to a folder where you want to store ncWMS configuration files


---

change the port on the line:

\- published: 12083

to the port you want to use for the ncWMS service


 


