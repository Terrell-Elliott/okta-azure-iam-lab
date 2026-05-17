# Okta + Azure AD IAM Lab


 **Author:** Terrell Elliott 
 **Status:** In Progress 

 ## What this project is 
 This is a hands on identity and access managment lab demostrating automated user lifcycle management using Okta as the identity provider and Azure AD (Entra ID) as the target directory, connected via SCIM 2.0 provisioning with SAML SSO. 

 ## What problem it solves 
 In enterprises, manually creating and removing user accounts
across systems is slow and error prone. This lab automates
that process when a user is added to a group in Okta, they
are automatically provisioned in Azure AD. When deactivated,
access is removed across both systems instantly.

## Architecture


## Technologies used
- Okta Developer (Identity Provider)
- Microsoft Azure AD / Entra ID (Target Directory)
- SCIM 2.0 (Provisioning protocol)
- SAML 2.0 (Single Sign-On)



## What I built
- [ ] Okta org with group-based RBAC
- [ ] SCIM 2.0 provisioning to Azure AD
- [ ] Full lifecycle test (provision, update, deprovision)
- [ ] SAML SSO for test application
- [ ] Access control policy documentation


## Key concepts demonstrated
- Identity lifecycle management
- Group-based access control (RBAC)
- Attribute-based access control (ABAC)
- Federated authentication (SAML)
- Zero Trust access principles


## Lessons learned
