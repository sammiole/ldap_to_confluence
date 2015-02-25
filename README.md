# LDAP to Confluence

###Scriptella Script

This script gets users from the University LDAP and either:

* Adds them if the user is new, or
* Edits them if the user exists

in the Atlassian Confluence users base. 

Currently the script edits: displayName (full name) and mail (email)

#### Getting Started

1. Add the confluence-soap jar file to your classpath. In my case, the jar file was added to the ```<scriptella directory>/lib``` directory.

2. Edit the LDAP properties file 

3. Replace "username" and "password" in the script with your confluence credentials 

4. Edit the LDAP query 

5. Use terminal / command line to navigate to the directory storing the script and properties file

6. Run ``scriptella ldap_to_confluence.etl.xml``