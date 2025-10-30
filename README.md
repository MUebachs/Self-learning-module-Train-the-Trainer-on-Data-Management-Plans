<!--


language: en

narrator: English Female

author: Marisabel Gonzalez-Ocanto

comment: **RDMTraining4NFDI Hybrid Event: Research Data Management for NFDI Consortia**

logo: https://base4nfdi.de/images/Logo_base4NFDI_kurz-1.png

classroom: false
classroom: disable
sharing: off

version: 1.0

logo: https://base4nfdi.de/images/Logo_base4NFDI_kurz-1.png
icon: https://base4nfdi.de/images/Logo_base4NFDI_kurz-1.png

-->

[![course badge](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://LiaScript.github.io/course/?https://raw.githubusercontent.com/MUebachs/Self-learning-module-Train-the-Trainer-on-Data-Management-Plans/refs/heads/main/README.md)

# Self-learning-module-Train-the-Trainer-on-Data-Management-Plans

## Introductory information

**Duration**: 2.5 hours

**About the module:** This module is based on the [DMP4NFDI Train-the-Trainer concept for Data Management Plans](https://doi.org/10.5281/zenodo.15771035) (DMPs). It expands upon the foundational knowledge of DMPs, guiding participants towards greater independence and a deeper understanding of how to apply DMPs.

**Requirements:** Participants should have a good understanding of DMPs, i.e. they should already be familiar with their purpose, structure and benefits.

**Target group:** NFDI members looking to enhance their knowledge of DMPs in order to provide effective support to their communities in developing their own.

**Learning objectives**: After completing this module, you will be able to...

 - ...discuss and analyse the application of both DMPs and maDMPs
 - ...compare and tailor funder requirements to domain-specific needs —  i.e. first steps in creating DMP templates
 - ...write and review DMPs independently
 - ...support researchers writing DMPs — e.g. evaluate the completeness and accuracy of answers
 - ...design and deliver didactic scenarios to train and empower other researchers

## Table of contents

1. Data Management Plan (DMP): Refreshing your knowledge
2. DMP Templates: A deep dive
3. Best practices for template creation and support 
4. Facilitating DMP learning
5. Further literature & online sources

# 1. Data Management Plan (DMP): Refreshing your knowledge

**Pop Quiz!**

Quick questions to check and refresh your foundational knowledge on DMPs.

Don't worry, it's just a bit of fun!

What does it mean that a DMP is a living document?

 - [( )] It must be handwritten and stored in physical form
 - [( )] It is fixed at the beginning of a project and should not be changed
 - [( )] It requires approval from a legal advisor before any changes
 - [(x)] It should be reviewed and updated during the project

What is one key benefit of using a DMP in a research project?

 - [( )] It increases project costs significantly
 - [( )] It eliminates the need for ethical approval
 - [(x)] It helps manage data and lowers the risk of data loss
 - [( )] It guarantees that research will be published

True or False

 - [( )] The DMP is primarily a control instrument of the funders.

To be FAIR, a data management plan should...

 - [(x)] Use standard metadata formats to support data exchange
 - [( )] Limit access to ensure data security
 - [( )] Store data in custom file formats for uniqueness
 - [( )] Focus only on internal team workflows

Which of these aspects are part of a DMP?

- [(x)] Information on storage and backup during the project
- [(x)] Costs of data management
- [( )] Vote of an ethics committee
- [(x)] Responsible people for data management
- [( )] Description of the benefits of the data management plan

**How did you do?**

If you got four or more answers right, well done! You master the DMP basics.
Less than four correct answers? Don't worry, we'll cover everything again on the next few slides. 

## Definition

📝Data Management Plans (DMPs) describe the data researchers intend to collect or generate during the research process. They explain how the data will be handled at all phases of the research data life cycle, thus supporting researchers in producing FAIR data. DMPs are not static but living documents, i.e. they are ideally regularly updated with changes documented by way of versioning.

![alt](https://github.com/MUebachs/Self-learning-module-Train-the-Trainer-on-Data-Management-Plans/blob/main/Ressources/Research_Data_Live_Cycle.png?raw=true)

⚠️ Writing DMPs is becoming a mandatory requirement for researchers applying to funding agencies. Thus, many researchers view DMPs as a mere formality, often completing them only at the proposal stage and neglecting them thereafter. They frequently express confusion about the relevance of DMPs to their specific workflows and struggle to see their long-term value, especially in disciplines where data management practices are less established.

## Components

**commonly used components in DMPs**

![alt](https://github.com/MUebachs/Self-learning-module-Train-the-Trainer-on-Data-Management-Plans/blob/main/Ressources/Components_in_DMPs.png?raw=true)

List of components:

 - Administrative information
 - Roles, responsibilities and obligations
 - Budget, costs and resources
 - Data origin, types and formats
 - Metadata (standards) and documentation
 - Data access and publication
 - Data storage and preservation
 - Legal aspects

> **DMPs can look very different depending on the size of the project, the types of data involved, and specific funder requirements.** The next section will guide you through key aspects to consider when assessing a DMP, helping you explore whether the research team has provided enough information to manage their data effectively. 

## Criteria for DMP evaluation 

**DOI:** [10.5281/zenodo.4915861](https://doi.org/10.5281/zenodo.4915861)

| **DMP component** | **Review criteria** |
|--------------------|---------------------|
| **Administrative information** | - The DMP contains the minimal information required to identify the applicant and the references of the project, e.g. name of applicant, project number, funding programme, version of DMP, DMP responsibles. |
| **Roles, responsibilities and obligations** | - The DMP clearly outlines the roles and responsibilities for data management and stewardship, and naming responsible individuals where possible. It also indicates who is responsible for the day-to-day implementation of, and any adjustments to, the DMP. For collaborative projects, the DMP explains how data management responsibilities are coordinated across partners. |
| **Budget, costs and resources** | - The DMP provides clear estimates of the resources and costs (e.g. hardware, staff time, repository charges) that will be dedicated to data management and ensuring that data will be FAIR. It describes how these costs will be covered. Alternatively, there is a statement that no additional resources are needed. |
| **Data origin, types and formats** | - The DMP clearly describes where the data come from and how new data will be collected or produced, including the methods and software used. If existing data are reused, it explains how they are accessed and any restrictions. Where relevant, it justifies why new data need to be collected instead of reusing existing ones.<br><br>- The DMP also outlines the types and formats of data to be generated (e.g. numeric, textual, audio, video), any conversion strategies, and the reasons for choosing specific formats (e.g. open vs. proprietary). The DMP includes estimates of data volume and, if applicable, states when no new data will be produced. |
| **Metadata (standards) and documentation** | - The DMP outlines the metadata that will accompany the data, following good practices in the research community and using established metadata standards where available. It specifies the documentation required to enable data re-use and indicates where this information will be recorded.<br><br>- The DMP also describes how data will be organised during the project, including naming conventions, version control strategies, and folder structures. Additionally, it explains the approach for ensuring and documenting quality control throughout the data collection process.|
**Data storage and preservation** | - The DMP describes where data and backups will be stored, how often backups occur, and the use of secure, managed storage. If institutional storage is not used, it explains alternatives and procedures. It covers data recovery, applicable protection policies, access rights, and security measures for sensitive data.<br><br>- The DMP also specifies which data and documentation will be preserved long-term, the rationale for retention or destruction, and potential for re-use. It explains how data and required technology will be archived, managed beyond the grant, and made available through a repository or curation approach. |
| **Data access and publication** | - The DMP describes how data and metadata will be made discoverable and shared, when they will be released, and under which licence. It names the repository, catalogue, or registry where data will be available and states how long they will be retained. Where sharing is limited or not possible, the DMP explains why, who can access the data, and under what conditions. It also outlines steps to reduce or overcome sharing restrictions.<br><br>- The DMP identifies the tools, software, or protocols needed to access and re-use the data, including any authentication or access request procedures. It explains how data can be re-used in other contexts, specifies whether persistent identifiers (PIDs) are provided, and justifies the chosen approach with reference to international standards. |
| **Legal aspects** | - The DMP indicates whether personal data will be collected or used and explains how compliance with relevant legislation will be ensured, for example through informed consent, encryption, anonymisation, or pseudonymisation. It describes procedures to restrict access to authorised users.<br><br>- Where relevant, the DMP clarifies who controls access to specific data, the applicable access conditions and re-use licenses, and how intellectual property rights are managed. For multi-partner projects or multiple data owners, it explains how these issues are addressed in agreements. Alternatively, it provides a clear statement if no restrictions apply and notes any restrictions on re-use of third-party data.<br><br>- The DMP outlines ethical considerations affecting data storage, transfer, use, sharing, and preservation, and describes measures in place to manage them. It mentions whether ethical review is being pursued or, if approval has been obtained, refers to the relevant committee and documents. The DMP also refers to applicable ethical guidelines or codes of conduct, or explains why ethical issues are not applicable. |

## Exercise 1

We will now present some DMP extracts. Using the evaluation criteria you have just seen, review each extract and reflect on the following:

 1. Which DMP component(s) apply best to the text?  
 2. To what extent is the information provided in the DMP sufficient to ensure that the research team will manage data as expected? 
 3. Could the provided answer be improved? How?

You can have a look at the extended evaluation criteria here: [10.5281/zenodo.4915861](https://doi.org/10.5281/zenodo.4915861)

Once you have completed your review, please send it to [rdmtraining4nfdi-orga@lists.nfdi.de](rdmtraining4nfdi-orga@lists.nfdi.de) 

**Exercise 1a**

**Text A**

Bristol’s Research Data Storage Facility (RDSF) will be used to store the data during the project. The facility represents 2 million pounds of digital resilient storage, with ongoing capital investment. Backup procedures are robust and secured access is in place.

Recordings made in the field will be copied to the RDSF via a secure web connection, by the PI, as soon as possible, but some delays are expected due to Sri Lankan facilities. These will remain the responsibility of the PI and filmmaker (each will be carried separately). Checking the quality of recordings made and photographs taken each day will be the responsibility of the PI.

**Exercise 1b**

**Text B**

Upon completion of the project the digital outputs of the project will be migrated to open standards for preservation. Outputs will be tagged with appropriate metadata to facilitate their discoverability. Long-term preservation of digital data is a considerable challenge; however, how best to preserve digital data is not the focus of this project and other projects within our partner institutions are already making significant progress in how this issue can be addressed.

**Exercise 1c**

**Text C**

The project will leverage existing metadata standards currently stored in Ecological Metadata Language (EML) format. We will add additional metadata entries for the arthropod community composition and arthropod stoichiometry; field notes taken during the time of collection will be recorded. Morpho software will be used to generate the metadata file in EML. We chose EML format for our metadata since it allows integration with existing NutNet data housed in the Knowledge Network for Biocomplexity (KNB) data repository. After publication of manuscripts based on the data we collect, we will share our data and metadata with the NutNet community. We will also submit both of our datasets (abundance and stoichiometry) to the {}, an archive for digital preservation. This will occur within a year of publication. 

# 2. DMP Templates : A deep dive

## General templates (EU/Germany)

As already mentioned, writing DMPs is becoming a mandatory requirement for researchers applying to funding agencies. Publicly available DMPs can serve as inspiration when developing a DMP for a research project, but researchers can also find templates, guidelines or checklists at their disposal from major funding bodies. These prescribe a specific structure or recommend a particular order.

Some examples:

 - **Horizon Europe Template:** The European Commission has created a DMP template for the Horizon Europe (2021-2027) funding programm. The template is strongly oriented towards the FAIR principles, and its use is not mandatory. However, the [Horizon Europe Model Grant Agreement](https://ec.europa.eu/info/funding-tenders/opportunities/docs/2021-2027/common/agr-contr/general-mga_horizon-euratom_en.pdf) requires that a DMP is established and regularly updated.

    - Horizon Europe Template: https://www.openaire.eu/images/Guides/HORIZON_EUROPE_Data-Management-Plan-Template.pdf 

 - **Science Europe Guide:**  This guide presents core requirements for DMPs, and how researchers can translate those requirements into a DMP template. It also provides criteria for the selection of trustworthy repositories, and a DMP evaluation rubric to support DMP reviewers.

    - DOI: [10.5281/zenodo.4915861](https://doi.org/10.5281/zenodo.4915861)

 - **DFG Checklist:** The Deutsche Forschungsgemeinschaft (DFG) has drawn up a detailed checklist for handling research data. The DFG and the reviewers it commissions pay very close attention to comprehensible and, in particular, reliable information on this topic in funding applications. 

    - DFG Checklist: https://www.dfg.de/resource/blob/174736/forschungsdaten-checkliste-en.pdf

## Discipline specific templates (NFDI)

Templates, guidelines, text modules and sample DMPs should always be understood as guidance. It is advisable to adapt them to discipline, project specifics and local conditions.
Some NFDI consortia have already created DMP templates optimized for the special requirements of their communities. Here some examples:

 - NFDI4Microbiota

   - DOI: [10.5281/zenodo.13628588](https://doi.org/10.5281/zenodo.13628588)

 - NFDI4Health

   - DOI: [10.4126/FRL01-006483994](https://doi.org/10.4126/FRL01-006483994)
   - DOI: [10.4126/FRL01-006483995](https://doi.org/10.4126/FRL01-006483995) 

 - NFDI4Chem

   - DOI: [10.5281/zenodo.10948509](https://doi.org/10.5281/zenodo.10948509)

⚠️ Adapting general templates, checklists or guidelines to the needs of a specific discipline or research community can be challenging. Some templates are too extensive and not always relevant. Others have gaps or lack clarification on highly relevant topics for the discipline, such as data protection and legal aspects. Consequently, researchers may experience difficulties and therefore be reluctant to complete DMPs based on such templates. 

## Exercise 2 

**Exercise 2a**

**Exploring DMP templates in your community**

 1. **Are there DMP templates tailored to the specific requirements of your consortium or discipline?**
   
    - **Yes:** Compare your template with those from other NFDI consortia linked below. What similarities and differences do you notice?
    - **No:** Review DMP templates from other NFDI consortia and identify 3–5 questions that do not fit your discipline. Why are they not suitable?
 2. If you were to create a DMP template for your consortium, 

    - How would you approach it? 
    - Who could you collaborate with to identify what is most important for your research community?

**DMP Templates developed by NFDI**

| **NFDI4Microbiota** | **NFDI4Chem** | **NFDI4Health** |
|--------------------|---------------------|---------------------|
|DOI: [10.5281/zenodo.13628588](https://doi.org/10.5281/zenodo.13628588)|DOI [10.5281/zenodo.10948509](https://doi.org/10.5281/zenodo.10948509)|DOI: [10.4126/FRL01-006483994](https://doi.org/10.4126/FRL01-006483994)<br><br>DOI: [10.4126/FRL01-006483995](https://doi.org/10.4126/FRL01-006483995)|

**Exercise 2b**

**Exploring automation**

Traditional DMPs can feel time-consuming and bureaucratic for researchers. However, when they become machine-actionable ([maDMPs](https://doi.org/10.1371/journal.pcbi.1006750)) and connect with researchers’ everyday tools, such as electronic laboratory notebooks (ELNs) or Persistent Identifiers (PIDs), parts of the plan can be automatically generated, updated, and shared.

 - **Which types of information, services, or tools could be automated or integrated into a DMP template within your consortium or research discipline to better support researchers?**

# 3. Best practices...
## ... for DMP Template Creation

Creating effective DMP templates requires balancing community needs, technical integration, and long-term sustainability. The following best practices draw on experiences and reflections shared by research data professionals who have worked on designing or improving DMP templates within their consortia.

**🏗️ Build on Shared Foundations**

 - Start with existing frameworks, such as established checklists or funder requirements, to ensure compliance and consistency.
 - Use common tools (for example, RDMO) as a central integration point that can connect with other systems and services.
 - Encourage collaboration between central RDM service units and research teams to align institutional and disciplinary perspectives.

**🛠️Adapt to Disciplinary Contexts**

 - Tailor the DMP template to reflect the specific data types, metadata standards, and repository options relevant to your field.
 - Keep the structure flexible—some sections may need to be optional or adapted depending on the research context.
 - Recognize that terminology matters: if “DMP” is not familiar in your community, link it to existing documentation or planning practices.

**🔄 Foster Iteration and Collaboration**

 - Regularly review and update DMP templates based on community feedback and evolving standards.
 - Collaborate with other research communities to share lessons learned and identify overlapping requirements.
 - Use evaluation of existing templates to guide improvements and promote interoperability.

 > 💡 Tip: The Basic Service DMP4NFDI supports NFDI consortia in providing a DMP service to their community. Their services include…<br><br> - …hosting RDMO for your consortium,<br><br>- …supporting the creation of DMP Templates aligned with international standards,<br><br>- …helping you raise awareness of DMPs within your consortium<br><br>- …supporting the integration of RDMO with other tools and service <br><br>Interested? Learn more and get in touch:  https://dmp.services.base4nfdi.de/

## ... for DMP support

Providing effective support for researchers in completing and maintaining DMPs goes beyond sharing templates. It involves communication, engagement, and institutional coordination. The following best practices can help you offer meaningful guidance and foster adoption of DMPs within your community.

**💬Support = Communication + Coordination**

 - Expect that 50–60% of your effort may go into communication tasks, including emails, meetings, and reminders.
 - Schedule smartly: Offer only 1–2 time options to avoid endless coordination.
 - Offer hands-on support: Helping researchers fill out a DMP can be more impactful than distributing written guidance alone.

**🤝Building Trust and Engagement**

 - Highlight how DMPs help researchers document for their future selves. 
 - Find ways to connect DMPs to everyday workflows, such as laboratory notebooks, project management tools, or data repositories, to reduce duplication and workload. 
 - Address real concerns with practical solutions (e.g. data sharing anxiety? → embargos are possible).
 - Frame DMPs as the future norm: “This is becoming standard practice”. If possible,  provide concrete examples of good practice and demonstrate how well-designed DMPs improve data quality, discoverability, and re-use.

**🏛️Activate Institutional Support Networks**

 - Get leadership support (e.g. principal investigators) to ensure continuity and legitimacy. 
 - Encourage researchers to reach out to library (UB) teams, they offer long-term support and continuity across changing roles.
 - Do you have research experience? Use it to help build credibility and relate to disciplinary challenges.

# 4. Facilitating DMP Learning

## Training with Impact

Effective DMP training goes beyond simply presenting information. Consider these approaches:

 1. **Integrate DMPs into broader RDM topics**

   - Embed DMP questions within wider research data management topics, such as data publication, anonymisation, or sharing practices.
   - Show how DMPs connect to everyday research workflows rather than treating them as isolated tasks, e.g. simplifying reporting, or facilitating collaboration among stakeholders.

 2. **Use storytelling to engage**

   - Illustrate concepts with real-life examples or “horror stories” of projects without DMPs, followed by lessons learned.
   - Storytelling helps clarify concepts and demonstrates the practical value of good data management.

 3. **Highlight key or challenging components early**

   - Identify DMP elements that are particularly important or difficult in your discipline, such as defining a “dataset” or handling sensitive data.
   - Address these components early to build confidence and understanding.

 4. **Go beyond surface-level questions**

   - Challenge researchers with meaningful, thought-provoking questions rather than simple checklists.
   - Encourage reflection and discussion to deepen understanding and foster better data management practices.

## Exercise 3

**Designing a DMP workshop**

Without clearly defined objectives, a workshop risks losing its purpose and impact. Your objectives act as a guiding star, helping you make informed decisions about content preparation and logistical planning. Equally important is understanding your target audience: knowing what they already know, what interests them, and what challenges they face allows you to tailor your content and interactions to their needs.

 1. **Review existing learning objectives for DMPs**

    - Explore the learning objectives for each level of the DMP module from the DMP4NFDI Train-the-Trainer concept. 

**DMP4NFDI Train-the-Trainer concept**

**Module:** Data Management Plans

| Level         | Learning objectives |
|----------------|--------------------|
| **Fundamentals** | Participants should be able to...  <br> • demonstrate and communicate the relevance and components of a DMP  <br> • identify relevant funding institutions and their requirements with respect to DMPs  <br> • write DMPs under guidance |
|                | • recognise the relevance of maDMPs |
| **Advanced** | Participants should be able to...  <br> • discuss and analyse the application of both DMPs and maDMPs  <br> • compare and tailor funder requirements to domain-specific needs — i.e. first steps in creating DMP templates  <br> • write DMPs independently  <br> • support researchers writing DMPs — e.g. evaluate the completeness and accuracy of answers |
| **Experts** | Participants should be able to...  <br> • identify and demonstrate good DMP practices, aligning requirements with real-world workflows  <br> • independently create DMP templates tailored to domain-specific needs  <br> • name DMP networks for idea exchange and support  <br> • design and deliver didactic scenarios to train and empower researchers |

 2. **Adapt and apply**

    - Collect those learning objectives relevant for a discipline-specific DMP course or training session you might offer. You can adapt them to your needs where necessary or add new ones.
    - Develop a short teaching script or outline showing how each learning objective will be addressed during your workshop. 

Teaching script example

|Unit|Content (working method)|Objective|Instruction|
|--------------------|---------------------|---------------------|---------------------|
|1. Presentation|1. Name <br>participants<br> (Talk) |The participants overcome their inhibitions to speak|Task: Participants state their names|

Send your teaching script or outline to [rdmtraining4nfdi-orga@lists.nfdi.de](rdmtraining4nfdi-orga@lists.nfdi.de) to receive feedback

>💡 Tip: Focus on aligning your teaching activities with the objectives. Each objective should have a clear plan for how participants will engage with and achieve it.
