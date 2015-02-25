# LDAP to Confluence
Scriptella Script

Gets users from the University LDAP and adds/edits them in Confluence.

*Adds if the user is new
*Edits if the user exists

Edits: displayName (full name) and mail (email)

##### Requirements
Add the confluence-soap jar file to your classpath. In my case, I added it to my ```<scriptella directory>/lib``` directory.
