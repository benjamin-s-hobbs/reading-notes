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
  * Integrity- SHA-256 hashes and digital signatures would be the way to go.
  * Availability-
    * I would definitely set up a high-availability (HA) cluster. Depending on our level of resources, I'd look into at least a RAID on one end, and perhaps an Active-Active (HA) on the other.

2. Explain how hashing verifies data integrity using non-technical terms.

  * If you were a very neat and tidy person that kept your busy desk just so, papers aligned to the edge of the mousepad and the pens arranged by height, and so on...if someone were to come in to your office and sit in your chair and then leave, you would know. Something would have changed that you would have noticed. The integrity of your pristine desk and office has been violated by someone not authorized to make changes.
In a similar way, hashes alert us to something being different in a file by completely altering the hash.

3. How are hashing and encryption different?
* For one- encryption is a two-way process...something that is encrypted should be able to have the correct cipher applied and **decrypt** the information. 
    * An anology I might use here could be a locker. If I know the combination, I can open the locker, place some apples and oranges inside, and close the locker. When the lock actuates-it doesn't affect the apples and oranges...you just need the combination to get them out. Put the combo in, the locker opens, and you get your info (or fruit) back.
    * hashing is a one-way process. An analogy I might use is a blender. I put apples and oranges in, turn on the blender, I can turn on the blender correctly again...my pulpy juice will not become unblemished apples and oranges again.
* Also, they have different aims. Encryption aims to preserve **confidentiality** while hashing aims to preserve **integrity**.


## What would I like to know more about?
## Other Interesting Reads
* [SSL vs SSH - A Not-So-Technical Comparison](https://www.jscape.com/blog/ssl-vs-ssh-simplified)