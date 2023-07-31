# Cloud Identity and Access Management (IAM) with AWS
From: [Anatomy of A Cloud Breach: How 100 Million Credit Card Numbers Were Exposed.](chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://www.zscaler.com/resources/white-papers/capital-one-data-breach.pdf)

### Likely Timeline of Actions






## Questions for Understanding
1. What were the three commands used for the attack?
* curl
* is
* syncs3

2. What misconfiguration of AWS components allowed the attacker to access sensitive data?
* There was a misconfiguration in the WAF (the firewall)

3. What are two of the AWS Governance practices that could have prevented such attack?
* Clean up unused cloud resources leftover from prior dev or prod debugging efforts
* Ensure each application, EC2 instance, or autoscaling group has its own IAM role. do not share roles across unrelated applications.