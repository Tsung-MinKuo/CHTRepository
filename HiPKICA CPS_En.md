# Chunghwa Telecom HiPKI Certification Authority Certificate Policy/Certification Practice Statement (HiPKICA CP/CPS)


- **Version: 1.3**


- **Chunghwa Telecom Co., Ltd.**
- **Publication date: September 14, 2026**

## Contents

- [1. Introduction](#1-introduction)
  - [1.1 Overview](#11-overview)
    - [1.1.1 This CP/CPS Applicability](#111-this-cpcps-applicability)
    - [1.1.2 Certificate Policy Object Identifiers cited by Certification Authority](#112-certificate-policy-object-identifiers-cited-by-certification-authority)
  - [1.2 Document Name and Identification](#12-document-name-and-identification)
  - [1.3 PKI Participants](#13-pki-participants)
    - [1.3.1 Certification Authorities](#131-certification-authorities)
    - [1.3.2 Registration Authorities](#132-registration-authorities)
    - [1.3.3 Subscribers](#133-subscribers)
    - [1.3.4 Relying Parties](#134-relying-parties)
    - [1.3.5 Other Participants](#135-other-participants)
  - [1.4 Certificate Usage](#14-certificate-usage)
    - [1.4.1 Appropriate Certificate Uses](#141-appropriate-certificate-uses)
    - [1.4.2 Prohibited Certificate Uses](#142-prohibited-certificate-uses)
  - [1.5 Policy Administration](#15-policy-administration)
    - [1.5.1 Organization Administering the Document](#151-organization-administering-the-document)
    - [1.5.2 Contact Person](#152-contact-person)
    - [1.5.3 Person Determining CP/CPS Suitability for the Policy](#153-person-determining-cpcps-suitability-for-the-policy)
    - [1.5.4 CPS Approval Procedures](#154-cps-approval-procedures)
  - [1.6 Definitions and Acronyms](#16-definitions-and-acronyms)
- [2. Publication and Repository Responsibilities](#2-publication-and-repository-responsibilities)
  - [2.1 Repositories](#21-repositories)
  - [2.2 Publication of Certification Information](#22-publication-of-certification-information)
  - [2.3 Time or Frequency of Publication](#23-time-or-frequency-of-publication)
  - [2.4 Access Controls on Repositories](#24-access-controls-on-repositories)
- [3. Identification and Authentication](#3-identification-and-authentication)
  - [3.1 Naming](#31-naming)
    - [3.1.1 Types of Names](#311-types-of-names)
    - [3.1.2 Need for Names to be Meaningful](#312-need-for-names-to-be-meaningful)
    - [3.1.3 Anonymity or Psuedonymity of Subscribers](#313-anonymity-or-psuedonymity-of-subscribers)
    - [3.1.4 Rules for Interpreting Various Name Forms](#314-rules-for-interpreting-various-name-forms)
    - [3.1.5 Uniqueness of Names](#315-uniqueness-of-names)
    - [3.1.6 Recognition, Authentication, and Role of Trademarks](#316-recognition-authentication-and-role-of-trademarks)
  - [3.2 Initial Identity Validation](#32-initial-identity-validation)
    - [3.2.1 Method to Prove Possession of Private Key](#321-method-to-prove-possession-of-private-key)
    - [3.2.2 Authentication of Organization Identity](#322-authentication-of-organization-identity)
    - [3.2.3 Authentication of Individual Identity](#323-authentication-of-individual-identity)
    - [3.2.4 Non-verified Subscriber Information](#324-non-verified-subscriber-information)
    - [3.2.5 Validation of Authority](#325-validation-of-authority)
    - [3.2.6 Criteria for Interoperation](#326-criteria-for-interoperation)
    - [3.2.7 Validation of Domain Authorization or Control](#327-validation-of-domain-authorization-or-control)
    - [3.2.8 Validation of Wildcard Domains](#328-validation-of-wildcard-domains)
    - [3.2.9 Data Source Accuracy](#329-data-source-accuracy)
    - [3.2.10 Multi-Perspective Issuance Corroboration](#3210-multi-perspective-issuance-corroboration)
  - [3.3 Identification and Authentication for Re-key Requests](#33-identification-and-authentication-for-re-key-requests)
    - [3.3.1 Identification and Authentication for Routine Re-key](#331-identification-and-authentication-for-routine-re-key)
    - [3.3.2 Identification and Authentication for Re-key after Revocation](#332-identification-and-authentication-for-re-key-after-revocation)
  - [3.4 Identification and Authentication for Revocation Request](#34-identification-and-authentication-for-revocation-request)
- [4. Certificate Life-cycle Operational Requirements](#4-certificate-life-cycle-operational-requirements)
  - [4.1 Certificate Application](#41-certificate-application)
    - [4.1.1 Who Can Submit a Certificate Application](#411-who-can-submit-a-certificate-application)
    - [4.1.2 Enrollment Process and Responsibilities](#412-enrollment-process-and-responsibilities)
  - [4.2 Certificate Application Processing](#42-certificate-application-processing)
    - [4.2.1 Performing Identification and Authentication Functions](#421-performing-identification-and-authentication-functions)
    - [4.2.2 Approval or Rejection of Certificate Applications](#422-approval-or-rejection-of-certificate-applications)
    - [4.2.3 Time to Process Certificate Applications](#423-time-to-process-certificate-applications)
  - [4.3 Certificate Issuance](#43-certificate-issuance)
    - [4.3.1 CA Actions during Certificate Issuance](#431-ca-actions-during-certificate-issuance)
    - [4.3.2 Notification to Subscriber by the CA of Issuance of Certificate](#432-notification-to-subscriber-by-the-ca-of-issuance-of-certificate)
  - [4.4 Certificate Acceptance](#44-certificate-acceptance)
    - [4.4.1 Conduct Constituting Certificate Acceptance](#441-conduct-constituting-certificate-acceptance)
    - [4.4.2 Publication of the Certificate by the CA](#442-publication-of-the-certificate-by-the-ca)
    - [4.4.3 Notification of Certificate Issuance by the CA to Other Entities](#443-notification-of-certificate-issuance-by-the-ca-to-other-entities)
  - [4.5 Key Pair and Certificate Usage](#45-key-pair-and-certificate-usage)
    - [4.5.1 Subscriber Private Key and Certificate Usage](#451-subscriber-private-key-and-certificate-usage)
    - [4.5.2 Relying Party Public Key and Certificate Usage](#452-relying-party-public-key-and-certificate-usage)
  - [4.6 Certificate Renewal](#46-certificate-renewal)
    - [4.6.1 Circumstances for Certificate Renewal](#461-circumstances-for-certificate-renewal)
    - [4.6.2 Who May Request Renewal](#462-who-may-request-renewal)
    - [4.6.3 Processing Certificate Renewal Requests](#463-processing-certificate-renewal-requests)
    - [4.6.4 Notification of New Certificate Issuance to Subscriber](#464-notification-of-new-certificate-issuance-to-subscriber)
    - [4.6.5 Conduct Constituting Acceptance of a Renewal Certificate](#465-conduct-constituting-acceptance-of-a-renewal-certificate)
    - [4.6.6 Publication of the Renewal Certificate by the CA](#466-publication-of-the-renewal-certificate-by-the-ca)
    - [4.6.7 Notification of Certificate Issuance by the CA to Other Entities](#467-notification-of-certificate-issuance-by-the-ca-to-other-entities)
  - [4.7 Certificate Re-Key](#47-certificate-re-key)
    - [4.7.1 Circumstance for Certificate Re-key](#471-circumstance-for-certificate-re-key)
    - [4.7.2 Who May Request Certification of a New Public Key](#472-who-may-request-certification-of-a-new-public-key)
    - [4.7.3 Processing Certificate Re-keying Requests](#473-processing-certificate-re-keying-requests)
    - [4.7.4 Notification of New Certificate Issuance to Subscriber](#474-notification-of-new-certificate-issuance-to-subscriber)
    - [4.7.5 Conduct Constituting Acceptance of a Re-keyed Certificate](#475-conduct-constituting-acceptance-of-a-re-keyed-certificate)
    - [4.7.6 Publication of the Re-keyed Certificate by the CA](#476-publication-of-the-re-keyed-certificate-by-the-ca)
    - [4.7.7 Notification of Certificate Issuance by the CA to Other Entities](#477-notification-of-certificate-issuance-by-the-ca-to-other-entities)
  - [4.8 Certificate Modification](#48-certificate-modification)
    - [4.8.1 Circumstance for Certificate Modification](#481-circumstance-for-certificate-modification)
    - [4.8.2 Who May Request Certificate Modification](#482-who-may-request-certificate-modification)
    - [4.8.3 Processing Certificate Modification Requests](#483-processing-certificate-modification-requests)
    - [4.8.4 Notification of New Certificate Issuance to Subscriber](#484-notification-of-new-certificate-issuance-to-subscriber)
    - [4.8.5 Conduct Constituting Acceptance of Modified Certificate](#485-conduct-constituting-acceptance-of-modified-certificate)
    - [4.8.6 Publication of the Modified Certificate by the CA](#486-publication-of-the-modified-certificate-by-the-ca)
    - [4.8.7 Notification of Certificate Issuance by the CA to Other Entities](#487-notification-of-certificate-issuance-by-the-ca-to-other-entities)
  - [4.9 Certificate Revocation and Suspension](#49-certificate-revocation-and-suspension)
    - [4.9.1 Circumstances for Revocation](#491-circumstances-for-revocation)
    - [4.9.2 Who Can Request Revocation](#492-who-can-request-revocation)
    - [4.9.3 Procedure for Revocation Request](#493-procedure-for-revocation-request)
    - [4.9.4 Revocation Request Grace Period](#494-revocation-request-grace-period)
    - [4.9.5 Time within Which CA Must Process the Revocation Request](#495-time-within-which-ca-must-process-the-revocation-request)
    - [4.9.6 Revocation Checking Requirement for Relying Parties](#496-revocation-checking-requirement-for-relying-parties)
    - [4.9.7 CRL Issuance Frequency](#497-crl-issuance-frequency)
    - [4.9.8 Maximum Latency for CRLs](#498-maximum-latency-for-crls)
    - [4.9.9 On-line Revocation/Status Checking Availability](#499-on-line-revocationstatus-checking-availability)
    - [4.9.10 On-line Revocation Checking Requirements](#4910-on-line-revocation-checking-requirements)
    - [4.9.11 Other Forms of Revocation Advertisements Available](#4911-other-forms-of-revocation-advertisements-available)
    - [4.9.12 Special Requirements Related to Key Compromise](#4912-special-requirements-related-to-key-compromise)
    - [4.9.13 Circumstances for Suspension](#4913-circumstances-for-suspension)
    - [4.9.14 Who Can Request Suspension](#4914-who-can-request-suspension)
    - [4.9.15 Procedure for Suspension Request](#4915-procedure-for-suspension-request)
    - [4.9.16 Limits on Suspension Period](#4916-limits-on-suspension-period)
    - [4.9.17 Procedure for Certificate Resumption](#4917-procedure-for-certificate-resumption)
  - [4.10 Certificate Status Services](#410-certificate-status-services)
    - [4.10.1 Operational Characteristics](#4101-operational-characteristics)
    - [4.10.2 Service Availability](#4102-service-availability)
    - [4.10.3 Optional Features](#4103-optional-features)
  - [4.11 End of Subscription](#411-end-of-subscription)
  - [4.12 Key Escrow and Recovery](#412-key-escrow-and-recovery)
    - [4.12.1 Key Escrow and Recovery Policy and Practices](#4121-key-escrow-and-recovery-policy-and-practices)
    - [4.12.2 Session Key Encapsulation and Recovery Policy and Practices](#4122-session-key-encapsulation-and-recovery-policy-and-practices)
- [5. Facility, Management, and Operation Controls](#5-facility-management-and-operation-controls)
  - [5.1 Physical Controls](#51-physical-controls)
    - [5.1.1 Site Location and Construction](#511-site-location-and-construction)
    - [5.1.2 Physical Access](#512-physical-access)
    - [5.1.3 Power and Air Conditioning](#513-power-and-air-conditioning)
    - [5.1.4 Water Exposures](#514-water-exposures)
    - [5.1.5 Fire Prevention and Protection](#515-fire-prevention-and-protection)
    - [5.1.6 Media Storage](#516-media-storage)
    - [5.1.7 Waste Disposal](#517-waste-disposal)
    - [5.1.8 Off-site Backup](#518-off-site-backup)
  - [5.2 Procedural Controls](#52-procedural-controls)
    - [5.2.1 Trusted Roles](#521-trusted-roles)
    - [5.2.2 Number of Persons Required per Task](#522-number-of-persons-required-per-task)
    - [5.2.3 Identification and Authentication for Each Role](#523-identification-and-authentication-for-each-role)
    - [5.2.4 Roles Requiring Separation of Duties](#524-roles-requiring-separation-of-duties)
  - [5.3 Personnel Controls](#53-personnel-controls)
    - [5.3.1 Qualifications, Experience, and Clearance Requirements](#531-qualifications-experience-and-clearance-requirements)
    - [5.3.2 Background Check Procedures](#532-background-check-procedures)
    - [5.3.3 Training Requirements](#533-training-requirements)
    - [5.3.4 Retraining Frequency and Requirements](#534-retraining-frequency-and-requirements)
    - [5.3.5 Job Rotation Frequency and Sequence](#535-job-rotation-frequency-and-sequence)
    - [5.3.6 Sanctions for Unauthorized Actions](#536-sanctions-for-unauthorized-actions)
    - [5.3.7 Independent Contractor Requirements](#537-independent-contractor-requirements)
    - [5.3.8 Documentation Supplied to Personnel](#538-documentation-supplied-to-personnel)
  - [5.4 Audit Logging Procedures](#54-audit-logging-procedures)
    - [5.4.1 Types of Events Recorded](#541-types-of-events-recorded)
    - [5.4.2 Frequency of Processing Log](#542-frequency-of-processing-log)
    - [5.4.3 Retention Period for Audit Log](#543-retention-period-for-audit-log)
    - [5.4.4 Protection of Audit Log](#544-protection-of-audit-log)
    - [5.4.5 Audit Log Backup Procedures](#545-audit-log-backup-procedures)
    - [5.4.6 Audit Collection System (Internal vs. External)](#546-audit-collection-system-internal-vs-external)
    - [5.4.7 Notification to Event-causing Subject](#547-notification-to-event-causing-subject)
    - [5.4.8 Vulnerability Assessments](#548-vulnerability-assessments)
  - [5.5 Records Archival](#55-records-archival)
    - [5.5.1 Types of Records Archived](#551-types-of-records-archived)
    - [5.5.2 Retention Period for Archive](#552-retention-period-for-archive)
    - [5.5.3 Protection of Archive](#553-protection-of-archive)
    - [5.5.4 Archive Backup Procedures](#554-archive-backup-procedures)
    - [5.5.5 Requirements for Time-stamping of Records](#555-requirements-for-time-stamping-of-records)
    - [5.5.6 Archive Collection System (Internal or External)](#556-archive-collection-system-internal-or-external)
    - [5.5.7 Procedures to Obtain and Verify Archive Information](#557-procedures-to-obtain-and-verify-archive-information)
  - [5.6 Key Changeover](#56-key-changeover)
  - [5.7 Compromise and Disaster Recovery](#57-compromise-and-disaster-recovery)
    - [5.7.1 Incident and Compromise Handling Procedures](#571-incident-and-compromise-handling-procedures)
    - [5.7.2 Computing Resources, Software, and/or Data Are Corrupted](#572-computing-resources-software-andor-data-are-corrupted)
    - [5.7.3 Entity Private Key Compromise Procedures](#573-entity-private-key-compromise-procedures)
    - [5.7.4 Business Continuity Capabilities after a Disaster](#574-business-continuity-capabilities-after-a-disaster)
  - [5.8 CA or RA Termination](#58-ca-or-ra-termination)
- [6. Technical Security Controls](#6-technical-security-controls)
  - [6.1 Key Pair Generation and Installation](#61-key-pair-generation-and-installation)
    - [6.1.1 Key Pair Generation](#611-key-pair-generation)
    - [6.1.2 Private Keys Delivery to Subscriber](#612-private-keys-delivery-to-subscriber)
    - [6.1.3 Public Key Delivery to Certificate Issuer](#613-public-key-delivery-to-certificate-issuer)
    - [6.1.4 CA Public Key Delivery to Relying Parties](#614-ca-public-key-delivery-to-relying-parties)
    - [6.1.5 Key Sizes](#615-key-sizes)
    - [6.1.6 Public Key Parameters Generation and Quality Checking](#616-public-key-parameters-generation-and-quality-checking)
    - [6.1.7 Key Usage Purposes (as per X.509 v3 Key Usage Field)](#617-key-usage-purposes-as-per-x509-v3-key-usage-field)
  - [6.2 Private Key Protection and Cryptographic Module Engineering Controls](#62-private-key-protection-and-cryptographic-module-engineering-controls)
    - [6.2.1 Cryptographic Module Standards and Controls](#621-cryptographic-module-standards-and-controls)
    - [6.2.2 Private Key (n-out-of-m) Multi-person Control](#622-private-key-n-out-of-m-multi-person-control)
    - [6.2.3 Private Key Escrow](#623-private-key-escrow)
    - [6.2.4 Private Key Backup](#624-private-key-backup)
    - [6.2.5 Private Key Archival](#625-private-key-archival)
    - [6.2.6 Private Key Transfer into or from a Cryptographic Module](#626-private-key-transfer-into-or-from-a-cryptographic-module)
    - [6.2.7 Private Key Storage on Cryptographic Module](#627-private-key-storage-on-cryptographic-module)
    - [6.2.8 Method of Activating Private Key](#628-method-of-activating-private-key)
    - [6.2.9 Method of Deactivating Private Key](#629-method-of-deactivating-private-key)
    - [6.2.10 Method of Destroying Private Key](#6210-method-of-destroying-private-key)
    - [6.2.11. Cryptographic Module Rating](#6211-cryptographic-module-rating)
  - [6.3 Other Aspects of Key Pair Management](#63-other-aspects-of-key-pair-management)
    - [6.3.1 Public Key Archival](#631-public-key-archival)
    - [6.3.2 Certificate Operational Periods and Key Pair Usage Periods](#632-certificate-operational-periods-and-key-pair-usage-periods)
  - [6.4 Activation Data](#64-activation-data)
    - [6.4.1 Activation Data Generation and Installation](#641-activation-data-generation-and-installation)
    - [6.4.2 Activation Data Protection](#642-activation-data-protection)
    - [6.4.3 Other Aspects of Activation Data](#643-other-aspects-of-activation-data)
  - [6.5 Computer Security Controls](#65-computer-security-controls)
    - [6.5.1 Specific Computer Security Technical Requirements](#651-specific-computer-security-technical-requirements)
    - [6.5.2 Computer Security Rating](#652-computer-security-rating)
    - [6.5.3 CA Infrastructure Inventory](#653-ca-infrastructure-inventory)
  - [6.6 Life Cycle Technical Controls](#66-life-cycle-technical-controls)
    - [6.6.1 System Development Controls](#661-system-development-controls)
    - [6.6.2 Security Management Controls](#662-security-management-controls)
    - [6.6.3 Life Cycle Security Controls](#663-life-cycle-security-controls)
  - [6.7 Network Security Controls](#67-network-security-controls)
  - [6.8 Time-stamping](#68-time-stamping)
- [7. Certificate, CRL, and OCSP Profiles](#7-certificate-crl-and-ocsp-profiles)
  - [7.1 Certificate Profile](#71-certificate-profile)
    - [7.1.1 Version Number(s)](#711-version-numbers)
    - [7.1.2 Certificate Extensions](#712-certificate-extensions)
    - [7.1.3 Algorithm Object Identifiers](#713-algorithm-object-identifiers)
    - [7.1.4 Name Forms](#714-name-forms)
    - [7.1.5 Name Constraints](#715-name-constraints)
    - [7.1.6 Certificate Policy Object Identifier](#716-certificate-policy-object-identifier)
    - [7.1.7 Usage of Policy Constraints Extension](#717-usage-of-policy-constraints-extension)
    - [7.1.8 Policy Qualifiers Syntax and Semantics](#718-policy-qualifiers-syntax-and-semantics)
    - [7.1.9 Processing Semantics for the Critical Certificate Policies Extension](#719-processing-semantics-for-the-critical-certificate-policies-extension)
  - [7.2 CRL Profile](#72-crl-profile)
    - [7.2.1 Version Number(s)](#721-version-numbers)
    - [7.2.2 CRL and CRL Entry Extensions](#722-crl-and-crl-entry-extensions)
  - [7.3 OCSP Profile](#73-ocsp-profile)
    - [7.3.1 Version Number(s)](#731-version-numbers)
    - [7.3.2 OCSP Extensions](#732-ocsp-extensions)
- [8. Compliance Audit and Other Assessments](#8-compliance-audit-and-other-assessments)
  - [8.1 Frequency or Circumstances of Assessment](#81-frequency-or-circumstances-of-assessment)
  - [8.2 Identity/Qualifications of Assessor](#82-identityqualifications-of-assessor)
  - [8.3 Assessor’s Relationship to Assessed Entity](#83-assessors-relationship-to-assessed-entity)
  - [8.4 Topics Covered by Assessment](#84-topics-covered-by-assessment)
  - [8.5 Actions Taken as a Result of Deficiency](#85-actions-taken-as-a-result-of-deficiency)
  - [8.6 Communications of Results](#86-communications-of-results)
  - [8.7 Self Audits](#87-self-audits)
- [9. Other Business and Legal Matters](#9-other-business-and-legal-matters)
  - [9.1 Fees](#91-fees)
    - [9.1.1 Certificate Issuance or Renewal Fees](#911-certificate-issuance-or-renewal-fees)
    - [9.1.2 Certificate Access Fees](#912-certificate-access-fees)
    - [9.1.3 Revocation or Status Information Access Fees](#913-revocation-or-status-information-access-fees)
    - [9.1.4 Fees for Other Services](#914-fees-for-other-services)
    - [9.1.5 Refund Policy](#915-refund-policy)
  - [9.2 Financial Responsibility](#92-financial-responsibility)
    - [9.2.1 Insurance Coverage](#921-insurance-coverage)
    - [9.2.2 Other Assets](#922-other-assets)
    - [9.2.3 Insurance or Warranty Coverage for End‐Entities](#923-insurance-or-warranty-coverage-for-endentities)
  - [9.3 Confidentiality of Business Information](#93-confidentiality-of-business-information)
    - [9.3.1 Scope of Confidential Information](#931-scope-of-confidential-information)
    - [9.3.2 Information Not Within the Scope of Confidential Information](#932-information-not-within-the-scope-of-confidential-information)
    - [9.3.3 Responsibility to Protect Confidential Information](#933-responsibility-to-protect-confidential-information)
  - [9.4 Privacy of Personal Information](#94-privacy-of-personal-information)
    - [9.4.1 Privacy Plan](#941-privacy-plan)
    - [9.4.2 Information Treated as Private](#942-information-treated-as-private)
    - [9.4.3 Information Not Deemed Private](#943-information-not-deemed-private)
    - [9.4.4 Responsibility to Protect Private Information](#944-responsibility-to-protect-private-information)
    - [9.4.5 Notice and Consent to Use Private Information](#945-notice-and-consent-to-use-private-information)
    - [9.4.6 Disclosure Pursuant to Judicial or Administrative Process](#946-disclosure-pursuant-to-judicial-or-administrative-process)
    - [9.4.7 Other Information Disclosure Circumstances](#947-other-information-disclosure-circumstances)
  - [9.5 Intellectual Property Rights](#95-intellectual-property-rights)
  - [9.6 Representations and Warranties](#96-representations-and-warranties)
    - [9.6.1 CA Representations and Warranties](#961-ca-representations-and-warranties)
    - [9.6.2 RA Representations and Warranties](#962-ra-representations-and-warranties)
    - [9.6.3 Subscriber Representations and Warranties](#963-subscriber-representations-and-warranties)
    - [9.6.4 Relying Party Representations and Warranties](#964-relying-party-representations-and-warranties)
    - [9.6.5 Representations and Warranties of Other Participants](#965-representations-and-warranties-of-other-participants)
  - [9.7 Disclaimers of Warranties](#97-disclaimers-of-warranties)
  - [9.8 Limitations of Liability](#98-limitations-of-liability)
  - [9.9 Indemnities](#99-indemnities)
    - [9.9.1 Indemnification by HiPKICA](#991-indemnification-by-hipkica)
    - [9.9.2 Indemnification by RA](#992-indemnification-by-ra)
  - [9.10 Term and Termination](#910-term-and-termination)
    - [9.10.1 Term](#9101-term)
    - [9.10.2 Termination](#9102-termination)
    - [9.10.3 Effect of Termination and Survival](#9103-effect-of-termination-and-survival)
  - [9.11 Individual Notices and Communications with Participants](#911-individual-notices-and-communications-with-participants)
  - [9.12 Amendments](#912-amendments)
    - [9.12.1 Procedure for Amendment](#9121-procedure-for-amendment)
    - [9.12.2 Notification Mechanism and Period](#9122-notification-mechanism-and-period)
    - [9.12.3 Circumstances under which OID Must Be Changed](#9123-circumstances-under-which-oid-must-be-changed)
  - [9.13 Dispute Resolution Provisions](#913-dispute-resolution-provisions)
  - [9.14 Governing Law](#914-governing-law)
  - [9.15 Compliance with Applicable Law](#915-compliance-with-applicable-law)
  - [9.16 Miscellaneous Provisions](#916-miscellaneous-provisions)
    - [9.16.1 Entire Agreement](#9161-entire-agreement)
    - [9.16.2 Assignment](#9162-assignment)
    - [9.16.3 Severability](#9163-severability)
    - [9.16.4 Enforcement (Attorney’s Fees and Waiver of Rights)](#9164-enforcement-attorneys-fees-and-waiver-of-rights)
    - [9.16.5 Force Majeure](#9165-force-majeure)
  - [9.17 Other Provisions](#917-other-provisions)
- [Appendix 1: Acronyms and Definitions](#appendix-1-acronyms-and-definitions)
- [Appendix 2: Glossary](#appendix-2-glossary)
- [Appendix 3: Certificate Profile Basic Fields and Extensions](#appendix-3-certificate-profile-basic-fields-and-extensions)
- [Appendix 3-1: CA Certificates](#appendix-3-1-ca-certificates)
- [Appendix 3-2: Subscriber Certificates](#appendix-3-2-subscriber-certificates)
- [Appendix 4: HiPKI CA Certificate List](#appendix-4-hipki-ca-certificate-list)
- [Appendix 5: BRs-Section 1.2.1 Revisions](#appendix-5-brs-section-121-revisions)

## CPS Version Control
<table>
<colgroup>
<col style="width: 16%" />
<col style="width: 21%" />
<col style="width: 62%" />
</colgroup>
<thead>
<tr>
<th align="center">Version </th>
<th style="text-align: center;">Date </th>
<th style="text-align: center;">Revision Summary </th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">1.0 </td>
<td nowrap>August 18, 2025 </td>
<td><ol type="1">
<li>First Released.</li>
<li>To meet the basic requirements for re-inclusion of the TLS Root certificate, this document integrates the HiPKI CP and HiPKICA CPS.</li>
<li>In accordance with the requirements of the Baseline Requirements (BR) and Browser Root Programs, the validation methods specified in BR sections 3.2.2.4.2, 3.2.2.4.4, 3.2.2.4.13, and 3.2.2.4.14 have been removed.</li>
</ol></td>
</tr>
<tr>
<td align="center">1.05 </td>
<td nowrap>August 25, 2025 </td>
<td><ol type="1">
<li>To align with the production of our new CA key, Section 1.3.1 has been updated to include the CA names: CHT TrustRoot CA and CHT Trust TLS CA.</li>
<li>Appendix 4 has been updated to include certificate information for CHT TrustRoot CA - G1 and CHT Trust TLS CA - G1. </li>
</ol></td>
</tr>
<tr>
<td align="center">1.1 </td>
<td nowrap>March 06, 2026 </td>
<td><ol type="1">
<li>To comply with the requirements of the BR and Browser Root Program policies, amendments have been made to Sections 1.1, 3.2.7, 3.2.7.1, 3.2.7.2, 3.2.7.3, 3.2.7.4, 4.2.2, 5.7.1.1, 5.7.1.2, 5.7.2 and Appendix 2.</li>
<li>Additional amendments have been made to Sections 1.4.2, 5.2.2, 5.3.5, 6.3.2.1, 7.1.5, Appendix 3-1, Appendix 3-2 and Appendix 4. </li>
</ol></td>
</tr>
<tr>
<td align="center">1.2 </td>
<td nowrap>June 11, 2026 </td>
<td><ol type="1">
<li>In accordance with Root Program Policy requirements, fields and corresponding extension descriptions for CRLs issued by Root CAs and Subordinate CAs have been added, along with minor textual refinements. </li>
<li>The scope of revisions covers Sections 3.1.5, 4.2.1, 6.3.2.1, 6.7, 7.1, 7.1.3, 7.1.4.3, 7.2, 7.2.2, 7.3.1, Appendix 3, Appendix 3-1, Appendix 3-2, and Appendix 5. </li>
</ol></td>
</tr>
<tr>
<td align="center">1.3 </td>
<td nowrap>September 14, 2026 </td>
<td><ol type="1">
<li>Revised in accordance with the review comments received during the Apple Root Certificate Program inclusion review. The revised sections include 3.2.2, 3.2.5, 3.2.6, 4.3.1.1 (new), 4.3.1.2 (new), 4.3.1.3 (new), 4.9.1.1, 4.9.3, 4.9.7, 5.1.2, 6.5.1 (new), 6.5.3 (new), 6.7, and 9.6.3.</li>
<li>Other updated sections include 1.1, 1.2, 4.2.1, 4.9.10, 6.1.1, 6.1.2, 6.1.6, 6.2.6, 7.2.2, Appendix 1, Appendix 2 and Appendix 5.</li>
</ol></td>
</tr>

</tbody>
</table>

# 1. Introduction

HiPKI is established in conjunction with the policies of Chunghwa Telecom Co., Ltd. (CHT) to promote electronic services and to create a sound e-commerce infrastructure environment. This Certificate Policy/Certification Practices Statement (CP/CPS) defines the policies, principles and practices related to HiPKI’s certification services. Certificates issued by HiPKI are applicable to various applications of e-commerce and e-government to provide more secure, reliable, and fast network services.

## 1.1 Overview

Root Certification Authority is the top-level CA and trust anchor of HiPKI. Root CA must maintain a high level of credibility so that relying parties can directly trust its certificates. This CP/CPS uses the brand name of Chunghwa Telecom HiPKI Certification Authority (HiPKICA) to refer to the Root CAs and its subordinate CAs in HiPKI. Please refer to Section 1.3.1 for a CA list of HiPKICA.

This CP/CPS is based on the official versions of relevant international standards or specifications, such as:
<ol>
<li>The Internet Engineering Task Force (IETF) Request for Comments (RFC) 3647, RFC 5280, RFC 6960, RFC 6962, RFC 5019, RFC 8659;</li>
<li>ITU-T X.509;</li>
</ol>

and the latest published versions of the following policy documents:
<ol>
<li>Baseline Requirements for the Issuance and Management of Publicly-Trusted TLS Server Certificates (Baseline Requirements) and Network and Certificate System Security Requirements published by the CA/Browser Forum (https://www.cabforum.org);</li>

<li>Mozilla Root Store Policy;</li>

<li>Microsoft Trusted Root Program Requirements;</li>

<li>Apple Root Certificate Program Policy;</li>

<li>Common CA Database (CCADB) Policy; and</li>

<li>Google Chrome Root Program Policy,</li>
</ol>
which together serve as the operational basis for the CAs within HiPKI. <p>

HiPKICA adheres to the latest published versions of the Google Chrome Root Program Policy and the CCADB Policy. HiPKICA shall also ensure the continued compliance of its publicly trusted PKI hierarchies, subordinate Certification Authorities, and delegated third parties participating in its certificate services with the applicable requirements of those policies.

The SSL (Secure Sockets Layer) protocol has been replaced by the TLS (Transport Layer Security) protocol. Because SSL certificates and TLS certificates both refer to certificates that allow the TLS protocol to operate and comply with the X.509 standard, this CP/CPS uses the term”TLS certificate” to replac the previous widely used one “SSL certificate”.

### 1.1.1 This CP/CPS Applicability

The practice statement stipulated in this CP/CPS applies to HiPKICA, registration authority (RA), subscribers, relying parties, repository, and other participants.

### 1.1.2 Certificate Policy Object Identifiers cited by Certification Authority

The certification policy object identifier (CP OID, see Section 1.2) used in HiPKI is used by CAs to indicate the assurance level when issuing a certificate for a specific purpose. CAs can directly reference registered CP OIDs, and relying parties can verify the applicability of certificates issued by CAs through the CP OIDs.

According to ITU-T X.509, the assurance levels defined in this CP/CPS must be expressed with the CP OID, which will be listed in the certificatePolicies extension of certificates.

CAs in HiPKI shall include appropriate CP OIDs when issuing certificates, such that interoperation with CAs that issue under same policies will be performed through policy mapping; or further cross-domain interoperation will be performed between HiPKI and other external PKI entries through the same means. Policy mapping can be confirmed if the issuing CA and subject CA have included the same CP OID.

## 1.2 Document Name and Identification

This document is Chunghwa Telecom HiPKi Certification Authority Certification Practice Statement. This CP/CPS can be obtained at: <https://chtca.hinet.net/en/repository.html>

CAs of HiPKI should comply with this CP/CPS. HiPKI classifies the certificates issued by CAs into four assurance levels according to the authentication method and appropriate scope. The higher the assurance level, the higher the security, reliability, and the stricter the authentication method.

The following table provides a reference to the CP OIDs for the various types of certificates, assurance levels, and documents mentioned in this CP/CPS:

<table>
<colgroup>
<col style="width: 46%" />
<col style="width: 53%" />
</colgroup>
<thead>
<tr>
<th style="text-align: center;"><strong>Object Name</strong></th>
<th style="text-align: center;"><strong>OIDs</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td>HiPKI</td>
<td>1 3 6 1 4 1 23459 200 0</td>
</tr>
<tr>
<td>Assurance levels</td>
<td></td>
</tr>
<tr>
<td align="center">test</td>
<td>1 3 6 1 4 1 23459 200 0 0</td>
</tr>
<tr>
<td align="center">Level 1</td>
<td>1 3 6 1 4 1 23459 200 0 1</td>
</tr>
<tr>
<td align="center">Level 2</td>
<td>1 3 6 1 4 1 23459 200 0 2</td>
</tr>
<tr>
<td align="center">Level 3</td>
<td>1 3 6 1 4 1 23459 200 0 3</td>
</tr>
<tr>
<td align="center">Level 4</td>
<td>1 3 6 1 4 1 23459 200 0 4</td>
</tr>
<tr>
<td>Baseline Requirements</td>
<td></td>
</tr>
<tr>
<td align="center">OV TLS certificates</td>
<td>2.23.140.1.2.2</td>
</tr>
</tbody>
</table>

OIDs with a prefix of {2.23.140} are required by CA/Browser Forum, and the arc id-pen-cht ::= {1 3 6 1 4 1 23459} is a private enterprise number (PEN) registered in IANA by CHT. The OID for HiPKI is {1 3 6 1 4 1 23459 200}, which has been quoted to the OIDs of various assurance levels.

The Root CA certificate is a self-signed certificate. According to international standards and practices, the Root CA certificate does not indicate the CP OID to reflect its high credibility and was operated with assuance level 4.

The CA that issues TLS certificates adheres to the Baseline Requirements specification, and uses the CP OIDs, defined by the CA/Browser Forum, ({joint‐iso‐itu‐t(2) international‐organizations(23) ca‐browser‐forum(140) certificate‐ policies(1) baseline‐ requirements(2) organization-validated(2)} (2.23.140.1.2.2)) for organization validation (OV) TLS certificates.

With regard to TLS certificates, if there is any inconsistency between this CP/CPS and the official version of the Baseline Requirements, then the Baseline Requirements takes precedence.

If any part is not regulated under the documents of CA/Browser Forum, the rule of assurance level 3 is applicable for CAs that issue OV TLS certificates. For Root CAs that issue self-signed, self-issued, and cross-certified certificates, the rule of assurance level 4 is always applicable.

## 1.3 PKI Participants

The key members of HiPKICA include:
1)  CAs of HiPKICA
2)  RAs
3)  Subscribers
4)  Relying Parties

### 1.3.1 Certification Authorities

The following CAs of HiPKICA are established and operated by Chunghwa Telecom Co., Ltd. (CHT), the relevant operating guidelines described in this CP/CPS shall be submitted to the Chunghwa Telecom Certificate Policy Management Authority (PMA) for review and approval.

<table>
<tr>
<td colspan="2">
<strong>Root CA</strong>
</td>
</tr>
<tr>
<td style="text-align: left;"></td>
<td style="text-align: left;">HiPKI RCA</td>
</tr>
<tr>
<td style="text-align: left;"></td>
<td style="text-align: left;">CHT TrustRoot CA</td>
</tr>
<tr>
<td colspan="2" style="text-align: left;">
<strong>Subordinate CA</strong>
</td>
</tr>
<tr>
<td style="text-align: left;"></td>
<td style="text-align: left;">HiPKI OV TLS CA</td>
</tr>
<tr>
<td style="text-align: left;"></td>
<td style="text-align: left;">CHT Trust TLS CA</td>
</tr>
</table>

HiPKICA’s CA certificate information and applicable CP/CPS, external audit report and management statement are all published in the CA repository. For a list of HiPKICA certificate serial numbers and certificate fingerprints, please refer to Appendix 4.

#### 1.3.1.1 Root CA
Root CA is also a principal CA in HiPKI. Its main tasks are:

1)  Issuing and administrating certificates issued by Root CA, including self-signed, self-issued and Subordinate CA certificates.

2)  Establishing the cross-certification procedures between Root CA and any Root CA outside HiPKI, including issuance and administration of the cross-certificates.

3)  Publishing the newly issued certificate revocation list (CRL) to the repository and ensure that the repository operates regularly.

After being approved by CHT, Root CA in HiPKI can perform cross-certification with any Root CA outside HiPKI.

#### 1.3.1.2 Subordinate CA
A Subordinate CA is another form of CA in HiPKI responsible for the issuance and administration of End-entity (EE) certificates. However, any Subordinate CA is not allowed to cross-certify with any CA outside HiPKI directly.

#### 1.3.1.3 Cross-Certified CA
Currently, Root CA in HiPKI does not have any cross-certification with any Root CA outside HiPKI. Before a Root CA issues a cross-certificate to another root CA outside of HiPKI, the decision to allow such issuance must be made by the PMA.

### 1.3.2 Registration Authorities

The RA is responsible for collection and authentication of subscriber identity and certificate-related information. The RA is comprised of one or more RA counters authorized under the organization approved by HiPKICA. Each RA counter has an RA officer (RAO) who is responsible for the review of certificate application, revocation, and re-key for different certificate groups and types.

Root CA directly accepts CA certificate registration and revocation requests and is responsible for collecting and verifying the identity and the certificate-related information of subordinate CAs and cross-certified CAs. There is no need to set up an RA.

The RA of a subordinate CA shall be directly established and operated by the subordinate CA itself and must also operate in compliance with the provisions of this CP/CPS.

HiPKICA does not permit any delegated third party to be the TLS RA counter to verify the ownership or control of domain names or IP addresses. The delegated third parties mean any natural person or legal entity that is not HiPKICA but is delegated to assist the certificate management procedure and is not covered by the external audit of HiPKICA.

### 1.3.3 Subscribers

A Subscriber refers to the subject who has applied for and obtained a certificate issued by HiPKICA. The relationship between the subscriber and certificate subject is listed in the following Table:

| **Certificate Subject** | **Subscriber**                    |
|-------------------------|-----------------------------------|
| Equipment               | owner of the equipment            |
| Application software    | owner of the application software |

Generation of subscriber key pairs shall comply with Section 6.1.1 of this CP/CPS. The subscriber must have the right and capability to control the private key that corresponds to its subscriber certificate. The Subscriber is not capable of issuing certificates to other parties.

In the HiPKI, a Subordinate CA is not called the subscriber because the Subordinate CA is capable of issuing certificates.

### 1.3.4 Relying Parties

The relying party refers to a third party that acts in reliance of the relationship between the certificate subject name and the public key. The relying party must verify the validity of the certificate used based on the corresponding CA certificate and certificate status information.

### 1.3.5 Other Participants

No stipulation.

## 1.4 Certificate Usage

CHT would evaluate various risks, application environment, possible vulnerability, and certificate usage prior to determining an appropriate assurance level for CA operation and certificate issuance and administration.

### 1.4.1 Appropriate Certificate Uses

Root CA issues four kinds of certificates: self-signed certificates, self-issued certificates, subordinate CA certificates and cross-certificates, where the assurance level of subordinate CA certificates is level 3 and the others are level 4 (please refer to Section 3.2.2 for authentication of organization identity). The types of certificates and their scope of application are shown as follows:

<table>
<colgroup>
<col style="width: 15%" />
<col style="width: 85%" />
</colgroup>
<thead>
<tr>
<th style="text-align: center;">
<strong>Cert. Type</strong>
</th>
<th style="text-align: center;">
<strong>Scope of Applications</strong>
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center;">
Self-signed certificates
</td>
<td style="text-align: justify;"><p>A self-signed certificate is used to establish the trust anchor of the HiPKI.</p>
<p>The subject of the self-signed certificate is the Root CA itself. The self-signed certificate contains the Root CA public key which can be used to verify the digital signatures on subordinate CA certificates, cross-certificates, self-issued certificates and certification revocation lists (CRLs) issued by the Root CA.</p></td>
</tr>
<tr>
<td style="text-align: center;">
Self-issued certificates
</td>
<td style="text-align: justify;"><p>A self-issued certificate is used in case of the Root CA re-key or certificate policy update of the CA certificate. It involves mutual signing between the old and new key pairs, or one-way issuance from the old to the new, to establish a trusted communication path.</p></td>
</tr>
<tr>
<td style="text-align: center;">
Subordinate CA certificates
</td>
<td style="text-align: justify;"><p>A subordinate CA certificate is used to construct the trust path required for the interoperability of CAs.</p>
<p>The subordinate CA certificate contains the subordinate CA public key which can be used to verify the digital signatures on certificates and CRLs issued by the subordinate CA.</p></td>
</tr>
<tr>
<td style="text-align: center;">
cross-certificates
</td>
<td style="text-align: justify;"><p>A cross-certificate is used to construct the trust path required for the interoperability of CAs under different PKIs.</p>
<p>The subject of the cross-certificate is the Root CA established under another PKI and cross-certifies with the Root CA.</p>
<p>The cross-certificate contains the cross-certified CA public key which can be used to verify the digital signatures on certificates and CRLs issued by that CA.</p></td>
</tr>
</tbody>
</table>

In compliance with the Chrome Root Certificate policy, the subordinate CAs of HiPKICA will only issue TLS certificates for equipments or application software that apply to the TLS communication protocol. Please refer to Section 3.2.2 for assurance level and authentication of organization identity, and the types of certificates and their scope of application are shown as follows:

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 75%" />
</colgroup>
<thead>
<tr>
<th style="text-align: center;">
<strong>Cert. Type</strong>
</th>
<th style="text-align: center;">
<strong>Scope of Applications</strong>
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center;">
<p>Level 3 OV TLS certificates</p></td>
<td style="text-align: left;">
<p>Provides encryption of communication channels, and it is suitable for protecting network communication when it is necessary to identify which organization the domain name owner belongs to.</p>
</td>
</tr>
</tbody>
</table>

Subscribers shall operate their private keys within secure and reliable computing environments and application systems to mitigate the risk of key compromise and potential loss of rights or interests. Subscribers and relying parties must carefully read and comply with this CP/CPS before using and trusting the certificate service provided by HiPKICA, and pay attention to the update of this CP/CPS.

Relying parties must use the keys in compliance with Section 6.1.7 and use the certificate validation methods in accordance with international standards (such as ITU-T X.509 or RFC 5280) to verify the validity of certificates.

### 1.4.2 Prohibited Certificate Uses

Certificates issued under this CP/CPS are prohibited from being used in the scope of:

1)  man-in-the-middle TLS traffic interception;

2)  applications or businesses that may result in bodily harm, psychological distress, or cause significant harm to social order and public interest; and

3)  explicitly prohibited or excluded by other relevant laws or the competent authorities for specific applications/business purposes.

    Subscribers are expected to comply with all requirements of all applicable browser root policies, including revocation periods of 24 hours and 5 days as specified herein.

## 1.5 Policy Administration

### 1.5.1 Organization Administering the Document

Chunghwa Telecom Co., Ltd. (CHT).

### 1.5.2 Contact Person

#### 1.5.2.1 CP/CPS Related Issues
Any suggestions regarding this CP/CPS, please contact us with the following information.

Email: <caservice@cht.com.tw>

Address: HiPKI Certification Authority (4F), Data Communication Building, No. 21, Sec.1, Hsinyi Rd., Taipei City 10048, Taiwan (R.O.C.)

#### 1.5.2.2 Certificate Problem Report
Subscribers, relying parties, application software suppliers, and other third parties may report private key lose, suspected private key compromise, certificate misuse, or other types of fraud, compromise, misuse, inappropriate conduct, or any other matter related to certificates by sending email to <report_abuse@cht.com.tw>.

HiPKICA may or may not revoke in response to this request. See Sections 4.9.3 and 4.9.5 for detail of actions performed by HiPKICA for making this decision.

### 1.5.3 Person Determining CP/CPS Suitability for the Policy

HiPKICA shall first check whether its practices conform to this CP/CPS and then submit this CP/CPS to the PMA for review and approval. After approval, HiPKICA can officially reference the certificate policies of HiPKI.

HiPKICA conducts regular internal/external audits to demonstrate that it has operated with the assurance level under this CP/CPS. In order to ensure smooth operation of certificates issued by HiPKICA across different operating systems, browsers, and software platforms, HiPKI has applied to the root certificate programs to include the self-signed certificates of Root CAs in the CA trust lists of these platforms. According to the regulations of the root certificate program, the audits of HiPKICA are conducted annually and the latest version of this CP/CPS as well as the audit reports are submitted to the root certificate programs. HiPKICA also publishes the audit seals to the CA website.

### 1.5.4 CPS Approval Procedures

This CP/CPS is published by HiPKICA following approval by the PMA.

After the revisions of this CP/CPS take effect, if there is any inconsistency between the original CP/CPS and the revised one, then the revised CP/CPS takes precedence unless stipulated otherwise.

## 1.6 Definitions and Acronyms

See Appendix 1 for the abbreviations and definitions and Appendix 2 for the glossary.

# 2. Publication and Repository Responsibilities

## 2.1 Repositories

The HiPKICA repository is responsible for the publication and storage of certificates and certificate revocation lists (CRLs) issued by HiPKICA and this CP/CPS. HiPKICA offers a certificate repository and query service for subscribers and relying parties, accessible via <https://chtca.hinet.net/en/repository.html>.

The repository will resume normal operation within two working days if unable to operate normally for some reason.

## 2.2 Publication of Certification Information

HiPKICA shall take responsibility for making the following information publicly accessible in its repository:

1)  This CP/CPS;

2)  All HiPKICA certificates, Cross-certificates, and CRLs;

3)  Privacy protection policy; and

4)  The latest external audit report (as specified in Section 8.6).

The CA that issues TLS certificates must host test Web pages (valid, expired, and revoked) that allow application software suppliers to test their software with subscriber certificates that chain up to each publicly trusted root certificate.

Certification Authority Authorization (CAA) issuer domain names (as specified in Section 4.2.1) of the CA that issues TLS certificates include ‘pki.hinet.net’ or ‘tls.hinet.net’.

## 2.3 Time or Frequency of Publication

1)  This CP/CPS is reviewed and updated at least once every 366 days, and a dated changelog is state in the “Document History” section even if no other changes are made to this document,

2)  New or modified version of this CP/CPS complied with by HiPKICA is published in the repository as soon as possible upon approval by the PMA,

3)  HiPKICA issues CRLs at least twice a day and publishes them in the repository, and

4)  HiPKICA certificates are published in the repository within seven working days after issuance.

## 2.4 Access Controls on Repositories

HiPKICA implements access control where it provides read-only access to prevent anyone from unauthorized writing operation, which would put repository security in risk.

# 3. Identification and Authentication

## 3.1 Naming

### 3.1.1 Types of Names

HiPKICA certificates are issued with the following types of names:

1)  The subject distinguished name (DN) shall comply with ITU-T X.500 standards.

2)  The subject alternative name extension for subscriber certificates must not be marked critical. When this extension contains a domain name syetem label, the domain name must be stored in the dNSName.

### 3.1.2 Need for Names to be Meaningful

The naming of the certificate subject should comply with the law of the country under the jurisdiction of the applicant.

The issuing CA and its RA may abridge the prefix or suffix of the organization name, e.g., change the official name “Company Name Incorporated” to its abbreviated version “Company Name, Inc.”, and the abbreviation must be made on the basis that the certificate subject is easily identifiable in the jurisdiction in which it is established or registered. If the organization name is longer than 64 characters, the issuing CA and its RA may abbreviate the organization name or delete the unimportant text in the organization name.

Fully qualified domain names (FQDN) shall be appeared in the commonNames and Subject Alternative Name fields for TLS certificate. The DN for organization validation (OV) TLS certificate shall include the organization field verified in Section 3.2.2.

### 3.1.3 Anonymity or Psuedonymity of Subscribers

HiPKICA does not issue end entity pseudonymous certificates.

For requests of internationalized domain names (IDNs) applying for TLS certificates, it must be converted into punycode to submit an application. The decoded hostname will undergo additional review to mitigate the risk for phishing and other fraudulent usage as stated in Section 4.2.1, e.g., homographic spoofing of IDNs; and the decoded hostname may be compared with previously rejected certificate requests or revoked certificates.

### 3.1.4 Rules for Interpreting Various Name Forms

The rules for interpreting name forms follow the definition of name attribute type documented in ITU-T X.520.

### 3.1.5 Uniqueness of Names

HiPKICA shall use the X.520 standard to define the various naming attributes for assembly to ensure the uniqueness of the X.500 naming space recognized by HiPKICA for name of the subscriber certificate subject name. The HiPKICA subscriber certificate subject name permits (but not limited to) the use of the following naming attributes defined in the X.520 standard for assembly:

- countryName (abbreviated as C)

- localityName (abbreviated as L)

- organizationName (abbreviated as O)

- commonName (abbreviated as CN)

### 3.1.6 Recognition, Authentication, and Role of Trademarks

The certificate subject name, including trademark or any name, business or company name or representation protected by law, provided by subscribers must comply with relevant regulations in our country’s Trademark Act, Fair-Trade Act, and other relevant laws and regulations. HiPKICA does not guarantee the recognition, verification, legality and uniqueness of the certificate subject name if it contains a trademark. Related disputes and arbitration shall not be the obligation of HiPKICA, the subscriber shall apply to relevant competent authorities, courts or arbitration institutions.

HiPKICA may reject any application or at its own discretion revoke certificates (refer to Section 4.9.1) that involves in a trademark dispute.

## 3.2 Initial Identity Validation

### 3.2.1 Method to Prove Possession of Private Key

HiPKICA shall verify that the entity (Subordinate CA or end entity) possesses the private key, which is paired with the public key to be contained in the certificate.

The certificate applicant shall self-generate the key pairs, creates the PKCS \#10 Certificate Signing Request (CSR), and signs it with the private key. When applying for a certification, the CSR is submitted to the RA. The RA shall use the subscriber’s public key to verify the signature on the CSR to prove that the subscriber is in possession of the corresponding private key.

### 3.2.2 Authentication of Organization Identity

The certification document required for organization identification and authentication, and the authentication and verification procedures whether need to be performed at the counter are determined based on various assurance levels as shown in the following Table.

<table>
<colgroup>
<col style="width: 17%" />
<col style="width: 82%" />
</colgroup>
<thead>
<tr>
<th style="text-align: center;"><strong>Assurance Level</strong></th>
<th style="text-align: center;"><strong>Procedures for Authentication of Organization Identity</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center;">test</td>
<td style="text-align: left;">No stipulation.</td>
</tr>
<tr>
<td style="text-align: center;">Level 1</td>
<td style="text-align: left;"><p>There is no requirement to link the applicant to a specific real-life identity. Any attributes provided in conjunction with the authentication process are self-asserted.</p>
<ol type="1">
<li>No identity verification required.</li>
<li>The applicant is required to demonstrate control of their domain name to which the certificate relates.</li>
<li>In-person identity proofing at counter is not required.</li>
</ol></td>
</tr>
<tr>
<td style="text-align: center;">Level 2</td>
<td style="text-align: left;"><p>Evidence supports the real-world existence of the claimed identity and verifies that the applicant is appropriately associated with this real-world identity.</p>
<ol type="1">
<li>No identity verification required.</li>
<li>In-person identity proofing at counter is not required.</li>
<li>The applicant is required to provide organization information such as organization ID number (i.e., withholding tax ID number) and organization name. HiPKICA may additionally cross-check the information provided by the applicant for consistency with available government or third-party data sources.</li>
</ol></td>
</tr>
<tr>
<td style="text-align: center;">Level 3</td>
<td style="text-align: left;">HiPKICA allows only remote method for authentication of organization identity:<p>
  
Remote identity proofing, which can be one of the following means and the detailed operating procedures are formulated in the internal control system of each RA:
<ol type="a">
<li>Application through an identity assurance level 3 organization certificate issued by the GPKI;</li>
<li>Organizations belonging to CHT apply for the certificate with e-form.</li>
</ol>
For CAs:
<ol type="1">
<li>The identity authentication of a CA established by CHT is reviewed by a PMA meeting convened by CHT.</li>
<li>For a CA not established by CHT, the CA shall apply for a subordinate CA certificate, and a PMA meeting shall be convened by CHT to review the application.</li>
</ol></td>
</tr>
<tr>
<td style="text-align: center;">Level 4</td>
<td style="text-align: left;"><ol type="1">
<li>The identity authentication of a CA established by CHT is reviewed by a PMA meeting convened by CHT.</li>
<li>For a CA not established by CHT, the CA shall apply for a cross-certificate, and a PMA meeting shall be convened by CHT to review the application.</li>
</ol></td>
</tr>
<tr>
<td style="text-align: center;">OV TLS certificates</td>
<td style="text-align: left;">In compliance with the Baseline Requirements and the provisions for assurance level 3.</td>
</tr>
</tbody>
</table>

Before relying on any document for validation of organization identity, legal existence, physical address, or operational existence, HiPKICA or its RA reviews the document for evidence of alteration, falsification, tampering, incompleteness, and inconsistency. Submitted documents are checked for authenticity indicators such as official seals, company seals, issuance dates, registration information, and document continuity. Information contained in the documents is cross-validated against authoritative government or reliable third-party data sources where applicable.

### 3.2.3 Authentication of Individual Identity

No stipulation.

### 3.2.4 Non-verified Subscriber Information

All information provided by the subscriber to be listed in the certificates must be verified.

### 3.2.5 Validation of Authority

When an Applicant Representative requests the issuance or revocation of a certificate and has an affiliation with the Subject named in the Certificate, HiPKICA SHALL validate the authority of the Applicant Representative to act on behalf of the Applicant in accordance with Section 3.2.5 of the Baseline Requirements before accepting the request.

HiPKICA MAY verify the authorization of the Applicant Representative through one of the following methods:

1)  Using verified organizational contact information to confirm the authorization with the Applicant or its authorized representative through a reliable method of communication, such as telephone calls or email communications.

2)  Verifying the consistency of the Applicant Representative's information as recorded in the application documents, government-issued identification documents, or the organization’s internal records.

3)  For remote identity proofing of OV TLS certificates, validating the digital signature generated using a level 3 organization certificate issued under the GPKI.

HiPKICA SHALL accept a certificate-related request submitted by an Applicant Representative only after confirming that such individual is authorized to act on behalf of the Applicant in connection with the requested certificate lifecycle activity.

### 3.2.6 Criteria for Interoperation

HiPKICA allows another root CA to interoperate with, please refer to the provisions of this CP/CPS.

When cross-certificates are issued, HiPKICA shall specify the path length constraint in the basicConstraints extension to ensure that the path for certificate interoperation is permitted. The value of path length is set depending on the path length that allows for certificate interoperation.

### 3.2.7 Validation of Domain Authorization or Control

HiPKICA performs the permitted processes and procedures for validating the Applicant’s ownership or control of the domain in accordance with Section 3.2.2.4 of the Baseline Requirements. HiPKICA shall use one of the following methods set forth in the Baseline Requirements to validate the Applicant’s right to use or control the domain name.

For all other Domain Validation methods, DNSSEC validation back to the IANA DNSSEC root trust anchor MUST be performed on all DNS queries associated with the validation of domain authorization or control by the Primary Network Perspective and CAs MUST NOT use local policy to disable DNSSEC validation on any DNS query associated with the validation of domain authorization or control.

#### 3.2.7.1 Validating the Applicant as a Domain Contact
Confirming the Applicant’s control over the FQDN by validating the Applicant is the Domain Contact. This method may only be used if HiPKICA is also the Domain Name Registrar, or an Affiliate of the Registrar, of the Base Domain Name. For example, Chunghwa Telecom Co., Ltd. is also the Domain Name Registrar of .tw.

**Note:** Once the FQDN has been validated using this method, HiPKICA MAY also issue TLS certificates for other FQDNs that end with all the labels of the validated FQDN. This method is suitable for validating Wildcard Domain Names. This method of validation confirms to Section 3.2.2.4.12 of the Baseline Requirements.

When issuing subscriber certificates, HiPKICA MUST NOT rely on Domain Contact information obtained using an HTTPS website, regardless of whether previously obtained information is within the allowed reuse period.

When obtaining Domain Contact information for a requested Domain Name, HiPKICA:

1)  MUST query IANA’s WHOIS server and follow referrals to the appropriate WHOIS server if using the WHOIS protocol (RFC 3912).

2)  MUST utilize IANA’s bootstrap file to identify and query the correct RDAP server for the domain if using the Registry Data Access Protocol (RFC 7482).

3)  MUST NOT rely on cached 1) WHOIS server information that is more than 48 hours old, or 2) RDAP bootstrap data from IANA that is more than 48 hours old, to ensure that it relies upon up-to-date and accurate information.

#### 3.2.7.2 Agreed‐Upon Change to Website
Confirming the Applicant’s control over the FQDN by verifying that the Request Token or Random Value is contained in the contents of a file.

1)  The entire Request Token or Random Value must not appear in the request used to retrieve the file, and

2)  HiPKICA MUST receive a successful HTTP response from the request (meaning a 2xx HTTP status code must be received).

The file containing the Request Token or Random Number:

1)  MUST be located on the Authorization Domain Name, and

2)  MUST be located under the “/.well-known/pki-validation” directory, and

3)  MUST be retrieved via either the “http” or “https” scheme, and

4)  MUST be accessed over an Authorized Port.

If the applicant adopts domain name redirects (also known as URL redirects), the following apply:

1)  Redirects MUST be initiated at the HTTP protocol layer:
Redirects MUST be the result of a 301, 302, or 307 HTTP status code response, as defined in RFC 7231, Section 6.4, or a 308 HTTP status code response, as defined in RFC 7538, Section 3. Redirects MUST be to the final value of the Location HTTP response header, as defined in RFC 7231, Section 7.1.2.

2)  Redirects MUST be to resource URLs with either via the “http” or “https” scheme.

3)  Redirects MUST be to resource URLs accessed via Authorized Ports.

If a Random Value is used, HiPKICA SHALL provide a Random Value unique to the certificate request, and the Random Value SHALL remain valid for use in a confirming response for no more than 30 days from its creation.

Except for Onion Domain Names, HiPKICA implements Multi-Perspective Issuance Corroboration (MPIC) as specified in Section 3.2.10 to perform validations. To count as corroborating, a Network Perspective MUST observe the same challenge information (i.e. Random Value or Request Token) as the Primary Network Perspective.

**Note:** HiPKICA MUST NOT issue certificates for other FQDNs that end with all the labels of the validated FQDN unless HiPKICA performs separate validations for each of those other FQDNs using authorized methods. This method is NOT suitable for validating Wildcard Domain Names. This method of validation confirms to Section 3.2.2.4.18 of the Baseline Requirements.

#### 3.2.7.3 Domain Name Service (DNS) Change
Confirming the Applicant’s control over the requested FQDN by confirming the presence of a Random Value or Request Token in a DNS CNAME, TXT or CAA record for either 1). an Authorization Domain Name; or 2). an Authorization Domain Name that is prefixed with a label that begins with an underscore character.

If a Random Value is used, HiPKICA SHALL provide a Random Value unique to the certificate request and SHALL not use the Random Value after (i) 30 days or (ii) if the Applicant submitted the certificate request, the timeframe permitted for reuse of validated information relevant to the certificate (such as in Section 4.2.1 of Baseline Requirement).

Meanwhile, HiPKICA implements MPIC as specified in Section 3.2.10 to perform validations. To count as corroborating, a Network Perspective MUST observe the same challenge information (i.e. Random Value or Request Token) as the Primary Network Perspective.

If HiPKICA or an Affiliate of HiPKICA operates a DNS zone to which Applicants can delegate (via CNAME) their underscore-prefixed Domain Label, HiPKICA MUST ensure that each Applicant delegates to a unique FQDN within that zone. HiPKICA or its Affiliate do not operate such a service.

**Note:** Once the FQDN has been validated using this method, HiPKICA MAY also issue TLS certificates for other FQDNs that end with all the labels of the validated FQDN. This method is suitable for validating Wildcard Domain Names. This method of validation confirms to Section 3.2.2.4.7 of the Baseline Requirements.

#### 3.2.7.4 Agreed-Upon Change to Website - ACME
Confirming the Applicant’s control over a FQDN by validating domain control of the FQDN using the Automated Certificate Management Environment (ACME) HTTP Challenge method defined in Section 8.3 of RFC 8555, performed in accordance with Section 3.2.2.4.19 of the Baseline Requirements and Section 8.3 of RFC 8555 as prescribed.

### 3.2.8 Validation of Wildcard Domains

If the FQDN portion of any Wildcard Domain Name in the Certificate is “registry‐controlled” or is a “public suffix” (e.g. “.com”, “.co.uk”, see RFC 6454 Section 8.2), HiPKICA applies additional scrutiny and checks to ensure the applicant has rightful control over the entire Domain Namespace.

If using the Public Suffix List (PSL), HiPKICA consults the “ICANN DOMAINS” section only, not the “PRIVATE DOMAINS” section.

### 3.2.9 Data Source Accuracy

Prior to using any data source as a Reliable Data Source, HiPKICA SHALL evaluate the source for its reliability, accuracy, and resistance to alteration or falsification. HiPKICA SHOULD consider the following during its evaluation:

1)  The age of the information provided,

2)  The frequency of updates to the information source,

3)  The data provider and purpose of the data collection,

4)  The public accessibility of the data availability, and

5)  The relative difficulty in falsifying or altering the data.

Databases maintained by HiPKICA, its owner, or its affiliated companies do not qualify as a Reliable Data Source, if the primary purpose of the database is to collect information according to the validation requirements in Section 3.2 of the Baseline Requirements.

### 3.2.10 Multi-Perspective Issuance Corroboration

From March 15, 2025, HiPKICA performs Multi-Perspective Issuance Corroboration (MPIC) for the required domain authorization or control validation and CAA record checks in accordance with Section 3.2.2.9 of the Baseline Requirements. MPIC can assist to corroborate the determinations (i.e., domain validation pass/fail, CAA permission/prohibition) made by the Primary Network Perspective from multiple remote Network Perspectives before certificate issuance.

Quorum Requirements Table

| **\# of Distinct Remote Network Perspectives Used** | **\# of Allowed non-Corroborations** |
|:---:|:---:|
| 2-5 | 1 |
| 6+ | 2 |

Phased Implementation Timeline:

- **Effective March 15, 2025**, HiPKICA must implement MPIC using at least 2 remote Network Perspectives. HiPKICA may proceed with certificate issuance if the number of remote Network Perspectives that do not corroborate the determinations made by the Primary Network Perspective (“non-corroborations”) is greater than allowed in the Quorum Requirements table above.

- **Effective September 15, 2025**, HiPKICA must implement MPIC using at least 2 remote Network Perspectives. HiPKICA MUST ensure that the requirements defined in Quorum Requirements Table above are satisfied. If the requirements are not satisfied, then HiPKICA MUST NOT proceed with issuance of the Certificate.

- **Effective March 15, 2026**, HiPKICA must implement MPIC using at least 3 remote Network Perspectives. HiPKICA MUST ensure that the requirements defined in Quorum Requirements Table above are satisfied, and the remote Network Perspectives that corroborate the Primary Network Perspective fall within the service regions of at least two (2) distinct Regional Internet Registries. If the requirements are not satisfied, then the CA MUST NOT proceed with issuance of the Certificate.

- **Effective June 15, 2026**, HiPKICA must implement MPIC using at least 4 remote Network Perspectives. HiPKICA MUST ensure that the requirements defined in Quorum Requirements Table above are satisfied, and the remote Network Perspectives that corroborate the Primary Network Perspective fall within the service regions of at least two (2) distinct Regional Internet Registries. If the requirements are not satisfied, then the CA MUST NOT proceed with issuance of the Certificate.

- **Effective December 15, 2026**, HiPKICA must implement MPIC using at least 5 remote Network Perspectives. HiPKICA MUST ensure that the requirements defined in Quorum Requirements Table above are satisfied, and the remote Network Perspectives that corroborate the Primary Network Perspective fall within the service regions of at least two (2) distinct Regional Internet Registries. If the requirements are not satisfied, then the CA MUST NOT proceed with issuance of the Certificate.

## 3.3 Identification and Authentication for Re-key Requests

### 3.3.1 Identification and Authentication for Routine Re-key

If the subscriber or CA’s private key needs to be renewed upon expiry of the certificate period, certificate rekey work may be performed, and the subscriber may re-apply for certification. The RA may validate the subscriber’s identity by using the subscriber’s public key to verify the CSR, or conduct an initial identity validation in accordance with Section 3.2. The identification and authentication for routine re-key of TLS certificate are handled in accordance with the Baseline Requirements.

### 3.3.2 Identification and Authentication for Re-key after Revocation

If the subscriber or CA’s private key needs to be re-keyed due to certificate revocation, the subscriber or CA shall re-apply for a new certificate with HiPKICA, and an initial identity validation shall be conducted in accordance with Section 3.2.

## 3.4 Identification and Authentication for Revocation Request

HiPKICA or RA must perform authentication of the certificate revocation request to verify that the applicant has the right to submit the request. The authentication procedure for certificate revocation request is the same as the regulations in Section 3.2.

# 4. Certificate Life-cycle Operational Requirements

## 4.1 Certificate Application

### 4.1.1 Who Can Submit a Certificate Application

Either the applicant or an individual authorized to request certificates on behalf of the applicant may submit certificate applications.

### 4.1.2 Enrollment Process and Responsibilities

The certificate application procedures are as follows:

1)  Use the appropriate secure platform to generate an appropriate key pair.

2)  Generate a PKCS#10 CSR using an appropriately tool.

3)  Fill out the information on the certificate application and agrees to a subscriber agreements or other applicable terms and conditions.

4)  Submit the certificate application request (including the CSR, the legal name of the organization or the website FQDN based on the type of the certificate applied for, etc.) and provide relevant identification documents to the RA, where the application information can be in electronic form.

The RA are responsible for ensuring the accuracy of the application request and performing the identification and authentication of the applicant before delivery the request to the issuing CA for issuance.

## 4.2 Certificate Application Processing

### 4.2.1 Performing Identification and Authentication Functions

Upon receipt of the certificate request, HiPKICA and RAs shall verify the application information in accordance with Section 3.2. The certificate applicant shall submit correct and complete factual information. The information required for the certificate application shall contain required and optional information.

HiPKICA SHALL NOT reuse subject identity information validation data beyond the maximum reuse period specified below:

| **Certificate issued on or after** | **Certificate issued before** | **Maximum data reuse period** |
|:--:|:--:|:--:|
| 2025-08-01 | 2026-03-15 | 398 days |
| 2026-03-15 | 2029-03-15 | 90 days |
| 2029-03-15 | \- | 10 days |

The applicable reuse period SHALL be determined based on the issuance date of the OV TLS certificate. The information submitted by the certificate applicant and contact records kept by HiPKICA and RA during the application process shall be properly kept in a secure, auditable manner in accordance with this CP/CPS.

For TLS certificates, the RA system maintains an internal database of all previously revoked certificates and previously rejected certificate requests due to suspected phishing or other fraudulent usage. The RA implements extra procedures that identify and require additional verification activity for High-Risk Certificate requests prior to the certificate’s approval, as reasonably necessary to ensure that such requests are properly verified under the Baseline Requirements.

Prior to issuing a TLS certificate, HiPKICA checks the DNS for the existence of a CAA record for each dNSName in the subjectAltName extension of the certificate to be issued, as specified in RFC 8659, and in accordance with Section 3.2.2.8 of the Baseline Requirements. If the certificate is issued, it will be issued within the Time to Live (TTL) of the CAA record, or 8 hours, whichever is greater.

HiPKICA supports the “issue” CAA tag and logs all actions taken. If a CAA record exists that does not list “pki.hinet.net” or “tls. hinet.net” as a CAA Issuer Domain Name, HiPKICA will not issue the certificate. HiPKICA does not dispatch reports of issuance requests to the contact(s) listed in an “iodef” property tag.

HiPKICA processes the accountURI and validationMethods parameters in accordance with RFC 8657, and supports case-insensitive labels for validationMethods.

### 4.2.2 Approval or Rejection of Certificate Applications

HiPKICA will not issue TLS certificates containing internal names or reserved IP addresses. The verification of the authorization domain name and the basic domain name must comply with the regulations as specified in Section 3.2.7.

Effective March 15, 2026, HiPKICA SHALL NOT issue certificates containing Domain Names that end in an IP Reverse Zone Suffix.

If all identity authentication work follows relevant regulations and best practices can be successfully implemented, HiPKICA may approve the certificate application. If the various identity authentication works cannot be successfully completed, HiPKICA may reject the certificate application. In addition to this reason, HiPKICA may refuse to issue certificates for other reasons. HiPKICA and its RA may also reject certificate application from applicants who have previously been rejected or have previously violated the subscriber agreements.

A PMA meeting is convened when any CA submits a Subordinate CA certificate or cross-certificate application. The PMA will review the related documents provided by the CAs to evaluate the appropriateness for becoming a subordinate CA or Cross-certified CA in HiPKI. The PMA may decide that the application enters the next stage, supplemental information is required, or the application is rejected.

### 4.2.3 Time to Process Certificate Applications

HiPKICA shall complete the certificate application within a reasonable period. Provided that the information submitted by the applicant is complete and complies with this CP/CPS and other checking requirements, the RAO shall quickly complete the review of certificate application. The time needed by RA to process certificate applications and HiPKICA to issue the certificates depends on the certificate group and type. These times may be disclosed in the subscriber agreements, contract or on the RA’s websites.

Upon receiving the certificate application, the RAO will complete the review process, and the applicant will be asked to accept the certificate. The times when the issuing CA completes the issuance of the certificate are given as follows:

<table>
<colgroup>
<col style="width: 49%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr>
<th style="text-align: center;"><strong>Type of Certificates</strong></th>
<th style="text-align: center;"><strong>Time required for processing and issuance of the Certificate</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">OV TLS Certificates</td>
<td align="center">
<p>within 2 working days</p>
</td>
</tr>
</tbody>
</table>

Issuance time frames are greatly dependent on when the applicant provides the details and documentation necessary to complete validation or complates the certificate acceptance. The time of certificate application processing may also be specified in the Subscriber Agreement or in the contract with the certificate applicant.

## 4.3 Certificate Issuance

### 4.3.1 CA Actions during Certificate Issuance

#### 4.3.1.1 Manual authorization of certificate issuance for Root CAs
Upon completion of the CA key generation ceremony, the issuance of Root CA self-signed certificates, self-issued certificates, and subordinate CA certificates SHALL be performed within a secure facility that is physically isolated from external networks and SHALL NOT be performed through automated processes. Prior to certificate issuance, the Root CA private key SHALL be jointly activated by two CA officers. In addition, two administrators and one internal auditor SHALL verify the accuracy of the certificate contents and the associated approval information before issuance is performed. Upon successful completion of these verification procedures, an authorized individual SHALL manually perform the certificate issuance process. All activities SHALL be subject to multi-person control, and all related operational records SHALL be retained in accordance with established procedures.

#### 4.3.1.2 Linting of to-be-signed Certificate content
Upon HiPKICA receive the certificate application, the relevant review procedures are enforced in accordance with Chapter 3 of this CP/CPS to serve as a basis for determining whether approve the certificate issuance.

Certificate issuance steps are follows:

1)  The RA submits the certificate application passed the review procedures to the issuing CA.

2)  When the issuing CA receives the certificate application submitted by the RA, the authorization status of the RA is first checked to confirm its authorized assurance level and scope, and then the certificate is issued according to the information of the certificate application submitted by the RA.

3)  If the authorized assurance level and scope of the RA does not comply with the certificate application, the issuing CA will respond to the error message to the RA and reject the request. If there are any questions, the RA may directly contact the issuing CA to understand where the problem is.

4)  In accordance with Section 4.3.1.2 of the Baseline Requirements, the CA’s certificate issuance system SHALL perform pre-issuance linting on all TLS Certificates prior to issuance. The pre-issuance linting process verifies that the certificate to be issued conforms to the applicable requirements of the Baseline Requirements and RFC 5280. Certificates that fail the linting checks SHALL NOT be issued and SHALL be rejected to prevent certificate mis-issuance.

5)  In order to ensure the security, integrity and non-repudiability of the data transmitted between the issuing CA and its RAs, the data of the certificate application is signed with a digital signature and transmitted through the network encrypted by TLS protocol.

#### 4.3.1.3 Linting of issued Certificates
HiPKICA performs a linting process on each issued certificate to verify its compliance with the applicable requirements.

### 4.3.2 Notification to Subscriber by the CA of Issuance of Certificate

HiPKICA shall notify the subscriber about the certificate issuance during the enrollment process by email or any other equivalent method. The email may contain the certificate itself or a link to download depending upon the workflow of the certificate requested.

## 4.4 Certificate Acceptance

### 4.4.1 Conduct Constituting Certificate Acceptance

Certificates are considered accepted if not revoked by the subscriber within 30 days of issuance. Acceptance of the certificate is deemed as the certificate applicant’s consent to comply with the rights and obligations in this CP/CPS or related contracts.

### 4.4.2 Publication of the Certificate by the CA

CA Certificates are published in the HiPKICA repository. End-entity certificates are published by delivering them to the subscriber.

### 4.4.3 Notification of Certificate Issuance by the CA to Other Entities

If there are newly issued self-signed certificates, CHT will submit the inclusion application in compliance with the root certificate program of operating system, browser, and software platform to include the certificate into the CA trust lists.

## 4.5 Key Pair and Certificate Usage

### 4.5.1 Subscriber Private Key and Certificate Usage

Key pairs of subscribers shall be generated in compliance with Section 6.1.1 of this CP/CPS. Subscribers must be able to control the private keys, which must not be used to issue certificates.

Subscribers shall protect their private keys from unauthorized use or disclosure and shall use their private keys only for the correct key usage (i.e., the policy for key usage specified in the extension of the certificates). Subscribers shall use their certificates in accordance with this CP/CPS and the Subscriber Agreement.

### 4.5.2 Relying Party Public Key and Certificate Usage

When relying parties use a certificate, they shall confirm its certificate usage and use it in accordance with this CP/CPS. Relying parties may only use a tool or a method that is compliant with the ITU-T X.509, IETF RFCs or Baseline Requirements.

Prior to a certificate’s use, the tool or method selected by relying parties must verify each certificate in the certificate chain, including the accuracy of the content of specific fields, the integrity of the signature, and the validity of the certificate status, where the certificate status may be obtained from a CRL or an online certificate status protocol (OCSP) service. After that, the TLS certificate in the certificate path can be used to authenticate the domain name of the server and the identity of the server owner and create an encrypted channel between the client and the server.

Relying parties shall also verify the certificate policies extension in both the issuing CA certificate and the TLS certificate to determine the assurance level of the certificates provided.

## 4.6 Certificate Renewal

HiPKICA does not allow certificate renewal.

### 4.6.1 Circumstances for Certificate Renewal

Not applicable.

### 4.6.2 Who May Request Renewal

Not applicable.

### 4.6.3 Processing Certificate Renewal Requests

Not applicable.

### 4.6.4 Notification of New Certificate Issuance to Subscriber

Not applicable.

### 4.6.5 Conduct Constituting Acceptance of a Renewal Certificate

Not applicable.

### 4.6.6 Publication of the Renewal Certificate by the CA

Not applicable.

### 4.6.7 Notification of Certificate Issuance by the CA to Other Entities

Not applicable.

## 4.7 Certificate Re-Key

### 4.7.1 Circumstance for Certificate Re-key

Under the following circumstances, the subordinate CA/cross-certified CA will renew the key and ask Root CA to issue a new subordinate CA/cross-certified CA certificate:

1)  The lifecycle of currently used keys has ended.

2)  Security issues exist for currently used keys (such as suspected or confirmed key compromise).

Subscribers whose certificates have not expired may request a re-key, and HiPKICA shall identify and authenticate them in accordance with Section 3.3.1. After the key pair is re-keyed, HiPKICA may revoke the old certificate and does not allow the modification or re-key of the old certificate.

### 4.7.2 Who May Request Certification of a New Public Key

The subject of the certificate or an authorized representative.

### 4.7.3 Processing Certificate Re-keying Requests

For subscriber certificate re-keying, HiPKICA shall validate the request in accordance with Sections 3.1, 3.2, 3.3, 4.1 and 4.2 and may re-validate the subscriber subject with any previously validated data when needed.

### 4.7.4 Notification of New Certificate Issuance to Subscriber

As stated in Section 4.3.2.

### 4.7.5 Conduct Constituting Acceptance of a Re-keyed Certificate

As stated in Section 4.4.1.

### 4.7.6 Publication of the Re-keyed Certificate by the CA

As stated in Section 4.4.2.

### 4.7.7 Notification of Certificate Issuance by the CA to Other Entities

No stipulation.

## 4.8 Certificate Modification

### 4.8.1 Circumstance for Certificate Modification

Certificate modification means creating a new certificate for the same subject, where authenticated information that slightly differs from the old certificate (e.g., changes to FQDN or other relatively attribute information). The new certificate has a new certificate serial number but with the same subject public key and ‘NotAfter’ date. After the certificate is modified, the old certificate shall be revoked.

### 4.8.2 Who May Request Certificate Modification

The subject of the certificate or an authorized representative.

### 4.8.3 Processing Certificate Modification Requests

1)  The application procedure for certificate modification is as Section 4.2.

2)  If there is any change to the important identity information such as the organization name, the original certificate must be revoked. The subscriber must submit a new certificate application with the modified organization name to obtain a new certificate.

### 4.8.4 Notification of New Certificate Issuance to Subscriber

As stated in Section 4.3.2.

### 4.8.5 Conduct Constituting Acceptance of Modified Certificate

As stated in Section 4.4.1.

### 4.8.6 Publication of the Modified Certificate by the CA

As stated in Section 4.4.2.

### 4.8.7 Notification of Certificate Issuance by the CA to Other Entities

No stipulation.

## 4.9 Certificate Revocation and Suspension

This section mainly describes under what circumstances a certificate may (or must) be suspended or revoked and explains the procedures.

### 4.9.1 Circumstances for Revocation

#### 4.9.1.1 Circumstances for Revoking a Subscriber Certificate
issuing CAs must revoke a certificate within 24 hours and use the corresponding CRL Reason confirming one or more of the following occurred:

1)  The subscriber requests in writing to the issuing CA to revoke the certificate but does not specify a reason (CRLReason, “unspecified (0)”); Selecting this option omits the reasonCode extension from the CRL);

2)  The subscriber notifies the issuing CA that the original certificate request was not authorized and does not retroactively grant authorization (CRLReason \#9, privilegeWithdrawn);

3)  The issuing CA obtains evidence that the subscriber’s private key corresponding to the public key in the certificate suffered a key compromise (CRLReason \#1, keyCompromise);

4)  The issuing CA is made aware of a demonstrated or proven method that can easily compute the subscriber’s private key based on the public key in the certificate including but not limited to those identified in Section 6.1.1.2 of the Baseline Requirements. (CRLReason \#1, keyCompromise); or

5)  The issuing CA obtains evidence that the validation of domain authorization or control for any FQDN or IP address in the certificate should not be relied upon (CRLReason \#4, superseded).

The issuing CA should revoke a certificate within 24 hours and must revoke a certificate within 5 days if one or more of the following occurs:

1)  The certificate no longer complies with the requirements of Sections 6.1.5 and 6.1.6 (CRLReason \#4, superseded);

2)  The issuing CA obtains evidence that the certificate was misused and/or used outside the intended purpose as indicated by the relevant agreement (CRLReason \#9, privilegeWithdrawn);

3)  The issuing CA is made aware that a subscriber has violated one or more of its material obligations under the Subscriber Agreement or Terms of Use (CRLReason \#9, privilegeWithdrawn);

4)  The issuing CA is made aware of any circumstance indicating that use of a FQDN or IP address in the certificate is no longer legally permitted (e.g., a court or arbitrator has revoked a Domain Name Registrant’s right to use the Domain Name, a relevant licensing or services agreement between the Domain Name Registrant and the Applicant has terminated, or the Domain Name Registrant has failed to renew the Domain Name) (CRLReason \#5, cessationOfOperation);

5)  The issuing CA is made aware that a wildcard certificate has been used to authenticate a fraudulently misleading Subordinate FQDN (CRLReason \#9, privilegeWithdrawn);

6)  The issuing CA is made aware of a material change in the information contained in the certificate (CRLReason \#9, privilegeWithdrawn);

7)  The issuing CA is made aware that the certificate was not issued in accordance with these requirements or this CP/CPS (CRLReason \#4, superseded);

8)  The issuing CA determines or is made aware that any of the information appearing in the certificate is inaccurate (CRLReason \#9, privilegeWithdrawn);

9)  The issuing CA’s right to issue certificates under these requirements expires or is revoked or terminated, unless the issuing CA has made arrangements to continue maintaining the CRL/OCSP Repository (CRLReason “unspecified (0)”);

10) Revocation is required by this CP/CPS (CRLReason “unspecified (0)”); or

11) The issuing CA is made aware of a demonstrated or proven method that exposes the subscriber’s private key to compromise or if there is clear evidence that the specific method used to generate the private key was flawed (CRLReason \#1, keyCompromise).

#### 4.9.1.2 Circumstances for Revoking a Subordinate CA Certificate
Root CA shall revoke a Subordinate CA certificate within seven (7) days if one or more of the following occurs:

1)  The Subordinate CA requests revocation in writing;

2)  The Subordinate CA notifies the Root CA that the original certificate request was not authorized and does not retroactively grant authorization;

3)  The Root CA obtains evidence that the Subordinate CA’s private key corresponding to the public key in the certificate suffered a key compromise or no longer complies with the requirements of Sections 6.1.5 and 6.1.6;

4)  The Root CA obtains evidence that the certificate was misused;

5)  The Root CA is made aware that the certificate was not issued in accordance with or that Subordinate CA has not complied with this CP/CPS;

6)  The Root CA determines that any of the information appearing in the certificate is inaccurate or misleading;

7)  The Root CA ceases operations for any reason and has not made arrangements for another CA to provide revocation support for the certificate;

8)  The Root CA’s right to issue certificates under these Requirements expires or is revoked or terminated, unless The Root CA has made arrangements to continue maintaining the CRL/OCSP Repository; or

9)  Revocation is required by this CP/CPS.

The issuing CA may at its own discretion revoke certificates, including subscriber certificates, subordinate CA certificates or cross-certificates, under the aforementioned circumstances.

### 4.9.2 Who Can Request Revocation

Subscribers or legally authorized third party (such as judicial or prosecution authorities, the subject of the certificate or an authorized representative, and legal heirs of natural person) can request revocation.

In addition, a subscriber, relying party, application software suppliers or other third party may submit certificate problem report to advise HiPKICA a reasonable reason to revoke the certificate. HiPKICA shall take actions in accordance with Section 4.9.5 and confirm the validity of the certificate revocation request upon receiving the certificate problem report.

### 4.9.3 Procedure for Revocation Request

1)  When requesting certificate revocation, the Applicant SHALL select the appropriate revocation reason based on the revocation reason descriptions provided by HiPKICA, the RA, or the applicable Subscriber Agreement, certificate revocation request interface, or related online resources;

2)  After the RA completes the review work, the certificate revocation request is sent to HiPKICA;

3)  When HiPKICA receives the certificate revocation request sent by the RA, HiPKICA first checks the authorization status of the relevant RA to verify that its authorized assurance level and scope. Afterward, the certificate is revoked based on the certificate revocation request;

4)  If the above checking does not comply with the revocation request, HiPKICA will respond to the error message to the RA and reject the request. If there are any questions, the RA may directly contact HiPKICA to understand where the problem is;

5)  In order to ensure the security, integrity and non-repudiability of the data transmitted between HiPKICA and its RA, the data of the certificate application is encrypted with a digital signature and transmitted through the network by TLS protocol;

6)  HiPKICA uses the same CA private key issuing the certificate to publish the revoked certificate serial number and the reason for revocation to the CRL by the digital signature; and

7)  HiPKICA receives certificate problem reports and provides 24x7 availability of certificate problem response mechanism, as specified in Section 4.9.3.1.

#### 4.9.3.1 Mechanism for Responding the Certificate Problems
Under “the Announcement of CPS” at the repository, HiPKICA provides the guidelines for certificate problem reports. Subscribers, relying parties, application software suppliers, and other third parties may submit certificate problem reports through the information specified in Section 1.5.2.2 under the circumstances of the private keys are cracked, the certificates are mis-issued, or the certificates are forged, cracked, abused, or used inappropriately.

### 4.9.4 Revocation Request Grace Period

The certificate revocation request grace period refers to the time to submit a revocation request when the subscriber has confirmed the certificate revocation circumstances. When the subscriber’s private key is lost or suspected or known to be compromised, the subscriber shall promptly submit a revocation request to the RA. The revocation request grace period is two working days. HiPKICA may extend the revocation grace period when deemed necessary.

If any of the circumstances described in Section 4.9.1 occur, CAs or RAs shall submit the revocation request within 10 working days.

### 4.9.5 Time within Which CA Must Process the Revocation Request

Within 24 hours after receiving a Certificate Problem Report, HiPKICA shall investigate the facts and circumstances related to a Certificate Problem Report and provide a preliminary report on its findings to both the Subscriber and the entity who filed the Certificate Problem Report.

After reviewing the facts and circumstances, HiPKICA shall work with the Subscriber and any entity reporting the Certificate Problem Report or other revocation-related notice to establish whether the certificate will be revoked, and if so, the period from receipt of the Certificate Problem Report or revocation-related notice to published revocation must not exceed the time frame set forth in Section 4.9.1. The date selected by HiPKICA shall consider the following criteria:

1)  The nature of the alleged problem (scope, context, severity, magnitude, risk of harm);

2)  The consequences of revocation (direct and collateral impacts to Subscribers and Relying Parties);

3)  The number of certificate problem reports received about a particular certificate or subscriber;

4)  The entity making the complaint; and

5)  Relevant legislation.

### 4.9.6 Revocation Checking Requirement for Relying Parties

Prior to relying on a certificate, relying parties must verify the status of all certificates in the certificate chain through the CRL or, if available, the OCSP services provided by HiPKICA. Relying parties shall determine the timing and frequency for obtaining certificate revocation information at their own discretion, considering relevant risks, responsibilities, and potential impacts.

### 4.9.7 CRL Issuance Frequency

The CRL issuance frequency of HiPKICA is at least twice per day. Issued CRL are valid for no more than 36 hours. Before the CRL expires, HiPKICA may issue a new CRL. The new CRL validity period may overlap the validity period of the old CRL. Even though the old CRL has not yet expired, relying parties still may obtain the new CRL from the HiPKICA repository to receive the updated certificate revocation information.

HiPKICA SHALL continue issuing CRLs for a Subordinate CA certificate until either:

1)  all Subordinate CA certificates containing the same subject public key are expired or revoked; or

2)  the corresponding Subordinate CA private key is destroyed.

### 4.9.8 Maximum Latency for CRLs

Except for the Root CA has pre-signed of CRLs, after a CRL is produced by other CAs, it will be released immediately.

### 4.9.9 On-line Revocation/Status Checking Availability

HiPKICA provides certificate revocation and status checking services through CRLs and web-based mechanisms for certificate search and download. OCSP services may also be offered based on the service offerings of the issuing CAs.

If the issuing CA provides an OCSP service, the CA shall use an OCSP responder to provide OCSP responses complying with RFC 6960 and/or RFC 5019, where the OCSP responses are signed by the OCSP responder using a 2048-bit or greater RSA key (that modulus size in bits is divisible by 8) and a hash algorithm at least as strong as SHA-256. In addition, the OCSP responder also provides OCSP responder certificates, which are issued by HiPKICA and contain the extension of type id-pkix-ocsp-nocheck, as defined by RFC 6960.

### 4.9.10 On-line Revocation Checking Requirements

Relying parties must confirm the validity of a certificate in accordance with Section 4.9.6 before using it.

If HiPKICA provides an OCSP service, an OCSP responder operated under the service shall support the HTTP POST and GET methods, as described in RFC 6960 and/or RFC 5019. The certificate status information provided by the service shall meet the following requirements:

1)  For the status of a TLS certificate or its corresponding precertificate: an authoritative OCSP response MUST be available (i.e. the responder MUST NOT respond with the “unknown” status) starting no more than 15 minutes after it is first published or otherwise made available. HiPKICA provides an updated OCSP response prior to one‐half of the validity period before the nextUpdate, and the validity interval of the OCSP response is greater than or equal to 8 hours and less than 16 hours.

2)  For status of self-issued certificates, subordinate CA certificates, and cross-certificates: HiPKICA updates the information at least every twelve months and within 24 hours after any of these certificates is revoked.

A certificate serial number within an OCSP request is either:

1)  “assigned” if the certificate serial number belongs to a certificate already issued by the issuing CA, or if it is the certificate serial number of a precertificate required for the issuance of a TLS certificate by the CA; or

2)  “unassigned” if neither of the previous conditions is met.

If the OCSP responder receives a request for the status of a certificate serial number that is “unassigned”, then the responder should not respond with a “good” status.

### 4.9.11 Other Forms of Revocation Advertisements Available

In order to speed up and instantly complete the verification of the TLS certificates status of high-traffic websites, HiPKICA supports OCSP stapling operation based on RFC 4366 and through the support of Certificate Transparency (CT) and technical review, or provision of relevant setting instructions to assist subscribers who own high-traffic websites to implement OCSP stapling.

### 4.9.12 Special Requirements Related to Key Compromise

In case of a compromise of the subscriber’s private key, the subscriber must immediately notify HiPKICA of the event. HiPKICA will revoke the certificate concerned (choose the reason for the revocation as ‘key compromised’) according to the procedures set forth in Sections 4.9.1, 4.9.2 and 4.9.3 of this CP/CPS, and publish a CRL to inform relying parties that the certificate can no longer be trusted.

In case of a compromise of CA’s private key, the Root CA will publish a CRL to inform software suppliers, subscribers, and relying parties about the private key compromise event.

The acceptable methods used by third parties as proof of key compromise are as follows:

1)  Confirming the third party’s possession of the private key by signing a challenge provided by HiPKICA using the compromised private key; or

2)  Submitting the private key itself.

### 4.9.13 Circumstances for Suspension

HiPKICA does not allow suspension of CA certificates and TLS certificates.

### 4.9.14 Who Can Request Suspension

Not applicable.

### 4.9.15 Procedure for Suspension Request

Not applicable.

### 4.9.16 Limits on Suspension Period

Not applicable.

### 4.9.17 Procedure for Certificate Resumption

Not applicable.

## 4.10 Certificate Status Services

### 4.10.1 Operational Characteristics

HiPKICA provides CRL and may offer OCSP services based on the issuing CA’s service offerings. Revocation entries on a CRL or OCSP response must not be removed until after the expiry date of the revoked certificate.

### 4.10.2 Service Availability

HiPKICA operates and maintains its CRL and optional OCSP capability with resources sufficient to provide a response time of 10 seconds or less under normal operating conditions.

HiPKICA maintains an online 24x7 repository that application software can use to automatically check the current status of all unexpired certificates issued by HiPKICA.

HiPKICA maintains a continuous 24x7 ability to respond internally to a high-priority certificate problem report, and where appropriate, forward such a complaint to law enforcement authorities, and/or revoke a certificate that is the subject of such a complaint.

### 4.10.3 Optional Features

No stipulation.

## 4.11 End of Subscription

End of subscription signifies that subscribers stop using HiPKICA’s services. HiPKICA allows subscribers to end their subscription to certificate services by having their certificate revoked or by allowing the certificate or applicable Subscriber Agreement to expire without renewal.

## 4.12 Key Escrow and Recovery

### 4.12.1 Key Escrow and Recovery Policy and Practices

HiPKICA’s private signing keys shall not be escrowed.

### 4.12.2 Session Key Encapsulation and Recovery Policy and Practices

HiPKICA does not currently support session key encapsulation and recovery.

# 5. Facility, Management, and Operation Controls

## 5.1 Physical Controls

### 5.1.1 Site Location and Construction

The HiPKICA facility is located in the Chunghwa Telecom Information Technology Group. The construction of the facility housing is consistent with facilities used to house high value, sensitive information. Combined with other physical security mechanisms including access control, security, intrusion detection and video monitoring, it provides robust protection against unauthorized access to related HiPKICA equipment.

### 5.1.2 Physical Access

HiPKICA has established suitable measures to control connections to the hardware, software and hardware security module that serves to HiPKICA.

The HiPKICA facility has a total of four levels of security control. On the first and second levels, there are year-round entrance and building security controls in place. On the third level, access is controlled to this floor using a card access control system. On the fourth level, a fingerprint recognition control system is used to control access for facility personnel. The fingerprint scanner uses 3D sampling technology which is capable of detecting whether the fingerprint is from a live object by fingerprint depth and color.

The access control system is able to protect the facilities against unauthorized access. There is also a monitoring system in place to control cabinet access which prevents unauthorized access to any hardware, software or hardware security module.

HiPKICA enforces multi-person control for physical access to Root CA Systems to prevent any individual from obtaining independent access to Root CA Systems. Access to the secure area housing Root CA Systems requires the participation of at least one physical security administrator and one system administrator. Both individuals must independently complete the required identity verification and physical access control procedures before access is granted. Physical access to Root CA equipment racks is controlled by the physical security administrator, while operation of the Root CA Systems is performed by the system administrator. No individual is permitted to perform both functions independently. This multi-person control process ensures that physical access to Root CA Systems and related critical operations are protected through dual-person authorization and oversight.

Portable storage devices that are brought into the facility housing are checked for computer viruses or other types of software that could damage the HiPKICA system. Non-HiPKICA personnel entering the facility are required to sign the entry/exit log and must be accompanied throughout by HiPKICA personnel.

The following checks and records need to be made when HiPKICA personnel leave the facility to prevent unauthorized personnel from entering the facility:

1)  Check if system equipment is operating normally.

2)  Check if the computer racks are locked.

3)  Check if the access control system is operating normally.

HiPKICA does not permit remote privileged access to any portion of its CA Infrastructure. All administrative activities, system maintenance, configuration changes, and other operations requiring privileged access shall be performed only by authorized personnel physically present within controlled CA facilities.

### 5.1.3 Power and Air Conditioning

In addition to municipal power, the power system at the HiPKICA facility is equipped with a generator (with enough fuel for six days of continuous operation) and an uninterrupted power system (UPS). The system is capable of automatically switching between municipal power and generator power. At least six hours of power can be supplied for repository backup work.

The HiPKICA facility has a constant temperature and humidity system to provide an optimal operation environment for the facility.

### 5.1.4 Water Exposures

The HiPKICA facility is located at the third or higher floor of a raised foundation building. This building has water gate and water pump protection and no history of major damage caused by flooding.

### 5.1.5 Fire Prevention and Protection

The HiPKICA facility has an automatic fire detection, alarm and protection system with self-activating extinguishing equipment. Switches are installed at every major entrance / exit of the facility to allow manual activation by personnel on-site during emergencies.

### 5.1.6 Media Storage

Audit records, archives and backups are kept in storage media at the facility described in Section 5.1.1. In addition, one copy shall be kept at an off-site location.

### 5.1.7 Waste Disposal

When the documents of HiPKICA detailed in Section 9.3.1 are no longer in use, it shall be shredded by the paper shredder. Any storage media that HiPKICA used shall be formatted to erase the information stored on it before scrapping, and discs shall be physically destroyed.

### 5.1.8 Off-site Backup

The off-site backup location shall be over 30 km away from the HiPKICA facility. The backup content shall include data and system programs.

## 5.2 Procedural Controls

In order to ensure that system procedures have a suitable assurance level, HiPKICA uses procedural controls to specify the trusted roles of HiPKICA system operations, the number of people required for each task and how each role is identified and authenticated.

### 5.2.1 Trusted Roles

In order to make appropriate segmentation and assignment of the responsibility for performing system-related operations, to prevent someone from maliciously using the CA system without being noticed, the trusted role authorized to perform each system access task is clearly defined in HiPKICA.

The seven PKI personnel roles assigned by HiPKICA are administrator, CA officer, internal auditor, system operator, physical security controller, cyber security coordinator and anti-virus and anti-hacking coordinator to prevent potential internal attacks. Each trusted role may be performed by multiple persons but one person in each group shall be assigned the chief role to lead group work. The tasks performed by the seven roles are as follows:

The administrator is responsible for:

- Installation, configuration and maintenance of the HiPKICA system

- Creation and maintenance of system user accounts

- Generation and backup of HiPKICA keys

- Activation / deactivation of related keys of certificate manager

- System hardware and software updates

- System backup and recovery

- Website maintenance

- Patching the system vulnerabilities

The CA officer is responsible for:

- Generation and backup of HiPKICA keys

- Activation / deactivation of keys for certificate issuance

- Activation / deactivation of keys for certificate revocation

- Activation / deactivation of keys for CRL issuance

The internal auditor is responsible for:

- Generation and backup of HiPKICA keys

- Checking, maintenance and archiving of audit logs

- Conducting or supervising internal audits to ensure HiPKICA is operating in accordance with this CP/CPS

- Patching the anti-virus and vulnerabilities of audit system

The system operator is responsible for:

- Archiving of audit logs

- Daily operation and maintenance of system equipment

- Storage media updating

- Set up protection mechanisms for system security and threats of virus or malware

The physical security controller is responsible for:

- System physical security controls (such as facility access controls, fire prevention, flood prevention and air conditioning systems)

The cyber security coordinator is responsible for:

- Maintenance of the network and network facilities

- Patches management for the vulnerabilities of the network facilities

- The network security of HiPKICA

- The detection and report of the network security events

The anti-virus and anti-hacking coordinator is responsible for:

- Researching, applying, or providing the anti-virus, anti-hacking, and anti-malicious software technologies or measures to ensure the security of the system and the network

- Reporting the collected threats or vulnerabilities of computer virus to the administrator or the cyber security coordinator for patches management

### 5.2.2 Number of Persons Required per Task

In accordance with security requirements, the number of persons required for each trusted role is as follows:

- Administrator

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; At least 3 qualified individuals are needed.

- CA Officer

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;At least 3 qualified individuals are needed.

- Internal Auditor

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; At least 2 qualified individuals are needed.

- System Operator

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; At least 2 qualified individuals are needed.

- Physical security controller

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; At least 2 qualified individuals are needed.

- Cyber security coordinator

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; At least 1 qualified individual.

- Anti-virus and anti-hacking coordinator

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; At least 1 qualified individual.

The number of people assigned to perform each task is as follows:

| Assignments | Administrator | CA Officer | Internal Auditor | System Operator | Physical security controller | Cyber security coordinator | Anti-virus and anti-hacking coordinator |
|----|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Installation, configuration, and maintenance of the HiPKICA system | 2 |  |  |  | 1 |  |  |
| Establishment and maintenance of system user accounts | 1 |  |  |  | 1 |  |  |
| Generation and backup of HiPKICA keys | 2 | 2 | 1 |  | 1 |  |  |
| Activation / deactivation of certificate issuance, certificate revocation and CRL issuance | 2 | 2 |  |  | 1 |  |  |
| Checking, maintenance and archiving of audit logs |  |  | 1 | 1 | 1 |  |  |
| Daily operation and maintenance of system equipment |  |  |  | 1 | 1 |  |  |
| System backup and recovery | 1 |  |  |  | 1 |  |  |
| Storage media updating |  |  |  | 1 | 1 |  |  |
| Hardware and software updates outside the HiPKICA system | 1 |  |  |  | 1 |  |  |
| Website maintenance | 1 |  |  |  | 1 |  |  |
| Daily operation and maintenance of the network and network facilities |  |  |  | 1 | 1 | 1 |  |
| Patching the vulnerabilities of the network facilities | 1 |  |  |  | 1 | 1 |  |
| Reporting the threats and vulnerabilities of computer virus |  |  |  |  |  |  | 1 |
| Patching the anti-virus and vulnerabilities (audit system) | 1 |  | 1 | 1 | 1 |  |  |
| Patching the anti-virus and vulnerabilities (systems other than the audit system) | 1 |  |  | 1 | 1 |  |  |

### 5.2.3 Identification and Authentication for Each Role

When the RA officers who log in the RA system and conduct related review actions, they shall use IC cards to verify their identities and execute digital signatures.

HiPKICA utilizes user accounts, passwords, and groups for system account management and IC card to identify and authenticate administrator, CA officer, internal auditor and system operator. HiPKICA utilizes the authority setting function of the central access control system to identify and authenticate physical security controllers.

HiPKICA utilizes user accounts, passwords, and groups for system account management, or other security mechanisms to identify the role of the cyber security coordinator.

### 5.2.4 Roles Requiring Separation of Duties

The seven trusted roles are defined in Section 5.2.1. Personnel and trusted roles must conform to the following regulations:

- Administrator, CA officer, internal auditor, and cyber security coordinator cannot assume any other roles among these four trust roles at the same time, but administrator, CA officer, and internal auditor can be system operator at the same time;

- Physical security controller shall not concurrently assume any role of administrator, CA officer, internal auditor, and system operator; and

- A person serving a trusted role is not allowed to perform self-audit.

## 5.3 Personnel Controls

### 5.3.1 Qualifications, Experience, and Clearance Requirements

1)  Security evaluation for personnel selection

    Personnel selection includes the following items:

    1)  Personality evaluation;

    2)  Applicant experience evaluation;

    3)  Academic and professional skills and qualifications evaluation;

    4)  Personal identity check; and

    5)  Evaluation of personnel conduct.

2)  Management of Personnel Evaluation

    All HiPKICA personnel performing certificate work shall have their qualifications reviewed at the initial time of employment to verify their reliability and work capabilities. After formal employment, personnel shall receive appropriate training and sign a document accepting responsibility to perform certain duties. All personnel shall have their qualifications rechecked each year to reconfirm their reliability and work ability. If personnel do not pass the qualification check, that person shall be reassigned to another position and a qualified person shall be assigned to serve in that position.

3)  Appointment, Dismissal and Transfer

    If there are changes to the employment terms or contract especially personnel severance and termination of temporary worker contracts, personnel are still required to fulfill their duty of confidentiality.

4)  Duty of Confidentiality Agreement

    Work personnel shall fulfill their duty of confidentiality in accordance with relevant regulations and sign a business secret agreement drafted by HiPKICA stating that personnel may not disclose business secrets verbally or by photocopy, loan, delivery, publishing or other methods.

### 5.3.2 Background Check Procedures

HiPKICA shall check the related identify and qualification documents for authenticity for those personnel performing the trusted roles defined in Section 5.2 at the initial time of employment.

### 5.3.3 Training Requirements

<table>
<colgroup>
<col style="width: 15%" />
<col style="width: 85%" />
</colgroup>
<thead>
<tr>
<th style="text-align: center;"><strong>Trusted Role</strong></th>
<th style="text-align: center;"><strong>Training Requirements</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center;">Administrator</td>
<td><ol type="1">
<li>HiPKICA security principles and mechanism.</li>
<li>Installation, configuration, and maintenance of the HiPKICA operation procedures.</li>
<li>The use and operation procedures of HiPKICA system software and hardware.</li>
<li>Establishment and maintenance of system user accounts operation procedures.</li>
<li>Audit parameter configuration setting procedures.</li>
<li>HiPKICA key generation and backup operation procedures.</li>
<li>Procedure of disaster recovery &amp; business continuity planning.</li>
</ol></td>
</tr>
<tr>
<td style="text-align: center;">CA Officer</td>
<td><ol type="1">
<li>HiPKICA security principles and mechanism.</li>
<li>HiPKICA key generation and backup operation procedures.</li>
<li>Activation/deactivation of certification issuance operation procedure.</li>
<li>Activation/ deactivation of certification revocation operation procedure.</li>
<li>Activation/ deactivation of certificate CRL issuance operation.</li>
<li>Procedure of disaster recovery &amp; business continuity planning.</li>
</ol></td>
</tr>
<tr>
<td style="text-align: center;">Internal Auditor</td>
<td><ol type="1">
<li>HiPKICA security principles and mechanism.</li>
<li>The use and operation procedures of HiPKICA audit Server.</li>
<li>HiPKICA key generation and backup operation procedures.</li>
<li>Audit log check, maintain and archiving procedures.</li>
<li>Procedure of disaster Recovery &amp; business continuity planning.</li>
</ol></td>
</tr>
<tr>
<td style="text-align: center;">System Operator</td>
<td><ol type="1">
<li>Daily operation and maintenance procedures for system equipment.</li>
<li>Upgrading of storage media procedure.</li>
<li>Procedure of disaster Recovery &amp; business continuity planning.</li>
<li>Network and website maintenance procedure.</li>
</ol></td>
</tr>
<tr>
<td style="text-align: center;">Physical security controller</td>
<td><ol type="1">
<li>Physical access authorization setting procedure.</li>
<li>Procedure of disaster Recovery &amp; business continuity planning.</li>
</ol></td>
</tr>
<tr>
<td style="text-align: center;">Cyber security coordinator</td>
<td><ol type="1">
<li>Network and network facilities maintain procedure.</li>
<li>Security mechanism for the network.</li>
</ol></td>
</tr>
<tr>
<td style="text-align: center;">Anti-virus and anti-hacking coordinator</td>
<td><ol type="1">
<li>Prevention to the threats and vulnerabilities of computer virus.</li>
<li>Security mechanism for the operating system and the network.</li>
</ol></td>
</tr>
</tbody>
</table>

### 5.3.4 Retraining Frequency and Requirements

In case of software/hardware upgrades, working procedures changed, equipment replaced, or relevant regulations changed, relevant personnel will be arranged for retraining and the training situation will be recorded, so as to make the personnel understand the changes in relevant operating procedures and regulations.

### 5.3.5 Job Rotation Frequency and Sequence
<ol>
<li>May not concurrently serve trusted roles. May not receive work reassignments.</li>
<li>Personnel with a full two years of experience as a system operators, cyber security coordinator, or anti-virus and anti-hacking coordinator with the requisite training and review may be reassigned to the position of administrator, CA officer or internal auditor.</li>
</ol>

### 5.3.6 Sanctions for Unauthorized Actions

HiPKICA related personnel shall be subject to appropriate administrative and disciplinary actions for violations of this CP/CPS or other procedures announced by HiPKICA. In the event of serious cases that result in damage, appropriate legal action shall be taken.

### 5.3.7 Independent Contractor Requirements

The duties, sanctions for unauthorized actions and required training documents of independent contractor serving a trusted role shall meet the requirements of Section 5.3 and the event logging and document retention shall meet the requirements of Section 5.4.1.

### 5.3.8 Documentation Supplied to Personnel

HiPKICA shall make available to related personnel relevant documentation pertaining to this CP/CPS and HiPKICA system operation manuals.

## 5.4 Audit Logging Procedures

HiPKICA shall keep security audit logs for all events related to HiPKICA security. Security audit logs shall be collected by automatic system generation, logbook or paper. All security audit logs shall be retained and made available during compliance audits in accordance with the archive retention regulations stated in Section 5.5.2.

### 5.4.1 Types of Events Recorded

1)  Key generation

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Key generation of CAs

2)  Private key loading and storage

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Loading the private key into a system component.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- All access to private keys kept by HiPKICA for key recovery work.

3)  Certificate registration

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Certificate registration request process.

4)  Certificate revocation

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Certificate revocation request process.

5)  Account administration

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Add or delete roles and users.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- User account or role access authority revisions.

6)  Certificate profile management

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Certificate profile changes.

7)  CRL profile management

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- CRL profile changes.

8)  Physical access / site security

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Known or suspect violation of physical security regulations.

9)  Anomalies

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Software defect.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- CP/CPS violation.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Reset system clock.

### 5.4.2 Frequency of Processing Log

HiPKICA shall routinely review audit logs to prevent possible malicious activity, and any significant operations should be further reviewed. Review work includes examining all log entries and conducting a final complete check for any warnings or anomalies. Audit checking results shall be documented.

### 5.4.3 Retention Period for Audit Log

Audit logs shall be retained on-site for two months, and the log retention management system shall be operated in accordance with Sections 5.4.4, 5.4.5, 5.4.6 and 5.5.

If the retention period of the audit record file expires, the auditor is responsible for removing the data and cannot be behalfed by other personnel.

### 5.4.4 Protection of Audit Log

Signature and encryption technology shall be used to protect the current and archived audit logs. A CD-R or other media storage that cannot change the audit logs is used, and only authorized personnels can access.

HiPKICA’s audit system enforces resource control and identity identification security mechanisms, only authorized auditor has backup and read access to logs, and the system keeps a log file of access audit records to detect and prevent improper access.

### 5.4.5 Audit Log Backup Procedures

1)  HiPKICA shall routinely archive event logs, and electronic audit logs are backed up at least once a month.

2)  At least one copy of the media for storing audit logs shall be kept at an off-site location with proper security control measures.

### 5.4.6 Audit Collection System (Internal vs. External)

Audit systems are built in the HiPKICA system, and audit procedures are activated when the HiPKICA system is activated and only stops when the HiPKICA system is shut down.

If the automated audit system cannot operate normally, HiPKICA shall suspend certificate issuance services until the issue is resolved before resuming service again to protect system information integrity and confidentiality when the security system is in a high-risk status.

### 5.4.7 Notification to Event-causing Subject

Where an event is logged by the audit system, the audit system does not need to notify the entity which caused the event.

### 5.4.8 Vulnerability Assessments

CAs that issuing TLS certificates shall follow the methods and frequency stipulated in the WebTrust Principles and Criteria for Certification Authorities – Network Security and Network and Certificate System Security Requirements to conduct the vulnerability assessments at least once per quarter and the penetration testing at least once per year. HiPKI OV TLS CA should perform a vulnerability assessment when identifying significant changes to a network or system. HiPKI OV TLS CA also must conduct penetration testing after it is determined that there is a significant upgrade or modification to the application program or infrastructure. HiPKICA shall implement the enhancement and correction measures after the penetration testing and the vulnerability assessment. HiPKICA shall record the skills, tools, followed ethics, competitive relations and independence guidelines for those personnel or groups capable of implementing reliable vulnerability scans, penetration testing, or information security diagnosis or security surveillance.

## 5.5 Records Archival

A reliable mechanism shall be adopted by HiPKICA to accurately and completely save certificate-related records such as computer data or in written form, including:

1)  Important tracking records regarding HiPKICA’s own key pair generation, storage, backup, and re-key.

2)  Important tracking records regarding certificate application, issuance, revocation, and reissuance.

In addition to being provided for tracking and audits, these records may also serve as evidence, if necessary, for dispute resolution. In order to follow the above regulations, RAs may ask applicants or their representatives to submit related certification documents when deemed necessary.

### 5.5.1 Types of Records Archived

HiPKICA retains the following information in its archives:
<ol>
<li>HiPKICA accreditation information from competent authorities.</li>

<li>CPS.</li>

<li>Major contracts.</li>

<li>System and equipment configuration settings.</li>

<li>System and configuration setting modifications and updates.</li>

<li>Certificate application information.</li>

<li>Revocation request information.</li>

<li>Subscriber identity identification information stipulated in Section 3.2.</li>

<li>Issued and published certificates.</li>

<li>HiPKICA re-key records.</li>

<li>Issued or announced CRLs.</li>

<li>Audit logs.</li>

<li>Other data or application programs used to verify and corroborate the archived content.</li>

<li>Documents required by the auditor.</li>
</ol>

### 5.5.2 Retention Period for Archive

HiPKICA retains data archived for at least 2 years. The application programs used to process archived data are retained until all archived data is deprecated.

### 5.5.3 Protection of Archive

1)  Amendments, modifications, and deletion of archived data are not allowed by any user.

2)  The archived data can be moved to another storage medium after passing through the HiPKICA authorized procedures.

3)  The archived data is stored in a secure, protected location.

### 5.5.4 Archive Backup Procedures

HiPKICA electronic records shall be regularly backed up and saved in storage media in accordance with backup procedures. Paper records shall be regularly sorted and filed by authorized HiPKICA personnel.

### 5.5.5 Requirements for Time-stamping of Records

All HiPKICA computer systems are regularly calibrated to ensure the accuracy and trustworthiness of the date and time information on electronic records. For archived electronic records (such as certificates, CRLs and audit logs), the timestamping information on each record shall include the date and time information with calibrated system time. These records shall have appropriate digital signature protection which can be used to check the date and time information on the records for alteration.

### 5.5.6 Archive Collection System (Internal or External)

There is currently no archive collection system.

### 5.5.7 Procedures to Obtain and Verify Archive Information

Only authorized HiPKICA personnel are allowed to access the archive.

Audit personnel shall follow verification procedures when verifying archive information. The authenticity of signatures and dates must be verified for written documents.

## 5.6 Key Changeover

HiPKICA shall periodically change its private keys in accordance with Section 6.3.2 and shall change its key pair before the usage period of its private key issuing subscriber certificates has expired. After key changeover of Subordinate CAs, it will use the new key pair to apply for a new CA certificate from the Root CA, and publish it in the repository for download after its issuance.

After key changeover of the Root CA, the Root CA shall sign a new self-signed certificate (by using the new private key) and mutually sign a new self-issued certificate (by using the new and old private keys, separately). The new self-signed certificate shall be delivered to relying parties in accordance with Section 6.1.4 while the new self-issued certificates shall be published in the repository.

HiPKICA shall still maintain and protect its old private keys and shall make the old certificate available to verify CRL or OCSP until all of the subscriber certificates signed with the private key have expired.

If HiPKICA’s certificate has been revoked, HiPKICA shall stop using its private keys and shall change its key pairs.

## 5.7 Compromise and Disaster Recovery

### 5.7.1 Incident and Compromise Handling Procedures

**5.7.1.1 Incident Response and Disaster Recovery Plans**

HiPKICA establishes incident and compromise reporting and handling procedures and conducts drills annually.

**5.7.1.2 Mass Revocation Plans**

HiPKICA develops and maintains a comprehensive and actionable plan for mass revocation events in accordance with Section 5.7.1.2 of the Baseline Requirements. HiPKICA conducts annual mass certificate revocation drills and incorporates lessons learned into such plan in order to continually improve our preparedness for mass revocation events over time.

### 5.7.2 Computing Resources, Software, and/or Data Are Corrupted

HiPKICA establishes recovery procedures in the event of computing resource, software and data corruption and conducts annual drills.

If HiPKICA’s computer equipment is damaged or unable to operate, but the HiPKICA signature key has not been destroyed, priority shall be given to restoring operation of the HiPKICA repository and quickly reestablishing certificate issuance and management capabilities.

### 5.7.3 Entity Private Key Compromise Procedures

HiPKICA implements the following recovery procedure in the event of signature key compromise:

1)  Publish in the repository and notify subscribers and relying parties about the event of key compromise.

2)  Revoke the HiPKICA signature key certificate and issued subscriber certificates.

3)  Generate new key pairs in accordance with the procedures in Section 5.6 and the new certificates are published in the HiPKICA repository.

HiPKICA shall conduct the drills of CA private key compromise at least once a year.

### 5.7.4 Business Continuity Capabilities after a Disaster

HiPKICA has established a disaster recovery procedure and conducts drills each year. In the event of a disaster, the emergency response team shall initiate the disaster recovery procedure. Priority shall be given to restoring the HiPKICA repository operations and quickly reestablishing certificate issuance and management capabilities.

## 5.8 CA or RA Termination

HiPKICA shall follow CA service termination procedures in accordance with related regulations during service termination. HiPKICA shall follow the item below to ensure the rights of subscribers and relying parties:

1)  HiPKICA should announce on its official website and notify subscribers 30 days prior to the scheduled termination of service.

2)  HiPKICA shall take the following measures when terminating their service:

    - For certificates which are valid at the time of termination, arrangements shall be made for other CA to take over the service. Matters regarding service termination and service acceptance by other CAs shall be published in the repository and subscribers with valid certificates shall be notified. This shall not apply if notification cannot be made.

    - All records and files during the operation period shall be handed over to the other CA that is taking over this service.

    - If there is no CA willing to take over the HiPKICA service, a report shall be submitted to the competent authority to arrange for other CA to take over this service.

    - If the competent authority arranges for other CA to take over the service but no other CA takes over the service, HiPKICA shall revoke the still valid certificates, publish the revoked certificates in the repository and notify all certificate-related persons 30 days prior to the scheduled termination of service. HiPKICA will refund the certificate issuance fee based on the propotion of the certificate validity.

    - The competent authorities, if necessary, may publish the certificates which are still valid at the time of revocation.

In case the RA terminates the service, HiPKICA shall stop its rights of review actions.

# 6. Technical Security Controls

## 6.1 Key Pair Generation and Installation

### 6.1.1 Key Pair Generation

According to the regulations in Section 6.2.2, HiPKICA generates key pairs within the hardware security module by using the algorithm and the procedures that meet NIST FIPS 140-2 or FIPS 140-3 standard.

HiPKICA key generation is witnessed and videotaped by those related personnel who need to sign key initiation witness document (the public key of the generated key pair is listed on it). The related personnel shall include the members of the PMA and/or the qualified auditors.

### 6.1.2 Private Keys Delivery to Subscriber

HiPKICA does not generate certificate key pairs on behalf of Subscribers or Subordinate CAs.

### 6.1.3 Public Key Delivery to Certificate Issuer

If a subscriber self-generates a key pair, the subscriber shall deliver the public key to the RA via a CSR file with PKCS# 10 format. The RA shall deliver the public key to HiPKICA via secure channels after it is verified that the subscriber is in possession of the corresponding private key in accordance with the regulations in Section 3.2.1.

Secure channels referred in this Chapter are the use of TLS or other equivalent or higher-level data encryption transmission protocols.

### 6.1.4 CA Public Key Delivery to Relying Parties

Commercial web browsers and platform operators are encouraged to embed Root Certificate Public Keys of HiPKICA into their root stores and operating systems. HiPKICA shall deliver the certificates containing the certificate chain of relevant CAs to the subscriber after certificate issuance. Relying parties can also download the public key certificates of the relevant CAs through the repository operated by HiPKICA. Excepet for the Root CA, HiPKICA notes the download location of the relevant public key certificates in the certificate chain through the Authority Information Access (AIA) extension of the issued certificate.

### 6.1.5 Key Sizes

The key sizes used by HiPKICA are described as follows:

1)  Root CAs shall use RSA keys with the modulus size of 4096 bits or ECDSA keys with a valid point on the NIST P-384 elliptic curve. The hash algorithm required to issue certificates depends on the Root CAs’ key algorithm:

    - RSA keys: SHA-256, SHA-384, or SHA-512;

    - ECDSA keys: SHA-384 (with the P-384 curve).

2)  Subordinate CAs and cross-certified CAs shall choose RSA keys with the modulus size of 4096 bits or ECDSA keys with a valid point on the NIST P-256/NIST P-384 elliptic curve. The hash algorithm required to issue certificates depends on the aforementioned CAs’ key algorithm:

    - RSA keys: SHA-256, SHA-384, or SHA-512.

    - ECDSA keys: SHA-256 (with the P-256 curve) or SHA-384 (with the P-384 curve).

3)  Subscribers shall use RSA keys with the modulus size of at least 2048 bits or ECDSA keys with a valid point on the NIST P-256/NIST P-384 elliptic curve.

4)  The modulus size of the aforementioned RSA key (in bits) must be divisible by 8.

### 6.1.6 Public Key Parameters Generation and Quality Checking

The public key parameter of the RSA algorithm is null.

When using RSA keys, the Root CA and its Subordinate CAs shall generate the key parameters required for the RSA algorithm in accordance with NIST FIPS 186-4 or its applicable successor standards to ensure compliance with the applicable security requirements.

Cross-certified CAs must perform appropriate key parameter quality checking according to the selected algorithm.

When subscriber key pairs are generated using the RSA algorithm within a software or hardware cryptographic module, the key generation process shall be conducted in accordance with the specifications of the cryptographic module used and applicable international standards. The public key of each key pair shall pass the necessary key quality checks, such as weak key checks, before it may be accepted for use in a certificate.

According to Section 5.3.3 of NIST SP 800-89, HiPKICA confirms that the value of the public exponent used by the RSA algorithm is an odd number greater than 3 and is in the range between 2<sup>16</sup>+1 and 2<sup>256</sup>‐1. Furthermore, the modulus should also meet the following characteristics: an odd number, not the power of a prime, and have no factors smaller than 752.

In addition, HiPKICA confirms the validity of all ECDSA keys using either the Elliptic Curve Cryptography (ECC) Full Public Key Validation Routine or the ECC Partial Public Key Validation Routine in accordance with NIST SP 800-56A Revision 3.

### 6.1.7 Key Usage Purposes (as per X.509 v3 Key Usage Field)

#### 6.1.7.1 Key Usage Purposes of CAs
The private key corresponding to the Root CA’s self-signed certificate can only be used for issuing self-signed certificates, self-issued certificates, subordinate CA certificates, cross-certificates, CRLs, OCSP responder certificates, or OCSP responses.

The contents of key usage and extended key usage extentions in the self-signed certificates, self-issued certificates, subordinate CA certificates and cross-certificates issued by the Root CA are handled in accordance with the provisions of Section 7.1.2.

#### 6.1.7.2 Key Usage Purposes of Subscribers
The contents of key usage and extended key usage extensions of TLS certificates are handled in accordance with the provisions of Section 7.1.2.

## 6.2 Private Key Protection and Cryptographic Module Engineering Controls

### 6.2.1 Cryptographic Module Standards and Controls

HiPKICA uses hardware security modules that are certified to FIPS 140-2 Level 3, FIPS 140-3 Level 3, or meet an equivalent cryptographic security standard.

### 6.2.2 Private Key (n-out-of-m) Multi-person Control

HiPKICA’s private keys are controlled in accordance with the multi-person control process specified in Section 5.2 of this CP/CPS, and this process can be used as the activation and deactivation methods for private keys as well as the backup and recovery methods for private key splitting.

There are no further regulations for multi-person control of subscriber private keys.

### 6.2.3 Private Key Escrow

HiPKICA does not escrow its private signing keys. HiPKICA does not provide private key escrow services as well.

### 6.2.4 Private Key Backup

Backups of HiPKICA private keys are made according to private key multi-person control set forth in Section 6.2.2, and high-security IC cards are used as the storage media for secret sharing. HiPKICA does not provide additional private key backup services.

### 6.2.5 Private Key Archival

The private signing keys of HiPKICA shall not be archived, and HiPKICA does not perform archival of subscribers’ private signing keys.

### 6.2.6 Private Key Transfer into or from a Cryptographic Module

Private keys are allowed to be exported from the cryptographic module into backup tokens or imported from backup tokens into the cryptographic module only during key backup/recovery or cryptographic module replacement. The private keys mentioned in the previous process are controlled complying with the requirements of Section 6.2.2. The private keys are encrypted or split when transferred out of the module or transported between cryptographic modules and never exist in plaintext form. After the private keys are imported, the related secret parameters generated during the transport process must be completely destroyed.

If HiPKICA becomes aware that the private key of its Subordinate CA or Cross-Certified CA has been communicated to an unauthorized person or an organization not affiliated with that CA, the Root CA shall revoke all certificates that include the public key corresponding to the communicated private key.

### 6.2.7 Private Key Storage on Cryptographic Module

As stated in Sections 6.1.1 and 6.2.1. When not in use, the hardware security module must be taken offline and stored in the location specified in Section 5.1.1.

### 6.2.8 Method of Activating Private Key

HiPKICA private key activation is controlled by multi-person controls of the different usage IC cards kept by administrator and CA officer.

Subscribers shall choose a secure computer environment and a trustworthy application system carefully and keep and use the private keys properly.

### 6.2.9 Method of Deactivating Private Key

When the private keys of HiPKICA are not in use, an appropriate deactivation method will be selected to deactivate the private keys in compliance with this CP/CPS. HiPKICA does not provide the deactivate services of subscribe private keys.

### 6.2.10 Method of Destroying Private Key

In order to prevent the theft of HiPKICA private keys which could endanger the authenticity of the entire certificate, the private key must be destroyed at the end of the HiPKICA key lifecycle. Therefore, when HiPKICA completes the key renewal and the Root CA issues a new HiPKICA certificate, after no additional certificates or CRL are issued, zeroization is done on the old HiPKICA private key stored inside the hardware security module to ensure that the old HiPKICA private key is destroyed. In addition to destroying the old HiPKICA private key in the hardware security module, physical destruction of the splitted IC cards with a backed-up key inside shall be done as well during the HiPKICA key renewal.

If services are permanently not provided by a cryptographic module but it is still accessible, all private keys (already used or possibly used) stored in that cryptographic module must be destroyed. After destroying the keys, the key management tools provided by this cryptographic module must be used to verify that the above keys no longer exist.

Subordinate CAs and cross-certified CAs must follow the regulations in this CP/CPS when choosing an appropriate private key destruction method. The destruction method for subscriber private keys is not stipulated.

### 6.2.11. Cryptographic Module Rating

See Section 6.2.1.

## 6.3 Other Aspects of Key Pair Management

### 6.3.1 Public Key Archival

HiPKICA archives certificates issued by it in accordance with Section 5.5.

### 6.3.2 Certificate Operational Periods and Key Pair Usage Periods

#### 6.3.2.1 CA Certificate Operational Periods and Key Pair Usage Periods
Certificates and private keys of HiPKICA’s issuing CAs have maximum validity periods of:

<table>
<colgroup>
<col style="width: 19%" />
<col style="width: 62%" />
<col style="width: 17%" />
</colgroup>
<thead>
<tr>
<th style="text-align: center;"><strong>Type of CA</strong></th>
<th style="text-align: center;"><strong>Private Key Usage</strong></th>
<th style="text-align: center;"><strong>Certificate Term</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td rowspan="4" style="text-align: center;">Root CA</td>
<td colspan="2" style="text-align: center;">Issued before August 1, 2025</td>
</tr>
<tr>
<td style="text-align: center;"><ul>
<li><p>Issuing self-signed certificates: 15 years</p></li>
<li><p>Issuing self-issued certificates: no stipulation</p></li>
<li><p>Issuing cross-certificates: no stipulation</p></li>
<li><p>Issuing subordinate CA certificates: 15 years</p></li>
<li><p>Issuing CRLs, OCSP responder certificates or OCSP responses: 25 years</p></li>
</ul></td>
<td style="text-align: center;">25 years</td>
</tr>
<tr>
<td colspan="2" style="text-align: center;">Issued on or after August 1, 2025</td>
</tr>
<tr>
<td style="text-align: center;"><ul>
<li><p>Issuing self-signed certificates: no stipulation</p></li>
<li><p>Issuing self-issued certificates: no stipulation</p></li>
<li><p>Issuing cross-certificates: no stipulation</p></li>
<li><p>Issuing subordinate CA certificates: no stipulation</p></li>
<li><p>Issuing CRLs, OCSP responder certificates or OCSP responses: 15.5 years</p></li>
</ul></td>
<td style="text-align: center;">15.5 years</td>
</tr>
<tr>
<td rowspan="4" style="text-align: center;">Subordinate CA</td>
<td colspan="2" style="text-align: center;">Issued before August 1, 2025</td>
</tr>
<tr>
<td style="text-align: center;"><ul>
<li><p>Issuing subscriber certificates: 10 years</p></li>
<li><p>Issuing CRLs, OCSP responder certificates or OCSP responses: 20 years</p></li>
</ul></td>
<td style="text-align: center;">20 years</td>
</tr>
<tr>
<td colspan="2" style="text-align: center;">Issued on or after August 1, 2025</td>
</tr>
<tr>
<td style="text-align: center;"><ul>
<li><p>Issuing subscriber certificates: 30 moinths</p></li>
<li><p>Issuing CRLs, OCSP responder certificates or OCSP responses: 3 years</p></li>
</ul></td>
<td style="text-align: center;">3 years</td>
</tr>
</tbody>
</table>

The validity period of the Root CA’s self-signed certificate shall be at least 2,922 days (approximately 8 years).

The expiry date of Subordinate CA certificates or cross-certificates issued by the Root CA must not be greater than the end of the Root CA’s self-signed certificate’s validity period.

The expiry date of the Root CA’s self-issued certificates cross-signed with old and new the Root CA keys shall be equal to the expiry date of the Root CA’s self-signed certificate issued with the old the Root CA key.

After the expiration of the certificate issuance validity period of the issuing CA’s private signing key, the issuing CA shall continue to provide CRLs, OCSP responder certificates, or OCSP responses until all issued certificates have expired.

The maximum validity period for private keys and certificates of an OCSP responder is 36 hours. An OCSP response signed by the OCSP reponder’s private key includes the signature and the OCSP responder certifcate that can be used by relying parties to verify the signature of the OCSP response.

#### 6.3.2.2 Subscriber Certificate Operational Periods and Key Pair Usage Periods
The maximum validity periods of the subscriber certificate and private key are:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr>
<th align="center">
<strong>Type of Cert.</strong>
</th>
<th align="center">
<strong>Private Key Usage Period</strong>
</th>
<th align="center">
<strong>Maximum Validity Period</strong>
</th>
</tr>
</thead>
<tbody>
<tr>
<td>OV TLS Certificates</td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td><ul>
<li>Issued before 1 August 2025</li>
</ul></td>
<td align="center">No stipulation</td>
<td align="center">398 days</td>
</tr>
<tr>
<td><ul>
<li>Issued on or after 1 August 2025 and before 15 March 2029</li>
</ul></td>
<td align="center">No stipulation</td>
<td align="center">90 days</td>
</tr>
<tr>
<td><ul>
<li>Issued on or after 15 March 2029</li>
</ul></td>
<td align="center">No stipulation</td>
<td align="center">47 days</td>
</tr>
</tbody>
</table>

## 6.4 Activation Data

### 6.4.1 Activation Data Generation and Installation

The activation data of HiPKICA’s private key is randomly generated and written to the hardware cryptographic module after completing identity verification for administrators of n-out-of-m control IC cards based on the access control list set during the generation of the afforementioned private key. Administrators must insert their n-out-of-m control IC cards into the card reader built in the hardware cryptographic module and enter the correct personal identification number (PIN) of IC cards when performing identity verification as mentioned above.

### 6.4.2 Activation Data Protection

Activation data is protected by the n-out-of-m control IC cards. Administrators who hold the IC cards are responsible for the safekeeping of the card PIN, which shall not be stored in any media. If the administrator enters the wrong PIN for more than 3 consecutive times, the IC card is locked. During IC card handover, a new PIN is set by the new administrator.

### 6.4.3 Other Aspects of Activation Data

No stipulation.

## 6.5 Computer Security Controls

### 6.5.1 Specific Computer Security Technical Requirements

HiPKICA and related auxiliary systems provide the following security control functions through the operating systems, combined operating systems, software, and physical protection measures:

1)  Trusted role or identity authentication login,

2)  Provide discretionary access control,

3)  Provide security audit capability, and

4)  Access control restrictions for certificate services and PKI trusted roles.

HiPKICA systems are deployed on operating platforms that have undergone security assessments, and the associated hardware, software, and operating systems SHALL operate using security-assessed configurations. HiPKICA SHALL enforce multi-factor authentication (MFA) for all accounts with access to CA Infrastructure. All accounts accessing CA Infrastructure systems SHALL use MFA, including accounts used to access certificate issuance systems, RA systems, certificate status service systems, monitoring systems, management systems, and any other security infrastructure supporting CA operations.

### 6.5.2 Computer Security Rating

HiPKICA servers use Common Criteria EAL 3 or above certified computer operating systems.

### 6.5.3 CA Infrastructure Inventory

HiPKICA maintains and periodically updates an inventory of its CA Infrastructure.

The CA Infrastructure inventory includes hardware, software, and network components that support certificate issuance, certificate lifecycle management, certificate status services, and related security controls. The inventory includes, but is not limited to:

1)  Hardware Components

    - Hardware Security Modules (HSMs)

    - CA Servers

    - Registration Authority (RA) Servers

    - Repository Servers

    - Database Servers

    - Network Switches

    - Firewalls

2)  Software Components

    - Operating Systems

    - Web Server Software

    - Application Software

    - CA System Programs and Administrative Tools

    - Applications developed or supplied by software vendors or system developers

HiPKICA maintains the inventory in accordance with its internal management procedures and updates the inventory whenever relevant hardware, software, or infrastructure components are added, modified, replaced, or removed.

## 6.6 Life Cycle Technical Controls

### 6.6.1 System Development Controls

HiPKICA follows established software engineering methodologies for system development and quality control.

System development, test and production environments shall operate independently to prevent unauthorized access or changes. In addition, HiPKICA may only use dedicated and authorized hardware and software.

RA software shall be checked for malicious code prior to the first use or any version update, and periodic security scans shall be performed to prevent the installation of malicious software.

For each product or program delivered to HiPKICA, it is required to provide the delivery list, test report, and source code analysis report, as well as be under version control.

### 6.6.2 Security Management Controls

HiPKICA shall not install software, hardware or components that are not related to its operation. When installing software onto a CA system, HiPKICA shall first confirm the integrity and correctness of the version and check the integrity of CA software regularly or before each use. In addition, HiPKICA documents and controls any change to the system as well as detecting unauthorized modifications to system software or configurations.

HiPKICA references the methodologies and standards in the ISO/IEC 27001, ISO/IEC 27002, ISO/IEC 27005, ISO/IEC 31000, WebTrust Principles and Criteria for Certification Authorities, Baseline Requirements, and Network and Certificate System Security Requirements for risk assessment, risk management, and security management and control measures.

### 6.6.3 Life Cycle Security Controls

HiPKICA shall conduct a risk assessment at least once a year to determine if there is any risk of compromise for existing keys.

## 6.7 Network Security Controls

HiPKICA implements network security control measures in compliance with the Network and Certificate System Security Requirements.

HiPKICA segments its CA Infrastructure into separate network security zones based on the functional and logical relationships of CA Infrastructure components in order to minimize attack surfaces, limit lateral movement, and protect CA Infrastructure from unauthorized access.

The CA Infrastructure is divided into security zones, including but not limited to:

- Root CA Zone

- Issuing CA Zone

- RA Zone

- Repository and Certificate Status Service Zone

- Monitoring Zone

Communication between security zones is protected through firewalls, network switching infrastructure, access control mechanisms, and other network boundary controls. Only authorized and operationally necessary network traffic is permitted between security zones, and such communications are controlled and monitored in accordance with HiPKICA security management procedures. Each security zone is logically and/or physically separated from other zones according to its operational role and security requirements.

The HiPKICA host and repository have firewalls and are connected to external networks. The repository is placed in the external service area of the firewall (de-militarized zone, DMZ) and connected to the Internet. Except during required maintenance or backup, the repository provides uninterrupted certificate and CRL inquiry services.

The certificates and CRLs issued by the HiPKICA are digitally signed and transmitted to the repository. The HiPKICA repository protects against denial of service and intrusion attacks by system patch updates, system vulnerability scans, intrusion defending/detection systems, firewall systems and filtering routers.

HiPKICA monitors the configuration of access control permissions, continuously monitors system health and security events, and performs penetration tests. Vulnerability scans of networks are performed at least once a quarter, and penetration tests at least annually. Remediation timelines are governed by severity, with critical vulnerabilities assessed within 96 hours and high/medium issues resolved within 45 to 90 days. Exceptions are documented, assessed for risk, and recorded.

## 6.8 Time-stamping

HiPKICA regularly conducts system clock synchronization with a reliable time source to maintain the correctness of system time and ensure the accuracy of the following times. Automatic or manual procedures may be used to adjust the system time, and system clock synchronizations shall be auditable events.

1)  Time of certificate issuance,

2)  Time of certificate revocation,

3)  Time of CRL issuance, and

4)  Time of system event occurrence.

#

# 7. Certificate, CRL, and OCSP Profiles

## 7.1 Certificate Profile

The certificates issued by HiPKICA conform to the official versions of the ITU-T X.509, Baseline Requirements and RFC 5280.

### 7.1.1 Version Number(s)

HiPKICA issues certificates in compliance with RFC 5280 and ITU-T X.509 version 3.

### 7.1.2 Certificate Extensions

See Appendix 3, 3-1, and 3-2 for details.

### 7.1.3 Algorithm Object Identifiers

HiPKICA uses the algorithms listed in the table below for signing certificates and generating key pairs.
<table>
<thead>
<tr>
<th>Purpose</th>
<th>Algorithm</th>
<th>OID</th>
</tr>
</thead>
<tbody>

<tr>
<td rowspan="5" align="center"><strong>Signature</strong></td>
<td>sha256WithRSAEncryption</td>
<td>{iso(1) member-body(2) us(840) rsadsi(113549) pkcs(1) pkcs-1(1) sha256WithRSAEncryption(11)}</td>
</tr>

<tr>
<td>sha384WithRSAEncryption</td>
<td>{iso(1) member-body(2) us(840) rsadsi(113549) pkcs(1) pkcs-1(1) sha384WithRSAEncryption(12)}</td>
</tr>

<tr>
<td>sha512WithRSAEncryption</td>
<td>{iso(1) member-body(2) us(840) rsadsi(113549) pkcs(1) pkcs-1(1) sha512WithRSAEncryption(13)}</td>
</tr>

<tr>
<td>ecdsaWithSHA256</td>
<td>{iso(1) member-body(2) us(840) ansi-x962(10045) signatures(4) ecdsa-with-SHA2(3) ecdsa-with-SHA256(2)}</td>
</tr>

<tr>
<td>ecdsaWithSHA384</td>
<td>{iso(1) member-body(2) us(840) ansi-x962(10045) signatures(4) ecdsa-with-SHA2(3) ecdsa-with-SHA384(3)}</td>
</tr>

<tr>
<td rowspan="2" align="center"><strong>Key Generation</strong></td>
<td>rsaEncryption</td>
<td>{iso(1) member-body(2) us(840) rsadsi(113549) pkcs(1) pkcs-1(1) rsaEncryption(1)}</td>
</tr>

<tr>
<td>ecPublicKey</td>
<td>{iso(1) member-body(2) us(840) ansi-x962(10045) keyType(2) ecPublicKey(1)}</td>
</tr>

</tbody>
</table>

During ECC algorithm is used for generarting ECDSA key pairs, the OIDs of the elliptic curve parameter are set as follows according to the key size:
<table>
<thead>
<tr>
<th align="center">Key Size</th>
<th align="center">Elliptic Curve Parameter</th>
<th align="left">OID</th>
</tr>
</thead>

<tbody>
<tr>
<td align="center">P-256</td>
<td align="center">secp256r1</td>
<td>{iso(1) member-body(2) us(840) ansi-x962(10045) curves(3) prime(1) prime256v1(7)}</td>
</tr>

<tr>
<td align="center">P-384</td>
<td align="center">secp384r1</td>
<td>{iso(1) identified-organization(3) certicom(132) curve(0) ansip384r1(34)}</td>
</tr>
</tbody>
</table>

### 7.1.4 Name Forms

The subject DN and issuer DN fields of a certificate must use the X.500 distinguished name and the name attribute type shall comply with the official versions of the ITU-T X.509, Baseline Requirements and RFC 5280.

#### 7.1.4.1 Name Encoding
According to Section 7.1.4.1 of the Baseline Requirements, the encoded content of the issuer DN field of certificates issued by an issuing CA shall be byte-for-byte identical with the encoded form of the subject DN field of the issuing CA’s certificate. If there are two or more CA certificates, including expired and revoked CA certificates, whose subject DNs can be compared as equal, the encoded content of the subject DN field of the aforementioned certificates shall be byte‐for‐byte identical.

#### 7.1.4.2 Subject Information–CA Certificates
Certificates can be issued after issuing CAs followed the procedures set forth in this CP/CPS to verify that all of the subject information was accurate. For self-signed certificates and subordinate CA certificates issued by Root CA of HiPKI, the subject field includes three attributes, namely “commonName”, “organizationName”, and “countryName”, described as follows:

1)  commonName

    The name used to identify the issuing CA. It is the unique identifier of the certificate and can be used to distinguish the issuing CA’s certificate from other CA certificates.

2)  organizationName

    The official name of the organization to which the issuing CA belongs. It can be adjusted according to the abbreviation method approved by our country. The authentication of this organization name shall be implemented in accordance with Section 3.2.2.

3)  countryName
   
    The country where the place of business that the issuing CA locates. It shall be represented by the country codes specified in ISO 3166-1, which is “TW”.

#### 7.1.4.3 Subject Information–Subscriber Certificates
By issuing the subscriber certificates, HiPKICA represents that they followed the procedures set forth in Section 3.2 of this CP/CPS to verify that, as of the subscriber certificate’s issuance date, all of the subject information was accurate.

For TLS certificates, if the Subject commonName field is present, this field must contain exactly one entry that is one of the values contianed in the subject alternative name extension. In addition, subject attributes MUST NOT contain only metadata such as ‘.’, ‘-’, and ‘ ’ (i.e. space) characters, and/or any other indication that the value is absent, incomplete, or not applicable.

The subject alternative name extension of subscriber certificates must contain at least one entry, which contains either an FQDN or a Wildcard Domain Name. The content must comply with the following requirements:

1)  The FQDN or the Wildcard Domain Name must be validated in accordance with Section 3.2.7.

2)  Wildcard Domain Names must be validated for consistency with Section 3.2.8.

3)  The entry must not contain an Internal Name.

4)  Effective March 15, 2026, the entry must not contain a Domain Name that ends in an IP Address Reverse Zone Suffix.

5)  The FQDN or the FQDN portion of the Wildcard Domain Name contained in the entry must be composed entirely of P-Labels or NR-LDH Labels joined together by a U+002E FULL STOP (“.”) character.

6)  The zero‐length Domain Label representing the root zone of the Internet Domain Name System must not be included.

HiPKICA includes attributes in the Certificate subject field that are listed in the table below, and other attributes not listed shall not be used.

<table>
<colgroup>
<col style="width: 35%" />
<col style="width: 10%" />
<col style="width: 55%" />
</colgroup>

<thead>
<tr>
<th align="center"><strong>Attribute Name</strong></th>
<th align="center"><strong>Presence</strong></th>
<th align="center"><strong>Description</strong></th>
</tr>
</thead>

<tbody>

<tr>
<td nowrap>countryName (C)</td>
<td align="center">MUST</td>
<td>
The two-letter ISO 3166-1 country code for the country associated with the Subject.
</td>
</tr>

<tr>
<td nowrap>localityName (L)</td>
<td align="center">MUST</td>
<td>
The Subject's locality information.
</td>
</tr>

<tr>
<td nowrap>organizationName (O)</td>
<td align="center">MUST</td>
<td>
The Subject's name and/or DBA/tradename.
</td>
</tr>

<tr>
<td nowrap>commonName (CN)</td>
<td align="center">OPTIONAL</td>
<td>
If present, must contain a value corresponding to one of the entries in the subject alternative name extension, which shall be either an FQDN or a Wildcard Domain Name.

<ul>
<li>Certificates issued by HiPKI OV TLS CA on or after August 21, 2025 no longer include this attribute in the subject field.</li>
<li>CHT Trust TLS CA does not use this attribute.</li>
</ul>
</td>
</tr>

</tbody>
</table>

### 7.1.5 Name Constraints

Name constraints are not applied to HiPKICA certificates. Self-signed certificates, self-issued certificates, subordinate CA certificates and cross-certificates, which are not technically constrained, will be disclosed publicly, such as being disclosed in the CCADB.

### 7.1.6 Certificate Policy Object Identifier

HiPKICA certificates, excluding self-signed certificates of the Root CA, must include the certificate policies extension. In addition to the CP OID(s) defined in this CP/CPS, this extension shall also contain the CA/Browser Forum-assigned OID(s) referenced in this CP/CPS according to the certificate purpose. For details regarding the CP OIDs, please refer to Section 1.2 of this CP/CPS.

### 7.1.7 Usage of Policy Constraints Extension

The policy constraints extension may be used as required for subordinate CA certificates and cross-certificates issued by the Root CA. Otherwise, certificates issued by HiPKICA do not contain this extension.

### 7.1.8 Policy Qualifiers Syntax and Semantics

The policy qualifier field in the certificate policies extension of HiPKICA certificates may be used as needed. When using this field, it may contain a CPS pointer qualifier that points to the URL of this CP/CPS.

### 7.1.9 Processing Semantics for the Critical Certificate Policies Extension

The certificate policies extension of the certificates issued by HiPKICA are not marked critical.

## 7.2 CRL Profile

The CRLs issued by HiPKICA comply with the applicable requirements of the Baseline Requirements and the current version of RFC 5280. The CRL fields and extensions are described as follows. For CRLs signed using ECDSA keys, the selection and use of the signature algorithm shall comply with Section 7.1.3.2.2 of the Baseline Requirements.

1)  CRL profile for CRLs issued by Root CAs

    <table>
    <colgroup>
    <col style="width: 26%" />
    <col style="width: 73%" />
    </colgroup>
    <thead>
    <tr>
    <th style="text-align: center;"><strong>Field</strong></th>
    <th style="text-align: center;"><strong>Description</strong></th>
    </tr>
    </thead>
    <tbody>
    <tr>
    <td style="text-align: left;">version</td>
    <td style="text-align: left;">v2</td>
    </tr>
    <tr>
    <td style="text-align: left;">signature</td>
    <td style="text-align: left;">The signature algorithm used to sign CRLs issued by the Root CA and the mapping between the algorithms and their corresponding OIDs are specified in Section 7.1.3.
    <ul>
      <li>
        RSA
        <ol type="a">
          <li>sha256WithRSAEncryption</li>
          <li>sha384WithRSAEncryption</li>
          <li>sha512WithRSAEncryption</li>
        </ol>
      </li>
    
      <li>
        ECDSA
        <ol type="a">
          <li>ecdsaWithSHA384</li>
        </ol>
      </li>
    </ul></td>
    </tr>
    <tr>
    <td style="text-align: left;">issuer</td>
    <td style="text-align: left;">The encoded value must be byte‐for‐byte identical to the subject field of the Root CA’s self-signed certificate.</td>
    </tr>
    <tr>
    <td style="text-align: left;">thisUpdate</td>
    <td style="text-align: left;">Indicates the issue date of the CRL.</td>
    </tr>
    <tr>
    <td style="text-align: left;">nextUpdate</td>
    <td style="text-align: left;">Indicates the date by which the next CRL will be issued. Its definition shall be governed by the provisions specified in Section 4.9.7.</td>
    </tr>
    <tr>
    <td style="text-align: left;">revokedCertificates</td>
    <td style="text-align: left;">The list of all CA certificates revoked by Root CA shall include, at a minimum, the certificate serial number and the revocation date. See the “CRL Entry Extensions” table in Section 7.2.2 for additional requirements of the CRL entry extensions.</td>
    </tr>
    <tr>
    <td style="text-align: left;">extensions</td>
    <td style="text-align: left;">See the “CRL Extensions” table in Section 7.2.2 for additional requirements.</td>
    </tr>
    </tbody>
    </table>

2)  CRL fields of Subordinate CAs

    <table>
    <colgroup>
    <col style="width: 26%" />
    <col style="width: 73%" />
    </colgroup>
    <thead>
    <tr>
    <th style="text-align: center;"><strong>Field</strong></th>
    <th style="text-align: center;"><strong>Description</strong></th>
    </tr>
    </thead>
    <tbody>
    <tr>
    <td style="text-align: left;">version</td>
    <td style="text-align: left;">v2</td>
    </tr>
    <tr>
    <td style="text-align: left;">signature</td>
    <td style="text-align: left;">The signature algorithm used to sign CRLs issued by the Subordinate CA and the mapping between algorithms and their corresponding OIDs are specified in Section 7.1.3.
    <ul>
      <li>
        RSA
        <ol type="a">
          <li>sha256WithRSAEncryption</li>
          <li>sha384WithRSAEncryption</li>
          <li>sha512WithRSAEncryption</li>
        </ol>
      </li>
    
      <li>
        ECDSA
        <ol type="a">
          <li>ecdsaWithSHA256</li>
          <li>ecdsaWithSHA384</li>
        </ol>
      </li>
    </ul>
    </td>
    </tr>
    <tr>
    <td style="text-align: left;">issuer</td>
    <td style="text-align: left;">The encoded value must be byte‐for‐byte identical to the subject field of the Subordinate CA’s self-signed certificate.</td>
    </tr>
    <tr>
    <td style="text-align: left;">thisUpdate</td>
    <td style="text-align: left;">Indicates the issue date of the CRL.</td>
    </tr>
    <tr>
    <td style="text-align: left;">nextUpdate</td>
    <td style="text-align: left;">Indicates the date by which the next CRL will be issued. Its definition shall be governed by the provisions specified in Section 4.9.7.</td>
    </tr>
    <tr>
    <td style="text-align: left;">revokedCertificates</td>
    <td style="text-align: left;">The list of all CA certificates revoked by Subordinate CA shall include, at a minimum, the certificate serial number and the revocation date. See the “CRL Entry Extensions” table in Section 7.2.2 for additional requirements of the CRL entry extensions.</td>
    </tr>
    <tr>
    <td style="text-align: left;">extensions</td>
    <td style="text-align: left;">See the “CRL Extensions” table in Section 7.2.2 for additional requirements.</td>
    </tr>
    </tbody>
    </table>

### 7.2.1 Version Number(s)

HiPKICA issues CRLs complying with RFC 5280 and ITU-T X.509 version 2.

### 7.2.2 CRL and CRL Entry Extensions

The CRL and CRL entry extensions in the CRL issued by HiPKICA comply with the official versions of the ITU-T X.509, Baseline Requirements and RFC 5280. These extensions are described below.

1)  CRL Extensions

    <table>
    <colgroup>
    <col style="width: 19%" />
    <col style="width: 16%" />
    <col style="width: 14%" />
    <col style="width: 49%" />
    </colgroup>
    <thead>
    <tr>
    <th style="text-align: center;"><strong>Extension</strong></th>
    <th style="text-align: center;"><strong>Presence</strong></th>
    <th style="text-align: center;"><strong>Criticality</strong></th>
    <th style="text-align: center;"><strong>Description</strong></th>
    </tr>
    </thead>
    <tbody>
    <tr>
    <td>Authority Key Identifier</td>
    <td align="center">MUST</td>
    <td align="center">N</td>
    <td style="text-align: left;">Only the keyIdentifier field, used to contain the SHA-1 hash value of the issuing CA’s public key, is present in this extension. Its value must be identical to the subjectKeyIdentifier extension of the issuing CA’s certificate.</td>
    </tr>
    <tr>
    <td>CRL Number</td>
    <td align="center">MUST</td>
    <td align="center">N</td>
    <td style="text-align: left;">The CRL number contains an integer value greater than or equal to zero (0) and less than 2¹⁵⁹, and conveys a strictly increasing sequence.</td>
    </tr>
    <tr>
    <td>Issuing Distribution Point</td>
    <td align="center">OPTIONAL</td>
    <td align="center">Y</td>
    <td style="text-align: left;">This extension is only applicable to a partitioned CRL, in which it is defined as a required extension. Its content is as follows:
    <ul>
    <li>The distributionPoint field is present and used to specify the HTTP URL of the issuing CA’s CRL service.</li>
    <li>The indirectCRL and onlyContainsAttributeCerts fields are set to FALSE (i.e., not asserted).</li>
    <li>HiPKICA does not simultaneously assert both the onlyContainsUserCerts and onlyContainsCACerts fields.</li>
    <li>The onlySomeReasons field is not included.</li>
    </ul></td>
    </tr>
    </tbody>
    </table>

2)  CRL Entry Extensions

    <table>
    <colgroup>
    <col style="width: 19%" />
    <col style="width: 16%" />
    <col style="width: 14%" />
    <col style="width: 49%" />
    </colgroup>
    <thead>
    <tr>
    <th style="text-align: center;"><strong>Extension</strong></th>
    <th style="text-align: center;"><strong>Presence</strong></th>
    <th style="text-align: center;"><strong>Criticality</strong></th>
    <th style="text-align: center;"><strong>Description</strong></th>
    </tr>
    </thead>
    <tbody>
    <tr>
    <td nowrap>Reason Code</td>
    <td style="text-align: center;">OPTIONAL</td>
    <td style="text-align: center;">N</td>
    <td style="text-align: left;"><p>This extension is used to indicate the most appropriate reason for revocation of the certificate. If this CRL entry extension is used to identify the revocation reason of self-signed certificates, self-issued certificates, subordinate CA certificates and cross-certificates, the reasonCode value can be the follows:</p>
    <ul>
    <li>caCompromise(2)</li>
    <li>affiliationChanged(3)</li>
    <li>superseded(4)</li>
    <li>cessationOfOperation(5)</li>
    <li>privilegeWithdrawn(9)</li>
    </ul>
    <p>When the CRL entry extension is used to indicate the revocation reason for subscriber certificates, the corresponding reasonCode value and its applicable scenario are as follows:</p>
    <ul>
    <li>unspecified (0): No specific reason for certificate revocation is provided. If the use of this reason code is permitted, the extension shall be omitted.</li>
    <li>keyCompromise(1): It is known or suspected that the subscriber’s private key has been compromised.</li>
    <li>affiliationChanged(3): The subject name or other subject identity information in the subscriber certificate has changed, but there is no cause to suspect that the private key corresponding to the public key included in the certificate has been compromised.</li>
    <li>superseded(4): The certificate is being replaced by a new one, for reasons that may include (but are not limited to) the following:
    
    <ol type="a">
    <li>The subscriber has requested a new certificate.</li>
    <li>HiPKICA has reasonable evidence that the validation of domain authorization or control for any FQDN in the certificate should not be relied upon.</li>
    <li>The certificate has been revoked for compliance reasons, such as non-conformance with the provisions of the Baseline Requirements or this CP/CPS.</li>
    </ol>
    </li>
    
    <li>cessationOfOperation(5): The website with the certificate is shut down prior to the expiration of the certificate, or if the subscriber no longer owns or controls the domain name in the certificate prior to the expiration of the certificate.</li>
    <li>privilegeWithdrawn(9): There has been a subscriber-side infraction that has not resulted in keyCompromise, such as the certificate subscriber provided misleading information in their certificate request or has not upheld their material obligations under the Subscriber Agreement.</li>
    </ul></td>
    </tr>
    </tbody>
    </table>

## 7.3 OCSP Profile

If HiPKICA provides OCSP services in compliance with RFC 6960 and/or RFC 5019, the HTTP URL of the issuing CA’s OCSP responder shall be included in the authority Information access extension of certificates issued by HiPKICA, excluding self-signed certificates issued by the Root CA.

### 7.3.1 Version Number(s)

An OCSP request accepted by HiPKICA shall contain the following information:

- Protocol version; and

- Target certificate identifier.

An OCSP response, issued by the OCSP responder, at a minimum consists of a responseStatus field indicating the processing status of the prior request. If the value of responseStatus is ‘successful’, the OCSP response must further include the other fields as follows:

<table>
<colgroup>
<col style="width: 36%" />
<col style="width: 63%" />
</colgroup>
<thead>
<tr>
<th style="text-align: center;"><strong>Field</strong></th>
<th style="text-align: center;"><strong>Description</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td>Version</td>
<td>v.1</td>
</tr>
<tr>
<td nowrap>OCSP Responder ID</td>
<td>The subject DN of OCSP responder</td>
</tr>
<tr>
<td nowrap>Produced Time</td>
<td style="text-align: left;">The time at which the OCSP response was signed</td>
</tr>
<tr>
<td style="text-align: left;" nowrap>Target Certificate Identifier</td>
<td>The contents of this field include the hash algorithm, the hash of the issuer’s DN, the hash of the issuer’s public key and the serial number of the target certificate.</td>
</tr>
<tr>
<td nowrap>Certificate Status</td>
<td style="text-align: left;">The meaning of certificate status value is described below:
<ul>
<li>0: valid</li>
<li>1: revoked<p>
    When this status value is used, this field shall also contain the revocation time and reason of that certificate. The revocationReason field within the RevokedInfo of the CertStatus shall be identical to the CRLReason of the revoked certificate noted in the CRL (See Section 7.2.2).</li>
<li>2: unknown</li>
</ul>
</td>
</tr>
<tr>
<td nowrap>Validity Period</td>
<td style="text-align: left;">Recommended validity period for this OCSP response, including ThisUpdate and NextUpdate</td>
</tr>
<tr>
<td nowrap>Signature Algorithm</td>
<td style="text-align: left;">OCSP response signature algorithm, which can be either:
<ul>
<li>sha256WithRSAEncryption, or</li>
<li>ecdsaWithsha384</li>
</ul></td>
</tr>
<tr>
<td>Signature</td>
<td>OCSP responder signature</td>
</tr>
<tr>
<td>Certificates</td>
<td>OCSP responder certificate</td>
</tr>
</tbody>
</table>

### 7.3.2 OCSP Extensions

The singleExtensions of an OCSP response MUST NOT contain the reasonCode (OID 2.5.29.21) CRL entry extension.

#

# 8. Compliance Audit and Other Assessments

## 8.1 Frequency or Circumstances of Assessment

HiPKICA shall undergo routine external audits at least once per year (the audited period may not exceed 12 months) and non-routine internal audits to confirm that the security regulations and procedures of this CP/CPS are being implemented and enforced.

## 8.2 Identity/Qualifications of Assessor

HiPKICA entrusts external audit operations to qualified auditors, who is familiar with the operations of HiPKICA and authorized by the WebTrust Principles and Criteria for Certification Authorities program management unit to implement relevant WebTrust Principles and Criteria for Certification Authorities audit criteria in R.O.C., to provide impartial and objective audit services. Audit personnel shall be a certified information system auditor or a person who has equivalent qualification; and shall at least possess the experience of conducting a WebTrust Principles and Criteria for Certification Authorities seal audit twice at 4 man-days or the experience of conducting a CA information security management audit twice at 8 man-days. HiPKICA shall conduct identity identification of auditors during audits.

## 8.3 Assessor’s Relationship to Assessed Entity

CHT shall entrust an impartial third party to conduct audits of HiPKICA operations.

## 8.4 Topics Covered by Assessment

HiPKICA undergoes the audit schemes of

- “WebTrust Principles and Criteria for Certification Authorities”;

- “WebTrust Principles and Criteria for Certification Authorities – TLS Baseline”; and

- “WebTrust Principles and Criteria for Certification Authorities – Network Security”.

The assessment shall include the following topics:

1)  Whether HiPKICA is operating in accordance with this CP/CPS, including management and technical audit of the physical environment, personnel procedural controls, key control, certificate lifecycle control, and hardware cryptographic module control, and assess whether the requirements are appropriate for the practical operation of HiPKICA; and

2)  Confirm whether the RA is operated in accordance with this CP/CPS and related procedures.

HiPKICA has the right to conduct the review and examination of the following (but not limited to) items to ensure its trustworthiness:

1)  If there is an event of computer emergency or key compromise that causes HiPKICA to reasonably suspect the RA is unable to comply with this CP/CPS;

2)  If the compliance audit has not been completed or there are special developments, HiPKICA has the right to conduct a risk management review; or

3)  If action or inaction by the RA causes actual or potential security and integrity threat to HiPKI, HiPKICA must conduct the related review or examination.

HiPKICA has the right to retain a third-party auditor to perform audit and examination functions. The audited RA shall provide full and reasonable cooperation with HiPKICA and the personnel conducting the audit and examination.

## 8.5 Actions Taken as a Result of Deficiency

If audit personnel find a discrepancy between the requirements of this CP/CPS and the design, operation, or maintenance of HiPKICA or its RA, the following actions shall be taken:

1)  Note the discrepancy,

2)  Notify HiPKICA about the discrepancy, and

3)  HiPKICA shall submit an improvement plan regarding the discrepancy items within 30 days and promptly implement it. The discrepancy items shall also be listed as follow-up audit tracking items. The RA is notified to make improvements to RA-related deficiencies.

## 8.6 Communications of Results

Except for any audit findings that could result in system attacks and the stipulations in Section 9.3, HiPKICA shall make its audit report publicly available. Audit results are displayed with appropriate seals, including WebTrust for Certification Authorities, WebTrust for Certification Authorities – TLS Baseline and WebTrust for Certification Authorities – Network Security seals, on HiPKICA’s homepage. The audit report and management’s assertions may be viewed by clicking on the seals. HiPKICA should make its audit report and management’s assertions publicly available no later than three months after the end of the audit period. In the event of a delay greater than three months, HiPKICA shall provide an explanatory letter signed by the qualified auditor.

## 8.7 Self Audits

According to the Baseline Requirements and WebTrust for CA – TLS Baseline, HiPKICA must assign auditors to perform self-audits on at least a quarterly basis against a randomly selected sample of the greater of one certificate or at least three percent of the certificates issued by it during the period commencing immediately after the previous self-audit sample was taken.

# 9. Other Business and Legal Matters

## 9.1 Fees

### 9.1.1 Certificate Issuance or Renewal Fees

The fee calculation framework for certificate application and issuance between HiPKICA and subscribers shall be stipulated in the related business contract terms and conditions and subscribers may directly connect to the repository to check related terms and conditions.

### 9.1.2 Certificate Access Fees

Certificate access fees are stipulated in related contract terms and conditions and subscribers may directly connect to the repository to check related terms and conditions.

### 9.1.3 Revocation or Status Information Access Fees

Fees may not be charged for subscriber CRL downloading or access. The fee calculation framework for OCSP service is stipulated in related contract terms and conditions. Subscribers may directly connect to the repository for inquiry.

### 9.1.4 Fees for Other Services

No stipulation.

### 9.1.5 Refund Policy

With regard to the certificate issuance fee charged by HiPKICA, if a subscriber is unable to use a certificate due to oversight by HiPKICA, HiPKICA shall issue a new certificate after conducting an investigation. If the subscriber does not accept the newly issued certificate, HiPKICA shall refund the fee to the subscriber. Except for the above circumstances and circumstances in section 4.9, other fees shall not be refunded.

## 9.2 Financial Responsibility

### 9.2.1 Insurance Coverage

HiPKICA is owned and operated by CHT. Its financial responsibilities are the responsibility of CHT.

### 9.2.2 Other Assets

HiPKICA finances are a part of the overall finances of CHT. CHT is a publicly listed company. In accordance with Article 36 of the Securities and Exchange Act, annual financial reports duly audited and attested by a certified public accountant, approved by the board of directors and recognized by the supervisors, are publically announced and registered with the competent authority within three months after the close of each fiscal year. Financial reports duly reviewed by a certified public accountant and reported to the board of directors are publicly announced and registered within 45 days after the end of the first, second and third quarters of each fiscal year. The operating status for the preceding month is publicly announced and registered within the first 10 days of each month. HiPKICA can provide self-insured asset prices based on CHT’s financial reports. CHT’s finances are sound and its ratio of current assets to current liabilities is no lower than 1.0 which meets the requirement of the CA/Browser Forum Guidelines for the Issuance and Management of Extended Validation Certificates.

### 9.2.3 Insurance or Warranty Coverage for End‐Entities

No stipulation.

## 9.3 Confidentiality of Business Information

### 9.3.1 Scope of Confidential Information

The following information generated, received and kept by HiPKICA or its RA is deemed confidential information:

1)  Private keys and passphrases used for operations,

2)  Key splitting safekeeping information,

3)  Subscriber application information,

4)  Audit and tracking logs generated or kept by HiPKICA,

5)  Audit logs and reports made by audit personnel during the audit process, and

6)  Operation-related documents listed as confidential level.

Current and departed personnel in HiPKICA and RA and audit personnel shall keep secrets for the aforementioned confidential information.

### 9.3.2 Information Not Within the Scope of Confidential Information

1)  Identification information and information listed in the certificate are not deemed confidential information unless stipulated otherwise, and

2)  Information of issued certificates, revoked certificates and CRLs published in the HiPKICA repository are not deemed confidential information.

### 9.3.3 Responsibility to Protect Confidential Information

HiPKICA shall handle subscriber application information in accordance with the related audit criteria of WebTrust Principles and Criteria for Certification Authorities, Baseline Requirements, and Personal Information Protection Act and its related sub-laws.

## 9.4 Privacy of Personal Information

### 9.4.1 Privacy Plan

HiPKICA has posted its personal information statement and privacy declaration on its website. HiPKICA conducts privacy impact analysis and personal information risk assessments and has established a privacy protection plan.

### 9.4.2 Information Treated as Private

Private information includes:

1)  The personal information listed on certificate applications should not be disclosed without the subscriber’s consent or in accordance with related laws,

2)  Subscriber information that cannot be obtained through certificates, CRLs or certificate catalog service,

3)  Personnel identifiable information in HiPKICA such as names together with palmprint or fingerprint biometrics, and

4)  Personal information on confidentiality agreements or contracts.

HiPKICA and its RAs implement security control measures to prevent personally identifiable information from unauthorized disclosure, leakage, or damage.

### 9.4.3 Information Not Deemed Private

The following information not deem as private:

1)  Identification information, information listed in certificates, and certificates are not deemed private information unless stipulated otherwise, and

2)  Information on issued certificates, revoked certificates and CRLs published in the HiPKICA repository are not private information.

### 9.4.4 Responsibility to Protect Private Information

The personal information required for the operation of HiPKICA, in either paper or digital form, must be handled in accordance with Personal Information Protection Act and its related sub-laws and privacy rights declaration posted on the website. HiPKICA shall negotiate the liability of protecting private information with its RA.

### 9.4.5 Notice and Consent to Use Private Information

Pursuant to the Personal Information Protection Act and its related sub-laws, personal information shall not be used for other purposes without the consent of subscriber or unless stipulated otherwise in Personal Information Protection Act, privacy rights declaration or this CP/CPS. Subscribers may inquire their application information specified in Section 9.3.1 paragraph (3); however, HiPKICA reserves the right to charge reasonable fees from subscribers applying for access to this information.

### 9.4.6 Disclosure Pursuant to Judicial or Administrative Process

If judicial, supervisory or law enforcement authorities need to check private information under Section 9.3.1 due to one of the following conditions, the matter shall be handled in accordance with law or regulation:

1)  The provisions of government decrees and the legal authorization of the competent authority; or

2)  The court handles disputes arising from the use of certificates and legal application needs for arbitration.

Otherwise, the registered personal information and identification-related information of subscribers will never be arbitrarily provided to the competent authority or any other person.

### 9.4.7 Other Information Disclosure Circumstances

Subscriber personal information obtained during HiPKICA operations is handled in accordance with related laws and may not be disclosed externally, unless stipulated otherwise under the law.

## 9.5 Intellectual Property Rights

The following is the intellectual property of HiPKICA:

1)  Related documents or system development for certificate management of HiPKICA;

2)  Certificates and CRLs issued by HiPKICA; and

3)  This CP/CPS.

This CP/CPS is available for free download from the repository or reasonable use according to the relevant provisions in the Copyright Act of R.O.C. This CP/CPS can be used reasonably and no fee will be charged. HiPKICA reserves the right to pursue legal action for any violation of the use or dissemination of this CP/CPS.

## 9.6 Representations and Warranties

### 9.6.1 CA Representations and Warranties

HiPKICA represents and warrants to the Certificate Beneficiaries including Subscribers, Relying Parties, and Application Software Suppliers that, during the period when the Certificate is valid, HiPKICA complies with this CP/CPS in issuing and managing the Certificate.

The Certificate Warranties specifically include, but not limited to, the following:

1)  **Right to Use Domain Name**: That, at the time of issuance, HiPKICA (i) implemented a procedure for verifying that the Applicant either had the right to use, or had control of, the Domain Name(s) listed in the Certificate’s subject field and subjectAltName extension (or, only in the case of Domain Names, was delegated such right or control by someone who had such right to use or control); (ii) followed the procedure when issuing the Certificate; and (iii) accurately described the procedure in this CP/CPS (see Section 3.2);

2)  **Authorization for Certificate**: That, at the time of issuance, HiPKICA (i) implemented a procedure for verifying that the Subject authorized the issuance of the Certificate and that the Applicant Representative is authorized to request the Certificate on behalf of the Subject; (ii) followed the procedure when issuing the Certificate; and (iii) accurately described the procedure in this CP/CPS (see Section 3.2.5);

3)  **Accuracy of Information**: That, at the time of issuance, HiPKICA (i) implemented a procedure for verifying the accuracy of all of the information contained in the Certificate; (ii) followed the procedure when issuing the Certificate; and (iii) accurately described the procedure in this CP/CPS (see Sections 3.2.2, 3.2.3 and 3.2.9);

4)  **No Misleading Information**: That, at the time of issuance, HiPKICA (i) implemented a procedure for reducing the likelihood that the information contained in the Certificate’s subject:organizationalUnitName attribute would be misleading; (ii) followed the procedure when issuing the Certificate; and (iii) accurately described the procedure in this CP/CPS (see Sections 3.2.2, 3.2.3 and 3.2.9);

5)  **Identity of Applicant**: That, if the Certificate contains Subject Identity Information, HiPKICA (i) implemented a procedure to verify the identity of the Applicant in accordance with Sections 3.2.2 and 3.2.3; (ii) followed the procedure when issuing the Certificate; and (iii) accurately described the procedure in this CP/CPS;

6)  **Subscriber Agreement**: That, if HiPKICA and Subscriber are not Affiliated, the Subscriber and HiPKICA are parties to a legally valid and enforceable Subscriber Agreement that satisfies the Baseline Requirements, or, if HiPKICA and Subscriber are the same entity or are Affiliated, the Applicant Representative acknowledged the Terms of Use;

7)  **Status**: That HiPKICA maintains a 24 x 7 publicly-accessible Repository with current information regarding the status (valid or revoked) of all unexpired Certificates (see Section 4.10.2); and

8)  **Revocation**: That HiPKICA will revoke the Certificate for any of the reasons specified in the Baseline Requirements (see Section 4.9.1).

### 9.6.2 RA Representations and Warranties

Certificate subject identity check is done for certificates issued by HiPKICA. Its checking level is the review results of the RAO at that time of validation, but no guarantee is provided for the credit status, financial capability, technical capability or reliability of the subscriber.

RAs shall represent and warrant that:

1)  Certificate verification is performed in compliance with this CP/CPS;

2)  All information provided to the issuing CA does not contain any false or misleading information;

3)  Translations performed by the RA are an accurate translation of the original information;

4)  All Certificates requested by the RA meet the requirements of this CP/CPS;

5)  Identification and authentication procedures for RAO are implemented; and

6)  RA private keys are securely managed.

### 9.6.3 Subscriber Representations and Warranties

For the express benefit of HiPKICA and the Certificate Beneficiaries, the Applicant shall warrant that, prior to the issuance of a certificate, HiPKICA will obtain, either:

1)  The Applicant’s agreement to the Subscriber Agreement with HiPKICA, or

2)  The Applicant’s acknowledgement of the Terms of Use.

The Subscriber Agreement, Subscriber Terms of Use, or any online resource referenced therein SHALL inform Subscribers of the available certificate revocation reason options and provide an explanation of the circumstances under which each revocation reason applies, so that Subscribers may select the appropriate revocation reason when submitting a certificate revocation request.

Applicants (or human sponsor for device certificates or agent under a subcontractor or hosting service relationship) shall represent and warrant to HiPKICA that it will:

1)  Securely generate its private keys and prevent its private keys from compromise,

2)  Provide accurate and complete information to HiPKICA and RA,

3)  Comply with the stipulations and procedures in Chapters 3 and 4,

4)  Confirm the accuracy of certificate data prior to using the certificate,

5)  Promptly notify HiPKICA, cease using a certificate, and request revocation of the certificate, if

-  any information in the certificate is or becomes incorrect or inaccurate, or
-  there is any actual or suspected misuse or compromise of the Subscriber’s private key associated with the public key included in the certificate (and cease using the private key),

6)  Use the certificate only for legal and authorized purposes, consistent with this CP/CPS and Subscriber Agreement, i.e., only installing TLS certificates on servers accessible at the domain listed in the certificate, and

7)  Promptly cease using the certificate and related private key after the certificate’s expiration.

### 9.6.4 Relying Party Representations and Warranties

Each relying party represents and warrants to:

1)  Comply with the provisions of this CP/CPS when using a certificate or querying the HiPKICA repository;

2)  Check the certificate assurance level before using it;

3)  Check the keyUsage field listed in the certificate prior to the use of certificates;

4)  Validate a certificate (issued by HiPKICA) by using a CRL or OCSP published by HiPKICA to confirm the validity;

5)  Carefully select secure computer environments and reliable application systems. If the rights of subscribers and relying parties are infringed due to the use of an untrusted computer environment or application system, relying parties shall bear the responsibility solely;

6)  Seek other ways for completion of legal acts as soon as possible if HiPKICA is unable to operate normally for some reason. It may not be a cause of defending others that HiPKICA is not function properly; and

7)  Have understood and agreed to the legal liability clauses of HiPKICA and will use the certificate in accordance with Section 1.4.1 when accepting the certificate.

If there is a violation, relying parties shall bear liability for damages in accordance with the Civil Code and related laws and regulations.

### 9.6.5 Representations and Warranties of Other Participants

No stipulation.

## 9.7 Disclaimers of Warranties

Except to the extent prohibited by law or as otherwise provided herein, HiPKICA disclaims all express and implied warranties including all warranties of merchantability or fitness for a particular purpose.

## 9.8 Limitations of Liability

Except to the extent HiPKICA has issued and managed the certificate in accordance with the Baseline Requirements and this CP/CPS, HiPKICA shall not be liable to the subscribers or relying parties for any losses suffered as a result of use or reliance on such certificate. Otherwise, HiPKICA will assume compensation liability no more than the amount stipulated in Section 9.9 of this CP/CPS.

## 9.9 Indemnities

### 9.9.1 Indemnification by HiPKICA

If subscribers or relying parties suffer damages due to the intentional or unintentional failure of HiPKICA to follow this CP/CPS, relevant laws or the provisions of contracts signed between HiPKICA and subscribers/relying parties when processing subscriber certificate-related work, HiPKICA shall be held liable. Subscribers may claim compensation for damages based on the related provisions of the contract set down between HiPKICA (or its RA) and subscribers. Relying parties shall request compensation in accordance with laws and regulations. The total compensation limit of HiPKICA for each subscriber or relying party is shown in the Table below. If the subscriber or relying party has signed a contract with HiPKICA, the certificate scope of use and transaction compensation limit shall be determined separately.

| **Certificate Assurance Level** | **Compensation Limit (NTD)** |
|:-------------------------------:|:----------------------------:|
|             Level 1             |            3,000             |
|             Level 2             |           100,000            |
|             Level 3             |          3,000,000           |
|             Level 4             |          5,000,000           |

These compensation limits are the maximum compensation amounts. The actual compensation amounts are based on the actual damage incurred by the subscribers or relying parties.

### 9.9.2 Indemnification by RA

If subscribers or relying parties suffer damages due to the RA intentional or unintentional failure to follow this CP/CPS, related laws or the provisions of contracts signed between the RA and subscribers/relying parties when processing subscriber certification registrations, HiPKICA is only responsible for compensation for the RA established by HiPKICA, and the compensation limits are detailed in Section 9.9.1. For other RA not established by HiPKICA, the RA takes responsibility for compensation. If the RA and subscribers or relying parties have a contract determing the usage of certificates and transaction compensation amounts, then the contract takes precedence. Compensation claims by subscribers shall be made in accordance with the related provisions in the contract set down with the RA. Compensation claims by relying parties shall be made in accordance with relevant laws and regulations.

## 9.10 Term and Termination

### 9.10.1 Term

This CP/CPS is effective when approved by the PMA and published to HiPKICA’s repository.

### 9.10.2 Termination

The new version of this CP/CPS is published after being approved by the PMA, and the current version is terminated.

### 9.10.3 Effect of Termination and Survival

The effect of this CP/CPS remains valid until the expiration or revocation of the last certificate issued according to this CP/CPS.

## 9.11 Individual Notices and Communications with Participants

HiPKICA, RAs, subscribers, and relieved parties shall adopt suitable methods for establishing mutual notification and communication channels including but not limited to official document, letter, telephone, fax, email or secure email.

## 9.12 Amendments

### 9.12.1 Procedure for Amendment

This CP/CPS is reviewed annually, and an assessment is made to determine if the CP/CPS needs to be amended to maintain its assurance level. This CP/CPS shall be amended accordingly if the Baseline Requirements are amended, and if so, changes to this CP/CPS are indicated by appropriate numbering. The new version of this CP/CPS will be published according to the regulations stated in Section 2.3.

### 9.12.2 Notification Mechanism and Period

HiPKICA will post appropriate notice on its websites of any major or significant changes to this CP/CPS as well as any appropriate period by when the revised CP/CPS becomes effective. If subscribers or relying parties have any comment on the change items, they can submit the comment within the comment period. Reassessment to the changes and response may or may not be made by HiPKICA according to these comments.

No further notice will be given in case of the typesetting of this CP/CPS.

### 9.12.3 Circumstances under which OID Must Be Changed

If modifications to this CP/CPS impact the stated certificate usage or assurance levels, the CP OID shall be updated accordingly.

## 9.13 Dispute Resolution Provisions

In the event of a dispute between subscribers/RA and HiPKICA, the parties shall resolve the dispute under the principle of good faith. In the event of litigation, the parties agree that Taiwan Taipei District Court shall be the court of first instance.

## 9.14 Governing Law

For disputes involving HiPKICA issued certificates, the applicable ROC laws shall govern.

## 9.15 Compliance with Applicable Law

Related ROC laws must be followed regarding the interpretation of any agreement signed based on this CP/CPS.

## 9.16 Miscellaneous Provisions

### 9.16.1 Entire Agreement

The commitments set forth in this CP/CPS constitute the entire agreement between the participants (HiPKICA, RAs, subscribers and relying parties).

### 9.16.2 Assignment

The participants describe in this CP/CPS may not assign or delegate their rights or obligations under this CP/CPS to other parties in any form without prior notice to HiPKICA.

### 9.16.3 Severability

If any chapter of this CP/CPS is held invalid or unenforceable by a competent court or tribunal, the remainder of this CP/CPS will remain valid and enforceable.

This CP/CPS complies with the Baseline Requirements; however, if there is any inconsistency between the related domestic laws followed by this CP/CPS and the Baseline Requirements, this CP/CPS may be adjusted to satisfy the requirements of the laws, and such adjustment shall be notified to CA/Browser Forum. If the domestic laws are not applicable anymore, or CA/Browser Forum revises the contents of the Baseline Requirements to be compatible with the domestic laws, this CP/CPS will delete and amend the adjusted contents. The aforesaid actions shall be completed within 90 days.

### 9.16.4 Enforcement (Attorney’s Fees and Waiver of Rights)

In the event that HiPKICA suffers damages attributable to an intentional or unintentional violation of this CP/CPS by a subscriber or relying party, HiPKICA may seek compensation for damages and indemnification and attorneys’ fees related to the dispute or litigation from the responsible party.

HiPKICA’s failure to assert rights with regard to the violation of this CP/CPS to the party does not waive HiPKICA’s right to pursue the violation of this CP/CPS later or in the future.

### 9.16.5 Force Majeure

HiPKICA is not liable for any delay or failure to perform an obligation under this CP/CPS to the extent that the delay or failure is caused by a force majeure or other circumstances not attributable to HiPKICA, including natural disasters, wars, or terrorism which may cause the interruption of telecommunications network. HiPKICA has set clear limitations for certificate usage and is not bear any legal responsibility for damages caused by exceeding these usage limitations.

## 9.17 Other Provisions

No stipulation.

#  Appendix 1: Acronyms and Definitions

| **Acronyms** | **Full Name** | **Definition** |
|----|----|:---|
| AIA | Authority Information Access | See Appendix 2. |
| CA | Certification Authority | See Appendix 2. |
| CAA | Certification Authority Authorization | See Appendix 2. |
| CPA | Chartered Professional Accountants Canada | See Appendix 2. |
| CP OID | CP Object Identifier |  |
| CPS | Certification Practice Statement | See Appendix 2. |
| CRL | Certificate Revocation List | See Appendix 2. |
| DN | Distinguished Name |  |
| DNS | Domain Name System | See Appendix 2. |
| EE | End Entities | See Appendix 2. |
| FIPS | (US Government) Federal Information Processing Standard | See Appendix 2. |
| FQDN | Fully Qualified Domain Name | See Appendix 2. |
| IANA | Internet Assigned Numbers Authority, IANA | See Appendix 2. |
| IDN | Internationalized Domain Name | See Appendix 2. |
| IETF | Internet Engineering Task Force | See Appendix 2. |
| NIST | (US Government) National Institute of Standards and Technology | See Appendix 2. |
| OCSP | Online Certificate Status Protocol | See Appendix 2. |
| OID | Object Identifier | See Appendix 2. |
| OV | Organization Validation | See Appendix 2. |
| PIN | Personal Identification Number |  |
| PKCS | Public-Key Cryptography Standard | See Appendix 2. |
| PKI | Public Key Infrastructure | See Appendix 2. |
| RA | Registration Authority | See Appendix 2. |
| RFC | Request for Comments | See Appendix 2. |
| SSL | Secure Sockets Layer | See Appendix 2. |
| TLS | Transport Layer Security | See Appendix 2. |
| UPS | Uninterrupted Power System | See Appendix 2. |

# Appendix 2: Glossary

<table>
<colgroup>
<col style="width: 28%" />
<col style="width: 71%" />
</colgroup>
<tbody>
<tr>
<td>Access</td>
<td style="text-align: left;">
  Use the information processing capabilities of system resources
</td>
</tr>
<tr>
<td>Access Control</td>
<td style="text-align: left;">
  Authorization procedure for access to information system resources given to subscribers, programs, procedures and other systems.
</td>
</tr>
<tr>
<td>Activation Data</td>
<td style="text-align: left;">
  Private data, other than keys, that are required to access cryptographic modules and that need to be protected (i.e., unlock private keys for signing or decryption events).
</td>
</tr>
<tr>
<td>Applicant</td>
<td style="text-align: left;">
  Subscribers who request certificates from a CA and have not yet completed the certificate procedure.
</td>
</tr>
<tr>
<td>Archive</td>
<td style="text-align: left;">
  A physically separate storage site for long-term information (storage site for important information) which can be used to support audit, usage and integrity services.
</td>
</tr>
<tr>
<td>Assurance</td>
<td style="text-align: left;">
  A basis that the trusted entity has complied with certain security requirements. [Article 2-1, Chapter 1, Regulations on Required Information for Certification Practice Statements]
</td>
</tr>
<tr>
<td>Assurance Level</td>
<td style="text-align: left;">
  A certain level in a relative assurance tier. [Article 2-2, Chapter 1, Regulations on Required Information for Certification Practice Statements]
</td>
</tr>
<tr>
<td>Audit</td>
<td style="text-align: left;">
  Assessment of whether system controls are adequate and ensure conformance with existing policy and operation procedures, and independent checking and review of recommended required improvements to existing controls, policies and procedures.
</td>
</tr>
<tr>
<td>Audit Data</td>
<td style="text-align: left;">
  Activity logs of a system organized in the order of time of occurrence that can be used to reconstruct or investigate the time sequence or changes that occurred during a certain event.
</td>
</tr>
<tr>
<td>Authenticate</td>
<td style="text-align: left;">
  <ol type="1">
  <li>Authentication is the process by which a claimed identity is verified. [A Guide to Understanding Identification and Authentication in Trusted Systems, National Computer Security Center]</li>
  <li>Determination of identity authenticity when an identity of a certain entity is shown.</li>
  </ol>
</td>
</tr>
<tr>
<td>Authentication</td>
<td style="text-align: left;">
  <ol type="1">
  <li>The process of establishing confidence in user identities electronically presented to an information system. [NIST.SP.800-63-2 Electronic Authentication Guideline]</li>
  <li>Safety measures used to secure data transmission or ways to authorize the privilege of individuals upon receiving certain types of information.</li>
  <li>Authentication is the process by which a claimed identity is verified. [A Guide to Understanding Identification and Authentication in Trusted Systems]</li>
  </ol>
Mutual authentication means that the authentication is performed between two parties during communication.</td>
</tr>
<tr>
<td>Authority Information Access (AIA)</td>
<td style="text-align: left;">Records extensions related to certificate authority information access. The content may include: OCSP service sites and certificate issuance authority certificate verification path downloading site.</td>
</tr>
<tr>
<td>Authorization Domain Name</td>
<td style="text-align: left;">The Domain Name used to obtain authorization for certificate issuance for a given FQDN. The CA may use the FQDN returned from a DNS CNAME lookup as the FQDN for the purposes of domain validation. If the FQDN contains a wildcard character, then the CA MUST remove all wildcard labels from the left most portion of requested FQDN. The CA may prune zero or more labels from left to right until encountering a Base Domain Name and may use any one of the intermediate values for the purpose of domain validation.</td>
</tr>
<tr>
<td>Backup</td>
<td style="text-align: left;">Information or program copying that can be used for recovery purposes when needed.</td>
</tr>
<tr>
<td>Base Domain Name</td>
<td style="text-align: left;">The portion of an applied‐for FQDN that is the first domain name node left of a registry controlled or public suffix plus the registry‐controlled or public suffix (e.g. "example.co.uk" or "example.com"). For FQDNs where the right‐most domain name node is a gTLD having ICANN Specification 13 in its registry agreement, the gTLD itself may be used as the Base Domain Name.</td>
</tr>
<tr>
<td>Baseline Requirements</td>
<td style="text-align: left;">“The Baseline Requirements for the Issuance and Management of Publicly-Trusted Certificates” issued by CA/Browser Forum, and all the amendments.</td>
</tr>
<tr>
<td>Binding</td>
<td style="text-align: left;">The process for binding (connecting) two related information elements.</td>
</tr>
<tr>
<td>CA Certificate</td>
<td style="text-align: left;">Certificates issued by CAs.</td>
</tr>
<tr>
<td>CA Key Pair</td>
<td style="text-align: left;">A Key Pair where the Public Key appears as the Subject Public Key Info in one or more Root CA Certificate(s) and/or Subordinate CA Certificate(s).</td>
</tr>
<tr>
<td>Certificate</td>
<td style="text-align: left;">
  <ol type="1">
  <li>Refers to verification information carrying a digital signature used to verify the identity and qualifications of the signer in electronic form [Article 2-6, Electronic Signatures Act]</li>
  <li>Digital presentation of information. The contents include:</li>
  </ol>
<ol type="A">
<li>Issuing certificate authority</li>
<li>Subscriber name or identity</li>
<li>Subscriber public key</li>
<li>Certificate validity period</li>
<li>Certification authority digital signature</li><p>
</ol>
The term ‘certificate’ referred to this CP/CPS specifically refers to ITU-T X.509 v.3 format certificates which states the certificate policy object identifier in the ‘certificate policy’ field.</td>
</tr>
<tr>
<td>Certification Authority (CA)</td>
<td style="text-align: left;">
  <ol type="1">
  <li>The agency or natural person that issues certificate [Article 2-5, Electronic Signatures Act]</li>
  <li>The competent body trusted by the subscriber. Its functions are the issuance and administration of ITU-T X.509 format public key certificates, and CRLs.</li>
  </ol>
</td>
</tr>
<tr>
<td>Certification Authority Authorization (CAA)</td>
<td style="text-align: left;">The certification authority authorization (CAA) DNS resource record allows a DNS domain name holder to specify one or more certification authorities (CAs) authorized to issue certificates for that domain. CAA resource records allow a public CA to implement additional controls to reduce the risk of unintended certificate mis-issue. [RFC 8659]</td>
</tr>
<tr>
<td>Certificate Policy (CP)</td>
<td style="text-align: left;">
  <ol type="1">
  <li>Refers to a named set of rules that indicates the applicability to a certain community or class of application with common security requirements [Article 2-3, Chapter 1, Regulations on Required Information for Certification Practice Statements]</li>
  <li>Certificate policy refers to the dedicated profile administration policy established for the electronic transactions performed through certificate administration. Certificate policy covers a variety of issues including the formation, generation, delivery, auditing, administration and restoration after compromise. Certificate policy indirectly controls the use and operation of certificate security systems to protect the transactions performed by the communication systems. The security services required for certain application are provided through control of the certificate extension methods, certificate policy and related technology.</li>
  </ol>
</td>
</tr>
<tr>
<td>Certification Practice Statement (CPS)</td>
<td style="text-align: left;">
  <ol type="1">
  <li>External notification by the certificate authority used to describe the practice statement of the certificate authority governing certificate issuance and processing of other certification work. [Article 2-7, Electronic Signatures Act]</li>
  <li>Announcement of a statement that certain procedures of the certificate authority for certificate work (including issuance, suspension, revocation, renewal and access) comply with certain requirements (listed in the certificate policy or other service contracts).</li>
  </ol>
</td>
</tr>
<tr>
<td>Certificate Profile</td>
<td style="text-align: left;">A set of documents or files that defines requirements for Certificate content and Certificate extensions in accordance with Section 7 of the Baseline Requirements. e.g. a Section in a CA’s CPS or a certificate template file used by CA software.</td>
</tr>
<tr>
<td>Certificate Problem Reports</td>
<td style="text-align: left;">The complaints regarding suspected cracking of keys, certificate misused, or other types of fraud, cracks, abuse, or inappropriate behaviors related to certificates.</td>
</tr>
<tr>
<td>Certificate Revocation</td>
<td style="text-align: left;">Termination of a certificate prior to its expiry date.</td>
</tr>
<tr>
<td>Certificate Revocation List (CRL)</td>
<td style="text-align: left;"><ol type="1">
<li>The certificate revocation list digitally signed by the certification authority provided for relying party use. [Article 2-8, Chapter 1, Regulations on Required Information for Certification Practice Statements]</li>
<li>List maintained by the certificate authority. The expiry dates of the above revoked certificates issued by the certification authority are recorded on the list.</li>
</ol></td>
</tr>
<tr>
<td>Chartered Professional Accountants Canada (CPA)</td>
<td style="text-align: left;">Institution which jointly drafted The Trust Services Principles and Criteria for Security, Availability, Processing Integrity, Confidentiality and Privacy system standards with the American Institute of Certified Public Accountants (AICPA) and the management organization for WebTrust for CA and SSL Baseline Requirement &amp; Network Security mark. Canadian Institute of Chartered Accountants is abbreviated as CICA.</td>
</tr>
<tr>
<td style="text-align: left;">Compromise</td>
<td style="text-align: left;">Information disclosed to unauthorized persons or unauthorized intentional or unintentional disclosure, modification, destruction or loss of objects which constitutes a violation of information security policy.</td>
</tr>
<tr>
<td>Confidentiality</td>
<td style="text-align: left;">Information which will not be known or be accessed by unauthorized entities or programs.</td>
</tr>
<tr>
<td>Cross-Certificate</td>
<td style="text-align: left;">A certificate used to establish a trust relationship between two Root CAs. This certificate is a type of CA certificate and not a subscriber certificate.</td>
</tr>
<tr>
<td>Cryptographic Module</td>
<td style="text-align: left;">A set of hardware, software, firmware or combination of the above used to run cryptologic or programs (including crypto algorithms) and included within the cryptographic boundaries of the module.</td>
</tr>
<tr>
<td style="text-align: left;">Data Integrity</td>
<td style="text-align: left;">Information that has been subjected to unauthorized access or accidental modification, damage or loss.</td>
</tr>
<tr>
<td><Digital Signature</td>
<td style="text-align: left;">An electronic signature generated by use of mathematic algorithm or other means to create a certain length of digital data encrypted by the signatory’s private key and capable of being verified by the public key. [Article 2-3, Electronic Signatures Act]</td>
</tr>
<tr>
<td>Domain Contact</td>
<td style="text-align: left;">The Domain Name Registrant, technical contact, or administrative contract (or the equivalent under a ccTLD) as listed in the WHOIS record of the Base Domain Name or in a DNS SOA record.</td>
</tr>
<tr>
<td>Domain Name</td>
<td style="text-align: left;">A node label assigned by the domain name system. Converts the IP address into a text name that is easily remembered by humans.</td>
</tr>
<tr>
<td>Domain Name Registrant</td>
<td style="text-align: left;">Sometimes referred to as the domain name owner, but it is more appropriate to say a certain individual or entity who have registered with the Domain Name Registrar to have the right to use a domain name and the Domain Name Registrant or WHOIS has listed the ‘registrant’ as a natural person or legal person.</td>
</tr>
<tr>
<td>Domain Name Registrar</td>
<td style="text-align: left;">A person or entity that registers Domain Names under the auspices of or by agreement with: (i) the Internet Corporation for Assigned Names and Numbers (ICANN), (ii) a national Domain Name authority/registry, or (iii) a Network Information Center (including their affiliates, contractors, delegates, successors, or assigns).</td>
</tr>
<tr>
<td>Domain Name System (DNS)</td>
<td style="text-align: left;">A distributed database used to automatically convert the IP address to domain name.</td>
</tr>
<tr>
<td>Duration</td>
<td style="text-align: left;">A certificate field made up of two subfields “start time of the validity period” (notBefore) and “end time of the validity period” (notAfter).</td>
</tr>
<tr>
<td>End Entity</td>
<td style="text-align: left;">The PKI includes the following two types of entities:
<ol type="1">
<li>Those responsible for the safeguarding and use of certificate public keys.</li>
<li>Third parties who trust the certificates issued by the PKI (not holders of private keys and not a certificate authority). The end entities are subscribers and relying parties including personnel, organizations, accounts, devices and sites.</li>
</ol></td>
</tr>
<tr>
<td>End-Entity Certificate</td>
<td style="text-align: left;">Certificates issued to end-entities.</td>
</tr>
<tr>
<td>Chunghwa Telecom HiPKI (HiPKI)</td>
<td style="text-align: left;">A hierarchical PKI established by CHT in compliance with Chrome Root Certificate policies and ITU-T X.509. The subordinate CA in this PKI will only issue TLS certificates for Transport Layer Security (TLS) communication protocol equipment or application software.</td>
</tr>
<tr>
<td>Chunghwa Telecom Certificate Policy Management Authority (PMA)</td>
<td style="text-align: left;">An organization which was established for electronic certificate management matters, such as (i) discussion and review of this CP/CPS and the electronic certificate framework of the PKI owned by CHT and (ii) review of interoperation requests submitted by subordinate CAs and cross-certified CAs and that of CP/CPS.</td>
</tr>
<tr>
<td>Federal Information Processing Standard (FIPS)</td>
<td style="text-align: left;">Except for military organizations in the US Federal Government System, information processing standard for all government organizations and government subcontractors. The security requirement standard for the cryptographic module is FIPS no. 140 standard (FIPS 140). FIPS 140-2 divides the cryptographic module into 11 types of security requirements. Each security requirement type is then divided into 4 security levels.</td>
</tr>
<tr>
<td>Firewall</td>
<td style="text-align: left;">An access restriction gateway between networks which complies with near-end (local area) security policy.</td>
</tr>
<tr>
<td>Fully Qualified Domain Name (FQDN)</td>
<td style="text-align: left;">An unambiguous domain name that specifies the exact location of a computer within the domain’s hierarchy. The FQDN consists of two parts: the host name (service name) and domain name. For example, ourserver.ourdomain.com.tw, ourserver is the host name and ourdomain.com.tw is the domain name. In this name, ourdomain is the third-level domain, com is the second-level domain name and tw is the country code top-level domain (ccTLD). A FQDN always starts with a host name.<p>
For example, www.ourdomain.com，www is the host name. Ourdomain is the the second-level domain name. com is Generic Top-Level Domain, gTLD.</td>
</tr>
<tr>
<td>High Risk Certificate Request</td>
<td style="text-align: left;">The CA marks the request to be referred to the internal standards maintained by the CA and other database for reviewing. They may include the high-risk names used for phishing or other wrongful purposes, Miller Smiles phishing list, Google Safe Browsing list, or the names identified by the CA with the risk-reducing standards.</td>
</tr>
<tr>
<td>Identification</td>
<td style="text-align: left;">A statement of who the user is. [A Guide to Understanding Identification and Authentication in Trusted Systems]<p>
A way that can be used to describe or claim the identity of an individual or entity, e.g., user account, name or email.</td>
</tr>
<tr>
<td>Integrity</td>
<td style="text-align: left;">Protecting information so that it is not subject to unauthorized modification or damage. Preserve information in an untampered state during transmission and storage following generation at its source until receipt by the final recipient.</td>
</tr>
<tr>
<td>Internationalized Domain Name (IDN)</td>
<td style="text-align: left;">A kind of internet domain name, including at least one script or alphabetic character of one specific language, and then encoded with Punycode, and used for the domain name service only accepting ASCII codes.</td>
</tr>
<tr>
<td>Internet Assigned Numbers Authority (IANA)</td>
<td style="text-align: left;">An organization that oversees the allocation of global IP address, domain names and many other parameters used for Internet.</td>
</tr>
<tr>
<td>Internet Engineering Task Force (IETF)</td>
<td style="text-align: left;">Responsible for the development and promotion of Internet standards. Official website is at: https://www.ietf.org/. Its vision is the generation of high quality technical documents affects how man designs, uses and manages the Internet and allows the Internet to operate smoothly.</td>
</tr>
<tr>
<td>IP Reverse Zone Suffix</td>
<td style="text-align: left;">One of the two FQDNs that consist of the Domain Labels “inaddr.arpa” or “ip6.arpa”. These two FQDNs serve as the root of the IP version 4 and IP version 6 reverse mapping space. “in-addr.arpa” is the root of the IP version 4 reverse mapping space and “ip6.arpa” is the root of the IP version 6 reverse mapping space.</td>
</tr>
<tr>
<td>Issuing CA</td>
<td style="text-align: left;">For a particular certificate, the CA that issues the certificate is the issuing CA.</td>
</tr>
<tr>
<td>Key Escrow</td>
<td style="text-align: left;">Storage of related information using the subscriber’s private key and according to the terms of the mandatory subscriber escrow agreement (or similar contract). The terms of this escrow agreement requires that one or more than one agencies have possession of the subscriber key provided it is beneficial to the subscriber, employer or another party in accordance with the provisions of the agreement.</td>
</tr>
<tr>
<td>Key Exchange</td>
<td style="text-align: left;">Mutual exchange of keys to establish a secure communication processing procedure.</td>
</tr>
<tr>
<td>Key Pair</td>
<td style="text-align: left;">Two mathematically related keys having the following properties:
<ol type="1">
<li>One (public) key can be used to encrypt a message that can only be decrypted by using the other (private) key, and</li>
<li>It is computationally infeasible to determine one key from another.</li>
</ol></td>
</tr>
<tr>
<td>Linting</td>
<td style="text-align: left;">A process in which the content of digitally signed data such as a Precertificate [RFC 6962], Certificate, Certificate Revocation List, or OCSP response, or data-to-be-signed object such as a tbsCertificate (as described in RFC 5280, Section 4.1.1.1) is checked for conformance with the profiles and requirements defined in these Requirements.</td>
</tr>
<tr>
<td>Non-Repudiation</td>
<td style="text-align: left;">Provide proof of delivery to the information sender and proof of sender identity to the receiver so neither party may repudiate the processing of this information after the fact. Technically speaking, non-repudiation refers to the guarantee that this signature must be signed by the corresponding private key if a certain public key can be used to verify a certain digital signature for a trusted party. Legally speaking, non-repudiation refers to the establishment of a possession and control system for private signature keys.</td>
</tr>
<tr>
<td>Object Identifier (OID)</td>
<td style="text-align: left;"><ol type="1">
<li>One type of unique alphanumeric / numeric identified registered under the International Standard Organization registration standard which could be used to identify the uniquely corresponding certificate policy; where this CP/CPS is modified, the OID is not changed accordingly. [Article 2-4, Chapter 1, Regulations on Required Information for Certification Practice Statements]</li>
<li>When a special form of code, object or object type is registered with the International Standard Organization (ISO), the unique code may be used as an identified. For example, this code can be used in the public key infrastructure to indicate what certificate policy and cryptographic algorithms are used.</li>
</ol></td>
</tr>
<tr>
<td>Online Certificate Status Protocol (OCSP)</td>
<td style="text-align: left;">The Online Certificate Status Protocol is a type of online certificate checking protocol which lets the application software of relying parties to determine the status (such as revoked or valid) of a certain certificate.</td>
</tr>
<tr>
<td>OCSP Responder</td>
<td style="text-align: left;">The online server that is authorized, maintained, and operated by the CA, and connects to the repository to process the certificate status request.</td>
</tr>
<tr>
<td>OCSP Stapling</td>
<td style="text-align: left;">This is a form of TLS Certificate Status Request extension, which may replace the OCSP to check X.509 certificate status.<p>

In practice, a website may obtain a “time limited (e.g. two hours)” OCSP response from the OCSP Responder and cache it. Next, this cached OCSP response will be sent to the subscriber (typically a browser) whenever initiating the TLS Handshake. The subscriber only needs to verify the validity of that OCSP response without sending the request of OCSP to the CA. In that way, the subscriber will not need to request the TLS certificate status from the CA when connecting to a high traffic TLS website, and thus to decrease the burden of the CA.<p>
This mechanism also prevents the privacy concern that the OCSP Responder knows which subscribers attempting to browsing that TLS website by having the TLS website referring the TLS certificate validity message issued regularly by the OCSP Responder to the CA.
</td>
</tr>
<tr>
<td>Out-of-Band</td>
<td style="text-align: left;">Delivery method other than ordinary information delivery channels. If the delivery method is by electric cable, a special secure channel may be the use of physical registered mail.</td>
</tr>
<tr>
<td>Organization Validation (OV)</td>
<td style="text-align: left;">In the TLS certificate approval process, except for identification and authentication of subscriber domain name control rights, following the certificate assurance level to identify and authenticate the identity of subscriber organizations. Therefore, connection to a website installed an Organization Validation TLS certificate is able to provide SSL encryption channels, in order to know who is the owner of the website and ensure the integrity of the transmitted information.</td>
</tr>
<tr>
<td>Persistent DCV TXT Record</td>
<td style="text-align: left;">A DNS TXT record identifying an Applicant in accordance with Section 3.2.2.4.22 of the Baseline Requirements.</td>
</tr>
<tr>
<td>Private Key</td>
<td style="text-align: left;"><ol type="1">
<li>The key in the signature key pair used to generate digital signatures.</li>
<li>The key in the encryption key pair used to decrypt secret information.</li>
</ol>

This key must be kept secret under these two circumstances.
</td>
</tr>
<tr>
<td>Public Key</td>
<td style="text-align: left;"><ol type="1">
<li>The key in the signature key pair used to verify the validity of the digital signature.</li>
<li>The key in the encryption key pair used for encrypting secret information.</li>
</ol>

These keys must be made public (usually in a digital certificate form) under these two circumstances.</td>
</tr>
<tr>
<td>Public-Key Cryptography Standard (PKCS)</td>
<td style="text-align: left;">In order to promote the use of public key technology, the RSA laboratory under the RSA Information Security Company has developed a series of public key cryptography standards that are widely used by the industry.</td>
</tr>
<tr>
<td>Public Key Infrastructure (PKI)</td>
<td style="text-align: left;">A set of law, policy, standards, personnel, equipment, facilities, technology, processes, audits and services developed on a broad scale and management of asymmetric cryptography and public key certificates.</td>
</tr>
<tr>
<td>Qualified Auditor</td>
<td style="text-align: left;">Accountant firms, entities, or individuals that satisfy the auditor qualification requirements specified in Section 8.2 of the Baseline Requirements, as well as independent from the audited parties.</td>
</tr>
<tr>
<td>Random Value</td>
<td style="text-align: left;">A value specified by a CA to the Applicant that exhibits at least 112 bits of entropy.</td>
</tr>
<tr>
<td>Registration Authority (RA)</td>
<td style="text-align: left;"><ol type="1">
<li>Responsible for checking the identity and other attributes of the certificate applicant but does not issue or administer certificates. The nature and scope of obligations borne by the registration authority are set down in the applicable certificate policy or agreement.</li>
<li>An entity responsible for the identity identification and authentication of the certificate subject which does not issue certificates.</li>
</ol></td>
</tr>
<tr>
<td>Re-key</td>
<td style="text-align: left;">Changing the key values used in the cryptographic system application program. It is commonly achieved by issuing a new certificate for the new public key.</td>
</tr>
<tr>
<td>Relying Party</td>
<td style="text-align: left;"><ol type="1">
<li>Recipient of a certificate who acts in reliance of that certificate or a digital signature to verify the public key listed in the certificate, or the counterpart to identify (or its attributes) of the subject named in a trusted certificate and public key listed in the certificate. [Article 2-6, Chapter 1, Regulations on Required Information for Certification Practice Statements]</li>
<li>The individual or agency which receives information including a certificate and digital signature (the public key listed on the certificate may be used to verify the digital signature) and may rely on this information.</li>
</ol></td>
</tr>
<tr>
<td>Repository</td>
<td style="text-align: left;"><ol type="1">
<li>A system for storing and retrieving certificates or other information relevant to certificates. [Article 2-7, Chapter 1, Regulations on Required Information for Certificate Practice Statements]</li>
<li>A database that contains information and data relating to certificates as specified in this CP/CPS.</li>
</ol></td>
</tr>
<tr>
<td>Request Token</td>
<td style="text-align: left;">
A value derived in a method specified by the CA which binds this demonstration of control to the certificate request.<p>

The Request Token SHALL incorporate the key used in the certificate request.<p>
A Request Token MAY include a timestamp to indicate when it was created.<p>
A Request Token MAY include other information to ensure its uniqueness.<p>
A Request Token that includes a timestamp SHALL remain valid for no more than 30 days from the time of creation.<p>
A Request Token that includes a timestamp SHALL be treated as invalid if its timestamp is in the future.<p>
A Request Token that does not include a timestamp is valid for a single use and the CA SHALL NOT re‐use it for a subsequent validation.<p>
The binding SHALL use a digital signature algorithm or a cryptographic hash algorithm at least as strong as that to be used in signing the certificate request.<p>
</td>
</tr>
<tr>
<td>Required Website Content</td>
<td style="text-align: left;">Either a Random Value or a Request Token, together with additional information that uniquely identifies the Subscriber, as specified by the CA.</td>
</tr>
<tr>
<td>Reserved IP Addresses</td>
<td style="text-align: left;">IPv4 and IPv6 addresses reserved in the IANA setting. See:</p>
<p>http://www.iana.org/assignments/ipv4-address-space/ipv4-address-space.xml and http://www.iana.org/assignments/ipv6-address-space/ipv6-address-space.xml</td>
</tr>
<tr>
<td>Request for Comments (RFC)</td>
<td style="text-align: left;">A series of memos issued by the Internet Engineer Task Force that include Internet, UNIX and Internet community standards, protocols and procedures for number assignment.</td>
</tr>
<tr>
<td>Secure Sockets Layer</td>
<td style="text-align: left;">Protocol issued by Netscape through introduction of their web browser which can encrypt network communication in the transport layer and ensure the integrity of transmitted information and perform identity authentication on the server and client.<p>
The advantage of the secure socket layer protocol is it is independent and separate from the application layer protocol. High level application layer protocol (such as: HTTP, FTP and Telnet) may be established on top of SSL. The SSL protocol completes encryption algorithm, communication secret key agreement and server authentication work before the application layer protocol communication. This protocol is a successor to the Transport Layer Security (TLS) protocol.</td>
</tr>
<tr>
<td>Subordinate CA</td>
<td style="text-align: left;">In a hierarchical PKI, a CA whose certificate signature key is certified by another CA, and whose activities are constrained by that other CA.</td>
</tr>
<tr>
<td>Subscriber</td>
<td style="text-align: left;">An entity that
<ol type="1">
<li>is the subject named or identified in a certificate issued to that entity,</li>
<li>holds a private key that corresponds to the public key listed in the certificate, and</li>
<li>does not itself issue certificates to another party.</li>
</ol>

This includes, but is not limited to, an individual, an organization, an application or network device.
</td>
</tr>
<tr>
<td>Technical Non-Repudiation</td>
<td style="text-align: left;">Technical evidence provided by the public key system to support non-repudiation security service.</td>
</tr>
<tr>
<td>Threat</td>
<td style="text-align: left;">Any status or event which may cause damage (including destruction, disclosure, malicious tampering or denial of service) to information systems. Can be divided into internal threats and outside threats. Internal threats are use of authorization to employ information destruction, disclosure, tampering or denial of service methods to damage the information system. Outside threats are an outside unauthorized entity which has the potential to damage the information system (including information destruction, tampering, disclosure and interruption of service).</td>
</tr>
<tr>
<td>Time-stamp</td>
<td style="text-align: left;">A digitally signed assertion by a trusted authority that a specific digital object existed at a certain time.</td>
</tr>
<tr>
<td>Top-Level Domain</td>
<td style="text-align: left;">From RFC 8499 (https://tools.ietf.org/html/rfc8499): “A Top-Level Domain is a zone that is one layer below the root, such as”com” or “jp”.”</td>
</tr>
<tr>
<td>Transport Layer Security (TLS)</td>
<td style="text-align: left;">TLS 1.0 was first defined in RFC 2246 by the IETF based on the SSL 3.0 and updated in RFC 5246 and RFC 6176 as TLS 1.2. The current version is TLS 1.3 defined in RFC 8446 by the IETF in 2018.</td>
</tr>
<tr>
<td>Trust List</td>
<td style="text-align: left;">List of trusted certificates used by relying parties to authenticate certificates.</td>
</tr>
<tr>
<td>Trusted Certificate</td>
<td style="text-align: left;">Certificate trusted by relying party obtained through a secure and reliable transmission method. The public key contained in this type of certificate comes from a trusted path. Also called a trust anchor.</td>
</tr>
<tr>
<td>Trustworthy System</td>
<td style="text-align: left;">Computer hardware, software and programs which possess the following attributes:
<ol type="1">
<li>Functions that protect again intrusion and misuse.</li>
<li>Provides reasonably accessible, reliable and accurate operations.</li>
<li>Appropriate implementation of preset function.</li>
<li>Security procedures uniformly accepted by the general public.</li>
</ol></td>
</tr>
<tr>
<td>Uninterrupted Power System (UPS)</td>
<td style="text-align: left;">Provide uninterrupted backup power to loading equipment in the event of abnormal power conditions (such as power outage, interference or power surge) to allow uninterrupted operation of servers, switches and other critical equipment and precision instruments to prevent loss of calculation data, communication network interruption and loss of instrument control.</td>
</tr>
<tr>
<td>Validation</td>
<td style="text-align: left;">The process of identification of certificate applicants. Validation is a subset of identification and refers to identification in the context of establishment of the identity of certificate applicants. [RFC 3647]</td>
</tr>
<tr>
<td>WHOIS</td>
<td style="text-align: left;">Information retrieved directly from the Domain Name Registrar or registry operator via the protocol defined in RFC 3912, the Registry Data Access Protocol defined in RFC 7482, or an HTTPS website.</td>
</tr>
<tr>
<td>Zeroize</td>
<td style="text-align: left;">Method to delete electronically stored information. Storage of changed information to prevent information recovery.</td>
</tr>
</tbody>
</table>

# Appendix 3: Certificate Profile Basic Fields and Extensions

The basic fields and extensions of certificates issued by HiPKICA are set in compliance with the official versions of the ITU-T X.509, Baseline Requirements and RFC 5280.

HiPKICA shall not issue a certificate with:

1)  Extensions that do not apply in the context of the public internet;

2)  Semantics that will mislead a relying party about the certificate information verified by HiPKICA; and

3)  Internal name or reserved IP address that may be contained in the commonName field of subject DN or in the entry within the subject alternative name extension.

The subordinate CAs of HiPKICA may support CT by including the X.509v3 extension in issued subscriber certificates, in accordance with RFC 6962, as described below.

1)  A subordinate CA submits a precertificate as defined in RFC 6962 to several CT logs and waits for individual log to return a signed certificate timestamp (SCT).

2)  The CA attachs SCTs to a certificate using an X.509v3 extension, signs the certificate, and delivers the certificate to the applicant for completing the certificate issuance.

3)  The aforementioned precertificates shall not be considered to be a certificate subject to the requirements of RFC 5280.

# Appendix 3-1: CA Certificates

CA certificates issued by HiPKICA include the self-signed certificate and self-issued certificate of root CA, subordinate CA certificate and cross-certificate. The certificate basic fields and extensions are described below. For certificates signed using ECDSA keys, the selection and use of the signature algorithm shall comply with the requirements set forth in Section 7.1.3.2.2 of the Baseline Requirements. Other extensions not specified in this Appendix shall be used in accordance with the provisions set forth in Appendix 3.

1)  Self-signed Certificate

    - Basic fields

      <table>
      <colgroup>
      <col style="width: 28%" />
      <col style="width: 71%" />
      </colgroup>
      <thead>
      <tr>
      <th style="text-align: center;"><strong>Field</strong></th>
      <th style="text-align: center;"><strong>Description</strong></th>
      </tr>
      </thead>
      <tbody>
      <tr>
      <td>version</td>
      <td style="text-align: left;">v3</td>
      </tr>
      <tr>
      <td>serialNumber</td>
      <td style="text-align: left;">It shall be a non‐sequential number greater than zero (0) and less than 2<sup>159</sup> containing at least 64 bits of output from a Cryptographically Secure Pseudorandom Number Generator (CSPRNG).</td>
      </tr>
      <tr>
      <td>signature</td>
      <td style="text-align: left;">The signature algorithm used to sign certificates issued by Root CA and the mapping between algorithms and their corresponding OIDs are specified in Section 7.1.3.
      
      <ul>
        <li>
          RSA
          <ol type="a">
            <li>sha256WithRSAEncryption</li>
            <li>sha384WithRSAEncryption</li>
            <li>sha512WithRSAEncryption</li>
          </ol>
        </li>
        <li>
          ECDSA
          <ol type="a">
            <li>ecdsaWithSHA384</li>
          </ol>
        </li>
      </ul>
      
      </td>
      </tr>
      <tr>
      <td>issuer</td>
      <td style="text-align: left;">The encoded value must be byte‐for‐byte identical to the subject field of the Root CA’s self-signed certificate.</td>
      </tr>
      <tr>
      <td>validity</td>
      <td style="text-align: left;">This field includes the notBefore and notAfter; the relevant requirements shall be implemented in accordance with Section 6.3.2.1.</td>
      </tr>
      <tr>
      <td>subject</td>
      <td style="text-align: left;">This field is used to specify the subject information of the Root CA’s self-signed certificate. For related details, please refer to Section 7.1.4.2.</td>
      </tr>
      <tr>
      <td>subjectPublicKeyInfo</td>
      <td style="text-align: left;">This field is used to specify the subject’s public key and the associated algorithm. The mapping between the algorithms, their parameters, and their corresponding OIDs is specified in Section 7.1.3.
      <ul>
        <li>RSA: rsaEncryption</li>
        <li>ECDSA: ecPublicKey
          <ol type="a">
            <li>secp384r1 (NIST P-384)</li>
          </ol>
        </li>
      </ul></td>
      </tr>
      </tbody>
      </table>

    - Extensions

      <table style="width:100%;">
      <colgroup>
      <col style="width: 28%" />
      <col style="width: 16%" />
      <col style="width: 15%" />
      <col style="width: 39%" />
      </colgroup>
      <thead>
      <tr>
      <th style="text-align: center;"><strong>Extension</strong></th>
      <th style="text-align: center;"><strong>Presence</strong></th>
      <th style="text-align: center;"><strong>Criticality</strong></th>
      <th style="text-align: center;"><strong>Description</strong></th>
      </tr>
      </thead>
      <tbody>
      <tr>
      <td>Authority Key Identifier</td>
      <td align="center">OPTIONAL</td>
      <td align="center">N</td>
      <td style="text-align: left;">If present, only the keyIdentifier field is present in this extension, and its value must be identical to the subjectKeyIdentifier extension.</td>
      </tr>
      <tr>
      <td>Subject Key Identifier</td>
      <td align="center">MUST</td>
      <td align="center">N</td>
      <td style="text-align: left;">The 160-bit SHA-1 hash value of the root CA’s public key.</td>
      </tr>
      <tr>
      <td nowrap>Basic Constraints</td>
      <td align="center">MUST</td>
      <td align="center">Y</td>
      <td style="text-align: left;">Subject Type=CA<p>
      Path Length Constraint=None</td>
      </tr>
      <tr>
      <td>Key Usage</td>
      <td align="center">MUST</td>
      <td align="center">Y</td>
      <td style="text-align: left;">Bits contained in this extension are as follows:
      <ul>
      <li>keyCertSign (required)</li>
      <li>cRLSign (required)</li>
      <li>digitalSignature (optional)</li>
      </ul></td>
      </tr>
      </tbody>
      </table>

2)  Self-issued Certificate

    - Basic fields

      <table>
      <colgroup>
      <col style="width: 28%" />
      <col style="width: 71%" />
      </colgroup>
      <thead>
      <tr>
      <th style="text-align: center;"><strong>Field</strong></th>
      <th style="text-align: center;"><strong>Description</strong></th>
      </tr>
      </thead>
      <tbody>
      <tr>
      <td>version</td>
      <td style="text-align: left;">v3</td>
      </tr>
      <tr>
      <td>serialNumber</td>
      <td style="text-align: left;">It shall be a non‐sequential number greater than zero (0) and less than 2<sup>159</sup> containing at least 64 bits of output from a CSPRNG.</td>
      </tr>
      <tr>
      <td>signature</td>
      <td style="text-align: left;">The signature algorithm used to sign certificates issued by new(old) Root CA and the mapping between algorithms and their corresponding OIDs are specified in Section 7.1.3.
      
      <ul>
        <li>
          RSA
          <ol type="a">
            <li>sha256WithRSAEncryption</li>
            <li>sha384WithRSAEncryption</li>
            <li>sha512WithRSAEncryption</li>
          </ol>
        </li>
        <li>
          ECDSA
          <ol type="a">
            <li>ecdsaWithSHA384</li>
          </ol>
        </li>
      </ul>
      </td>
      </tr>
      <tr>
      <td>issuer</td>
      <td style="text-align: left;">The encoded value must be byte‐for‐byte identical to the subject field of the new (old) Root CA’s self-signed certificate.</td>
      </tr>
      <tr>
      <td>validity</td>
      <td style="text-align: left;">This field includes the notBefore and notAfter; the relevant requirements shall be implemented in accordance with Section 6.3.2.1.</td>
      </tr>
      <tr>
      <td>subject</td>
      <td style="text-align: left;">This field is used to specify the subject information of the Root CA’s self-issued certificate. This encoded value must be byte‐for‐byte identical to the subject field of the old (new) Root CA’s self-signed certificate.</td>
      </tr>
      <tr>
      <td>subjectPublicKeyInfo</td>
      <td style="text-align: left;">This field is used to specify the subject’s public key and the associated algorithm. The mapping between the algorithms, their parameters, and their corresponding OIDs is specified in Section 7.1.3.
      <ul>
        <li>RSA: rsaEncryption</li>
        <li>ECDSA: ecPublicKey
          <ol type="a">
            <li>secp384r1 (NIST P-384)</li>
          </ol>
        </li>
      </ul></td>
      </tr>
      </tbody>
      </table>

    - Extensions

      <table>
      <colgroup>
      <col style="width: 28%" />
      <col style="width: 13%" />
      <col style="width: 15%" />
      <col style="width: 43%" />
      </colgroup>
      <thead>
      <tr>
      <th style="text-align: center;"><strong>Extension</strong></th>
      <th style="text-align: center;"><strong>Presence</strong></th>
      <th style="text-align: center;"><strong>Criticality</strong></th>
      <th style="text-align: center;"><strong>Description</strong></th>
      </tr>
      </thead>
      <tbody>
      <tr>
      <td style="text-align: left;">Authority Key Identifier</td>
      <td align="center">MUST</td>
      <td align="center">N</td>
      <td style="text-align: left;">Only the keyIdentifier field, used to contain the SHA-1 hash value of the new (old) root CA’s public key, is present in this extension. Its value must be identical to the subjectKeyIdentifier extension of the self-signed certificate issued by the new (old) root CA.</td>
      </tr>
      <tr>
      <td style="text-align: left;">Subject Key Identifier</td>
      <td align="center">MUST</td>
      <td align="center">N</td>
      <td style="text-align: left;">The 160-bit SHA-1 hash value of the old (new) root CA’s public key.</td>
      </tr>
      <tr>
      <td style="text-align: left;">CRL Distribution Points</td>
      <td align="center">MUST</td>
      <td align="center">N</td>
      <td style="text-align: left;">The HTTP URL of the new (old) root CA’s CRL service.</td>
      </tr>
      <tr>
      <td style="text-align: left;">Authority Information Access</td>
      <td align="center">MUST</td>
      <td align="center">N</td>
      <td style="text-align: left;">This extension shall contain at least one of the following:
      <ul>
      <li>The HTTP URL of the new (old) root CA’s self-signed certificate (optional)</li>
      <li>The HTTP URL of the new (old) root CA’s OCSP responder (optional)</li>
      </ul></td>
      </tr>
      <tr>
      <td nowrap>Certificate Policies</td>
      <td align="center">MUST</td>
      <td align="center">N</td>
      <td style="text-align: left;">This extension must contain the following information. The policy qualifier field in this extension may be used as needed. When using this field, it may contain a CPS pointer qualifier that points to this CP/CPS.
      <ul>
      <li>All the CA/Browser Forum-assigned OID(s) referenced in this CP/CPS.</li>
      <li>All CP OIDs defined in this CP/CPS.</li>
      </ul></td>
      </tr>
      <tr>
      <td style="text-align: left;">Extended Key Usage (EKU)</td>
      <td align="center">MUST</td>
      <td align="center">N</td>
      <td style="text-align: left;">KeyPurposeIds contained in this extension are as follows:
      <ul>
      <li>id-kp-serverAuth (required)</li>
      <li>id-kp-clientAuth (optional; however, it shall not be included in certificates issued on or after June 15, 2025)</li>
      </ul></td>
      </tr>
      <tr>
      <td style="text-align: left;">Key Usage</td>
      <td align="center">MUST</td>
      <td align="center">Y</td>
      <td style="text-align: left;">The content in this extension shall be identical to the content of the key usage extension in the old (new) root CA’s self-signed certificate.</td>
      </tr>
      <tr>
      <td nowrap>Basic Constraints</td>
      <td align="center">MUST</td>
      <td align="center">Y</td>
      <td style="text-align: left;">Subject Type=CA <p>
      Path Length Constraint=None</td>
      </tr>
      </tbody>
      </table>

3)  Subordinate CA Certificate

    - Basic fields

      <table>
      <colgroup>
      <col style="width: 28%" />
      <col style="width: 71%" />
      </colgroup>
      <thead>
      <tr>
      <th style="text-align: center;"><strong>Field</strong></th>
      <th style="text-align: center;"><strong>Description</strong></th>
      </tr>
      </thead>
      <tbody>
      <tr>
      <td>version</td>
      <td style="text-align: left;">v3</td>
      </tr>
      <tr>
      <td>serialNumber</td>
      <td style="text-align: left;">It shall be a non‐sequential number greater than zero (0) and less than 2<sup>159</sup> containing at least 64 bits of output from a CSPRNG.</td>
      </tr>
      <tr>
      <td>signature</td>
      <td style="text-align: left;">The signature algorithm used to sign certificates issued by Root CA and the mapping between algorithms and their corresponding OIDs are specified in Section 7.1.3.
      
      <ul>
        <li>
          RSA
          <ol type="a">
            <li>sha256WithRSAEncryption</li>
            <li>sha384WithRSAEncryption</li>
            <li>sha512WithRSAEncryption</li>
          </ol>
        </li>
        <li>
          ECDSA
          <ol type="a">
            <li>ecdsaWithSHA384</li>
          </ol>
        </li>
      </ul>
      </td>
      </tr>
      <tr>
      <td>issuer</td>
      <td style="text-align: left;">The encoded value must be byte‐for‐byte identical to the subject field of the Root CA’s self-signed certificate.</td>
      </tr>
      <tr>
      <td>validity</td>
      <td style="text-align: left;">This field includes the notBefore and notAfter; the relevant requirements shall be implemented in accordance with Section 6.3.2.1.</td>
      </tr>
      <tr>
      <td>subject</td>
      <td style="text-align: left;">This field is used to specify the subject information of the Subordinate CA certificate. For related details, please refer to Section 7.1.4.2.</td>
      </tr>
      <tr>
      <td>subjectPublicKeyInfo</td>
      <td style="text-align: left;">This field is used to specify the subject’s public key and the associated algorithm. The mapping between the algorithms, their parameters, and their corresponding OIDs is specified in Section 7.1.3.
      <ul>
        <li>RSA: rsaEncryption</li>
        <li>ECDSA: ecPublicKey
          <ol type="a">
            <li>secp256r1(NIST P-256)</li>
            <li>secp384r1(NIST P-384)</li>
          </ol>
        </li>
      </ul>
      </td>
      </tr>
      </tbody>
      </table>

    - Extensions

      <table>
      <colgroup>
      <col style="width: 27%" />
      <col style="width: 14%" />
      <col style="width: 15%" />
      <col style="width: 43%" />
      </colgroup>
      <thead>
      <tr>
      <th style="text-align: center;"><strong>Extension</strong></th>
      <th style="text-align: center;"><strong>Presence</strong></th>
      <th style="text-align: center;"><strong>Criticality</strong></th>
      <th style="text-align: center;"><strong>Description</strong></th>
      </tr>
      </thead>
      <tbody>
      <tr>
      <td>Authority Key Identifier</td>
      <td align="center">MUST</td>
      <td align="center">N</td>
      <td style="text-align: left;">Only the keyIdentifier field, used to contain the SHA-1 hash value of the root CA’s public key, is present in this extension. Its value must be identical to the subjectKeyIdentifier extension of the self-signed certificate issued by the root CA.</td>
      </tr>
      <tr>
      <td>Subject Key Identifier</td>
      <td align="center">MUST</td>
      <td align="center">N</td>
      <td style="text-align: left;">The 160-bit SHA-1 hash value of the subordinate CA’s public key.</td>
      </tr>
      <tr>
      <td>CRL Distribution Points</td>
      <td align="center">MUST</td>
      <td align="center">N</td>
      <td style="text-align: left;">The HTTP URL of the root CA’s CRL service.</td>
      </tr>
      <tr>
      <td>Authority Information Access</td>
      <td align="center">MUST</td>
      <td align="center">N</td>
      <td style="text-align: left;">This shall contain at least one of the following:
      <ul>
      <li>The HTTP URL of the root CA’s self-signed certificate (optional)</li>
      <li>The HTTP URL of the root CA’s OCSP responder (optional)</li>
      </ul></td>
      </tr>
      <tr>
      <td nowrap>Certificate Policies</td>
      <td align="center">MUST</td>
      <td align="center">N</td>
      <td style="text-align: left;">This extension is used to indicate the CP OID(s) that the root CA approved and permitted the subordinate CA to use. The policy qualifier field in this extension may be used as needed. When using this field, it may contain a CPS pointer qualifier that points to this CP/CPS. The following CP OIDs may be contained in this extension:
      <ul>
      <li>The CA/Browser Forum-assigned OID(s) referenced in this CP/CPS. It must be associated with the given subscriber certificate type and only one may be contained (required)</li>
      <li>The CP OIDs defined in this CP/CPS (optional)</li>
      </ul></td>
      </tr>
      <tr>
      <td>Extended Key Usage</td>
      <td align="center">MUST</td>
      <td align="center">N</td>
      <td style="text-align: left;">KeyPurposeIds contained in this extension are as follows:
      <ul>
      <li>id-kp-serverAuth (required)</li>
      <li>id-kp-clientAuth (optional; however, it shall not be included in certificates issued on or after June 15, 2025)</li>
      </ul></td>
      </tr>
      <tr>
      <td>Key Usage</td>
      <td align="center">MUST</td>
      <td align="center">Y</td>
      <td style="text-align: left;">Bits contained in this extension are as follows:
      <ul>
      <li>keyCertSign (required)</li>
      <li>cRLSign (required)</li>
      <li>digitalSignature (optional)</li>
      </ul></td>
      </tr>
      <tr>
      <td nowrap>Basic Constraints</td>
      <td align="center">MUST</td>
      <td align="center">Y</td>
      <td style="text-align: left;">Subject Type=CA<p>
      Path Length Constraint=0</td>
      </tr>
      </tbody>
      </table>

4)  Cross-Certificate

    The subject of a cross-certificate shall be a root CA, and this root CA shall not directly issue subscriber certificates.

    - Basic fields

      <table>
      <colgroup>
      <col style="width: 28%" />
      <col style="width: 71%" />
      </colgroup>
      <thead>
      <tr>
      <th style="text-align: center;"><strong>Field</strong></th>
      <th style="text-align: center;"><strong>Description</strong></th>
      </tr>
      </thead>
      <tbody>
      <tr>
      <td>version</td>
      <td style="text-align: left;">v3</td>
      </tr>
      <tr>
      <td>serialNumber</td>
      <td style="text-align: left;">It shall be a non‐sequential number greater than zero (0) and less than 2<sup>159</sup> containing at least 64 bits of output from a CSPRNG.</td>
      </tr>
      <tr>
      <td>signature</td>
      <td style="text-align: left;">The signature algorithm used to sign certificates issued by Root CA and the mapping between algorithms and their corresponding OIDs are specified in Section 7.1.3.
      
      <ul>
        <li>
          RSA
          <ol type="a">
            <li>sha256WithRSAEncryption</li>
            <li>sha384WithRSAEncryption</li>
            <li>sha512WithRSAEncryption</li>
          </ol>
        </li>
        <li>
          ECDSA
          <ol type="a">
            <li>ecdsaWithSHA384</li>
          </ol>
        </li>
      </ul>
      </td>
      </tr>
      <tr>
      <td>issuer</td>
      <td style="text-align: left;">The encoded value must be byte‐for‐byte identical to the subject field of the Root CA’s self-signed certificate.</td>
      </tr>
      <tr>
      <td>validity</td>
      <td style="text-align: left;">This field includes the notBefore and notAfter; the relevant requirements shall be implemented in accordance with Section 6.3.2.1.</td>
      </tr>
      <tr>
      <td>subject</td>
      <td style="text-align: left;">This field is used to specify the subject information of the Cross-certificate. This encoded value must be byte‐for‐byte identical to the subject field of the existing Cross-certificate.</td>
      </tr>
      <tr>
      <td>subjectPublicKeyInfo</td>
      <td style="text-align: left;">This field is used to specify the subject’s public key and the associated algorithm. The mapping between the algorithms, their parameters, and their corresponding OIDs is specified in Section 7.1.3.
      
      <ul>
        <li>RSA: rsaEncryption</li>
        <li>ECDSA: ecPublicKey
          <ol type="a">
            <li>secp256r1(NIST P-256)</li>
            <li>secp384r1(NIST P-384)</li>
          </ol>
        </li>
      </ul>
      
      </td>
      </tr>
      </tbody>
      </table>

    - Extensions

      <table>
      <colgroup>
      <col style="width: 28%" />
      <col style="width: 13%" />
      <col style="width: 15%" />
      <col style="width: 43%" />
      </colgroup>
      <thead>
      <tr>
      <th style="text-align: center;"><strong>Extension</strong></th>
      <th style="text-align: center;"><strong>Presence</strong></th>
      <th style="text-align: center;"><strong>Criticality</strong></th>
      <th style="text-align: center;"><strong>Description</strong></th>
      </tr>
      </thead>
      <tbody>
      <tr>
      <td>Authority Key Identifier</td>
      <td align="center">MUST</td>
      <td align="center">N</td>
      <td style="text-align: left;">Only the keyIdentifier field, used to contain the SHA-1 hash value of the root CA’s public key, is present in this extension. Its value must be identical to the subjectKeyIdentifier extension of the self-signed certificate issued by the root CA.</td>
      </tr>
      <tr>
      <td>Subject Key Identifier</td>
      <td align="center">MUST</td>
      <td align="center">N</td>
      <td style="text-align: left;">The 160-bit SHA-1 hash value of the cross-certified CA’s public key.</td>
      </tr>
      <tr>
      <td>CRL Distribution Points</td>
      <td align="center">MUST</td>
      <td align="center">N</td>
      <td style="text-align: left;">The HTTP URL of the root CA’s CRL service.</td>
      </tr>
      <tr>
      <td>Authority Information Access</td>
      <td align="center">MUST</td>
      <td align="center">N</td>
      <td style="text-align: left;">This extension shall contain at least one of the following:
      <ul>
      <li>The HTTP URL of the root CA’s self-signed certificate (optional)</li>
      <li>The HTTP URL of the root CA’s OCSP responder (optional)</li>
      </ul></td>
      </tr>
      <tr>
      <td nowrap>Certificate Policies</td>
      <td align="center">MUST</td>
      <td align="center">N</td>
      <td style="text-align: left;">This extension is used to indicate the CP OID(s) that the root CA approved and permitted the cross-certified CA to use. The policy qualifier field in this extension may be used as needed. When using this field, it may contain a CPS pointer qualifier that points to this CP/CPS. The following CP OIDs may be contained in this extension:
      <ul>
      <li>The CA/Browser Forum-assigned OID(s) referenced in this CP/CPS. It must be associated with the given subscriber certificate type transitively issued by this certificate, and at least one such CP OID shall be included. (required)</li>
      <li>The CP OIDs defined in this CP/CPS (optional)</li>
      </ul></td>
      </tr>
      <tr>
      <td>Extended Key Usage</td>
      <td align="center">MUST</td>
      <td align="center">N</td>
      <td style="text-align: left;">KeyPurposeIds contained in this extension are as follows:
      <ul>
      <li>id-kp-serverAuth (required)</li>
      <li>id-kp-clientAuth (optional; however, it shall not be included in certificates issued on or after June 15, 2025)</li>
      </ul></td>
      </tr>
      <tr>
      <td>Key Usage</td>
      <td align="center">MUST</td>
      <td align="center">Y</td>
      <td style="text-align: left;">Bits contained in this extension are as follows:
      <ul>
      <li>keyCertSign (required)</li>
      <li>cRLSign (required)</li>
      <li>digitalSignature (optional)</li>
      </ul></td>
      </tr>
      <tr>
      <td nowrap>Basic Constraints</td>
      <td align="center">MUST</td>
      <td align="center">Y</td>
      <td style="text-align: left;">Subject Type=CA<p>
      Path Length Constraint= Set according to the needed certificate path length of the cross-certified CA. It may not be present as well.</td>
      </tr>
      </tbody>
      </table>

# Appendix 3-2: Subscriber Certificates

For TLS certificates issued by subordinate CAs of HiPKICA, the basic fields and extensions are described as follows. For certificates signed using ECDSA keys, the selection and use of the signature algorithm shall comply with the requirements set forth in Section 7.1.3.2.2 of the Baseline Requirements. Other extensions not specified in this Appendix shall be used in accordance with the provisions set forth in Appendix 3.

- Basic fields

  <table>
  <colgroup>
  <col style="width: 28%" />
  <col style="width: 71%" />
  </colgroup>
  <thead>
  <tr>
  <th style="text-align: center;"><strong>Field</strong></th>
  <th style="text-align: center;"><strong>Description</strong></th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td>version</td>
  <td style="text-align: left;">v3</td>
  </tr>
  <tr>
  <td>serialNumber</td>
  <td style="text-align: left;">It shall be a non‐sequential number greater than zero (0) and less than 2<sup>159</sup> containing at least 64 bits of output from a CSPRNG.</td>
  </tr>
  <tr>
  <td>signature</td>
  <td style="text-align: left;">The signature algorithm used to sign certificates issued by Subordinate CA and the mapping between algorithms and their corresponding OIDs are specified in Section 7.1.3.
  
  <ul>
    <li>
      RSA
      <ol type="a">
        <li>sha256WithRSAEncryption</li>
        <li>sha384WithRSAEncryption</li>
        <li>sha512WithRSAEncryption</li>
      </ol>
    </li>
    <li>
      ECDSA
      <ol type="a">
        <li>ecdsaWithSHA256</li>
        <li>ecdsaWithSHA384</li>
      </ol>
    </li>
  </ul>
  
  </td>
  </tr>
  <tr>
  <td>issuer</td>
  <td style="text-align: left;">The encoded value must be byte‐for‐byte identical to the subject field of the Subordinate CA certificate.</td>
  </tr>
  <tr>
  <td>validity</td>
  <td style="text-align: left;">This field includes the notBefore and notAfter; the relevant requirements shall be implemented in accordance with Section 6.3.2.2.</td>
  </tr>
  <tr>
  <td>subject</td>
  <td style="text-align: left;">This field is used to specify the subject information of the TLS certificate. For related details, please refer to Section 7.1.4.3.</td>
  </tr>
  <tr>
  <td>subjectPublicKeyInfo</td>
  <td style="text-align: left;"><p>This field is used to specify the subject’s public key and the associated algorithm. The mapping between the algorithms, their parameters, and their corresponding OIDs is specified in Section 7.1.3.</p>
  
  <ul>
    <li>RSA: rsaEncryption</li>
    <li>ECDSA: ecPublicKey
      <ol type="a">
        <li>secp256r1(NIST P-256)</li>
        <li>secp384r1(NIST P-384)</li>
      </ol>
    </li>
  </ul>
  
  </td>
  </tr>
  </tbody>
  </table>

- Extensions

  <table>
  <colgroup>
  <col style="width: 24%" />
  <col style="width: 16%" />
  <col style="width: 14%" />
  <col style="width: 45%" />
  </colgroup>
  <thead>
  <tr>
  <th style="text-align: center;"><strong>Extension</strong></th>
  <th style="text-align: center;"><strong>Presence</strong></th>
  <th style="text-align: center;"><strong>Criticality</strong></th>
  <th style="text-align: center;"><strong>Description</strong></th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td>Authority Key Identifier</td>
  <td align="center">MUST</td>
  <td align="center">N</td>
  <td style="text-align: left;">Only the keyIdentifier field, used to contain the SHA-1 hash value of the subordinate CA’s public key, is present in this extension. Its value must be identical to the subjectKeyIdentifier extension of the subordinate CA certificate.</td>
  </tr>
  <tr>
  <td>Subject Key Identifier</td>
  <td align="center">OPTIONAL</td>
  <td align="center">N</td>
  <td style="text-align: left;">The 160-bit SHA-1 hash value of the subscriber’s public key.</td>
  </tr>
  <tr>
  <td nowrap>Certificate Policies</td>
  <td align="center">MUST</td>
  <td align="center">N</td>
  <td style="text-align: left;">This extension is used to indicate the CP OID(s) that the subordinate CA uses. The policy qualifier field in this extension may be used as needed. When using this field, it may contain a CPS pointer qualifier that points to this CP/CPS. The following CP OIDs may be contained in this extension:
  <ul>
  <li>The CA/Browser Forum-assigned OID(s) referenced in this CP/CPS. It must be associated with the given subscriber certificate type and only one may be contained (required)</li>
  <li>CP OIDs defined in this CP/CPS (optional)</li>
  </ul></td>
  </tr>
  <tr>
  <td>CRL Distribution Points</td>
  <td align="center">MUST</td>
  <td align="center">N</td>
  <td style="text-align: left;">The HTTP URL of the subordinate CA’s CRL service.</td>
  </tr>
  <tr>
  <td>Authority Information Access</td>
  <td align="center">MUST</td>
  <td align="center">N</td>
  <td style="text-align: left;">The information contained in this extension are as follows:
  <ul>
  <li>The HTTP URL of the subordinate CA’s certificate (required)</li>
  <li>The HTTP URL of the subordinate CA’s OCSP responder (optional)</li>
  </ul></td>
  </tr>
  <tr>
  <td>Subject Alternative Name</td>
  <td align="center">MUST</td>
  <td align="center">N</td>
  <td style="text-align: left;">The extension MUST contain at least one entry, which contains either an FQDN or a Wildcard Domain Name.</td>
  </tr>
  <tr>
  <td nowrap>Basic Constraints</td>
  <td align="center">OPTIONAL</td>
  <td align="center">Y</td>
  <td style="text-align: left;">Subject Type=End Entity<p>
  Path Length Constraint= None</td>
  </tr>
  <tr>
  <td>Key Usage</td>
  <td align="center">MUST</td>
  <td align="center">Y</td>
  <td style="text-align: left;">For RSA public keys, bits contained in this extension are as follows:
  
  <ul>
    <li>digitalSignature (required)</li>
    <li>keyEncipherment (as specified below by CA)
      <ol type="a">
        <li>The keyEncipherment bit shall not be set in this extension of certificates issued by HiPKI OV TLS CA on or after March 2026.</li>
        <li>The keyEncipherment bit shall not be set in this extension of certificates issued by CHT Trust TLS CA.</li>
      </ol>
    </li>
  </ul>  
  
  <p>For ECDSA public keys, bits contained in this extension are as follows:</p>
  <ul>
  <li>digitalSignature</li>
  </ul>
  </td>
  </tr>
  <tr>
  <td>Extended Key Usage</td>
  <td align="center">MUST</td>
  <td align="center">N</td>
  <td style="text-align: left;">KeyPurposeIds contained in this extension are as follows:
  
  <ul>
    <li>id-kp-serverAuth (required)</li>
    <li>id-kp-clientAuth (as specified below by CA)
      <ol type="a">
        <li>HiPKI OV TLS CA has ceased asserting id-kp-clientAuth in this extension, and certificates issued on or after March 15, 2027, shall not include it.</li>
        <li>CHT Trust TLS CA shall not assert id-kp-clientAuth in this extension.</li>
      </ol>
    </li>
  </ul>
    
  </td>
  </tr>
  <tr>
  <td>Signed Certificate Timestamp List</td>
  <td align="center">OPTIONAL</td>
  <td align="center">N</td>
  <td style="text-align: left;">If present, this extension includes an OCTET STRING that contains the encoded SignedCertificateTimestampList, in accordance with RFC 6962.</td>
  </tr>
  </tbody>
  </table>

# Appendix 4: HiPKI CA Certificate List

See the list of our CA certificates at https://chtca.hinet.net/assets/download/CACertlist.pdf.

# Appendix 5: BRs-Section 1.2.1 Revisions

The revision of this CP/CPS is based on version 2.3.0 of the Baseline Requirements.

<table style="width:100%;">
<colgroup>
<col style="width: 8%" />
<col style="width: 8%" />
<col style="width: 48%" />
<col style="width: 18%" />
<col style="width: 18%" />
</colgroup>
<thead>
<tr>
<th style="text-align: center;"><strong>Ver.</strong></th>
<th style="text-align: center;"><strong>Ballot</strong></th>
<th><strong>Description</strong></th>
<th style="text-align: center;"><strong>Adopted</strong></th>
<th style="text-align: center;"><strong>Effective*</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">2.0.6</td>
<td align="center">SC75</td>
<td>Pre-sign linting</td>
<td align="center" nowrap>28-Jun-2024</td>
<td align="center" nowrap>6-Aug-2024</td>
</tr>
<tr>
<td align="center">2.0.7</td>
<td align="center">SC67</td>
<td>Require Multi-Perspective Issuance Corroboration</td>
<td align="center" nowrap>2-Aug-2024</td>
<td align="center" nowrap>6-Sep-2024</td>
</tr>
<tr>
<td align="center">2.0.8</td>
<td align="center">SC77</td>
<td>Update WebTrust Audit name in Section 8.4 and References</td>
<td align="center" nowrap>2-Sep-2024</td>
<td align="center" nowrap>2-Oct-2024</td>
</tr>
<tr>
<td align="center">2.0.9</td>
<td align="center">SC78</td>
<td>Subject organizationName alignment for DBA / Assumed Name</td>
<td align="center" nowrap>2-Oct-2024</td>
<td align="center" nowrap>8-Nov-2024</td>
</tr>
<tr>
<td align="center">2.1.0</td>
<td align="center">SC76</td>
<td>Clarify and improve OCSP requirements</td>
<td align="center" nowrap>26-Sep-2024</td>
<td align="center" nowrap>14-Nov-2024</td>
</tr>
<tr>
<td align="center">2.1.1</td>
<td align="center">SC79</td>
<td>Allow more than one Certificate Policy in a Cross-Certified Subordinate CA Certificate</td>
<td align="center" nowrap>30-Sep-2024</td>
<td align="center" nowrap>14-Nov-2024</td>
</tr>
<tr>
<td align="center">2.1.2</td>
<td align="center">SC80</td>
<td>Strengthen WHOIS lookups and Sunset Methods 3.2.2.4.2 and 3.2.2.4.15</td>
<td align="center" nowrap>7-Nov-2024</td>
<td align="center" nowrap>16-Dec-2024</td>
</tr>
<tr>
<td align="center">2.1.3</td>
<td align="center">SC83</td>
<td>Winter 2024‐2025 Cleanup Ballot</td>
<td align="center" nowrap>23‐Jan‐2025</td>
<td align="center" nowrap>24‐Feb‐2025</td>
</tr>
<tr>
<td align="center">2.1.4</td>
<td align="center">SC84</td>
<td>DNS Labeled with ACME Account ID Validation Method</td>
<td align="center" nowrap>28‐Jan‐2025</td>
<td align="center"nowrap>1‐Mar‐2025</td>
</tr>
<tr>
<td align="center">2.1.5</td>
<td align="center">SC81</td>
<td>Introduce Schedule of Reducing Validity and Data Reuse Periods</td>
<td align="center" nowrap>11-Apr-2025</td>
<td align="center" nowrap>16-May-2025</td>
</tr>
<tr>
<td align="center">2.1.6</td>
<td align="center">SC085v2</td>
<td>Require Validation of DNSSEC (when present) for CAA and DCV Lookups</td>
<td align="center" nowrap>19-Jun-2025</td>
<td align="center" nowrap>21-Jul-2025</td>
</tr>
<tr>
<td align="center">2.1.7</td>
<td align="center">SC089</td>
<td>Mass Revocation Planning</td>
<td align="center" nowrap>23-Jul-2025</td>
<td align="center" nowrap>25-Aug-2025</td>
</tr>
<tr>
<td align="center">2.1.8</td>
<td align="center">SC092</td>
<td>Sunset Precertificate Signing CAs</td>
<td align="center" nowrap>03-Oct-2025</td>
<td align="center" nowrap>04-Nov-2025</td>
</tr>
<tr>
<td align="center">2.1.9</td>
<td align="center">SC088</td>
<td>DNS TXT Record with Persistent Value DCV Method</td>
<td align="center" nowrap>09-Oct-2025</td>
<td align="center" nowrap>10-Nov-2025</td>
</tr>
<tr>
<td align="center">2.2.0</td>
<td align="center">SC086</td>
<td>Sunset the Inclusion of Address and Routing Parameter Area Names</td>
<td align="center" nowrap>2025- 11-13</td>
<td align="center" nowrap>2026-12-15</td>
</tr>
<tr>
<td align="center">2.2.1</td>
<td align="center">SC091</td>
<td><ol type="1">
<li>Sunset 3.2.2.5.3 Reverse Address Lookup Validation</li>
<li>new DNS-based validation using Persistent DCV TXT Record for IP addresses</li>
</ol></td>
<td align="center" nowrap>2025-11-13</td>
<td align="center" nowrap>2026-12-16</td>
</tr>
<tr>
<td align="center">2.2.2</td>
<td align="center">SC090</td>
<td>Gradually sunset remaining email-based, phone-based, and ‘crossover’ validation methods</td>
<td align="center" nowrap>2025-11-20</td>
<td align="center" nowrap>2026-01-12</td>
</tr>
<tr>
<td align="center">2.2.3</td>
<td align="center">SC094</td>
<td>DNSSEC exception in email DCV methods</td>
<td align="center" nowrap>2026-01-15</td>
<td align="center" nowrap>2026-02-16</td>
</tr>
<tr>
<td align="center">2.2.4</td>
<td align="center">SC096</td>
<td>Carve-out for DNSSEC verification logging requirements</td>
<td align="center" nowrap>2026-01-14</td>
<td align="center" nowrap>2026-02-17</td>
</tr>
<tr>
<td align="center">2.2.5</td>
<td align="center">SC097</td>
<td>Sunset all remaining use of SHA‐1 signatures in Certificates and CRLs</td>
<td align="center" nowrap>2026‐02‐24</td>
<td align="center" nowrap>2026‐02‐25</td>
</tr>
<tr>
<td align="center">2.2.6</td>
<td align="center">SC095</td>
<td>Clean‐up 2025</td>
<td align="center" nowrap>2026‐02‐27</td>
<td align="center" nowrap>2026‐03‐31</td>
</tr>
<tr>
<td align="center">2.2.7</td>
<td align="center">SC099</td>
<td>Improve Recording of Validation Method</td>
<td align="center" nowrap>2026‐04‐18</td>
<td align="center" nowrap>2026‐05‐19</td>
</tr>
<tr>
<td align="center">2.2.8</td>
<td align="center">SC098</td>
<td>Process RFC 8657 CAA Parameters</td>
<td align="center" nowrap>2026-05-13</td>
<td align="center" nowrap>2026-06-16</td>
</tr>
<tr>
<td align="center">2.2.9</td>
<td align="center">SC101</td>
<td>Clarify Authorization Domain Names</td>
<td align="center" nowrap>2026-07-02</td>
<td align="center" nowrap>2026-08-06</td>
</tr>
<tr>
<td align="center">2.3.0</td>
<td align="center">SC100</td>
<td>DNSSEC Clarification and Consolidation</td>
<td align="center" nowrap>2026-08-06</td>
<td align="center">2026-09-07</td>
</tr>
<tr>
<td align="center"></td>
<td align="center"></td>
<td></td>
<td align="center"></td>
<td align="center"></td>
</tr>
</tbody>
</table>

