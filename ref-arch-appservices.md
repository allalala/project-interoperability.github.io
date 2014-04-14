---
published: true
permalink: /ref-arch-appservices/
layout: default
filename: ref-arch-appservices.md
title: Applications/Services Domain Reference Architecture Template
---

The reference architecture (RA) templates are designed to aid the development of reference architecture artifacts to support interoperability. To learn more about the purpose, structure, method, and how to use these templates, visit the main [Reference Architecture Template](/ref-arch-template) page.

**Alignment with Project Interoperability Toolsand Resources:** Operational Capabilities, Technical Standards, Technical Capabilities, Exchange Patterns, Exchange Specifications.

**Overview:** Describe the technical services supporting the common activities used for discovering, identifying, distributing, protecting, and managing the data/ information needed by external users. Provide any applicable service standards, application architecture approaches such as SOA, or other information required to interact with the applications/service within the domain.

**Objective of the Architecture:** Capture the specifications and functional requirements of the applications/service to the level necessary for external application developers can interface with application/services available to externals.

Application/Service Environment Considerations:

* Identify services and common activities, their service component and the interfaces/ interconnections between the services and data assets that are exchanged. (A1)

* Describe recommended and/or possible implementation approaches (e.g., Cloud, SOA, Mobile) and considerations for approaches to be captured in applicable artifacts.

* Provide standards and/or standards requirements for consideration by the reference architecture. These need not be prescriptive but suggestive and currently utilized within the application class. (A6)

* Describe extensibility approaches for future users/applications in any modernization plan artifacts.

* Describe how the application architecture scales for more users in any modernization plan artifacts.

Application/Service Requirements/Constraints:

* Specify the standards/specifications used by the services to make them discoverable.

* Describe the functions performed by the applications/services and any constraints on the data used and the flow of the data. (A3)

* Describe the data assets used by the applications/services and how the data is exchanged between the services. (A2)

* Describe the data flows being exchanged between services and the attributes of the exchanges. (A4)

* Specify any service standards used by or required by the applications/services. (A6)

* Specify how the "service-level agreements" are enforced (manually or machine-level) and the standard/specification if machine-level. (A6)

Application/Service Provider and User Roles and Responsibilities:

* Specify the provider and user roles and responsibilities with respect to application/service lifecycle (Development – O&M – Retirement). (B4)

* Specify rules/laws with respect to products/data/information generated by the applications/services. (A5)

API Considerations:

* APIs published/exposed so that future users can access and create applications with the information/data, describe how the developers access the APIs. (A6)

Cloud Application/Service Implementation Considerations:

* Describe 'continuity of operations' considerations for information/data flows. (A3)

Mobile Application/Service Implementation Considerations:

* Describe mobile implementation considerations that are unique to the mobile architecture environment in addition to service identification. 

*Key Focus Area: Applications/Services - Describe the applications/services and their interconnections between other services as well as the data assets and the information flows that are being used and exchanged. Applications/service and their external interfaces should be standardized when possible for scalability and interoperability purposes. Specify the service standards used and their applicability both internally, externally and reusability.*

### Architecture Framework Alignment Grid

| ISE Interoperability Framework: Minimum Requirements for Interoperability | ISE Interoperability Framework: Artifact Description | FEAF | DoDAF/UAF | GRA Service Specification Package v 1.0.0 | IC-related (based on ICEA PAG) | TOGAF |
| Technical services supporting the common activities used for discovering, identifying, distributing, protecting, and managing information | (A1) Identify services and common activities, their service components, and the interconnections between the services, as well as the data asset being exchanged (A2) Provide a description of the data asset exchanged between services (A3) Describe the functions performed by the services and the service data flows among the service functions (A4) Describe the details of the data flows being exchanged between services and the attributes of the exchanges (A5) Describe the resource/data flows between operation activities; this will be transformed to the flows between services | Application Interface Diagram Application Communication Diagram Application Data Exchange Matrix Data Flow Diagram | [SvcV-1 Services Context Description](http://dodcio.defense.gov/dodaf20/dodaf20_services1.aspx) [SvcV-2 Services Resource Flow Description](http://dodcio.defense.gov/dodaf20/dodaf20_services2.aspx) [SvcV-4 Services Functionality Description](http://dodcio.defense.gov/dodaf20/dodaf20_services4.aspx) [SvcV-6 Services Resource Flow Matrix](http://dodcio.defense.gov/dodaf20/dodaf20_services6.aspx) [OV-2: Operational Resource Flow Description](http://dodcio.defense.gov/dodaf20/dodaf20_ov2.aspx) | Interface Description Requirements Service Interfaces | Service Component View Interaction Diagram View Interaction Matrix Service Sequence | Phase C: Information Systems Architecture – Applications Application Portfolio Catalogue Interface Catalogue Application Organization Matrix Application Role Matrix Application Function Matrix Application Interface Diagram Application Communication Diagram Application and User Diagrams Application Location Diagrams Process Application Diagram Application Use Case Diagrams Software Engineering Diagram Software Distribution Diagrams |
| Developing service standards including service metadata, protocol standards, service oriented architecture, and standard APIs | (A6) Document the service standards to be used by the services and applications | Technical Standards Profile | [StdV-1 Standards Profile](http://dodcio.defense.gov/dodaf20/dodaf20_stdv1.aspx) | x | Relevant Standard Matrix | Application Function Matrix Application Interaction Matrix |