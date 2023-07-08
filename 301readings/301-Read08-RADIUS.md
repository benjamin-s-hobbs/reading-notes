# RADIUS Authentication
From GeeksForGeeks.org's  [Computer Network | AAA (Authentication, Authorization, and Accounting)](https://www.geeksforgeeks.org/computer-network-aaa-authentication-authorization-and-accounting/) by saurabhsharma56. Last updated Oct 28, 2021 (accessed 6/7/2023 by Benjamin Hobbs)

* AAA is a standard-based framework used to control who is permitted to use network resources. This is achieved through 3 means:

    * ***Authenication***- Verifying the identity of the person (so that they are who they say they are)

        * Common methods of Authentication 

            - Who you are: Biometrics such as fingerprints, facescans, retinal scans, etc.

            - What you know: Usernames, Passwords, Passphrases, Security Questions, etc.

            - What you have: Fobs, Badges, Tokens, etc.

        * Common locations to encounter authentication

            - console ports, AUX ports, or vty lines

            - Local databases (like routers), **Access Control System** (ACS) Server [external]

    * ***Authorization***- Verifying that the individual identified has the authority or permission to do what they are seeking to do.

        * Common methods of authorization

            - Permissions sets: Mandatory, Discretionary, Role-Based, etc.

        * Common locations to encounter authorization

            - local databases, ACS servers, etc.

    * ***Accounting***- Verifying the network's ability to capture the actions performed while being accessed.

        * An adminstrator may create an accouting method list to specify what should be accounted for and to whom should the accounting records be sent.

## AAA Implementation

* local database

* ACS server 

## Reading Questions for understanding

1. Explain each of the three A’s as you would to a non-technical family member. Use an analogy or a story.

    * Let's use the analogy of a bar (in the U.S., one must be over the age of 21 to be served in a bar)

        * Authentication - As someone tries to enter, it's likely that someone at the door (like a bouncer, or security) will ask for ID. In this case we are talking about something that you have (photo ID). The bouncer will look at the ID to see if it's fake...and look at you (ideally) to see that you match the ID. This is how he checks to see that you are who you say you are. If satisfied, he'll let you pass.

        * Authorization - The bouncer is not only checking that your face matches the ID and the ID is valid, but also that you have authorization to pass (that you're over the age of  21.) Once you're in, you may order a drink- but you still don't have free rein of the place. There are place that you aren't authorized to go (storeroom, behind the bar, manager's office). Only employees are authorized (This shows levels of authorization.)

        * Accounting - If there is a security camera outside watching the entrance and exit, then an accounting (or a log) of access is created. Paying with a credit card/starting a bar tab does the same thing, keeps an account of drinks that you've ordered and/or paid for.

2. What should the administrator do if the ACS server fails to authenticate a user during AAA implementation?

    * The administrator should use the local database of the device as a backup in the event of an ACS server failure.

3. What is the role of the NAS in the AAA implementation using an ACS server? Use a diagram.

    * A Network Access Server (NAS) assumes a role of **client** as it sends authentication requests to the Access Control System (ACS) Server

# Remote Authentication Dial-In User Service (RADIUS)
From Peter L. "RADIUS (Remote Authentication Dial-In User Service)" https://archive.is/27Y19 Last updated Sep 2021 (accessed by Benjamin Hobbs 6/7/2023)

## What is RADIUS?


## How does RADIUS authentication work?


## How are RADIUS servers used?

1. What are the benefits of using RADIUS for authentication and authorization?

2. What is RADIUS and what does it stand for?

    * RADIUS (Remote Authentication Dial-In User Service) is an Access Control System. It's a client-server protocol and software that 

3. Research: What encryption algorithms does RADIUS use?

    * symmetric
    
    * MD5 hashing algorithm


### Reading Questions for understanding


## What do I want to know more about?



