Identity and Access Management (IAM) - Ensures the right access for the right people at the right times  
&nbsp;Identification - Claims a username or email as an identity  
&nbsp;Authentication - Verifies user's identity, device, or system  
&nbsp;Authorization - Establishes the user's access permissions or levels  
&nbsp;Accounting/Auditing - Invloves monitoring and recording user actions for comnpliance and security records  
 	
Identity and Access Management (IAM) - Systems and processes used to manage access to information in an organization to ensure that the right indiciduals have access to the right resouces at the right times for the right reasons  
Provisioning - Process of creating new user accounts, assigning them appropriate permissions, and providing users with access to systems  
Deprovisioning - Process of removing an individual's access rights when the rights are no longer required  
Identity Proofing - Process of verifying the identity of a user before the account is created  
Interoperability - The ability of different systems, devices, and applications to work together and share information  
Attestation - Process of validating that user accounts and access rights are correct and up-to-date  

Multi-Factor Authentication (MFA) - Security system that requires more than one method of authentication from independent categories of credentials to verify the user's identity  
Something you know (Knowledge factor) - Relies on information that a user can recall (passwd)  
Something you have (Posession factor) - Relies on the user presenting a physical item to authenticate themselves (One-time sms code)  
Something you are (Inherence Factor)  - Relies on the user providing a unique physical or behavioural characteristic of the person to validate that they are who they claim to be (biometric)  
Something you do (Action Factor) - Relies on the user conducting a unique action to prove who they are (behavioral analysis)  
Somewhere you are (Location factor) - Relies on the user being in a vertain geographic location before access is granted (Location service and check)  
Passkeys - Users can create and access online accounts without needing to input a password  

Password Security - Measures the password's ability to resist guessing abd brute-force attacks  
Password Managers - Store, generate, and autofill passwords to enhance security  

Dictionary Attack - Using a list (or 'Dictionary') of commonly used passwords and trying them all  
Password Spraying - A form of brute force attack that involves trying a small number of commonly used passwords against a large number of usernames or accounts  
Hybrid Attack - Blends brute force and dictionary techniques by using common passwords with variations such as adding numbers or special characters  

Single Sign-On (SSO) - Authentication process that allows a user to access multiple applications or websites by logging in only once with a single set of credentials  
Identity Provider (IdP) - System that creates, maintains and manages identity information for principals while providing authentication services to relying applications within a federation or distributed network  
Lightweight Directory Access Protocol (LDAP) - Used to access and maintain distriburted directory information services over an Internet protocol network  
Open Authorization (OAuth) - Open standard for token-based authentication and autorization that allows an individual's account information to be used by third-party services without exposing the user's password  
Security Assertion Marup Language (SAML) - A standard for logging users into applications based on their sessions in another context  

Federeation - Process that allows for the linking of electronic identities and attributes to store information across multiple distinct identity management systems  
&nbsp;Login initiation - The user accesses a service or application and chooses to log in  
&nbsp;Redirection to an identity provider - The service provider redirects the user to the Identity Provider for authentication   
&nbsp;Authenticating the user - After a user submits credentials to the Identity Provider, it validates the user's identity   
&nbsp;Generation of an assertion - The IdP creates an assertion that includes information about the user's identity   
&nbsp;Returning to a service provider - The user is redirected back to the service provider with the authentication assertion from the Identity Provider  
&nbsp;Verification and access - The service provider checks the assertion from a trusted IdP and grants access based on its information  
 	
Privileged Access Management (PAM) - Solution that helps organizations restrict and monitor privileged access within an IT environment  
Just-in-time Permissions - Security model where administrative access is granted only when needed for a specific period  
Password Vaulting - Technique used to store and manage passwords in a secure environment, such as in a digital vault  
Temporal Accounts - Used to provide time-limited access to resources, and they are automatically disabled or deleted after a certain period of time  

Mandatory Access Control (MAC) - Employs security labels to authorize user access to specific resources  
Discretionary Access Control (DAC) - Resource's owner determines which users can access each resource  
Role-Based Access Control (RBAC) - Assigns users to roles and uses these roles to grant permissions to resources  
Rule-Based Access Control (RBAC) - Enables administrators to apply security policies to all users  
Attribute-based Access Control (ABAC) - Uses object characteristics for access control decisions  
Permission or Authorization Creep - Occurs when a user gains excessive rights during their career progression in the company  
