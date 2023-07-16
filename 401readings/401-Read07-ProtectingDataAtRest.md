# Protecting Data at Rest with Device Encryption
From: [Data Protection: Data In transit vs. Data At Rest](https://www.digitalguardian.com/blog/data-protection-data-in-transit-vs-data-at-rest) (accessed by Benjamin Hobbs on 7/15/2023)

## What is "Data In Transit" Vs "Data At Rest?"

* Data in transit (also "data in motion") is when data is actively moving from one location to another (like through a network or across networks)
  * Data is considered less secure while in transit (motion.)

* Data at rest is data that is being stored on a device (hard drive, flash drive, storage array, etc.)
  * While it is generally considered to be less vulnerable than data in transit, attackers oftn consider it a more valuable target.

## Best Practices for Protecting Data (In Transit and At Rest)

* Implement robust security controls
  * Firewalls
  * Network Access Control (NAC)

* Enable user prompting, or automatic encryption to remind users. Conduct training to maximize awareness

* Create policies to systematically categorize and classify all company data (at rest or in transit)

* Select a cloud provider for their security measures they offer, but don't rely on just them. Bring your own as well.

## Exercises for Understanding

1. From your day to day computer use, provide examples of when data is at rest and when it is in transit.
  * At rest - 
    * the stored text messages on my phone
    * the stored documents in my computer
    * The stored documents on my OneDrive/GoogleDrive
  * In transit -
    * when I hit send on a text
    * when I hit send on an email
    * when I ACP my GitHub
    * when I'm downloading...(anything)
    * when I'm streaming...(anything)
    * using GPS

2. Explain the role data encryption with regards to the CIA triad.
  * Encrypting data is defending the confidentiality of the data. An attacker could still steal the data and deny the rightful owner access to it - which would be a violation of Availability. An attacker could take the data and destroy it, which would violate both Integrity and Availability...but unless they defeated the encryption to ACCESS the data, it would remain confidential.