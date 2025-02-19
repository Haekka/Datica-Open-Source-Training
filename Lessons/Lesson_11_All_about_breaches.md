Title:
Lesson 11 | All about breaches
---

Lesson Notes: Everything you wanted to know about data breaches?
- :dart: What you do in the case of a breach can determine the penalties.
- :dart: It’s important to understand your role in a breach and to know how to identify a breach.

---

Lesson Content:

One of the most important aspects of HIPAA has nothing to do with technical security like encryption or backup or logging or any of other requirements for securing data. What’s important is what happens in the case of an unauthorized disclosure of ePHI, or a breach of ePHI.

A breach is defined as unauthorized exposure of ePHI or disclosure that’s not authorized or allowed under the HIPAA Privacy Rule. The breach rules were amended in 2013 as part of the HITECH Act.

HIPAA requires notification of a breach “without unreasonable delay” but allows, at a maximum, 60 days to report a known breach. 

---

External resources:

**HIPAA Breaches**

One of the most important aspects of HIPAA has nothing to do with technical security like encryption or backup or logging or any of other requirements for securing data. What’s important is what happens in the case of an unauthorized disclosure of ePHI, or a breach of ePHI.

**Definition of Breach**

A breach is defined as unauthorized exposure of ePHI or disclosure that’s not authorized or allowed under the HIPAA Privacy Rule. The breach rules were amended in 2013 as part of the HITECH Act.

HITECH Act Sec. 13402(b) Notification of Covered Entity by Business Associate states - A business associate of a covered entity that accesses, maintains, retains, modifies, records, stores, destroys, or otherwise holds, uses, or discloses unsecured protected health information shall, following the discovery of a breach of such information, notify the covered entity of such breach. Such notice shall include the identification of each individual whose unsecured protected health information has been, or is reasonably believed by the business associate to have been, accessed, acquired, or disclosed during such breach.

**Notifications**

HIPAA requires notification of a breach “without unreasonable delay” but allows, at a maximum, 60 days to report a known breach. Most covered entities that we’ve worked with want that timeline to be much shorter, and the range we usually hear is somewhere between 24 hours and 5 days. This can be a sticking point in business associate discussions. Some hosting providers have polices in place for breach reporting that are 30 days, 45 days, even 60 days out; this is typically not in line with what a hospital or a payer or another large enterprise in healthcare would expect from a business associate agreement and a breach policy for a business associate that they are working with. Despite the 60 day window HIPAA rules also go on to require “evidence demonstrating the necessity of any delay.” If it takes 60 days, there have to be reasons given for that delay.

Breach policy and breach notification are things that are extremely important. There are templates for breach notification, but the policy alone does not mitigate risk. There needs to be an understanding within the organization, business associate or covered entity, of what a breach is and what the breach policy is. There also need to be auditing and logging and other systems (IDS) in place to detect and investigate a breach. Detecting the breach is often the challenge which is why having a comprehensive audit log is necessary and more importantly, being able to generate alerts off the log is critical.

**Expectations vs Reality**

The majority of breaches are actually not software breaches. They’re not hacking into a system that causes the unauthorized disclosures. Breaches affecting over 500 records are [published][1] by CMS. You can see there’s a searchable database of breaches that have occurred, how many records were affected and the type of breach. The vast majority of breaches are hardware breaches. The majority, if not almost all of the breaches, seem to happen because of [employee carelessness][2]. It seems like it’s almost always a contractor’s laptop that’s been unencrypted and has been storing tons of patient records. The laptop is stolen from a car or a house or a coffee shop or an airport or whatever.

“Hacking/IT Incident” only accounts for a relatively small number of breaches. There is great potential to have a breach with a malicious hacker breaking into a private network or any sort of cloud-based storage, especially public cloud. This potential has fueled much of the slow pace of ePHI to the cloud.

The important thing when it comes to a breach is actually having a process in place that details the steps to take in case of a breach. How do you assess what information was exposed in an unauthorized way and then how do you go about notifying relevant parties of that breach? The necessary notifications includes anybody, from the actual patient whose medical record was exposed, to the media, covered entities, and business associates. The notification policy should lay out plans for forensics to discover the extent of the breach and the cause of the breach. There is typically a chain of command that is outlined in a breach notification strategy that lays out, in detail, who is responsible for different aspects of notification and mitigation. The rules also put the burden on the business associate “of demonstrating that all notifications were made as required” by HIPAA.

The policies should be consistent with what is in the requirements of a business associate agreement as it relates to timing to report a breach. HIPAA requires notification of a breach “without unreasonable delay” but allows, at a maximum, 60 days to report a known breach. Most covered entities that we’ve worked with want that timeline to be much shorter, and the range we usually hear is somewhere between 24 hours and 5 days. This can be a sticking point in business associate discussions. Despite the 60 day window HIPAA rules also go on to require “evidence demonstrating the necessity of any delay.” If it takes 60 days, there have to be reasons given for that delay.

Breach policy and breach notification are things that are extremely important. There are templates for breach notification, but the policy alone does not mitigate risk. There needs to be an understanding within the organization, business associate or covered entity, of what a breach is and what the breach policy is. There also needs to be auditing and logging and other systems (IDS) in place to detect and investigate a breach. Detecting the breach is often the challenge, which is why having a comprehensive audit log is necessary and more importantly, being able to generate alerts off the log is critical.

---

Lesson Scenario:

What is the maximum time to report a breach under HIPAA?

- `24 hours`
- `72 hours`
- `1 week`
- `1 month`
- `60 days`


Answer: 60 days is the maximum time allowed under HIPAA for reporting a breach.


[1]:	https://ocrportal.hhs.gov/ocr/breach/breach_report.jsf
[2]:	http://rockhealth.com/wp-content/uploads/2013/03/34f9a961f56ac6d3013d8b1bd266ef3b96fee194.png