# Firestore-SecurityRules
<i/>Google Cloud Firestore Security Rules for #### project</i>

The requirements for Database access were provided as follows: 

<b/>Users</b>
  - User: Read instance
  - Manager: ReadWrite instance
  - Admin: ReadWrite all
  
<b/>Settings</b>
  - User/Manager/Admin: Read all
  
<b/>Settings/default/**</b>
  - User/Manager: Read all
  - Admin: ReadWrite all
  
<b/>Instances</b>
  - User/Manager: Read instance
  - Admin: ReadWrite all

<b/>Instances/{instanceId}/companies</b>
  - User: Read instance
  - Manager: ReadWrite instance
  - Admin: ReadWrite all
  
<b/>Instances/{instanceId}/controls</b>
  - User/Manager: ReadWrite instance
  - Admin: ReadWrite all

<b/>Instances/{instanceId}/risks</b>
  - User: Read instance, Write personal
  - Manager: ReadWrite instance
  - Admin: ReadWrite all
  
<b/>Instances/{instanceId}/**</b>
  - User/Manager: Read instance
  - Admin: ReadWrite all
