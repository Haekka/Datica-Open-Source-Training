
Title:
Lesson 14 | Business Associate Agreements (BAAs)
---

Lesson Notes: Business associate agreements codify relationships between entities under HIPAA.
- :dart: BAAs govern the relationship and responsibility between covered entities and business associates.

---

Lesson Content:

Business associate agreements are basically legal contracts that outline the ways in which business associates follow HIPAA, as well as the responsibilities and risks that the business associate takes on. They typically define the type of services that the business associate is providing, the type of data that they are interacting with, stating that they will follow HIPAA and not disclose PHI without authorization. They also should address areas around breach notifications and penalties.

Business associate agreements became a lot more interesting with the passing of the new HITECH HIPAA Omnibus Rule in 2013, which expanded upon that definition of business associate to include something called subcontractors. These subcontractors have to sign business associate agreements with business associates, who in turn have to sign a business associate agreement with covered entities. 

---

External resources:

The HIPAA Privacy Rule outlines the types of entities that are covered by HIPAA and entities that have to follow the HIPAA security and privacy rules. The main categories are clearinghouses, covered entities (CEs) - typically hospitals, payers, and providers, and business associates. Business associates are far away the biggest cohort of cloud computing companies.

Business associates are people or organizations who contract and provide services and/or technology for covered entities. In the process of providing those services or those technologies, business associates handle, process, transmit, or in some way interact with electronic protected health information (ePHI) from those covered entities. With this ePHI access, business associates are required to sign what's called a business associate agreement (BAA). Below is the actual language from HIPAA 164.308.

* (b)(1) Business associate contracts and other arrangements. A covered entity may permit a business associate to create, receive, maintain, or transmit electronic protected health information on the covered entity's behalf only if the covered entity obtains satisfactory assurances, in accordance with §164.314(a), that the business associate will appropriately safeguard the information. A covered entity is not required to obtain such satisfactory assurances from a business associate that is a subcontractor.

* (2) A business associate may permit a business associate that is a **subcontractor** to create, receive, maintain, or transmit electronic protected health information on its behalf only if the business associate obtains satisfactory assurances, in accordance with §164.314(a), that the subcontractor will appropriately safeguard the information.

Business associate agreements are basically legal contracts that outline the ways in which business associates follow HIPAA, as well as the responsibilities and risks that the business associate takes on. They typically define the type of services that the business associate is providing, the type of data that they are interacting with, stating that they will follow HIPAA and not disclose PHI without authorization. They also should address areas around breach notifications and penalties. Traditionally, pre-cloud and prior to the HIPAA Omnibus changes of 2013, BAAs were boiler plate. Here's the [template BAA][1] from HHS.

Business associate agreements became a lot more interesting with the passing of the new HITECH HIPAA Omnibus Rule in 2013, which expanded upon that definition of business associate to include something called subcontractors. Subcontractors are typically service or technology organizations that provide additional services to the business associates, which are providing services for the covered entities. With subcontractors and APIs and SaaS, there is now a chain of entities touching ePHI in some way, and each of them need to have BAAs in place that are consistent and not contradictory to one another. As an example, a business associate selling to hospital A can't have a breach notification policy of less than 24 hours if the hosting provider they use has a physical breach notification policy of 2 months.

As the internet, cloud computing, and APIs have broken down silos, more and more applications rely on different layers of technology and services, considered subcontractors. These subcontractors have to sign business associate agreements with business associates, who in turn have to sign a business associate agreement with covered entities. That's actually a very common use case for us at Datica, where most of our early customers are business associates, and their customers are covered entities.

We spent a lot of time and a lot of money with our attorneys on our BAAs because this is a new area, an area we don't think is well defined yet; we don't think the existing BAA templates are adequate or even make sense for most hosted vendors. In this new paradigm of health technology there are interesting definitions around which entities are responsible, both technically and financially in the case of a breach, for different aspects of the HIPAA rules. We tell our prospective customers to read their current business associate agreements that they have with their hosting providers or other services companies to get a sense of what the legal responsibility is for the business associate, and the aspects to which the subcontractor is ultimately responsible. Regardless of who is issuing the BAA, you should read through it in detail, because at some point a compliance or security officer likely will read it and you want to be as proactive about compliance issues as you can.

If you boil it down, business associate agreements are just contracts that outline the ways in which different organizations are going to handle electronic protected health information (ePHI), the types of responsibilities that those organizations take on, some of the very specific rules around their obligations with regards to HIPAA. This last one, the obligations of subcontractors, is an area in which you want to pay close attention. Specifically read what the subcontractor's obligations are in terms of timeliness of breach notification, because that was a part of the changes in the HIPAA Omnibus Rule that just went into effect. We have had several early customers come to us because the time period for breach notifications with their existing hosting provider is not acceptable for covered entities they are selling to. We've talked to several companies that have run into roadblocks with enterprises because their business associate agreements with their hosting providers had been out of line, and especially relating to breach notification.

---

Lesson Scenario:

What is true of business associate agreements (BAAs)?

- `They are standardized`
- `Cloud providers do not sign them`
- `They are executed between business associates and covered entities`
- `The are unenforceable`

Answer: BAAs are executed between business associates and covered entities.




[1]:	http://www.hhs.gov/ocr/privacy/hipaa/understanding/coveredentities/contractprov.html