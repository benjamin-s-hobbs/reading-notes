# Active Directory
From https://www.cyberark.com/what-is/active-directory/

* Active Directory (AD) is Microsoft's directory and identity management service for windows domain networks. 
    * Introduced in Windows 2000
    * Used by a variety of Microsoft systems (Exchange Server, SharePoint Server, third-party app and services)

## Yes, but what IS Active Directory REALLY?

* AD consists of a number of different directory services, including:
    * Active Directory Domain Services (AD DS) - The core AD service. Manages users and resources.
    * Active Directory Lightweight Directory Services (AD LDS) - A low-overhead version of AD DS for directory-enabled applications.
    * Active Directory Certificate Services (AD CS) - for issuing and managing digital security certificates
    * Active Directory Federation Services (AD FS) - for sharing identity and access management information across organizations and enterprises.
    * Active Directory Rights Management Services (AD RMS) - for information rights management (controlling access permissions to documents, workbooks, presentations, etc.)

* Basic AD features and capabilities include: 
    * A schema - defining classes of objects and attributes contained in the directory
       * Users - name/address/number
       * Groups - name/permissions/
       * Contacts - email/phone/location
       * Computer - name/serial/OS/location
       * Shared Folder - name/filepath/group
       * Printer - name/location/IP
       * Organizational Unit (OU)
    * A global catalog - containing detailed info about all the objects in the directory
    * A query and index mechanism - allowing users, admins, and apps to efficiently find info in the directory 
    * A replication service - disseminating directory data across the network

## Active Directory Domain Services (AD DS) Overview

* Authenticates users
* Controls access to network resources

## AD Data Structures

AD stores info in a hierarchical structure consisting of domains, trees, and, forests.
* Domains - are collections of objects (e.g. users, groups, devices, etc.) sharing the same AD database. Domains are defined by a DNS name (globex.com)
* Trees - are collections of one or more domains with a contiguious namespace (a common DNS root name [like globex.com] so it would appear as sales.globex.com, marketing.globex.com, services.globex.com)
* Forests - are collections of one or more trees that share a common schema, global catalog, and directory configuration-but aren't part of a contiguous namespace. 
    * Forests typically serve as security boundaries for enterprise networks.

## AD Benefits

* Security 

* Extensibilty

* Simplicity

* Resiliency


## Questions for Understanding
1. What exactly is “Active Directory” and what are the key services it provides?
* Active Directory, or AD, is actually a number of different directory services, including:
    * Active Directory Domain Services (AD DS)
    * Active Directory Lightweight Directory Services (AD LDS)
    * Active Directory Certificate Services (AD CS)
    * Active Directory Federation Services (AD FS) 
    * Active Directory Rights Management Services (AD RMS)

2. What are the differences between a domain, forest, and tree in Active Directory?
* A domain is a collection of objects (users/groups/devices/etc)
* A tree consists of more than one domain (with a common root name)
* A forest consists of similiar trees (sharing a common schema, global catalog, and directory configuration)

3. How can objects (e.g. users, devices) within a domain be grouped?
* geographically, functionally, or businesswise. 
* They may also be place in Organizational Units (OU)

4. Explain the benefits of Active Directory, as you would to a family member.
* Using AD allows the organization of the data in a business, much like the books in a library.
    * Domains are like a collection - like all of the things in a library. (e.g. mylibrary.com)
        * There is someone in control of a library, like the Head Librarian who makes decisions that affect the whole library and people's experience of the library. 
        * The Head Librarian can add people and subtract people. They can allow people more permissions. They make sure that everything in the library runs well.
    * Trees are like different ways to ways to organize things in the library (e.g. authors, patrons, books, sections, levels, branches, staff, VIPs, donors, etc.)
        * This can look like: books.mylibrary.com, staff.mylibrary.com, patrons.mylibrary.com, donors.mylibrary.com, etc.
    * Forests could be if all of the libraries in the state (or county) shared their schema and global catalog so that someone could look for books.mylibrary.com, books.yourlibrary.com, books.thatlibrary.com, books.thislibrary.com, books.alibrary.com


## What do I want to know more about?
