<h3>AD Components</h3>

- Physical Components 
1. Domain Controller 
    - Authenticates all the users in the network
    - Env can have multiple domain controllers -> DC will replicate data to all DCs

2. AD DS (Data Store)
    - Contains the database files
    - Consists of Ntds.dit file -> File containing senstive data including information about user objects, groups, and group membership. It includes the password hashes for all users in the domain.
    - Is stored by default in the %SystemRoot%\NTDS folder on all domain controllers
    - Is accessible only through the domain controller processes and protocols
