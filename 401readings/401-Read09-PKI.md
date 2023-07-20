# Public Key Infrastructure (PKI)
From: [What is Public Key Infrastructure (PKI)](https://www.ssh.com/academy/pki) (accessed by Benjamin Hobbs on 7/15/2023)

## What is PKI?
* Public Key Infrastructure (PKI) is a technology for authentication for users and devices. 

    * Basic Idea:
      * A trusted party digitally signs a "document" to certify that a certain 
      cryptological key (used for access) belongs to a particular user or device.
      * The key (with the signed document) can then be used as an identity for the user on a digital network 
      * The purpose of PKI is to securely associate a key with an entity (user/device/program/process/component/etc.)

* The aforementioned Trusted Party is called a Certificate Authority (CA). A CA has a key that is used to sign these "documents" called certificates.

## Common Use Cases for Certificates

* Secure Web Sites - HTTPS

* Authenticating Users and Computers - SSH

* Email Signing and Encryption

## Questions for Understanding
1. Name the three main components which make up PKI.
  * Public Key
  * Private Key
  * Public Key Cryptography

2. How would you explain, to a non-technical friend, the role PKI plays in protecting traffic between your browser and a web server.
  * Well, for one PKI is how HTTPS (secure websites) stay secure (and prevent others from listening in)
  * Also- digital signatures is possible becuase of this technology
  
3. What is the main weakness of the PKI architecture?
  * any Certificate Authority can sign a certficate for any person or computer.


## Additional Resources
### Videos
[Prof Messer Security+ PKI Components](https://www.youtube.com/watch?v=3yuad7_bszE)