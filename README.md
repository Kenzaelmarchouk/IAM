# IAM (Identity Access Management)
This repository contains a brief base of IAM (Identity and Access managment) with a simple practical example to handle IAM.
# Table of content
[Identity](##Identity management?)
## Identity?

Set of attributes that distinguish an entity (individual unit)

![IAM-Page-2](https://github.com/Kenzaelmarchouk/IAM/assets/122173924/a52a5efa-9a01-43fd-8551-ca2457b500b9)
## Identity management?
Deals with creating, maintaining, and deleting an identity.

## Acess management?

Control access to a protected resource by managing authentication and authorization.

## Authentication?
- The verification of an identity to access the system.
- Common methods to ensure authentification: passwords, biometrics, tokens, and MFA
## Authorization?
What an authenticated user is allowed to do.
## What is IAM?
IAM is a combination of processes, policies, and technologies that manage digital identities and control access to an organization's resources. In simplly, it determines **who** can access **what** in a system and ensures that they have **the appropriate permissions** based on their **roles**.

# Example of opensource IAM tools:

* [Keycloak](https://www.keycloak.org/)
* [LemonLDAP-NG](https://lemonldap-ng.org/)
* [FreeIPA](https://www.freeipa.org/)
* [IdentityServer4](https://identityserver4.readthedocs.io/en/latest/)
* [shibboleth](https://www.shibboleth.net/)
* [WSO2 Identity Server](https://wso2.com/)
  
![opensource](https://github.com/Kenzaelmarchouk/IAM/assets/122173924/4ed259fc-a36a-48f5-965b-0650adb01888)

# Practical examples
1. Deploy Keycloak using Docker compose
   - [Medium article](https://medium.com/@kenzamarchouk/deploying-keycloak-with-docker-38fe36f34b95)
   - [GitHub repository](https://github.com/Kenzaelmarchouk/Keycloak)
3. Keycloak Authentication in Node.js Express: User Management and Access Control
   - [Medium article Part1](https://medium.com/@kenzamarchouk/keycloak-authentication-in-node-js-express-user-management-and-access-control-part1-0c3370c75838)
   - [Medium article Part2](https://medium.com/@kenzamarchouk/keycloak-authentication-in-node-js-express-user-management-and-access-control-part2-e7d1dc6391f9)
   - [Medium article Part3](https://medium.com/@kenzamarchouk/keycloak-authentication-in-node-js-express-user-management-and-access-control-part3-950b6aad1353)
   - [Github repository](https://github.com/Kenzaelmarchouk/KeycloakApp)
