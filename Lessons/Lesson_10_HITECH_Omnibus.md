
Title:
Lesson 10 | HITECH Omnibus
---

Lesson Notes: What did the 2013 HIPAA Omnibus Rule change?
- :dart: The Omnibus rule clarified definitions around breaches, updated penalties, and clarified entity types.

---

Lesson Content:

The new HIPAA Omnibus ("omnibus" means something with several volumes or chapters) rules that went into effect on 9/23/2013, amongst other changes, created a category of entities called subcontractors.

Previously HIPAA rules only defined two categories of entities - covered entities and business associates. Subcontractors are entities that business associates use to process, create, or store PHI. 

The best examples of subcontractors we can think of are hosted services providers like Amazon Web Services, Datica, and Rackspace. 

---

External resources:

The new HIPAA Omnibus ("omnibus" means something with several volumes or chapters) rules that went into effect on 9/23/2013, amongst other changes, created a category of entities called subcontractors.

Previously HIPAA rules only defined two categories of entities - covered entities and business associates. Covered entities are basically providers, payers, and clearinghouses. Business associates are basically entities that work with covered entities to perform a service or services to store, transmit, and/or process PHI. The new HIPAA rules expanded the number of categories of entities by 50% with the addition of subcontractors; for those of us in health tech, we think this is a pretty big deal.

Subcontractors are entities that business associates use to process, create, or store PHI. Subcontractors don't have business associate agreements, or really any direct relationships, with covered entities; but, starting 9/23/2013, theses subcontractors need to have business associate agreements (BAAs) with business associates. It's all very obvious and confusing at the same time. Essentially you can think of subcontractors as a business associate of a business associate.

The best examples of subcontractors we can think of are hosted services providers like Amazon Web Services, Datica, and Rackspace. Datica is a subcontractor for some of our customers and, as such, we do sign BAAs. We also act as a business associate directly for covered entities like enterprises, and sign BAAs in this capacity. We offer the same API-based services for developers in both circumstances, but the relationship is slightly different in the eyes of HIPAA.

At Datica we know that subcontractors, as defined by HIPAA, have existed for a long time. As more health apps and services have shifted to hosted, or cloud based, and more infrastructure tools (app dev, logging, analytics, data collections, etc) have become mainstream, covered entities and business associates have begun to rely on "subcontractors". The new HIPAA rules now mean those subcontractors need to work with business associates to assure all parties are covered in terms of liability.

This is a very exciting and major shift for health tech. HIPAA has finally acknowledged subcontractors and the role they play in creating, processing, and transmitting PHI. That's important for health tech to build smart, scalable, and interoperable tools. As a developer in healthcare, if you're considering acting as a business associate, or selling services to a covered entity, you need to understand if you fit into a certain entity category as defined by HIPAA.

We encourage you to read the rest of the [rules][1], or at least one of the commentaries that covers them in more detail, to see about the other changes that are a part of the Omnibus rule.

---

Lesson Scenario:

What changes did the HIPAA Omnibus Rule make to HIPAA?

- `More leniant penalties`
- `Defined "subcontractor"`
- `Outlawed the use of anything "cloud"`
- `Made EHR data harder to get`

Answer: The Ombinus Rule clarified entity types by defining "subcontractors", which are essentially business associates of business associates.

[1]:	http://www.hhs.gov/news/press/2013pres/01/20130117b.html