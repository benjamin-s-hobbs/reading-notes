# Data file encryption
From: [Applying The CIA Triad To Your Enterprise File Transfer](https://www.jscape.com/blog/implementing-the-cia-triad-when-transferring-files-through-the-internet) (accessed by Benjamin Hobbs on 7/15/2023)

# CIA Triad (Confidentiality, Integrity, and Availability)
* A foundational concept of information security, the CIA Triad is also critical to enterprise-level file transfers. The article explains how the Triad applies to B2B data transfers.

## Confidentiality

* Refers to the principle of restricting access to (or knowledge of) certain information to certain individuals. This may be for a myriad of reasons:

  * Company trade secrets, salaries, product development, etc.

  * privileged communications (e.g. doctor-patient privilege, attorney-client, etc.)

  * To secure customer data in compliance with regulations (e.g. HIPAA)

### Attacks that undermine Confidentiality

 * Man-In-The-Middle Attack (MITM) 

## Integrity

* Refers to the principle of tampering with data (changing it without authorization.)


## Availablity

* Refers to the concept of being able to access your data when it is needed. 

## Technical Solutions for Data to preserve the CIA Triad

* Encryption (Confidentiality)- data is said to be encrypted ***"end-to-end"*** when it is:
   * Encrypted "at rest" (while stored on a hard disk or removable media)
   * Encrypted "in use" (while being actively worked on and stored in a computer's working memory, or RAM)
   * Encrypted "in transit" (while it is being transported through networks from one endpoint to another)
* Hashing (and salting) (Integrity)- Hashes provide assurance that the information hashed has not been changed. Hashing is NOT the same thing as encryption. Salting is the process of placing random characters in the data prior to hashing to make it more difficult to crack.
* High Availability/ Redundancy (Availability)- Using the concept of redundancy, businesses attempt to preserve the ability to always have access to the information they need.

# Hashes (MD5, SHA-1, SHA-256)
From [What Are MD5, SHA-1, and SHA-256 Hashes, and How Do I Check Them?](https://www.howtogeek.com/67241/htg-explains-what-are-md5-sha-1-hashes-and-how-do-i-check-them/) (accessed by Benjamin Hobbs on 7/15/2023)







## Questions for Understanding 
1. You have been made responsible for the company’s file server. How would you preserve the three elements of the CIA triad?
  * Confidentiality- 
    * I would conduct full-disk encryption on the file server and the endpoints that communicate with it either using Veeam or Bacula (data at rest). I would also set up a VPN (just a tunnel) but still transfer via SSH (encrypted in-transit)

2. Explain how hashing verifies data integrity using non-technical terms.

3. How are hashing and encryption different?