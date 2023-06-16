# Group Policy
From Jason C. "What is Group Policy (GPO) and What Role Does It Play in Data Security" https://www.lepide.com/blog/what-is-group-policy-gpo-and-what-role-does-it-play-in-data-security/ Updated Nov 18, 2022 (accessed Jun 15, 2023 by Benjamin Hobbs)

## What is Group Policy?
Group Policy Objects (GPOs) are a feature of Microsoft Windows that enables a wide range of advanced settings that network admins use to control the working environments of users and computer accounts in Active Directory (AD). 

 * It's a centralized place for admins to manage and configure operating systems, updates, patches, apps, and other settings and rules.

 * When used correctly, GPOs


 ## Questions from the reading for understanding.

1. What role does Group Policy play in Windows Active Directory?
     * managing multiple computers on a domain at once. This enables one or few people to ensure that potentially thousands of users are in compliance with company IT policy (because they have no other choice.)

2. Name and describe different ways GPOs can benefit security.
    * An admin scheduling maintenance (e.g. patches, updates, refreshes, etc.)
    * An admin adjusting allowlists or denylists can also have a positive effect on security.
    * An admin setting password rules via GPO can assist in preventing a user unintentionally being a security threat by setting weak passwords.

3. How can the acronym “LSDOU” help you figure out which policies are in effect?
    * LSDOU is a method to remember the order that the GPOs are processed
        * Local -
        * Site 
        * Domain 
        * Organizational Unit (OU) 
    * Last applied policies win in the event of a conflict.