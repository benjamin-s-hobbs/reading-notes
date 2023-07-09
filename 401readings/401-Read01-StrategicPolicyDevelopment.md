# Strategic Policy Development

From: [The Ultimate Guide to SOC 2 Compliance](https://www.vendr.com/blog/soc-2-compliance-guide) (accessed by Ben Hobbs on 7/7/2023)


***Begin with a statement addressing why this topic matters as it relates to what you are studying in this module.
Answer each and every question or prompt presented in the assignment above.
If there are no questions provided, summarize and explain this topic via an analogy from your previous work or home experience.***



## What is SOC 2 compliance?

* SOC 2 is a framework applying to businesses storing computer data in the cloud.
  * Why SOC 2 Compliance is relevant?
     * If a company stores customer data, they should be concerned with the protection of that data. A SOC 2 Report demonstrates that a company is doing what can reasonably be expected to safeguard data.
     * The process of preparation for SOC 2 can bolster company culture.
     * SOC 2 compliance provides documentation.
     * SOC 2 preparation assists with risk management.
* SOC 2 Certification (on its own) is generally not enough to prove 100% security as an organization, but it is a good start.
* SOC stands for Service Organizations Control Report No. 2

### History

Prior to SOC 2, the standard for auditing service organizations was a Statement of Auditing Standards No. 70 (SAS 70.) SAS 70 audits were:
  * performed by Certified Public Accountants (CPAs)
     * original intent was to report on the effectiveness of internal financial controls. 
     * introduced in the early 1990's.
     * Over time, it became a way to report on the effectiveness of a company's internal controls around information security more broadly.
Around 2010, SOC 1 and SOC 2 reports were introduced by the American Institute of Certified Public Accountants (AICPA) 
  * created to explicitly address the growing need for companies to externally validate and communicate their state of security.
    * SOC 1 reports are centered are controls impacting financial reports, similar to the original SAS 70.
    * SOC 2 reports are written against the Trust Services Criteria (TSC) standard, which is ideal to improve a company's maturity around business processes and security.

## SOC 2 "Trust Principles"

SOC audits are organized around five "Trust Principles." When audited, a company chooses which principles they want the auditor to attest to- a business decision driven by what is important to the company's clientle. The five Trust Principles are:
  * **Security** - The foundational security principle, common to all audits. 
  * **Confidentiality** - Protection from unauthorized disclosure of data.
  * **Availability** - Protection that systems or data will be available as agreed or required. 
  * **Integrity** - Protection that systems or data are not changed in an unauthorized manner.
  * **Privacy** - The use, collection, retentin, disclosure, and disposal of personal information is protected.


## SOC 2 Audits

### SOC 2 "Common Criteria"

All SOC 2 audits include "Common Criteria." This is the largest section of the audit and touches on every aspect of information security controls. Companies might start with a Common Criteria audit if they are looking to keep the scope small. 
* More mature Software as a Service (SaaS) companies tend to add on **Confidentiality** and **Availability**.
* Companies processing a lot of transactions (like financial institutions) typically choose **Integrity**
* Note: **Privacy** is seldom included as part of a SOC 2 audit as most organizations tend to focus their privacy compliance efforts with a separate, often more stringent, standard (such as the Health Insurance Portability and Accountability Act ([HIPAA](https://en.wikipedia.org/wiki/Health_Insurance_Portability_and_Accountability_Act)) in the U.S. or the General Data Protection Regulation ([GDPR](https://en.wikipedia.org/wiki/General_Data_Protection_Regulation)) in the EU.)

The Common Criteria Topics are:
* Organization & Management
* Communications
* Risk Management
* Monitoring of Controls
* Logical and Physical Access Controls
* System Operations
* Change Management

### SOC 2 Audit Process

The SOC 2 reporting standard is defined by the AICPA. All SOC 2 audits are signed by licensed CPAs. Companies typically prepare anywhere from six months to a year for a SOC 2 audit. 

* Prep
  * Identifying which systems will be in scope for the audit.
  * Developing policies and procedures in compliance with the standard.
    * Create new official documentation.
  * Implementing new security controls (if necessary) to reduce risk. 
    * Update internal processes.
    * Conduct employee training and education on new policies and procedures.
* Audit 
  * The Organization will hire a licensed CPA auditor to conduct the audit.
  * CPA conducts the actual process, which consists of (to include):
    * Scoping (determining the scope of the audit)
      * What type of audit is this? SOC 1? SOC 2? Type I? Type II?
      * SOC 1 - Financial Scope
      * SOC 2 - Information Security Scope
      * Type I audit - At a single point in time
      * Type II audit - Over a period of time (usually six months or a year)
      * e.g. A SOC 2 Type II audit would be for an Information Security Scope over a period of time. 
    * Document request and collection (Requests usually made via phone or email)
    * Conduct an On-Site Visit (typically 2 days)
      * Interviews
      * Review submitted materials

## SOC 2 Documentation Framework (Pyramid & the "3Ps")

![SOC Pyramid](https://github.com/benjamin-s-hobbs/reading-notes/blob/main/repo-images/SOC2-framework-pyramid.png)











1. FOUNDATION - Security **Policies** ***"WHAT*** you do"

 * Policies govern the behavior of employees, vendors, contractors, etc. to meet security requirements.

 * General policies included in a SOC 2 audit include:

    * Information Security Policy
    * Access Control Policy
    * Password Policy
    * Change Management Policy
    * Risk Assessment and Mitigation Policy
    * Incident Response Policy
    * Logging and Monitoring Policy
    * Vendor Management Policy
    * Data Classification Policy
    * Acceptable Use Policy
    * Information, Software and System Backup Policy
    * Business Continuity and Disaster Recovery Plan

2. EXECUTION -  Security **Procedures** ***"HOW*** you do it"

* Procedures demonstrate how your policies work operationally, e.g. what steps you take in response to key events to manage data.

* They describe how the business adheres to policies that they've set.

* Policies should be general enough that procedures can have some latitude to be adjusted without changing the policy. Major changes would necessitate a change in policy.

3. **PROOF** - Supporting Documentation "Proof you ***DID*** it"

* Supporting Documentation demonstrates adherence to policies and procedures.




## Questions for Understanding

1. How would you convince your future company to pursue SOC2 compliance?
* SaaS?

2. What are the five SOC2 Trust Principles?
* Security 
* Confidentiality
* Availability 
* Integrity
* Privacy

3. How would you explain the three levels of the SOC 2 pyramid in an analogy your friends or former colleagues would understand?
* In real estate, documentation is easy to understand. I would tell my colleagues (and my clients).
  * The foundation is like having your company policy be to "focus on educating clients and doing all we can to advocate on their behalf." 
  * From that foundation, your procedures would communicate how you intend to have your agents make that happen. Perhaps your office manager comes up with a checklist of things to address so clients have a complete experience. Having templates prepared for use a creating a process for your clients would also be procedures that you could train to in order to enforce the policy.
  * In the end, after your client's process is complete, you may have a completed checklist to show that you addressed all procedures in turn. You may have your client sign something to prove that you advised them of a concept. All of this documentation can be shown to support that you completed the procedures and adhered to your policy to "focus on educating clients and doing all we can to advocate on their behalf."

## What more do I want to know? 

## Additional Materials

### Videos
* [Security Audits - CompTIA Security+ SY0-401: 2.3](https://www.youtube.com/watch?v=FrzpyLZYKxo) (accessed by Ben Hobbs on 7/7/2023)