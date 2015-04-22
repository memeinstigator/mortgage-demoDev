JBoss BPM Suite Mortgage Demo - demo client sources 
==================================================


Quickstart
----------

1. Run `mvn clean install` here to build the war, client jar in the generated target directory.
2. Deploy WAR file created from WS project into <EAP_HOME>/standalone/deployments to deploy web service called by the business process in mortgage-demoBP project
3. Run client

   ```
   You can pre-load the BPM Suite Mortgage project with multiple pre-configured process instances, some will run through the rejected path, some will be waiting for you in the various human task when you login. To inject these pre-configured requests just run the client jar from a command line shell. You can run the following command from the 'support' directory:

   java -jar mortgage-demo-client.jar <userid> <password>
   ```

