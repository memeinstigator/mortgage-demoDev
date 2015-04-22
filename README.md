JBoss BPM Suite Mortgage Demo - demo client sources 
==================================================

1. Check our this repository to a directory on a deveveloper workstataion. Or you can check out this project into JBoss Developer Studio using Git plugin and import project as Maven projects.
2. This includes Test cases, web service projects.
3. Run mvn clean install.
4. Deploy the WAR file ws project target director to EAP/standalone/deployments folder to deploy web service used by the mortgage-demoBP project business process.
5. Run java client under client project - java -jar <jar name>. This will invoke business process using KIE REST client.
