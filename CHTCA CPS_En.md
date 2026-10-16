# Chunghwa Telecom Certification Authority Certification Practice Statement (CHTCA CPS)


- **Version: 1.5**
- **Chunghwa Telecom Co., Ltd.**
- **Publication date: October 12, 2026**


<div style="page-break-before: always;"></div>

## Table of Contents

<!-- TOC -->
- [1 Introduction](#section-1)
  - [1.1 Overview](#section-1-1)
    - [1.1.1 Certification Practice Statement](#section-1-1-1)
    - [1.1.2 CPS Applicability](#section-1-1-2)
  - [1.2 Document Name and Identification](#section-1-2)
  - [1.3 PKI Participants](#section-1-3)
    - [1.3.1 Certification Authorities](#section-1-3-1)
    - [1.3.2 Registration Authorities](#section-1-3-2)
    - [1.3.3 Subscribers](#section-1-3-3)
    - [1.3.4 Relying Parties](#section-1-3-4)
    - [1.3.5 Other Participants](#section-1-3-5)
  - [1.4 Certificate Usage](#section-1-4)
    - [1.4.1 Appropriate Certificate Uses](#section-1-4-1)
    - [1.4.2 Prohibited Certificate Uses](#section-1-4-2)
  - [1.5 Policy Administration](#section-1-5)
    - [1.5.1 Organization Administering the Document](#section-1-5-1)
    - [1.5.2 Contact Person](#section-1-5-2)
      - [1.5.2.1 CPS Related Issues](#section-1-5-2-1)
      - [1.5.2.2 Certificate Problem Report](#section-1-5-2-2)
    - [1.5.3 Person Determining CPS Suitability for the Policy](#section-1-5-3)
    - [1.5.4 CPS Approval Procedures](#section-1-5-4)
  - [1.6 Definitions and Acronyms](#section-1-6)
- [2 Publication and Repository Responsibilities](#section-2)
  - [2.1 Repositories](#section-2-1)
  - [2.2 Publication of Certification Information](#section-2-2)
  - [2.3 Time or Frequency of Publication](#section-2-3)
  - [2.4 Access Controls on Repositories](#section-2-4)
- [3 Identification and Authentication](#section-3)
  - [3.1 Naming](#section-3-1)
    - [3.1.1 Types of Names](#section-3-1-1)
    - [3.1.2 Need for Names to be Meaningful](#section-3-1-2)
    - [3.1.3 Anonymity or Pseudonymity of Subscribers](#section-3-1-3)
    - [3.1.4 Rules for Interpreting Various Name Forms](#section-3-1-4)
    - [3.1.5 Uniqueness of Names](#section-3-1-5)
    - [3.1.6 Recognition, Authentication, and Role of Trademarks](#section-3-1-6)
  - [3.2 Initial Identity Validation](#section-3-2)
    - [3.2.1 Method to Prove Possession of Private Key](#section-3-2-1)
    - [3.2.2 Authentication of Organization Identity](#section-3-2-2)
    - [3.2.3 Authentication of Individual Identity](#section-3-2-3)
    - [3.2.4 Non-verified Subscriber Information](#section-3-2-4)
    - [3.2.5 Validation of Authority](#section-3-2-5)
    - [3.2.6 Criteria for Interoperation](#section-3-2-6)
    - [3.2.7 Data Source Accuracy](#section-3-2-7)
  - [3.3 Identification and Authentication for Re-key Requests](#section-3-3)
    - [3.3.1 Identification and Authentication for Routine Re-key](#section-3-3-1)
    - [3.3.2 Identification and Authentication for Re-key after Revocation](#section-3-3-2)
  - [3.4 Identification and Authentication for Revocation Request](#section-3-4)
- [4 Certificate Life-cycle Operational Requirements](#section-4)
  - [4.1 Certificate Application](#section-4-1)
    - [4.1.1 Who Can Submit a Certificate Application](#section-4-1-1)
    - [4.1.2 Enrollment Process and Responsibilities](#section-4-1-2)
  - [4.2 Certificate Application Processing](#section-4-2)
    - [4.2.1 Performing Identification and Authentication Functions](#section-4-2-1)
    - [4.2.2 Approval or Rejection of Certificate Applications](#section-4-2-2)
    - [4.2.3 Time to Process Certificate Applications](#section-4-2-3)
  - [4.3 Certificate Issuance](#section-4-3)
    - [4.3.1 CA Actions during Certificate Issuance](#section-4-3-1)
    - [4.3.2 Notification to Subscriber by the CA of Issuance of Certificate](#section-4-3-2)
  - [4.4 Certificate Acceptance](#section-4-4)
    - [4.4.1 Conduct Constituting Certificate Acceptance](#section-4-4-1)
    - [4.4.2 Publication of the Certificate by the CA](#section-4-4-2)
    - [4.4.3 Notification of Certificate Issuance by the CA to Other Entities](#section-4-4-3)
  - [4.5 Key Pair and Certificate Usage](#section-4-5)
    - [4.5.1 Subscriber Private Key and Certificate Usage](#section-4-5-1)
    - [4.5.2 Relying Party Public Key and Certificate Usage](#section-4-5-2)
  - [4.6 Certificate Renewal](#section-4-6)
    - [4.6.1 Circumstances for Certificate Renewal](#section-4-6-1)
    - [4.6.2 Who May Request Renewal](#section-4-6-2)
    - [4.6.3 Processing Certificate Renewal Requests](#section-4-6-3)
    - [4.6.4 Notification of New Certificate Issuance to Subscriber](#section-4-6-4)
    - [4.6.5 Conduct Constituting Acceptance of a Renewal Certificate](#section-4-6-5)
    - [4.6.6 Publication of the Renewal Certificate by the CA](#section-4-6-6)
    - [4.6.7 Notification of Certificate Issuance by the CA to Other Entities](#section-4-6-7)
  - [4.7 Certificate Re-Key](#section-4-7)
    - [4.7.1 Circumstance for Certificate Re-key](#section-4-7-1)
    - [4.7.2 Who May Request Certification of a New Public Key](#section-4-7-2)
    - [4.7.3 Processing Certificate Re-keying Requests](#section-4-7-3)
    - [4.7.4 Notification of New Certificate Issuance to Subscriber](#section-4-7-4)
    - [4.7.5 Conduct Constituting Acceptance of a Re-keyed Certificate](#section-4-7-5)
    - [4.7.6 Publication of the Re-keyed Certificate by the CA](#section-4-7-6)
    - [4.7.7 Notification of Certificate Issuance by the CA to Other Entities](#section-4-7-7)
  - [4.8 Certificate Modification](#section-4-8)
    - [4.8.1 Circumstance for Certificate Modification](#section-4-8-1)
    - [4.8.2 Who May Request Certificate Modification](#section-4-8-2)
    - [4.8.3 Processing Certificate Modification Requests](#section-4-8-3)
    - [4.8.4 Notification of New Certificate Issuance to Subscriber](#section-4-8-4)
    - [4.8.5 Conduct Constituting Acceptance of Modified Certificate](#section-4-8-5)
    - [4.8.6 Publication of the Modified Certificate by the CA](#section-4-8-6)
    - [4.8.7 Notification of Certificate Issuance by the CA to Other Entities](#section-4-8-7)
  - [4.9 Certificate Revocation and Suspension](#section-4-9)
    - [4.9.1 Circumstances for Revocation](#section-4-9-1)
      - [4.9.1.1 Circumstances for Revoking a Subscriber Certificate](#section-4-9-1-1)
      - [4.9.1.2 Circumstances for Revoking a Subordinate CA Certificate](#section-4-9-1-2)
    - [4.9.2 Who Can Request Revocation](#section-4-9-2)
    - [4.9.3 Procedure for Revocation Request](#section-4-9-3)
      - [4.9.3.1 Mechanism for Responding the Certificate Problems](#section-4-9-3-1)
    - [4.9.4 Revocation Request Grace Period](#section-4-9-4)
    - [4.9.5 Time within Which CA Must Process the Revocation Request](#section-4-9-5)
    - [4.9.6 Revocation Checking Requirement for Relying Parties](#section-4-9-6)
    - [4.9.7 CRL Issuance Frequency](#section-4-9-7)
    - [4.9.8 Maximum Latency for CRLs](#section-4-9-8)
    - [4.9.9 On-line Revocation/Status Checking Availability](#section-4-9-9)
    - [4.9.10 On-line Revocation Checking Requirements](#section-4-9-10)
    - [4.9.11 Other Forms of Revocation Advertisements Available](#section-4-9-11)
    - [4.9.12 Special Requirements Related to Key Compromise](#section-4-9-12)
    - [4.9.13 Circumstances for Suspension](#section-4-9-13)
    - [4.9.14 Who Can Request Suspension](#section-4-9-14)
    - [4.9.15 Procedure for Suspension Request](#section-4-9-15)
    - [4.9.16 Limits on Suspension Period](#section-4-9-16)
    - [4.9.17 Procedure for Certificate Resumption](#section-4-9-17)
  - [4.10 Certificate Status Services](#section-4-10)
    - [4.10.1 Operational Characteristics](#section-4-10-1)
    - [4.10.2 Service Availability](#section-4-10-2)
    - [4.10.3 Optional Features](#section-4-10-3)
  - [4.11 End of Subscription](#section-4-11)
  - [4.12 Key Escrow and Recovery](#section-4-12)
    - [4.12.1 Key Escrow and Recovery Policy and Practices](#section-4-12-1)
    - [4.12.2 Session Key Encapsulation and Recovery Policy and Practices](#section-4-12-2)
- [5 Facility, Management, and Operation Controls](#section-5)
  - [5.1 Physical Controls](#section-5-1)
    - [5.1.1 Site Location and Construction](#section-5-1-1)
    - [5.1.2 Physical Access](#section-5-1-2)
    - [5.1.3 Power and Air Conditioning](#section-5-1-3)
    - [5.1.4 Water Exposures](#section-5-1-4)
    - [5.1.5 Fire Prevention and Protection](#section-5-1-5)
    - [5.1.6 Media Storage](#section-5-1-6)
    - [5.1.7 Waste Disposal](#section-5-1-7)
    - [5.1.8 Off-site Backup](#section-5-1-8)
  - [5.2 Procedural Controls](#section-5-2)
    - [5.2.1 Trusted Roles](#section-5-2-1)
    - [5.2.2 Number of Persons Required per Task](#section-5-2-2)
    - [5.2.3 Identification and Authentication for Each Role](#section-5-2-3)
    - [5.2.4 Roles Requiring Separation of Duties](#section-5-2-4)
  - [5.3 Personnel Controls](#section-5-3)
    - [5.3.1 Qualifications, Experience, and Clearance Requirements](#section-5-3-1)
    - [5.3.2 Background Check Procedures](#section-5-3-2)
    - [5.3.3 Training Requirements](#section-5-3-3)
    - [5.3.4 Retraining Frequency and Requirements](#section-5-3-4)
    - [5.3.5 Job Rotation Frequency and Sequence](#section-5-3-5)
    - [5.3.6 Sanctions for Unauthorized Actions](#section-5-3-6)
    - [5.3.7 Independent Contractor Requirements](#section-5-3-7)
    - [5.3.8 Documentation Supplied to Personnel](#section-5-3-8)
  - [5.4 Audit Logging Procedures](#section-5-4)
    - [5.4.1 Types of Events Recorded](#section-5-4-1)
    - [5.4.2 Frequency of Processing Log](#section-5-4-2)
    - [5.4.3 Retention Period for Audit Log](#section-5-4-3)
    - [5.4.4 Protection of Audit Log](#section-5-4-4)
    - [5.4.5 Audit Log Backup Procedures](#section-5-4-5)
    - [5.4.6 Audit Collection System (Internal vs. External)](#section-5-4-6)
    - [5.4.7 Notification to Event-causing Subject](#section-5-4-7)
    - [5.4.8 Vulnerability Assessments](#section-5-4-8)
  - [5.5 Records Archival](#section-5-5)
    - [5.5.1 Types of Records Archived](#section-5-5-1)
    - [5.5.2 Retention Period for Archive](#section-5-5-2)
    - [5.5.3 Protection of Archive](#section-5-5-3)
    - [5.5.4 Archive Backup Procedures](#section-5-5-4)
    - [5.5.5 Requirements for Time-stamping of Records](#section-5-5-5)
    - [5.5.6 Archive Collection System (Internal or External)](#section-5-5-6)
    - [5.5.7 Procedures to Obtain and Verify Archive Information](#section-5-5-7)
  - [5.6 Key Changeover](#section-5-6)
  - [5.7 Compromise and Disaster Recovery](#section-5-7)
    - [5.7.1 Incident and Compromise Handling Procedures](#section-5-7-1)
    - [5.7.2 Computing Resources, Software, and/or Data Are Corrupted](#section-5-7-2)
    - [5.7.3 Entity Private Key Compromise Procedures](#section-5-7-3)
    - [5.7.4 Business Continuity Capabilities after a Disaster](#section-5-7-4)
  - [5.8 CA or RA Termination](#section-5-8)
- [6 Technical Security Controls](#section-6)
  - [6.1 Key Pair Generation and Installation](#section-6-1)
    - [6.1.1 Key Pair Generation](#section-6-1-1)
    - [6.1.2 Private Keys Delivery to Subscriber](#section-6-1-2)
    - [6.1.3 Public Key Delivery to Certificate Issuer](#section-6-1-3)
    - [6.1.4 CA Public Key Delivery to Relying Parties](#section-6-1-4)
    - [6.1.5 Key Sizes](#section-6-1-5)
    - [6.1.6 Public Key Parameters Generation and Quality Checking](#section-6-1-6)
    - [6.1.7 Key Usage Purposes (as per X.509 v3 Key Usage Field)](#section-6-1-7)
      - [6.1.7.1 Key Usage Purposes of CAs](#section-6-1-7-1)
      - [6.1.7.2 Key Usage Purposes of Subscribers](#section-6-1-7-2)
  - [6.2 Private Key Protection and Cryptographic Module Engineering Controls](#section-6-2)
    - [6.2.1 Cryptographic Module Standards and Controls](#section-6-2-1)
    - [6.2.2 Private Key (n-out-of-m) Multi-person Control](#section-6-2-2)
    - [6.2.3 Private Key Escrow](#section-6-2-3)
    - [6.2.4 Private Key Backup](#section-6-2-4)
    - [6.2.5 Private Key Archival](#section-6-2-5)
    - [6.2.6 Private Key Transfer into or from a Cryptographic Module](#section-6-2-6)
    - [6.2.7 Private Key Storage on Cryptographic Module](#section-6-2-7)
    - [6.2.8 Method of Activating Private Key](#section-6-2-8)
    - [6.2.9 Method of Deactivating Private Key](#section-6-2-9)
    - [6.2.10 Method of Destroying Private Key](#section-6-2-10)
    - [6.2.11 Cryptographic Module Rating](#section-6-2-11)
  - [6.3 Other Aspects of Key Pair Management](#section-6-3)
    - [6.3.1 Public Key Archival](#section-6-3-1)
    - [6.3.2 Certificate Operational Periods and Key Pair Usage Periods](#section-6-3-2)
      - [6.3.2.1 CA Certificate Operational Periods and Key Pair Usage Periods](#section-6-3-2-1)
      - [6.3.2.2 Subscriber Certificate Operational Periods and Key Pair Usage Periods](#section-6-3-2-2)
  - [6.4 Activation Data](#section-6-4)
    - [6.4.1 Activation Data Generation and Installation](#section-6-4-1)
    - [6.4.2 Activation Data Protection](#section-6-4-2)
    - [6.4.3 Other Aspects of Activation Data](#section-6-4-3)
  - [6.5 Computer Security Controls](#section-6-5)
    - [6.5.1 Specific Computer Security Technical Requirements](#section-6-5-1)
    - [6.5.2 Computer Security Rating](#section-6-5-2)
  - [6.6 Life Cycle Technical Controls](#section-6-6)
    - [6.6.1 System Development Controls](#section-6-6-1)
    - [6.6.2 Security Management Controls](#section-6-6-2)
    - [6.6.3 Life Cycle Security Controls](#section-6-6-3)
  - [6.7 Network Security Controls](#section-6-7)
  - [6.8 Time-stamping](#section-6-8)
- [7 Certificate, CRL, and OCSP Profiles](#section-7)
  - [7.1 Certificate Profile](#section-7-1)
    - [7.1.1 Version Number(s)](#section-7-1-1)
    - [7.1.2 Certificate Extensions](#section-7-1-2)
    - [7.1.3 Algorithm Object Identifiers](#section-7-1-3)
    - [7.1.4 Name Forms](#section-7-1-4)
      - [7.1.4.1 Name Encoding](#section-7-1-4-1)
      - [7.1.4.2 Subject Information–CA Certificates](#section-7-1-4-2)
      - [7.1.4.3 Subject Information–Subscriber Certificates](#section-7-1-4-3)
    - [7.1.5 Name Constraints](#section-7-1-5)
    - [7.1.6 Certificate Policy Object Identifier](#section-7-1-6)
    - [7.1.7 Usage of Policy Constraints Extension](#section-7-1-7)
    - [7.1.8 Policy Qualifiers Syntax and Semantics](#section-7-1-8)
    - [7.1.9 Processing Semantics for the Critical Certificate Policies Extension](#section-7-1-9)
  - [7.2 CRL Profile](#section-7-2)
    - [7.2.1 Version Number(s)](#section-7-2-1)
    - [7.2.2 CRL and CRL Entry Extensions](#section-7-2-2)
  - [7.3 OCSP Profile](#section-7-3)
    - [7.3.1 Version Number(s)](#section-7-3-1)
    - [7.3.2 OCSP Extensions](#section-7-3-2)
- [8 Compliance Audit and Other Assessments](#section-8)
  - [8.1 Frequency or Circumstances of Assessment](#section-8-1)
  - [8.2 Identity/Qualifications of Assessor](#section-8-2)
  - [8.3 Assessor’s Relationship to Assessed Entity](#section-8-3)
  - [8.4 Topics Covered by Assessment](#section-8-4)
  - [8.5 Actions Taken as a Result of Deficiency](#section-8-5)
  - [8.6 Communications of Results](#section-8-6)
- [9 Other Business and Legal Matters](#section-9)
  - [9.1 Fees](#section-9-1)
    - [9.1.1 Certificate Issuance or Renewal Fees](#section-9-1-1)
    - [9.1.2 Certificate Access Fees](#section-9-1-2)
    - [9.1.3 Revocation or Status Information Access Fees](#section-9-1-3)
    - [9.1.4 Fees for Other Services](#section-9-1-4)
    - [9.1.5 Refund Policy](#section-9-1-5)
  - [9.2 Financial Responsibility](#section-9-2)
    - [9.2.1 Insurance Coverage](#section-9-2-1)
    - [9.2.2 Other Assets](#section-9-2-2)
    - [9.2.3 Insurance or Warranty Coverage for End-Entities](#section-9-2-3)
  - [9.3 Confidentiality of Business Information](#section-9-3)
    - [9.3.1 Scope of Confidential Information](#section-9-3-1)
    - [9.3.2 Information Not Within the Scope of Confidential Information](#section-9-3-2)
    - [9.3.3 Responsibility to Protect Confidential Information](#section-9-3-3)
  - [9.4 Privacy of Personal Information](#section-9-4)
    - [9.4.1 Privacy Plan](#section-9-4-1)
    - [9.4.2 Information Treated as Private](#section-9-4-2)
    - [9.4.3 Information Not Deemed Private](#section-9-4-3)
    - [9.4.4 Responsibility to Protect Private Information](#section-9-4-4)
    - [9.4.5 Notice and Consent to Use Private Information](#section-9-4-5)
    - [9.4.6 Disclosure Pursuant to Judicial or Administrative Process](#section-9-4-6)
    - [9.4.7 Other Information Disclosure Circumstances](#section-9-4-7)
  - [9.5 Intellectual Property Rights](#section-9-5)
  - [9.6 Representations and Warranties](#section-9-6)
    - [9.6.1 CA Representations and Warranties](#section-9-6-1)
    - [9.6.2 RA Representations and Warranties](#section-9-6-2)
    - [9.6.3 Subscriber Representations and Warranties](#section-9-6-3)
    - [9.6.4 Relying Party Representations and Warranties](#section-9-6-4)
    - [9.6.5 Representations and Warranties of Other Participants](#section-9-6-5)
  - [9.7 Disclaimers of Warranties](#section-9-7)
  - [9.8 Limitations of Liability](#section-9-8)
  - [9.9 Indemnities](#section-9-9)
    - [9.9.1 Indemnification by CHTCA](#section-9-9-1)
    - [9.9.2 Indemnification by RA](#section-9-9-2)
  - [9.10 Term and Termination](#section-9-10)
    - [9.10.1 Term](#section-9-10-1)
    - [9.10.2 Termination](#section-9-10-2)
    - [9.10.3 Effect of Termination and Survival](#section-9-10-3)
  - [9.11 Individual Notices and Communications with Participants](#section-9-11)
  - [9.12 Amendments](#section-9-12)
    - [9.12.1 Procedure for Amendment](#section-9-12-1)
    - [9.12.2 Notification Mechanism and Period](#section-9-12-2)
    - [9.12.3 Circumstances under which OID Must Be Changed](#section-9-12-3)
  - [9.13 Dispute Resolution Provisions](#section-9-13)
  - [9.14 Governing Law](#section-9-14)
  - [9.15 Compliance with Applicable Law](#section-9-15)
  - [9.16 Miscellaneous Provisions](#section-9-16)
    - [9.16.1 Entire Agreement](#section-9-16-1)
    - [9.16.2 Assignment](#section-9-16-2)
    - [9.16.3 Severability](#section-9-16-3)
    - [9.16.4 Enforcement (Attorney’s Fees and Waiver of Rights)](#section-9-16-4)
    - [9.16.5 Force Majeure](#section-9-16-5)
  - [9.17 Other Provisions](#section-9-17)
- [Appendix 1: Acronyms and Definitions](#appendix-1)
- [Appendix 2: Glossary](#appendix-2)
- [Appendix 3: Certificate Extensions](#appendix-3)
- [Appendix 3-1: CA Certificates](#appendix-3-1)
- [Appendix 3-2: Subscriber Certificates](#appendix-3-2)
<!-- /TOC -->

## CPS Version Control
<table>
<colgroup>
<col style="width: 16%" />
<col style="width: 21%" />
<col style="width: 62%" />
</colgroup>
<thead>
<tr>
<th style="text-align: center;">Version </th>
<th style="text-align: center;">Date </th>
<th style="text-align: center;">Revision Summary </th>
</tr>
</thead>
<tbody>
<tr>
<td>0.95 </td>
<td nowrap>April 22, 2022 </td>
<td><ol type="1">
<li>First Released.</li>
<li>Combined version of CPS documents of four CAs, including eCA,
PublicCA, eTSCA and CHT SMIME CA.</li>
</ol></td>
</tr>
<tr>
<td>1.0 </td>
<td nowrap>April 6, 2023 </td>
<td style="text-align: left;">The version approved by the competent
authority, Ministry of Digital Affairs. This version is a CPS document
that integrates eCA CPS version 1.75, eTSCA CPS version 1.01, PublicCA
CPS version 2.06 and CHT SMIME CA CPS version 1.05. After the
announcement of this document, the effectiveness of the aforementioned
four CPS documents will be terminated and will be removed to the archive
area simultaneously.</td>
</tr>
<tr>
<td>1.05 </td>
<td nowrap>August 29, 2023 </td>
<td style="text-align: left;">Amendments are made on Sections 1.2, 2.3,
3.1.6, 3.2.2, 3.2.3, 3.2.5, 3.2.5.7, 4.1.1, 4.5.2, 4.9.10, 5.3.3, 6.1.2,
6.1.5, 6.1.6, 6.2.3, 6.2.6, 6.2.8, 6.2.9, 6.3.2.1, 6.4.1, 6.4.3, 6.6.1,
7.1.4.2, 7.2.2, 8.4, 8.7, 9.5 and 9.6.1.</td>
</tr>
<tr>
<td>1.07 </td>
<td nowrap>May 06, 2024 </td>
<td style="text-align: left;">Incrementing the version number.</td>
</tr>
<tr>
<td>1.1 </td>
<td nowrap>Aug. 27, 2024 </td>
<td style="text-align: left;">The version approved by the competent
authority, Ministry of Digital Affairs.</td>
</tr>
<tr>
<td>1.2 </td>
<td nowrap>May 19, 2025 </td>
<td><ol type="1">
<li>Amendments are made on Sections 1.1.1, 1.2, 1.3.1, 1.3.2, 1.4.1,
1.4.2, 1.5.3, 2.1, 2.2, 2.3, 3.1.1, 3.1.2, 3.1.3, 3.1.5, 3.2.2, 3.2.4,
3.2.5, 3.2.7, 3.2.8, 3.3.1, 4.2.1, 4.2.2, 4.2.3, 4.3.1, 4.4.1, 4.4.2,
4.4.3, 4.5.2, 4.9.1.1, 4.9.10, 4.9.11, 4.9.13, 5.4.8, 6.1.2, 6.1.6,
6.1.7.1, 6.1.7.2, 6.2.5, 6.2.7, 6.3.2.1, 6.3.2.2, 6.6.1, 6.6.2, 7.1,
7.1.2, 7.1.4, 7.1.4.1, 7.1.4.2, 7.1.4.3, 7.2.2, 7.3.1, 8.2, 8.4, 8.6,
8.7, 9.2.2, 9.3.3, 9.6.1, 9.6.3, 9.12.3, 9.16.3, Appdendix 1, Appendix
2, Appendix 3, Appendix 3-1, and Appendix 3-2.</li>
<li>In light of PublicCA’s cessation of TLS certificate issuance as
of December 10, 2024, all corresponding provisions related to TLS
certificates have been formally removed from this CPS.</li>
</ol></td>
</tr>
<tr>
<td>1.3 </td>
<td nowrap>Oct. 29, 2025 </td>
<td><ol type="1">
<li>The version approved by the competent authority, Ministry of
Digital Affairs.</li>
<li>Amendments are made on Section 6.3.2.2.</li>
</ol></td>
</tr>
<tr>
<td>1.4 </td>
<td nowrap>April 21, 2026 </td>
<td><ol type="1">
<li>PMA approved version.</li>
<li>Removal of the S/MIME service description and Sections 3.2.8 and
8.7.</li>
<li>Amendments are made on Sections 1.1, 1.1.1, 1.2, 1.3.1, 1.3.4,
2.2, 3.1.1, 3.1.5, 3.2.2, 3.2.3, 3.2.5, 4.2.3, 4.3.1, 4.5.1, 4.5.2, 4.6,
4.8.1, 4.9.6, 4.9.9, 4.9.10, 4.9.13, 4.10.1, 4.10.2, 6.1.1, 6.1.7.2,
6.2.1, 6.2.8, 6.3.2.1, 6.3.2.2, 6.6.1, 7.1, 7.1.3, 7.1.4, 7.1.4.3,
7.1.5, 7.1.6, 7.1.7, 7.2, 7.2.2, 7.3, 8.4, 9.6.1, Appdendix 1, Appendix
2, Appendix 3, Appendix 3-1, and Appendix 3-2.</li>
</ol></td>
</tr>
<tr>
<td>1.4.1 </td>
<td nowrap>June 11, 2026 </td>
<td><ol type="1">
<li>PMA approved version.</li>
<li>Amendments are made on Sections 1.1.1, 1.2, 6.7, 7.1, 7.2.2 and
7.3.1.</li>
</ol></td>
</tr>

<tr>
<td>1.5 </td>
<td nowrap>October 12, 2026 </td>
<td><ol type="1">
<li>The version approved by the competent authority, Ministry of
Digital Affairs.</li>
<li>Amendments are made on Sections 6.2.6, 6.7, 7.2.2, and Appdendix 3-1.</li>
</ol></td>
</tr>
</tbody>
</table>

<a id="section-1"></a>
## 1 Introduction

<a id="section-1-1"></a>
### 1.1 Overview

According to the ePKI Certificate Policy (CP), ePKI Root Certification
Authority (eCA) is a top-level CA and a trust anchor of ePKI. eCA must
maintain a high level of credibility that relying parties can directly
trust its certificates.

This Certification Practice Statement (CPS) uses the brand name of
Chunghwa Telecom Certification Authority (CHTCA) to refer to the eCA and
its subordinate CAs, including Public Certification Authority
(PublicCA), and ePKI Timestamping Certification Authority (eTSCA), owned
and operated by Chunghwa Telecom Co., Ltd. (CHT) in ePKI.

<a id="section-1-1-1"></a>
#### 1.1.1 Certification Practice Statement

This CPS describes the practices used to comply with the ePKI CP, the
R.O.C.

1)  Electronic Signatures Act and

2)  its sub-law “Regulations on Required Information for Certification
    Practice Statements”

and the latest published versions of related international standards or
regulations, including

1)  The Internet Engineering Task Force (IETF) request for comments
    (RFC) 3647, RFC 5280, RFC 6960, RFC 6962, RFC 5019, RFC 8659, RFC
    3161, RFC 5816 and RFC 3628;

2)  ITU-T X.509;

3)  TS 102 023, EN 319 421 and EN 319 422 of (European
    Telecommunications Standards Institute, ETSI);

4)  Baseline Requirements for the Issuance and Management of
    Publicly-Trusted Certificates (Baseline Requirements), and Network
    and Certificate System Security Requirements published by CA/Browser
    Forum (<https://www.cabforum.org>);

5)  Mozilla Root Store Policy;

6)  Microsoft Trusted Root Program Requirements;

7)  Apple Root Certificate Program Policy;

8)  Common CA Database (CCADB) Policy; and

9)  Google Chrome Root Program Policy,

to provide guidance and requirements for what CHTCA should include in
its CPS.

<a id="section-1-1-2"></a>
#### 1.1.2 CPS Applicability

The practice statement stipulated in this CPS applies to CAs of CHTCA,
registration authority (RA), subscribers, relying parties, repository,
and other participants.

<a id="section-1-2"></a>
### 1.2 Document Name and Identification

This document is Chunghwa Telecom Certification Authority Certification
Practice Statement. This CPS can be obtained at:
<https://chtca.hinet.net/en/repository.html>.

The identity assurance level (IAL) and the CP object identifiers (OIDs)
are listed in the Table below:

| **IAL** |              **OID Name**              |       **OID Value**        |
|:-------:|:--------------------------------------:|:--------------------------:|
| Level 1 | id-cht-ePKI-certpolicy-class1Assurance | {id-cht-ePKI-certpolicy 1} |
| Level 2 | id-cht-ePKI-certpolicy-class2Assurance | {id-cht-ePKI-certpolicy 2} |
| Level 3 | id-cht-ePKI-certpolicy-class3Assurance | {id-cht-ePKI-certpolicy 3} |
| Level 4 | id-cht-ePKI-certpolicy-class4Assurance | {id-cht-ePKI-certpolicy 4} |

The eCA certificate is a self-signed certificate. According to
international standards and practices, the eCA certificate does not
indicate the CP OID to reflect its high credibility of root CA and was
operated with IAL 4.

The above OIDs are gradually transferred to the id-pen-cht arc OID
registered as private enterprise number (PEN) with the Internet Assigned
Numbers Authority (IANA) from December 2014.

id-pen-cht ::= {1 3 6 1 4 1 23459}

id-pen-cht-ePKI ::= {1 3 6 1 4 1 23459 100}

id-pen-cht-ePKI-certpolicy::= {id-pen-cht-ePKI 0}

| **IAL** | **OID Name** | **OID Value** |
|:--:|----|----|
| Level 1 | id-pen-cht-ePKI-certpolicy-class1Assurance | {id-pen-cht-ePKI-certpolicy 1} |
| Level 2 | id-pen-cht-ePKI-certpolicy-class2Assurance | {id-pen-cht-ePKI-certpolicy 2} |
| Level 3 | id-pen-cht-ePKI-certpolicy-class3Assurance | {id-pen-cht-ePKI-certpolicy 3} |
| Level 4 | id-pen-cht-ePKI-certpolicy- class4Assurance | {id-pen-cht-ePKI-certpolicy 4} |

The CA certificate and PDF signing certificates (assurance level 2 or 3
certificates issued to organizations or individuals) issued by PublicCA
may use the OID 1.3.6.1.4.1.23459.100.0.9, which is approved by the
Adobe Approved Trust List (AATL).

<a id="section-1-3"></a>
### 1.3 PKI Participants

The key members of CHTCA include:

1)  CHTCA

2)  RAs

3)  Subscribers

4)  Relying Parties

<a id="section-1-3-1"></a>
#### 1.3.1 Certification Authorities

The following CAs of CHTCA are established and operated by Chunghwa
Telecom Co., Ltd. (CHT), the relevant CPS shall be submitted to the
Chunghwa Telecom Certificate Policy Management Authority (PMA) for
review and approve.

| **Certification Authority** | **Description** |
|:--:|:---|
| eCA | Root certificate authority, which has been implanted in major Root Certificate Programs. |
| PublicCA | Responsible for issuing publicly-trusted TLS certificates and natural person, organization, device, time-stamp or application software certificates. PublicCA will not issue TLS, time-stamp and S/MIME certificates since the 3rd generation. |
| eTSCA | CHT operates a time-stamping authority (TSA) and provides proof-of-existence for data at an instant in time. eTSCA is responsible for issuing a time-stamp certificate to the TSA. |

CHTCA’s CA certificate information and applicable CP/CPS, external audit
report and management statement are all published in the CA repository.
PublicCA has ceased issuing TLS server certificates as of December 10,
2024.

<a id="section-1-3-2"></a>
#### 1.3.2 Registration Authorities

The RA is responsible for collection and authentication of subscriber
identity and certificate-related information. The RA is comprised of one
or more RA counters authorized under the organization approved by CHTCA.
Each RA counter has an RA officer (RAO) who is responsible for the
review of certificate application, revocation, re-key, and renewal for
different certificate groups and classes.

eCA directly accepts CA certificate registration and revocation requests
and is responsible for collecting and verifying the identity and the
certificate-related information of subordinate CAs and cross-certified
CAs. There is no need to set up a RA.

The RA of the subordinate CA can be directly established and maintained
by the subordinate CA (known as internal RA), or may be established and
maintained by the customer contracted by the CHT (known as external RA).
RAs shall operate in accordance with this CPS, where internal RA may
adopt stricter security control practices than this CPS.

<a id="section-1-3-3"></a>
#### 1.3.3 Subscribers

A Subscriber refers to the subject who has applied for and obtained a
certificate issued by CHTCA. The relationship between the subscriber and
certificate subject is listed in the following Table:

| **Certificate Subject**         | **Subscriber**                    |
|---------------------------------|-----------------------------------|
| Natural person                  | himself                           |
| Organization                    | an authorized representative      |
| Equipment                       | owner of the equipment            |
| Application software            | owner of the application software |
| TSA or Time-stamping Unit (TSU) | owner of TSA                      |

Generation of subscriber key pairs shall comply with Section 6.1.1 of
this CPS. The subscriber must have the right and capability to control
the private key that corresponds to its subscriber certificate. The
Subscriber is not capable of issuing certificates to other parties.

In the ePKI, a Subordinate CA is not called the subscriber because the
Subordinate CA is capable of issuing certificates.

<a id="section-1-3-4"></a>
#### 1.3.4 Relying Parties

The relying party refers to a third party that acts in reliance of the
relationship between the certificate subject name and the public key.
The relying party must verify the validity of the certificate used based
on the corresponding CA certificate and certificate status information.

For other certificates, it may be used for the following purposes:

1)  Verify the integrity of a digitally signed electronic document.

2)  Identify the creator of a digitally signed electronic document.

3)  Establish a secure communication channel with the subscriber.

<a id="section-1-3-5"></a>
#### 1.3.5 Other Participants

Other authorities include TSA and card management center (responsible
for the production and management of tokens).

<a id="section-1-4"></a>
### 1.4 Certificate Usage

<a id="section-1-4-1"></a>
#### 1.4.1 Appropriate Certificate Uses

eCA issues four kinds of certificates: self-signed certificates,
self-issued certificates, subordinate CA certificates and
cross-certificates. The types of certificates and their scope of
application are shown as follows:

<table>
<colgroup>
<col style="width: 18%" />
<col style="width: 81%" />
</colgroup>
<thead>
<tr>
<th style="text-align: center;"><strong>Cert. Type</strong> </th>
<th style="text-align: center;"><strong>Scope of Applications</strong> </th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center;">Self-signed certificates </td>
<td style="text-align: left;"><p>A self-signed certificate is used to
establish the trust anchor of the ePKI.</p>
<p>The issuance subject of the self-signed certificate is the eCA
itself. The self-signed certificate contains the eCA public key which
can be used to verify the digital signatures on subordinate CA
certificates, cross-certificates, self-issued certificates and
certification authority revocation lists (CARLs) issued by eCA.</p></td>
</tr>
<tr>
<td style="text-align: center;">Self-issued certificates </td>
<td style="text-align: left;">A self-issued certificate is used for the
eCA re-key or as the path for certificate policy mutual trust.</td>
</tr>
<tr>
<td style="text-align: center;">Subordinate CA certificates </td>
<td style="text-align: left;"><p>A subordinate CA certificate is used
construct the trust path required for the interoperability of CAs.</p>
<p>The issuance subject of the subordinate CA certificate is subordinate
CA established under the ePKI.</p>
<p>The subordinate CA certificate contains the subordinate CA public key
which can be used to verify the digital signatures on certificates and
CRLs issued by the subordinate CA.</p></td>
</tr>
<tr>
<td style="text-align: center;">cross-certificates </td>
<td style="text-align: left;"><p>A cross-certificate is used construct
the trust path required for the interoperability of CAs under different
PKIs.</p>
<p>The issuance subject of the cross-certificate is a root CA which is
established under another PKI and cross-certifies with eCA.</p>
<p>The cross-certificate contains the cross-certified CA public key
which can be used to verify the digital signatures on certificates and
CARLs issued by that CA.</p></td>
</tr>
</tbody>
</table>

The various types of subscriber certificates, defined in the ePKI CP,
issued by the subordinate CAs are described below, along with their
respective types and applicable scopes are shown as follows:

<table>
<colgroup>
<col style="width: 18%" />
<col style="width: 81%" />
</colgroup>
<thead>
<tr>
<th style="text-align: center;"><strong>Cert. Type</strong> </th>
<th style="text-align: center;"><strong>Scope of Applications</strong> </th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center;">Level 1 subscriber certificates </td>
<td style="text-align: left;"><p>Use email notification to verify that
the applicant can control the email address. Suitable for use in network
environments in which the risk of malicious activity is considered to be
low or a higher assurance level cannot be provided. When used for
digital signatures, it can identify that the subscriber originates from
a certain email address or guarantee the integrity of the signed
document. When used for encryption, the relying party can use the
subscriber’s certificate public key to encrypt the symmetric key to
guarantee the confidentiality of email content. Not suitable for online
transactions that require identification and Non-Repudiation/
contentCommitment.</p>
For example, information encryption and signatures required for
emails. </td>
</tr>
<tr>
<td style="text-align: center;">Level 2 subscriber certificates </td>
<td style="text-align: left;"><p>Suitable for use with information which
may be tampered with, but the network environment has no malicious
tampering (data interception is possible but likelihood is not high).
Not suitable for the signing of important documents/emails (life
essential and high value transaction documents).</p>
For example, information encryption and identity authentication for
small value e-commerce transactions. </td>
</tr>
<tr>
<td style="text-align: center;">Level 3 subscriber certificates </td>
<td style="text-align: left;"><p>Suitable for use in network
environments in which there are malicious users, who may intercept or
tamper with information, and with risks greater than the environment of
level 2. A signature shall be adopted to confirm its identity, which can
be used for non-repudiation/content commitment online transactions.</p>
Suitable for e-commerce application, Internet tax filing,
e-government, email application, TLS encryption channel or identity
identifying service. </td>
</tr>
<tr>
<td style="text-align: center;">Time-stamp certificates </td>
<td style="text-align: left;"><ul>
<li>Provide evidence that an electronic document existed at or before
a particular time.</li>
<li>Proof of signature time of electronic documents.</li>
<li>Electronic document storage and proof service.</li>
<li>The recipient verifies the correctness of the time-stamp of the
electronic document.</li>
<li>Protection the evidence of digital asset generation time or
issuance time.</li>
<li>Scope of application includes (but not limited to): e-policy,
e-contract, electronic bill, business secret protection, intellectual
property protection, e-bidding, e-voting, e-documents, e-certificate
letter and code signing, etc.</li>
</ul></td>
</tr>
</tbody>
</table>

If CHTCA can confirm that the token for storing the subscriber private
key (e.g., the TSU private key is stored in a hardware cryptographic
module), in addition to include the IAL, the authenticator assurance
levels (AAL) defined in the ePKI CP can be included in the certificates.
The AAL are described as follows:

<table>
<colgroup>
<col style="width: 17%" />
<col style="width: 82%" />
</colgroup>
<thead>
<tr>
<th align="center"><span class="smallcaps">AAL</span></th>
<th align="left">Descriptions</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center" nowrap>Level 1</td>
<td align="left"><p>Providing only partial assurance as to
whether or not the token controller truly binded the Subscribers’
accounts. Its successful single-factor or multi-factor authentication
via the use of any available verification technique shall, via a secure
authentication protocol, be able to confirm that the subscriber truly
have possession of and control over that token.</p>

1) Permitted token type: can use any one of the following
types.

    - Memorable secret code, such as: password or personal identification number;
   
    - Single-factor encryption software;
    
    - Single-factor encryption equipment;
    
    - Multi-factor encryption software;

    - Multi-factor encryption equipment.

2) Requirements of the token and validator:

    - The encryption token shall use the approved encryption
technology. The software token can also try to detect the possible of
malicious attack to the terminal equipment (such as: installed with
malicious software). If it is found, the certification in question shall
be terminated.

    - The token owner and validator shall communicate with each other
via authorized and securely encrypted channel to avoid man-in-the-middle
attack.
</td></tr>

<tr>
<td align="center" nowrap>Level 2</td>
<td align="left"><p>Providing reliable assurance as to
whether or not the token controller truly binded the Subscribers’
accounts. Its authentication carried out under the secure environment of
authentication protocol via the use of two authentication factors shall
include the approved encryption technology.</p>

1) Permitted token type: The verify operation shall be performed via
multi-factor authentication or two-factor authentication.

    - If multi-factor authentication is taken, the available types of token include:
      - Multi-factor encryption software;
      - Multi-factor encryption equipment.
    
    - If the authentication mechanism is only two-factor, it shall include a memorable secret code token and any one-time token described below:</p>
      - Single-factor encryption software;
      - Single-factor encryption equipment.

2) Requirements of the token and validator:

    - Encryption token shall use the approved encryption technology.
The token for government procurement shall pass FIPS 140 level 1
certification. The software token can also try to detect the possible of
malicious attack to the terminal equipment (such as: installed with
malicious software). If it is found, the certification in question shall
be terminated. In addition, at least one type of token with replay
attacks prevention capacity, such as dynamic passwords, shall be
used.

    - The token owner and validator shall communicate with each other
via authorized and securely encrypted channel to avoid man-in-the-middle
attack.

    - If equipment such as mobile device is used in the verification
process, the equipment’s original unlocking function (such as:
fingerprint recognition or personal identification number verification)
shall not be regarded as a verification factor.
</td>
</tr>

<tr>
<td align="center" nowrap>Level 3</td>
<td align="left"><p>Providing highly reliable assurance as
to whether or not the token controller truly binded the Subscribers’
accounts. It verifies ownership of the subscriber’s key via encryption
protocol. The verification operation requires hardware password token
and token capable of blocking from hacked validator (can also
simultaneously use equipment with the aforesaid functions) and shall be
carried out under the secure environment of authentication protocol via
the use of two authentication factors, which shall include the approved
encryption technology.</p>

1) Permitted token type: can use a combination of any one of the
following tokens.

    - Multi-factor encryption equipment;
    - A combination of single-factor encryption equipment and memorable secret code.

2) Requirements of the token and validator:

    - The token owner and validator shall communicate with each other
via authorized and securely encrypted channel to avoid man-in-the-middle
attack. All encryption equipment token shall be equipped with validator
capable of anti-hacking and replay attacks prevention.

    - The token shall be cryptographic module which passed FIPS 140
level 2 (or up) or is in compliance with Global Platform Trusted
Execution Environment.

    - If equipment such as mobile device is used in the verification
process, the equipment’s original unlocking function (such as:
fingerprint recognition or personal identification number verification)
shall not be regarded as a verification factor.
</td>
</tr>
</tbody>
</table>

Below are the OIDs for each AAL defined in the ePKI CP:

| **AAL** |         **OID Name**         |       **OID Value**       |
|:-------:|:----------------------------:|:-------------------------:|
| Level 1 | id-cht-ePKI-tokenAssurance 1 | 1.3.6.1.4.1.23459.100.4.1 |
| Level 2 | id-cht-ePKI-tokenAssurance 2 | 1.3.6.1.4.1.23459.100.4.2 |
| Level 3 | id-cht-ePKI-tokenAssurance 3 | 1.3.6.1.4.1.23459.100.4.3 |

Subscribers and relying parties must carefully read and comply with this
CPS before using and trusting the certificate service provided by CHTCA,
and pay attention to the update of this CPS.

<a id="section-1-4-2"></a>
#### 1.4.2 Prohibited Certificate Uses

Certificates issued under this CPS are prohibited from being used in the
scope of:

1)  Man-in-the-middle TLS traffic interception;

2)  applications or businesses that may result in bodily harm,
    psychological distress, or cause significant harm to social order
    and public interest; and

3)  applications or businesses explicitly prohibited or excluded by the
    Electronic Signatures Act, other relevant laws, or the competent
    authorities for specific business purposes.

Subscribers are expected to comply with all requirements of all applicable browser root policies, including revocation periods of 24 hours and 5 days as specified herein.

<a id="section-1-5"></a>
### 1.5 Policy Administration

<a id="section-1-5-1"></a>
#### 1.5.1 Organization Administering the Document

Chunghwa Telecom Co., Ltd. (CHT).

<a id="section-1-5-2"></a>
#### 1.5.2 Contact Person

<a id="section-1-5-2-1"></a>
##### 1.5.2.1 CPS Related Issues

Any suggestions regarding this CPS, please contact us by the following
information.

E-mail: <caservice@cht.com.tw>

Address: 10048 CHT Certification Authority (4F), Data Communication
Building, No. 21, Sec.1, Hsinyi Rd., Taipei City, Taiwan (R.O.C.)

<a id="section-1-5-2-2"></a>
##### 1.5.2.2 Certificate Problem Report

Subscribers, relying parties, application software suppliers, and other
third parties may report private key lose, suspected private key
compromise, certificate misuse, or other types of fraud, compromise,
misuse, inappropriate conduct, or any other matter related to
certificates by sending email to <report_abuse@cht.com.tw>.

CHTCA may or may not revoke in response to this request. See Sections
4.9.3 and 4.9.5 for detail of actions performed by CHTCA for making this
decision.

<a id="section-1-5-3"></a>
#### 1.5.3 Person Determining CPS Suitability for the Policy

CHTCA shall first check whether this CPS conforms to the ePKI CP
regulations and then submit the CPS to the PMA for review and approval.
After approval, CHTCA is able to officially reference the certificate
policies of ePKI.

In addition, according to the Electronic Signatures Act, CAs can provide
the service of certificate issuance after the CPS has been approved by
the competent authority, Ministry of Digital Affairs.

CHTCA conducts regular internal/external audits to demonstrate that it
has operated with the assurance level under the ePKI CP. According to
the regulations of the root certificate program, the audits of CHTCA are
conducted annually and the latest CPS as well as the audit reports are
submitted to the root certificate programs. CHTCA also publishes the
audit seals to the CHTCA websites.

<a id="section-1-5-4"></a>
#### 1.5.4 CPS Approval Procedures

This CPS is published by CHTCA following approval by the PMA or Ministry
of Digital Affairs, the competent authority of the Electronic Signatures
Act. This CPS must be revised in response to any revision of the ePKI
CP, and the revised CPS must be submitted to the PMA and Ministry of
Digital Affairs for approval.

After the revisions of this CPS take effect, if there is any
inconsistency between the original CPS and the revised CPS, then the
revised CPS takes precedence unless stipulated otherwise.

<a id="section-1-6"></a>
### 1.6 Definitions and Acronyms

See Appendix 1 for the abbreviations and definitions and Appendix 2 for
the glossary.

<a id="section-2"></a>
## 2 Publication and Repository Responsibilities

<a id="section-2-1"></a>
### 2.1 Repositories

The CHTCA repository is responsible for the publication and storage of
certificates and certificate revocation lists (CRLs) issued by CHTCA and
this CPS. CHTCA provides availability of a repository inquiry service to
subscribers and relying parties and the repository is available
at: <https://chtca.hinet.net/repository.html>

The repository will resume normal operation within two working days if
unable to operate normally for some reason.

<a id="section-2-2"></a>
### 2.2 Publication of Certification Information

CHTCA shall take responsibility for making the following information
publicly accessible in its repository:

1)  This CPS and the ePKI CP.

2)  All CHTCA certificates, Cross-certificates, and CRLs

3)  Privacy protection policy.

4)  The latest external audit report (as specified in Section 8.6).

<a id="section-2-3"></a>
### 2.3 Time or Frequency of Publication

1)  This CPS is reviewed and updated at least once every 366 days, and a
    dated changelog is state in the “Document History” section even if
    no other changes are made to this document. New or modified version
    of this CPS is published in the repository as soon as possible upon
    receiving the approval letter from the competent authority,

2)  New or modified version of the ePKI CP complied with by CHTCA is
    published in the repository as soon as possible upon the approval of
    the PMA,

3)  CHTCA issues CRLs at least twice a day and publishes it in the
    repository, and

4)  CHTCA certificates are published in the repository within seven
    working days after accepting issuance by an upper-level CA.

<a id="section-2-4"></a>
### 2.4 Access Controls on Repositories

CHTCA implements access control where it provides read-only access to
prevent anyone from unauthorized writing operation, which would put
repository security in risk.

<a id="section-3"></a>
## 3 Identification and Authentication

<a id="section-3-1"></a>
### 3.1 Naming

<a id="section-3-1-1"></a>
#### 3.1.1 Types of Names

CHTCA certificates are issued with the following types of names:

1)  The subject distinguished name (DN) shall comply with ITU-T X.500
    standards.

2)  The subject alternative name extension for subscriber certificates
    must not be marked critical.

<a id="section-3-1-2"></a>
#### 3.1.2 Need for Names to be Meaningful

The naming of the certificate subject should comply with the law of the
country under the jurisdiction of the applicant.

The issuing CA and its RA may abridge the prefix or suffix of the
organization name, e.g., change the official name “Company Name
Incorporated” to its abbreviated version “Company Name, Inc.”, and the
abbreviation must be made on the basis that the certificate subject is
easily identifiable in the jurisdiction in which it is established or
registered. If the organization name is longer than 64 characters, the
issuing CA and its RA may abbreviate the organization name or delete the
unimportant text in the organization name.

<a id="section-3-1-3"></a>
#### 3.1.3 Anonymity or Pseudonymity of Subscribers

CHTCA may issue pseudonymous subscriber certificates if they are not
prohibited by policy and any applicable name space uniqueness
requirements are met.

<a id="section-3-1-4"></a>
#### 3.1.4 Rules for Interpreting Various Name Forms

The rules for interpreting name forms follow the definition of name
attribute type documented in ITU-T X.520.

<a id="section-3-1-5"></a>
#### 3.1.5 Uniqueness of Names

CHTCA shall use the X.520 standard to define the various naming
attributes for assembly to ensure the uniqueness of the X.500 naming
space recognized by CHTCA for name of the subscriber certificate subject
name. The CHTCA subscriber certificate subject name permits (but not
limited to) the use of the following naming attributes defined in the
X.520 standard for assembly:

- countryName (abbreviated as C)

- organizationName (abbreviated as O)

- organizationalUnitName (abbreviated as OU)

- commonName (abbreviated as CN)

- serialNumber

<a id="section-3-1-6"></a>
#### 3.1.6 Recognition, Authentication, and Role of Trademarks

The certificate subject name, including trademark or any name, business
or company name or representation protected by law, provided by
subscribers must comply with relevant regulations in our country’s
Trademark Act, Fair-Trade Act, and other relevant laws and regulations.
CHTCA does not guarantee the recognition, verification, legality and
uniqueness of the certificate subject name if it contains a trademark.
Related disputes and arbitration shall not be the obligation of CHTCA,
the subscriber shall apply to relevant competent authorities, courts or
arbitration institutions.

CHTCA may reject any application or at its own discretion revoke
certificates (refer to Section 4.9.1) that involves in a trademark
dispute.

<a id="section-3-2"></a>
### 3.2 Initial Identity Validation

<a id="section-3-2-1"></a>
#### 3.2.1 Method to Prove Possession of Private Key

CHTCA shall verify that the entity (Subordinate CA or individual)
possesses the private key, which is paired with the public key to be
contained in the certificate, with the following two methods:

1)  The subscriber self-generates the key pairs, creates the PKCS \#10
    Certificate Signing Request (CSR), and signs it with the private
    key. When applying for a certification, the CSR is submitted to the
    RA. The RA shall use the subscriber’s public key to verify the
    signature on the CSR to prove that the subscriber is in possession
    of the corresponding private key.

2)  The card management center securely generates the subscriber’s key
    pair inside the chip. During the issuance of the certificate, the RA
    delivers the subscriber’s public key to CHTCA through a secure
    channel. In this way, the subscriber does not need to prove the
    possession of its private key when applying for the certificate.

<a id="section-3-2-2"></a>
#### 3.2.2 Authentication of Organization Identity

The certification document required for organization identification and
authentication, and the authentication and verification procedures
whether need to be performed at the counter are determined based on
various assurance levels as shown in the following Table.

<table>
<colgroup>
<col style="width: 19%" />
<col style="width: 80%" />
</colgroup>
<thead>
<tr>
<th align="center"><strong>Assurance Level</strong></th>
<th align="center"><strong>Procedures for Authentication of
Organization Identity</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center" nowrap>Level 1</td>
<td align="left"><p>There is no requirement to link the
applicant to a specific real-life identity. Any attributes provided in
conjunction with the authentication process are self-asserted.</p>
<ol type="1">
<li>No identity verification required.</li>
<li>The applicant is required to demonstrate control of their email
address or domain name to which the certificate relates.</li>
<li>In-person identity proofing at counter is not required.</li></td>
</tr>
<tr>
<td align="center" nowrap>Level 2</td>
<td align="left"><p>Evidence supports the real-world
existence of the claimed identity and verifies that the applicant is
appropriately associated with this real-world identity.</p>
<ol type="1">
<li>No identity verification required.</li>
<li>In-person identity proofing at counter is not required.</li>
<li>The applicant is required to provide organization information
such as organization ID number (i.e., withholding tax ID number) and
organization name. CHTCA may additionally cross-check the information
provided by the applicant for consistency with available government or
third-party data sources.</li>
</ol></td>
</tr>
<tr>
<td align="center" nowrap>Level 3</td>
<td align="left">CHTCA allows the following methods for
authentication of organization identity:

1) In-person (physically-present) identity proofing at counter,
which can be one of the following means:

    - a. A certification document or official document issued by government agency in the jurisdiction of the applicant;
    - b. Public information obtained from a qualified government
information source (QGIS) such as the MOEA industry and business
registration database or a qualified government tax information source
(QTIS) such as the Fiscal Information Agency of MOF; or
    - c. Organizations belonging to CHT apply for the certificate with
written application.

2) Remote identity proofing, which can be one of the following means
and the detailed operating procedures are formulated in the internal
control system of each RA:
    - a. Application through an identity assurance level 3 organization certificate issued by the GPKI or ePKI;
    - b. For those organization who has complete registration procedure
with the competent authority, like 1-a or 1-b, mailing the copies of
the certification documents is acceptable;
    - c. A letter attesting that subject information is correct written by an accountant, lawyer, or notary;
    - d. A site visit by CA personnel or a third party who is acting as an agent for the CA; or
    - e. Organizations belonging to CHT apply for the certificate with e-form.
</td>
</tr>

<tr>
<td align="center" nowrap>Level 4</td>
<td align="left"><ol type="1">
<li>The identity authentication of a CA established by CHT is
reviewed by a PMA meeting convened by CHT.</li>
<li>For a CA not established by CHT, the CA shall submit an
application of subordinate CA certificate or cross-certificate, and a
PMA meeting shall conven by CHT to review the application.</li>
</ol></td>
</tr>
</tbody>
</table>

<a id="section-3-2-3"></a>
#### 3.2.3 Authentication of Individual Identity

The certification document required for individual identification and
authentication, and the authentication and verification procedures
whether need to be performed at the counter are determined based on
various assurance levels as shown in the following Table.

<table>
<colgroup>
<col style="width: 19%" />
<col style="width: 80%" />
</colgroup>
<thead>
<tr>
<th align="center"><strong>Assurance Level</strong></th>
<th align="center"><strong>Procedures for Authentication of
Individual Identity</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center" nowrap>Level 1</td>
<td align="left">There is no requirement to link the
applicant to a specific real-life identity. Any attributes provided in
conjunction with the authentication process are self-asserted.
<ol type="1">
<li>No identity verification required.</li>
<li>No identity verification other than control of the email address
listed in the certificate.</li>
<li>In-person identity proofing at counter is not required.</li>
</ol></td>
</tr>

<tr>
<td align="center" nowrap>Level 2</td>
<td align="left">Evidence supports the real-world
existence of the claimed identity and verifies that the applicant is
appropriately associated with this real-world identity.
<ol type="1">
<li>No identity verification required.</li>
<li>The applicant is required to provide a legible copy of a valid
government issued national identity document or photo ID (such as
National ID, passport or health insurance card), and CHTCA will verify
the information through reliable communications.</li>
<li>In-person identity proofing at counter is not required</li>
</ol></td>
</tr>

<tr>
<td align="center" nowrap>Level 3</td>
<td align="left">CHTCA allows the following methods for
authentication of individual identity:

1) In-person (physically-present) identity proofing at counter,
which can be one of the following means:

    The applicant must in-person proofing his / her identity at the CA or
RA counter, at least present a national government-issued photo ID (such
as National ID card, passport or health insurance card) to the RAO to
examine whether they are authentic and unexpired. If the applicant is
unable to present the application in person at the counter, the
applicant may submit a letter of appointment to appoint an agent to
submit the application. When the applicant is not the citizen of Taiwan,
the verification should be conducted according to the relevant
regulations, where the detailed operating procedures are formulated in
the internal control system of each RA.</p>

    If an applicant (such as minor under 18 years old) is unable to
submit the above photo ID, government-issued credentials (such as
household registration) sufficient to prove the identity of the
applicant and one adult with legal capacity to guarantee the applicant’s
identity in writing may be used in its place. The identity of the adult
providing the guarantee must pass through the above authentication. </p>

2) Remote identity proofing, which can be one of the following means
and the detailed operating procedures are formulated in the internal
control system of each RA:

    - Application through a Citizen Digital Certificate IC Card;
    - Delegate the duty of individual’s identity examination to a financial institution who has business with the applicant;
    - A declaration of applicant’s identity that is witnessed and
signed by a notary, lawyer, accountant, or any entity certified by a
State or National Government as authorized to confirm
identities;
    - Other identity proofing mechanisms for remote account opening
recognized by the competent authority of the relying party;
    - Application through an identity assurance level 3 individual certificate issued by ePKI;
    - A site visit by CA personnel or a third party who is acting as an agent for the CA; or
    - Application through a telecommunications authentication where the related information is obtained from a telecommunications service provider under the applicant’s consent. This method, where Subscriber
Identity Module (SIM) authentication is used, provides the witness that the applicant and the number hirer have the same National ID number and the applicant had made identity proofing at the counter of Regular Chain
stores at the time of dealing telecommunications business.
</td>
</tr>
</tbody>
</table>

<a id="section-3-2-4"></a>
#### 3.2.4 Non-verified Subscriber Information

The common name of an assurance level 1 individual certificate is not
verified as the legal name of the subscriber. The OU fields of other
certificates are generally not validated unless required by industry
standards.

<a id="section-3-2-5"></a>
#### 3.2.5 Validation of Authority

When a certificate lifecycle activity such as a certificate application
or revocation request is submitted by an individual (an authorized
representative) related to the certificate subject, CHTCA or its RA
shall perform a validation of authority to verify that the individual
can represent the certificate subject.

<a id="section-3-2-6"></a>
#### 3.2.6 Criteria for Interoperation

CHTCA allows another root CA to interoperate with, see ePKI CP for
details.

<a id="section-3-2-7"></a>
#### 3.2.7 Data Source Accuracy

Prior to using any data source as a Reliable Data Source, CHTCA SHALL
evaluate the source for its reliability, accuracy, and resistance to
alteration or falsification. CHTCA SHOULD consider the following during
its evaluation:

1)  The age of the information provided,

2)  The frequency of updates to the information source,

3)  The data provider and purpose of the data collection,

4)  The public accessibility of the data availability, and

5)  The relative difficulty in falsifying or altering the data.

Databases maintained by CHTCA, its owner, or its affiliated companies do
not qualify as a Reliable Data Source, if the primary purpose of the
database is to collect information for the purpose of fulfilling the
validation requirements in Section 3.2 of the Baseline Requirements.

<a id="section-3-3"></a>
### 3.3 Identification and Authentication for Re-key Requests

<a id="section-3-3-1"></a>
#### 3.3.1 Identification and Authentication for Routine Re-key

If the subscriber or CA’s private key needs to be renewed upon expiry of
the certificate period, certificate rekey work may be performed, and the
subscriber may re-apply for certification. The RA may validate the
subscriber’s identity by using the subscriber’s public key to verify the
CSR or conduct an initial identity validation in accordance with Section
3.2. CHTCA shall re-validate the subscriber’s identity through an
initial registration process in accordance with Section 3.2 at least
once every nine years from the time of initial registration.

<a id="section-3-3-2"></a>
#### 3.3.2 Identification and Authentication for Re-key after Revocation

If the subscriber or CA’s private key needs to be re-keyed due to
certificate revocation, the subscriber or CA shall re-apply for the
certificate with CHTCA. The RA shall conduct an initial identity
validation in accordance with Section 3.2.

<a id="section-3-4"></a>
### 3.4 Identification and Authentication for Revocation Request

CHTCA or RA must perform authentication of the certificate revocation
request to verify that the applicant has the right to submit the
certificate revocation. The authentication procedure for certificate
revocation request is the same as the regulations in Section 3.2.

<a id="section-4"></a>
## 4 Certificate Life-cycle Operational Requirements

<a id="section-4-1"></a>
### 4.1 Certificate Application

<a id="section-4-1-1"></a>
#### 4.1.1 Who Can Submit a Certificate Application

Either the applicant or an individual authorized to request certificates
on behalf of the applicant may submit certificate applications.

<a id="section-4-1-2"></a>
#### 4.1.2 Enrollment Process and Responsibilities

The certificate application procedures are as follows:

1)  Use the appropriate secure platform to generate an appropriate key
    pair.

2)  Generate a PKCS#10 CSR using an appropriately tool.

3)  Fill out the information on the certificate application and agrees
    to a subscriber agreements or other applicable terms and conditions.

4)  Submit the certificate application request (including the CSR, the
    legal name of the organization or the website FQDN based on the type
    of the certificate applied for, etc.) and provide relevant
    identification documents to the RA, where the application
    information can be in electronic form.

The RA are responsible for ensuring the accuracy of the application
request and performing the identification and authentication of the
applicant before delivery the request to the issuing CA for issuance.

<a id="section-4-2"></a>
### 4.2 Certificate Application Processing

<a id="section-4-2-1"></a>
#### 4.2.1 Performing Identification and Authentication Functions

Upon receipt of the certificate request, CHTCA and RAs shall verify the
application information in accordance with Section 3.2. The certificate
applicant shall submit correct and complete factual information. The
information required for the certificate application shall contain
required and optional information. The information submitted by the
certificate applicant and contact records kept by CHTCA and RA during
the application process shall be properly kept in a secure, auditable
manner in accordance with the ePKI CP and this CPS.

<a id="section-4-2-2"></a>
#### 4.2.2 Approval or Rejection of Certificate Applications

The verification of the authorization domain name and the basic domain
name must comply with the regulations as specified in Section 3.2.5. If
all identity authentication work follows relevant regulations and best
practices can be successfully implemented, CHTCA may approve the
certificate application.

If the various identity authentication works cannot be successfully
completed, CHTCA may reject the certificate application. In addition to
this reason, CHTCA may refuse to issue certificates for other reasons.
CHTCA and its RA may also reject certificate application from applicants
who have previously been rejected or have previously violated the
subscriber agreements.

A PMA meeting is convened when any CA submits a Subordinate CA
certificate or cross-certificate application. The PMA will review the
related documents provided by the CAs to evaluate the appropriateness
for becoming a subordinate CA or Cross-certified CA of eCA. The PMA may
decide that the application enters the next stage, supplemental
information is required, or the application is rejected.

<a id="section-4-2-3"></a>
#### 4.2.3 Time to Process Certificate Applications

CHTCA shall complete the certificate application within a reasonable
period. Provided that the information submitted by the applicant is
complete and complies with the ePKI CP, this CPS and other checking
requirements, the RAO shall quickly complete the certificate application
review. The time needed by RA to process certificate applications and
CHTCA to issue the certificates depends on the certificate group and
type. These times may be disclosed in the subscriber agreements,
contract or on the RA’s websites.

Upon receiving the certificate application, the RAO will complete the
review process, and the applicant will be asked to accept the
certificate. The times when the issuing CA completes the issuance of the
certificate are given as follows according to difference certificate
types:

<table>
<colgroup>
<col style="width: 49%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr>
<th style="text-align: center;"><strong>Type of
Certificates</strong></th>
<th style="text-align: center;"><strong>Time required for processing and
issuance the Certificate</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">Time-stamp Certificates </td>
<td align="center">5-10 working days </td>
</tr>
<tr>
<td align="center">AATL Certificates </td>
<td align="center">2 working days </td>
</tr>
</tbody>
</table>

Issuance time frames are greatly dependent on when the applicant
provides the details and documentation necessary to complete validation
or complates the certificate acceptance.

<a id="section-4-3"></a>
### 4.3 Certificate Issuance

<a id="section-4-3-1"></a>
#### 4.3.1 CA Actions during Certificate Issuance

eCA cannot automatically issue certificates and shall follow the
regulations in Section 5.2.2.

Upon CHTCA receive the certificate application, the relevant review
procedures are enforced in accordance with Chapter 3 of this CPS to
serve as a basis for determining whether approve the certificate
issuance.

Certificate issuance steps are follows:

1)  The RA submits the certificate application passed the review
    procedures to the issuing CA.

2)  When the issuing CA receives the certificate application submitted
    by the RA, the authorization status of the RA is first checked to
    confirm its authorized assurance level and scope, and then the
    certificate is issued according to the information of the
    certificate application submitted by the RA.

3)  If the authorized assurance level and scope of the RA does not
    comply with the certificate application, the issuing CA will
    response the error message to the RA and reject the request. If
    there are any questions, the RA may directly contact the issuing CA
    to understand where the problem is.

4)  In order to ensure the security, integrity and non-repudiability of
    the data transmitted between the issuing CA and its RAs, the data of
    the certificate application is signed with a digital signature and
    transmitted through the network encrypted by TLS protocol.

<a id="section-4-3-2"></a>
#### 4.3.2 Notification to Subscriber by the CA of Issuance of Certificate

CHTCA shall notify the subscriber about the certificate issuance during
the enrollment process by email or any other equivalent method. The
email may contain the certificate itself or a link to download depending
upon the workflow of the certificate requested.

<a id="section-4-4"></a>
### 4.4 Certificate Acceptance

<a id="section-4-4-1"></a>
#### 4.4.1 Conduct Constituting Certificate Acceptance

Certificates are considered accepted if not revoked by the subscriber
within 30 days of issuance. Acceptance of the certificate is deemed as
the certificate applicant’s consent to comply with the rights and
obligations in this CPS or related contracts.

<a id="section-4-4-2"></a>
#### 4.4.2 Publication of the Certificate by the CA

CA Certificates are published in the CHTCA repository. End-entity
certificates are published by delivering them to the subscriber.

<a id="section-4-4-3"></a>
#### 4.4.3 Notification of Certificate Issuance by the CA to Other Entities

RAs, partners, and other entities involved in the enrollment process may
be informed of issuance.

<a id="section-4-5"></a>
### 4.5 Key Pair and Certificate Usage

<a id="section-4-5-1"></a>
#### 4.5.1 Subscriber Private Key and Certificate Usage

Key pairs of subscribers shall be generated in compliance with Section
6.1.1 of this CPS. Subscribers must be able to control the private keys,
which must not be used to issue certificates.

Subscribers shall protect their private keys from unauthorized use or
disclosure and shall use their private keys only for the correct key
usage (i.e., the policy for key usage specified in the extension of the
certificates). Subscribers shall use their certificates in accordance
with the ePKI CP, this CPS, and the Subscriber Agreement.

<a id="section-4-5-2"></a>
#### 4.5.2 Relying Party Public Key and Certificate Usage

When relying parties use a certificate, they shall confirm its
certificate usage and use it in accordance with this CPS. Relying
parties shall use a tool or a method that is appropriate for the
intended certificate usage and compliant with applicable international
standards, such as ITU-T X.509 and relevant IETF RFCs.

Prior to a certificate’s use, the tool or method selected by relying
parties must verify each certificate in the certificate chain, including
the accuracy of the content of specific fields, the integrity of the
signature, and the validity of the certificate status, where the
certificate status may be obtained from a CRL or an Online Certificate
Status Protocol (OCSP) service.

In addition, relying parties shall check the certificate policies
extension of the issuing CA certificate and the subscriber certificate
to confirm the assurance level.

<a id="section-4-6"></a>
### 4.6 Certificate Renewal

CHTCA does not allow renewal of CAs and time-stamp certificates, where
which key pair generation and certificate request submission shall be
conducted in the same manner as the initial registration. Only the other
subscriber certificates can be renewed.

<a id="section-4-6-1"></a>
#### 4.6.1 Circumstances for Certificate Renewal

Unrevoked certificates which are about to expire may be renewed under
the following circumstances:

1)  The public key listed on the certificate has not reached the
    usage period stipulated in Section 6.3.2.2.

2)  The subscriber and its attribute information remain consistent.

3)  The private key corresponding to the public key listed on the
    certificate is still valid and has not been lost or compromised.

<a id="section-4-6-2"></a>
#### 4.6.2 Who May Request Renewal

The subject of the certificate or an authorized representative whose
certificates that are about to expired.

<a id="section-4-6-3"></a>
#### 4.6.3 Processing Certificate Renewal Requests

The private key is used to sign a signature to the CSR when the
subscriber makes a certificate renewal request, and the certificate
application file is submitted to the RA. The RA uses the subscriber’s
public key to verify the digital signature on the certificate
application file to authenticate the subscriber’s identity.

<a id="section-4-6-4"></a>
#### 4.6.4 Notification of New Certificate Issuance to Subscriber

According to Section 4.3.2, CHTCA shall issue a notification to the
subscriber whose certificate has been renewed, to download the renewed
certificate. If CHTCA denies the renewal, the reason of denial shall be
communicated to the subscriber.

<a id="section-4-6-5"></a>
#### 4.6.5 Conduct Constituting Acceptance of a Renewal Certificate

As stated in Section 4.4.1.

<a id="section-4-6-6"></a>
#### 4.6.6 Publication of the Renewal Certificate by the CA

As stated in Section 4.4.2.

<a id="section-4-6-7"></a>
#### 4.6.7 Notification of Certificate Issuance by the CA to Other Entities

No stipulation.

<a id="section-4-7"></a>
### 4.7 Certificate Re-Key

<a id="section-4-7-1"></a>
#### 4.7.1 Circumstance for Certificate Re-key

Under the following circumstances, the Subordinate CA/Cross-certified
CA will renew the key and ask eCA to issue a new subordinate
CA/Cross-certified CA certificate:

1)  The lifecycle of currently used keys has ended.

2)  Security issues exist for currently used keys (such as suspected or
    confirmed key compromise).

Subscribers whose certificates have not expired may request a re-key,
and CHTCA shall identify and authenticate them in accordance with
Section 3.3.1. After the key pair is re-keyed, CHTCA may revoke the old
certificate and does not allow the renewal, modification, or re-key of
the old certificate.

<a id="section-4-7-2"></a>
#### 4.7.2 Who May Request Certification of a New Public Key

The subject of the certificate or an authorized representative.

<a id="section-4-7-3"></a>
#### 4.7.3 Processing Certificate Re-keying Requests

For subscriber certificate re-keying, CHTCA shall validate the request
in accordance with Sections 3.1, 3.2, 3.3, 4.1 and 4.2 and may
re-validate the subscriber subject with any previously validated data
when needed.

<a id="section-4-7-4"></a>
#### 4.7.4 Notification of New Certificate Issuance to Subscriber

As stated in Section 4.3.2.

<a id="section-4-7-5"></a>
#### 4.7.5 Conduct Constituting Acceptance of a Re-keyed Certificate

As stated in Section 4.4.1.

<a id="section-4-7-6"></a>
#### 4.7.6 Publication of the Re-keyed Certificate by the CA

As stated in Section 4.4.2.

<a id="section-4-7-7"></a>
#### 4.7.7 Notification of Certificate Issuance by the CA to Other Entities

No stipulation.

<a id="section-4-8"></a>
### 4.8 Certificate Modification

<a id="section-4-8-1"></a>
#### 4.8.1 Circumstance for Certificate Modification

CHTCA does not allow modification of time-stamp certificates.

Certificate modification means creating a new certificate for the same
subject, where authenticated information that slightly differs from the
old certificate (e.g., changes to email address or other relatively
attribute information). The new certificate has a new certificate serial
number but with the same subject public key and ‘NotAfter’ date. After
the certificate is modified, the old certificate shall be revoked.

<a id="section-4-8-2"></a>
#### 4.8.2 Who May Request Certificate Modification

The subject of the certificate or an authorized representative.

<a id="section-4-8-3"></a>
#### 4.8.3 Processing Certificate Modification Requests

1)  The application procedure for certificate modification is as Section
    4.2.

2)  If there is any change to the important identity information such as
    the organization name, individual name or national ID number, the
    original certificate must be revoked. The subscriber must submit a
    new certificate application with the modified organization name,
    individual name, or national ID number to obtain a new certificate.

<a id="section-4-8-4"></a>
#### 4.8.4 Notification of New Certificate Issuance to Subscriber

As stated in Section 4.3.2.

<a id="section-4-8-5"></a>
#### 4.8.5 Conduct Constituting Acceptance of Modified Certificate

As stated in Section 4.4.1.

<a id="section-4-8-6"></a>
#### 4.8.6 Publication of the Modified Certificate by the CA

As stated in Section 4.4.2.

<a id="section-4-8-7"></a>
#### 4.8.7 Notification of Certificate Issuance by the CA to Other Entities

No stipulation.

<a id="section-4-9"></a>
### 4.9 Certificate Revocation and Suspension

This section mainly describes under what circumstances a certificate may
(or must) be suspended or revoked and explains the procedures.

<a id="section-4-9-1"></a>
#### 4.9.1 Circumstances for Revocation

<a id="section-4-9-1-1"></a>
##### 4.9.1.1 Circumstances for Revoking a Subscriber Certificate

CHTCA shall revoke a certificate within 24 hours if one or more of the
following occurs:

1)  The subscriber requests in writing to the CA that they wish to
    revoke the certificate;

2)  The subscriber notifies CHTCA that the original certificate request
    was not authorized and does not retroactively grant authorization;

3)  CHTCA obtains evidence that the subscriber’s private key
    corresponding to the public key in the certificate suffered a key
    compromise;

4)  CHTCA is made aware of a demonstrated or proven method that can
    easily compute the subscriber’s private key based on the public key
    in the certificate (such as a Debian weak key, see
    https://wiki.debian.org/SSLkeys); or

5)  CHTCA obtains evidence that the validation of domain authorization
    or control for any FQDN or IP address in the certificate should not
    be relied upon.

CHTCA should revoke a certificate within 24 hours and must revoke a
certificate within 5 days if one or more of the following occurs:

1)  The certificate no longer complies with the requirements of Sections
    6.1.5 and 6.1.6;

2)  CHTCA obtains evidence that the certificate was misused;

3)  CHTCA is made aware that a subscriber has violated one or more of
    its material obligations under the Subscriber Agreement or Terms of
    Use;

4)  CHTCA is made aware of any circumstance indicating that use of a
    FQDN or email address in the certificate is no longer legally
    permitted (e.g., a court or arbitrator has revoked a Domain Name
    Registrant’s right to use the Domain Name, a relevant licensing or
    services agreement between the Domain Name Registrant and the
    Applicant has terminated, or the Domain Name Registrant has failed
    to renew the Domain Name);

5)  CHTCA is made aware of a material change in the information
    contained in the certificate;

6)  CHTCA is made aware that the certificate was not issued in
    accordance with these requirements or the ePKI CP or this CPS;

7)  CHTCA determines or is made aware that any of the information
    appearing in the certificate is inaccurate;

8)  CHTCA’s right to issue certificates under these requirements expires
    or is revoked or terminated, unless CHTCA has made arrangements to
    continue maintaining the CRL/OCSP Repository;

9)  Revocation is required by the ePKI CP and/or this CPS; or

10) CHTCA is made aware of a demonstrated or proven method that exposes
    the subscriber’s private key to compromise or if there is clear
    evidence that the specific method used to generate the private key
    was flawed.

<a id="section-4-9-1-2"></a>
##### 4.9.1.2 Circumstances for Revoking a Subordinate CA Certificate

eCA shall revoke a Subordinate CA certificate within seven (7) days if
one or more of the following occurs:

1)  The Subordinate CA requests revocation in writing to eCA;

2)  The Subordinate CA notifies eCA that the original certificate
    request was not authorized and does not retroactively grant
    authorization;

3)  eCA obtains evidence that the Subordinate CA’s private key
    corresponding to the public key in the certificate suffered a key
    compromise or no longer complies with the requirements of Sections
    6.1.5 and 6.1.6;

4)  eCA obtains evidence that the certificate was misused;

5)  eCA is made aware that the certificate was not issued in accordance
    with or that Subordinate CA has not complied with this document or
    the applicable CP/CPS;

6)  eCA determines that any of the information appearing in the
    certificate is inaccurate or misleading;

7)  eCA ceases operations for any reason and has not made arrangements
    for another CA to provide revocation support for the certificate;

8)  eCA’s right to issue certificates under these Requirements expires
    or is revoked or terminated, unless eCA has made arrangements to
    continue maintaining the CRL/OCSP Repository; or

9)  Revocation is required by the ePKI CP and/or this CPS.

The issuing CA may at its own discretion revoke certificates, including
subscriber certificates, Subordinate CA certificates or
cross-certificates, under the aforementioned circumstances.

<a id="section-4-9-2"></a>
#### 4.9.2 Who Can Request Revocation

Subscribers or legally authorized third party (such as judicial or
prosecution authorities, the subject of the certificate or an authorized
representative, and legal heirs of natural person) can request
revocation.

In addition, a subscriber, relying party, application software suppliers
or other third party may submit certificate problem report to advise
CHTCA a reasonable reason to revoke the certificate. CHTCA shall take
actions in accordance with Section 4.9.5 and confirm the validity of the
certificate revocation request upon receiving the certificate problem
report.

<a id="section-4-9-3"></a>
#### 4.9.3 Procedure for Revocation Request

1)  The Applicant shall submit the certificate revocation request in
    accordance with the operation procedures established by the RA.
    After the RA receives the certificate revocation request, the
    relevant review procedures are implemented and records of all
    certificate revocation requests are kept including the Applicant’s
    name and contact information, reason for revocation, and time and
    date of revocation to serve a basis for subsequent accountability;

2)  After the RA completes the review work, the certificate revocation
    request is sent to CHTCA;

3)  When CHTCA receives the certificate revocation request sent by the
    RA, CHTCA first checks the authorization status of the relevant RA
    to verify that its authorized assurance level and scope. Afterward,
    the certificate is revoked based on the certificate revocation
    request;

4)  If the above checking does not comply with the revocation request,
    CHTCA will response the error message to the RA and reject the
    request. If there are any questions, the RA may directly contact
    CHTCA to understand where the problem is;

5)  In order to ensure the security, integrity and non-repudiability of
    the data transmitted between CHTCA and its RA, the data of the
    certificate application is encrypted with a digital signature and
    transmitted through the network by TLS protocol;

6)  CHTCA uses the same CA private key issuing the certificate to
    publish the revoked certificate serial number and the reason for
    revocation to the CRL by the digital signature; and

7)  CHTCA receives certificate problem reports and provides 24x7
    availability of certificate problem response mechanism, as specified
    in Section 4.9.3.1.

<a id="section-4-9-3-1"></a>
##### 4.9.3.1 Mechanism for Responding the Certificate Problems

Under “the Announcement of CPS” at the repository, CHTCA provides the
guidelines for certificate problem reports. Subscribers, relying
parties, application software suppliers, and other third parties may
submit certificate problem reports through the information specified in
Section 1.5.2.2 under the circumstances of the private keys are cracked,
the certificates are mis-issued, or the certificates are forged,
cracked, abused, or used inappropriately.

<a id="section-4-9-4"></a>
#### 4.9.4 Revocation Request Grace Period

The certificate revocation request grace period refers to the time to
submit a revocation request when the subscriber has confirmed the
certificate revocation circumstances. When the subscriber’s private key
is lost or suspect or known to be compromised, the subscriber shall
promptly submit a revocation request to the RA. The revocation request
grace period is two working days. CHTCA may extend the revocation grace
period when deemed necessary.

If any of the circumstances described in Section 4.9.1 occurs, CAs or
RAs shall submit the revocation request within 10 working days.

<a id="section-4-9-5"></a>
#### 4.9.5 Time within Which CA Must Process the Revocation Request

Within 24 hours after receiving a Certificate Problem Report, CHTCA
shall investigate the facts and circumstances related to a Certificate
Problem Report and provide a preliminary report on its findings to both
the Subscriber and the entity who filed the Certificate Problem Report.

After reviewing the facts and circumstances, CHTCA shall work with the
Subscriber and any entity reporting the Certificate Problem Report or
other revocation-related notice to establish whether the certificate
will be revoked, and if so, the period from receipt of the Certificate
Problem Report or revocation-related notice to published revocation must
not exceed the time frame set forth in Section 4.9.1. The date selected
by CHTCA shall consider the following criteria:

1)  The nature of the alleged problem (scope, context, severity,
    magnitude, risk of harm);

2)  The consequences of revocation (direct and collateral impacts to
    Subscribers and Relying Parties);

3)  The number of certificate problem reports received about a
    particular certificate or subscriber;

4)  The entity making the complaint; and

5)  Relevant legislation.

<a id="section-4-9-6"></a>
#### 4.9.6 Revocation Checking Requirement for Relying Parties

Prior to relying on a certificate, relying parties must verify the
accuracy and validity of each certificate in the certificate chain,
including checking for the certificate validity, digital signature,
issuer/subject name chaining, certificate policies, key usage, and
certifciate status, where the certificate status may be checked through
a CRL or an OCSP response.

Relying parties shall also verify the digital signature and validity of
the CRL or OCSP response prior to use.

<a id="section-4-9-7"></a>
#### 4.9.7 CRL Issuance Frequency

The CRL issuance frequency of CHTCA is at least twice per day. Issued
CRL are valid for no more than 36 hours. Before the CRL expires, CHTCA
may issue a new CRL. The new CRL validity period may overlap the
validity period of the old CRL. Even though the old CRL has not yet
expired, relying parties still may obtain the new CRL from the CHTCA
repository to receive the updated certificate revocation information.

<a id="section-4-9-8"></a>
#### 4.9.8 Maximum Latency for CRLs

Except for eCA has pre-signed of CRLs, after a CRL is produced by other
CAs, it will be released immediately.

<a id="section-4-9-9"></a>
#### 4.9.9 On-line Revocation/Status Checking Availability

CHTCA provides certificate revocation and status checking services
through CRLs and web-based mechanisms for certificate search and
download. OCSP services may also be offered based on the service
offerings of the issuing CAs.

If the issuing CA provides an OCSP service, the CA shall use an OCSP
responder to provide OCSP responses complying with RFC 6960 and/or RFC
5019, where the OCSP responses are signed by the OCSP responder using a
2048-bit or greater RSA key (that modulus size in bits is divisible by
8) and a hash algorithm at least as strong as SHA-256. In addition, the
OCSP responder also provides OCSP responder certificates, which are
issued by CHTCA and contain the extension of type id-pkix-ocsp-nocheck,
as defined by RFC 6960.

<a id="section-4-9-10"></a>
#### 4.9.10 On-line Revocation Checking Requirements

Relying parties must confirm the validity of a certificate in accordance
with Section 4.9.6 before using it.

If CHTCA provides an OCSP service, an OCSP responder operated under the
service shall support the HTTP-based POST and GET methods, as described
in RFC 6960 and/or RFC 5019. The certificate status information provided
by the service shall meet the following requirements:

1)  For status of subscriber certificates: an authoritative OCSP
    response MUST be available (i.e. the responder MUST NOT respond with
    the “unknown” status) starting no more than 15 minutes after the
    certificate is first published or otherwise made available. CHTCA
    provides an updated OCSP response prior to one-half of the validity
    period before the nextUpdate, and the validity interval of the OCSP
    response is greater than or equal to 8 hours and less than 16 hours.

2)  For status of self-issued certificates, subordinate CA certificates,
    and cross-certificates: CHTCA updates the information at least every
    twelve months and within 24 hours after any of these certificates is
    revoked.

A certificate serial number within an OCSP request is either:

1)  “assigned” if a certificate with that serial number has been issued
    by CHTCA; or

2)  “unassigned” if neither of the previous conditions is met.

If the OCSP responder receives a request for the status of a
    certificate serial number that is “unassigned”, then the responder
    should not respond with a “good” status.

<a id="section-4-9-11"></a>
#### 4.9.11 Other Forms of Revocation Advertisements Available

No Stipulation.

<a id="section-4-9-12"></a>
#### 4.9.12 Special Requirements Related to Key Compromise

In case of a compromise of the subscriber’s private key, the subscriber
must immediately notify CHTCA of the event. CHTCA will revoke the
concerned certificate (choose the reason for the revocation as ‘key
compromised’) according to the procedures set forth in Sections 4.9.1,
4.9.2 and 4.9.3 of this CPS, and publish a CRL to inform relying parties
that the certificate can no longer be trusted.

The acceptable methods used by third parties as proof of key compromise
are as follows:

1)  Confirming the third party’s possession of the private key by
    signing a challenge provided by CHTCA using the compromised private
    key; or

2)  Submitting the private key itself.

<a id="section-4-9-13"></a>
#### 4.9.13 Circumstances for Suspension

CHTCA does not allow suspension of time-stamp certificates (i.e.,
Sections 4.9.13 to 4.9.17 are not applicable).

In addition, CHTCA may suspend the certificate under the following
circumstances without advance permission from the subscriber:

1)  The subscriber is ordered to suspend operations.

2)  Notification in accordance with subscriber registered authority or
    the industry competent authority.

3)  Notification in accordance with judicial, supervisory or law
    enforcement agencies.

<a id="section-4-9-14"></a>
#### 4.9.14 Who Can Request Suspension

The following two groups may apply for certificate suspension:

1)  The subscriber whose certificate is to be suspended.

2)  The subscriber registered authority or industry competent authority.

<a id="section-4-9-15"></a>
#### 4.9.15 Procedure for Suspension Request

Subscribers submit the request. After the RA examines the application
for accuracy and errors, a digital signature is affixed, and the
information is transmitted to CHTCA. CHTCA then immediately suspends the
certificate or may refuse the certificate suspension request if the
review fail or for other reasons.

<a id="section-4-9-16"></a>
#### 4.9.16 Limits on Suspension Period

After the subscriber submits the certificate suspension request, the RA
shall promptly complete the review procedure within one working day.
After passing review, CHTCA shall complete the certificate suspension
within one working day.

When making a certificate suspension request, the subscriber does not
need to state the suspension period required. The longest certificate
suspension period set by CHTCA is the period from the request approval
time to the expiry date of that certificate.

If the subscriber cancels the certificate suspension during the
suspension period, the status of the certificate would become ‘valid’.

<a id="section-4-9-17"></a>
#### 4.9.17 Procedure for Certificate Resumption

The subscriber submits the request. After the RA examines the
application for accuracy and errors and the period of the suspended
certificate has not expired, a digital signature is affixed, and the
information is transmitted to CHTCA. CHTCA then immediately resumes use
of the certificate or may refuse the certificate resume request if the
review fail or for other reasons.

<a id="section-4-10"></a>
### 4.10 Certificate Status Services

<a id="section-4-10-1"></a>
#### 4.10.1 Operational Characteristics

CHTCA provides CRLs and may offer OCSP services based on the issuing
CA’s service offerings. Revocation entries on a CRL or OCSP response
must not be removed until after the expiry date of the revoked
certificate. If a revocation entry contains the information of a
suspended certificate, the entry can only be removed after the
certificate has been resumed or expired.

<a id="section-4-10-2"></a>
#### 4.10.2 Service Availability

CHTCA operates and maintains its CRL and optional OCSP capability with
resources sufficient to provide a response time of ten seconds or less
under normal operating conditions.

CHTCA maintains an online 24x7 repository that application software can
use to automatically check the current status of all unexpired
certificates issued by CHTCA.

CHTCA maintains a continuous 24x7 ability to respond internally to a
high-priority certificate problem report, and where appropriate, forward
such a complaint to law enforcement authorities, and/or revoke a
certificate that is the subject of such a complaint.

<a id="section-4-10-3"></a>
#### 4.10.3 Optional Features

No stipulation.

<a id="section-4-11"></a>
### 4.11 End of Subscription

End of subscription signifies that subscriber stop using CHTCA’s
services. CHTCA allows subscribers to end their subscription to
certificate services by having their certificate revoked or by allowing
the certificate or applicable Subscriber Agreement to expire without
renewal.

<a id="section-4-12"></a>
### 4.12 Key Escrow and Recovery

<a id="section-4-12-1"></a>
#### 4.12.1 Key Escrow and Recovery Policy and Practices

CHTCA’s private signing keys shall not be escrowed, but subscriber’s
private signing keys may be escrowed.

<a id="section-4-12-2"></a>
#### 4.12.2 Session Key Encapsulation and Recovery Policy and Practices

CHTCA does not currently support session key encapsulation and recovery.

<a id="section-5"></a>
## 5 Facility, Management, and Operation Controls

<a id="section-5-1"></a>
### 5.1 Physical Controls

<a id="section-5-1-1"></a>
#### 5.1.1 Site Location and Construction

The CHTCA facility is located in the Chunghwa Telecom Information
Technology Group. The construction of the facility housing is consistent
with facilities used to house high value, sensitive information.
Combined with other physical security mechanisms including access
control, security, intrusion detection and video monitoring, it provides
robust protection against unauthorized access to related CHTCA
equipment.

<a id="section-5-1-2"></a>
#### 5.1.2 Physical Access

CHTCA has established suitable measures to control connections to the
hardware, software and hardware security module that serves to CHTCA.

The CHTCA facility has a total of four levels of security control. On
the first and second levels, there are year-round entrance and building
security controls in place. On the third level, access is controlled to
this floor using a card access control system. On the fourth level, a
fingerprint recognition control system is used to control access for
facility personnel. The fingerprint scanner uses 3D sampling technology
which is capable of detecting whether the fingerprint is from a live
object by fingerprint depth and color.

The access control system is able to protect the facilities against
unauthorized access. There is also a monitoring system in place to
control cabinet access which prevents unauthorized access to any
hardware, software or hardware security module.

Portable storage devices that are brought into the facility housing are
checked for computer viruses or other types of software that could
damage the CHTCA system.

Non-CHTCA personnel entering the facility are required to sign the
entry/exit log and must be accompanied throughout by CHTCA personnel.

The following checks and records need to be made when CHTCA personnel
leave the facility to prevent unauthorized personnel from entering the
facility:

1)  Check if system equipment is operating normally.

2)  Check if the computer racks are locked.

3)  Check if the access control system is operating normally.

<a id="section-5-1-3"></a>
#### 5.1.3 Power and Air Conditioning

In addition to municipal power, the power system at the CHTCA facility
is equipped with a generator (with enough fuel for six days of
continuous operation) and an uninterrupted power system (UPS). The
system is capable of automatically switching between municipal power and
generator power. At least six hours of power can be supplied for
repository backup work.

The CHTCA facility has a constant temperature and humidity system to
provide an optimal operation environment for the facility.

<a id="section-5-1-4"></a>
#### 5.1.4 Water Exposures

The CHTCA facility is located at the third or higher floor of a raised
foundation building. This building has water gate and water pump
protection and no history of major damage caused by flooding.

<a id="section-5-1-5"></a>
#### 5.1.5 Fire Prevention and Protection

The CHTCA facility has an automatic fire detection, alarm and protection
system with self-activating extinguishing equipment. Switches are
installed at every major entrance / exit of the facility to allow manual
activation by personnel on-site during emergencies.

<a id="section-5-1-6"></a>
#### 5.1.6 Media Storage

Audit records, archives and backups are kept in storage media at the
facility described in Section 5.1.1. In addition, one copy shall be kept
at an off-site location.

<a id="section-5-1-7"></a>
#### 5.1.7 Waste Disposal

When the documents of CHTCA detailed in Section 9.3.1 are no longer in
use, it shall be shredded by the paper shredder. Any storage media that
CHTCA used shall be formatted to erase the information stored on it
before scrapping, and discs shall be physically destroyed.

<a id="section-5-1-8"></a>
#### 5.1.8 Off-site Backup

The off-site backup location shall be over 30 km away from the CHTCA
facility. The backup content shall include data and system programs.

<a id="section-5-2"></a>
### 5.2 Procedural Controls

In order to ensure that system procedures have a suitable assurance
level, CHTCA uses procedural controls to specify the trusted roles of
CHTCA system operations, the number of people required for each task and
how each role is identified and authenticated.

<a id="section-5-2-1"></a>
#### 5.2.1 Trusted Roles

In order to make appropriate segmentation and assignment of the
responsibility for performing system-related operations, to prevent
someone from maliciously using the CA system without being noticed, the
trusted role authorized to perform each system access task is clearly
defined in CHTCA.

The seven PKI personnel roles assigned by CHTCA are administrator, CA
officer, internal auditor, system operator, physical security
controller, cyber security coordinator and anti-virus and anti-hacking
coordinator to prevent potential internal attacks. Each trusted role may
be performed by multiple persons but one person in each group shall be
assigned the chief role to lead group work. The tasks performed by the
seven roles are as follows:

The administrator is responsible for:

- Installation, configuration and maintenance of the CHTCA system

- Creation and maintenance of system user accounts

- Generation and backup of CHTCA keys

- Activation / deactivation of related keys of certificate manager

- System hardware and software updates

- System backup and recovery

- Website maintenance

- Patching the system vulnerabilities

The CA officer is responsible for:

- Generation and backup of CHTCA keys

- Activation / deactivation of keys for certificate issuance

- Activation / deactivation of keys for certificate revocation

- Activation / deactivation of keys for CRL issuance

The internal auditor is responsible for:

- Generation and backup of CHTCA keys

- Checking, maintenance and archiving of audit logs

- Conducting or supervising internal audits to ensure CHTCA is operating
  in accordance with this CPS

- Patching the anti-virus and vulnerabilities of audit system

The system operator is responsible for:

- Archiving of audit logs

- Daily operation and maintenance of system equipment

- Storage media updating

- Set up protection mechanisms for system security and threats of virus
  or malware

The physical security controller is responsible for:

- System physical security controls (such as facility access controls,
  fire prevention, flood prevention and air conditioning systems)

The cyber security coordinator is responsible for:

- Maintenance of the network and network facilities

- Patches management for the vulnerabilities of the network facilities

- The network security of CHTCA

- The detection and report of the network security events

The anti-virus and anti-hacking coordinator is responsible for:

- Researching, applying, or providing the anti-virus, anti-hacking, and
  anti-malicious software technologies or measures to ensure the
  security of the system and the network

- Reporting the collected threats or vulnerabilities of computer virus
  to the administrator or the cyber security coordinator for patches
  management

<a id="section-5-2-2"></a>
#### 5.2.2 Number of Persons Required per Task

In accordance with security requirements, the number of persons required
for each trusted role is as follows:

- Administrator

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; At least 3 qualified individuals are needed.

- CA Officer

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; At least 3 qualified individuals are needed.

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

The number of persons assigned to perform each task is as follows:

| Assignments | Administrator | CA Officer | Internal Auditor | System Operator | Physical security controller | Cyber security coordinator | Anti-virus and anti-hacking coordinator |
|----|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Installation, configuration, and maintenance of the CHTCA system | 2 |  |  |  | 1 |  |  |
| Establishment and maintenance of system user accounts | 2 |  |  |  | 1 |  |  |
| Generation and backup of CHTCA keys | 2 | 2 | 1 |  | 1 |  |  |
| Activation / deactivation of certificate issuance, certificate revocation and CRL issuance | 2 | 2 |  |  | 1 |  |  |
| Checking, maintenance and archiving of audit logs |  |  | 1 | 1 | 1 |  |  |
| Daily operation and maintenance of system equipment |  |  |  | 1 | 1 |  |  |
| System backup and recovery | 1 |  |  |  | 1 |  |  |
| Storage media updating |  |  |  | 1 | 1 |  |  |
| Hardware and software updates outside the CHTCA system | 1 |  |  |  | 1 |  |  |
| Website maintenance | 1 |  |  |  | 1 |  |  |
| Daily operation and maintenance of the network and network facilities |  |  |  | 1 | 1 | 1 |  |
| Patching the vulnerabilities of the network facilities | 1 |  |  |  | 1 | 1 |  |
| Reporting the threats and vulnerabilities of computer virus |  |  |  |  |  |  | 1 |
| Patching the anti-virus and vulnerabilities (audit system) | 1 |  | 1 | 1 | 1 |  |  |
| Patching the anti-virus and vulnerabilities (systems other than the audit system) | 1 |  |  | 1 | 1 |  |  |

<a id="section-5-2-3"></a>
#### 5.2.3 Identification and Authentication for Each Role

When the RA officers who log in the RA system and conduct related review
actions, they shall use IC cards to verify their identities and execute
digital signatures.

CHTCA utilizes user accounts, passwords, and groups for system account
management and IC card to identify and authenticate administrator, CA
officer, internal auditor and system operator. CHTCA utilizes the
authority setting function of the central access control system to
identify and authenticate physical security controllers.

CHTCA utilizes user accounts, passwords, and groups for system account
management, or other security mechanisms to identify the role of the
cyber security coordinator.

<a id="section-5-2-4"></a>
#### 5.2.4 Roles Requiring Separation of Duties

The seven trusted roles are defined in Section 5.2.1. Personnel and
trusted roles must conform to the following regulations:

- Administrator, CA officer, internal auditor, and cyber security
  coordinator cannot assume any other roles among these four trust roles
  at the same time, but administrator, CA officer, and internal auditor
  can be system operator at the same time;

- Physical security controller shall not concurrently assume any role of
  administrator, CA officer, internal auditor, and system operator; and

- A person serving a trusted role is not allowed to perform self-audit.

<a id="section-5-3"></a>
### 5.3 Personnel Controls

<a id="section-5-3-1"></a>
#### 5.3.1 Qualifications, Experience, and Clearance Requirements

1)  Security evaluation for personnel selection

    Personnel selection includes the following items:

    1)  Personality evaluation;

    2)  Applicant experience evaluation;

    3)  Academic and professional skills and qualifications evaluation;

    4)  Personal identity check; and

    5)  Evaluation of personnel conduct.

2)  Management of Personnel Evaluation

    All CHTCA personnel performing certificate work shall have their
qualifications reviewed at the initial time of employment to verify
their reliability and work capabilities. After formal employment,
personnel shall receive appropriate training and sign a document
accepting responsibility to perform certain duties. All personnel shall
have their qualifications rechecked each year to reconfirm their
reliability and work ability. If personnel do not pass the qualification
check, that person shall be reassigned to another position and a
qualified person shall be assigned to serve in that position.

3)  Appointment, Dismissal and Transfer

    If there are changes to the employment terms or contract especially
personnel severance and termination of temporary worker contracts,
personnel are still required to fulfill their duty of confidentiality.

4)  Duty of Confidentiality Agreement

    Work personnel shall fulfill their duty of confidentiality in
accordance with relevant regulations and sign a business secret
agreement drafted by CHTCA stating that personnel may not disclose
business secrets verbally or by photocopy, loan, delivery, publishing
or other methods.

<a id="section-5-3-2"></a>
#### 5.3.2 Background Check Procedures

CHTCA shall check the related identify and qualification documents for
authenticity for those personnel performing the trusted roles defined in
Section 5.2 at the initial time of employment.

<a id="section-5-3-3"></a>
#### 5.3.3 Training Requirements

<table>
<colgroup>
<col style="width: 19%" />
<col style="width: 80%" />
</colgroup>
<thead>
<tr>
<th style="text-align: center;"><strong>Trusted Role</strong></th>
<th style="text-align: center;"><strong>Training
Requirements</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center;">Administrator</td>
<td><ol type="1">
<li>CHTCA security principles and mechanism.</li>
<li>Installation, configuration, and maintenance of the CHTCA
operation procedures.</li>
<li>The use and operation procedures of CHTCA system software and
hardware.</li>
<li>Establishment and maintenance of system user accounts operation
procedures.</li>
<li>Audit parameter configuration setting procedures.</li>
<li>CHTCA key generation and backup operation procedures.</li>
<li>Disaster recovery and continuous operation procedure.</li>
</ol></td>
</tr>
<tr>
<td style="text-align: center;">CA Officer</td>
<td><ol type="1">
<li>CHTCA security principles and mechanism.</li>
<li>CHTCA key generation and backup operation procedures.</li>
<li>Activation/deactivation of certification issuance operation
procedure.</li>
<li>Activation/ deactivation of certification revocation operation
procedure.</li>
<li>Activation/ deactivation of certificate CRL issuance
operation.</li>
<li>Disaster recovery and continuous operation procedure.</li>
</ol></td>
</tr>
<tr>
<td style="text-align: center;">Internal Auditor</td>
<td><ol type="1">
<li>CHTCA security principles and mechanism.</li>
<li>The use and operation procedures of CHTCA audit Server.</li>
<li>CHTCA key generation and backup operation procedures.</li>
<li>Audit log check, maintain and archiving procedures.</li>
<li>Disaster recovery and continuous operation procedure.</li>
</ol></td>
</tr>
<tr>
<td style="text-align: center;">System Operator</td>
<td><ol type="1">
<li>Daily operation and maintenance procedures for system
equipment.</li>
<li>Upgrading of storage media procedure.</li>
<li>Disaster recovery and continuous operation procedure.</li>
<li>Network and website maintenance procedure.</li>
</ol></td>
</tr>
<tr>
<td style="text-align: center;">Physical security controller</td>
<td><ol type="1">
<li>Physical access authorization setting procedure.</li>
<li>Disaster recovery and continuous operation procedure.</li>
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
<td style="text-align: center;">Anti-virus and anti-hacking
coordinator</td>
<td><ol type="1">
<li>Prevention to the threats and vulnerabilities of computer
virus.</li>
<li>Security mechanism for the operating system and the
network.</li>
</ol></td>
</tr>
</tbody>
</table>

<a id="section-5-3-4"></a>
#### 5.3.4 Retraining Frequency and Requirements

In case of software/hardware upgrades, working procedures changed,
equipment replaced, or relevant regulations changed, relevant personnel
will be arranged for retraining and the training situation will be
recorded, so as to make the personnel understand the changes in relevant
operating procedures and regulations.

<a id="section-5-3-5"></a>
#### 5.3.5 Job Rotation Frequency and Sequence

1)  May not concurrently serve trusted roles. May not receive work
    reassignments.

2)  Personnel with a full two years of experience as a system operators,
    cyber security coordinator, or anti-virus and anti-hacking
    coordinator with the requisite training and review may be reassigned
    to the position of administrator, CA officer or internal auditor.

3)  Administrator, CA officer and internal auditor may be reassigned to
    the position of administrator, CA officer or internal auditor after
    they have been transferred from their original positions for one
    full year.

<a id="section-5-3-6"></a>
#### 5.3.6 Sanctions for Unauthorized Actions

CHTCA related personnel shall be subject to appropriate administrative
and disciplinary actions for violations of the ePKI CP, this CPS or
other procedures announced by CHTCA. In the event of serious cases that
result in damages, appropriate legal action shall be taken.

<a id="section-5-3-7"></a>
#### 5.3.7 Independent Contractor Requirements

The duties, sanctions for unauthorized actions and required training
documents of independent contractor serving a trusted role shall meet
the requirements of Section 5.3 and the event logging and document
retention shall meet the requirements of Section 5.4.1.

<a id="section-5-3-8"></a>
#### 5.3.8 Documentation Supplied to Personnel

CHTCA shall make available to related personnel relevant documentation
pertaining to the ePKI CP, this CPS, CHTCA system operation manuals, the
Electronic Signatures Act and its enforcement rules.

<a id="section-5-4"></a>
### 5.4 Audit Logging Procedures

CHTCA shall keep security audit logs for all events related to CHTCA
security. Security audit logs shall be collected by automatic system
generation, logbook or paper. All security audit logs shall be retained
and made available during compliance audits in accordance with the
archive retention regulations stated in Section 5.5.2.

<a id="section-5-4-1"></a>
#### 5.4.1 Types of Events Recorded

1)  Key generation

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Key generation of CAs

2)  Private key loading and storage

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Loading the private key into a system component.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- All access to private keys kept by CHTCA for key recovery work.

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

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- CPS violation.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Reset system clock.

<a id="section-5-4-2"></a>
#### 5.4.2 Frequency of Processing Log

CHTCA shall routinely review audit logs to prevent possible malicious
activity, and any significant operations should be further reviewed.
Review work includes examining all log entries and conducting a final
complete check for any warnings or anomalies. Audit checking results
shall be documented.

<a id="section-5-4-3"></a>
#### 5.4.3 Retention Period for Audit Log

Audit logs shall be retained on-site for two months, and the log
retention management system shall be operated in accordance with
Sections 5.4.4, 5.4.5, 5.4.6 and 5.5.

If the retention period of the audit record file expires, the auditor is
responsible for removing the data and cannot be behalfed by other
personnel.

<a id="section-5-4-4"></a>
#### 5.4.4 Protection of Audit Log

Signature and encryption technology shall be used to protect the current
and archived audit logs. A CD-R or other media storage that cannot
change the audit logs is used, and only authorized personnels can
access.

CHTCA’s audit system enforces resource control and identity
identification security mechanisms, only authorized auditor has backup
and read access to logs, and the system keeps a log file of access audit
records to detect and prevent improper access.

<a id="section-5-4-5"></a>
#### 5.4.5 Audit Log Backup Procedures

1)  CHTCA shall routinely archive event logs, and electronic audit logs
    are backed up at least once a month.

2)  At least one copy of the media for storing audit records shall be
    kept at an off-site location with proper security control measures.

<a id="section-5-4-6"></a>
#### 5.4.6 Audit Collection System (Internal vs. External)

Audit systems are built in the CHTCA system, and audit procedures are
activated when the CHTCA system is activated and only stops when the
CHTCA system is shut down.

If the automated audit system cannot operate normally, CHTCA shall
suspend certificate issuance services until the issue is resolved before
resuming service again to protect system information integrity and
confidentiality when the security system is in a high-risk status.

<a id="section-5-4-7"></a>
#### 5.4.7 Notification to Event-causing Subject

Where an event is logged by the audit system, the audit system does not
need to notify the entity which caused the event.

<a id="section-5-4-8"></a>
#### 5.4.8 Vulnerability Assessments

PublicCA should perform a vulnerability assessment when identifying
significant changes to a network or system. PublicCA also must conduct
penetration testing after it is determined that there is a significant
upgrade or modification to the application program or infrastructure.
CHTCA shall implement the enhancement and correction measures after the
penetration testing and the vulnerability assessment. CHTCA shall record
the skills, tools, followed ethics, competitive relations and
independence guidelines for those personnel or groups capable of
implementing reliable vulnerability scans, penetration testing, or
information security diagnosis or security surveillance.

<a id="section-5-5"></a>
### 5.5 Records Archival

A reliable mechanism shall be adopted by CHTCA to accurately and
completely save certificate-related records as computer data or in
written form, including:

1)  Important tracking records regarding CHTCA’s own key pair
    generation, storage, backup, and re-key.

2)  Important tracking records regarding certificate application,
    issuance, revocation, and reissuance.

In addition to being provided for tracking and audits, these records may
also serve as evidence, if necessary, for dispute resolution. In order
to follow the above regulations, RAs may ask applicants or their
representatives to submit related certification documents when deemed
necessary.

<a id="section-5-5-1"></a>
#### 5.5.1 Types of Records Archived

CHTCA retains the following information in its archives:

1)  CHTCA accreditation information from competent authorities.

2)  CPS.

3)  Major contracts.

4)  System and equipment configuration settings.

5)  System and configuration setting modifications and updates.

6)  Certificate application information.

7)  Revocation request information.

8)  Subscriber identity identification information stipulated in Section
    3.2.

9)  Issued and published certificates.

10) CHTCA re-key records.

11) Issued or announced CRLs.

12) Audit logs.

13) Other data or application programs used to verify and corroborate
    the archived content.

14) Documents required by the auditor.

<a id="section-5-5-2"></a>
#### 5.5.2 Retention Period for Archive

CHTCA retains archived data for at least 2 years. The application
programs used to process archived data are retained for 10 years.

<a id="section-5-5-3"></a>
#### 5.5.3 Protection of Archive

1)  Amendments, modifications, and deletion of archived data are not
    allowed by any user.

2)  The archived data can be moved to another storage medium after pass
    through the CHTCA authorized procedures.

3)  The archived data is stored in a secure, protected location.

<a id="section-5-5-4"></a>
#### 5.5.4 Archive Backup Procedures

CHTCA electronic records shall be regularly backed up and saved in
storage media in accordance with backup procedures. Paper records
shall be regularly sorted and filed by authorized CHTCA personnel.

<a id="section-5-5-5"></a>
#### 5.5.5 Requirements for Time-stamping of Records

All CHTCA computer systems are regularly calibrated to ensure the
accuracy and trustworthiness of the date and time information on
electronic records. For archived electronic records (such as
certificates, CRLs and audit logs), the timestamping information on each
record shall include the date and time information with calibrated
system time. These records shall have appropriate digital signature
protection which can be used to check the date and time information on
the records for alteration.

<a id="section-5-5-6"></a>
#### 5.5.6 Archive Collection System (Internal or External)

There is currently no archive collection system.

<a id="section-5-5-7"></a>
#### 5.5.7 Procedures to Obtain and Verify Archive Information

Only authorized CHTCA personnel are allowed to access the archive.

Audit personal shall follow verification procedures when verifying
archive information. The authenticity of signatures and dates must be
verified for written documents.

<a id="section-5-6"></a>
### 5.6 Key Changeover

CHTCA shall periodically change its private keys in accordance with
Section 6.3.2 and shall change its key pair before the usage period of
its private key issuing subscriber certificates has expired. After key
changeover of Subordinate CAs, an application for a new CA certificate
shall be submitted to eCA is required and the new CA certificate shall
be published in the CHTCA repository.

After key changeover of eCA, eCA shall sign a new self-signed
certificate (by using the new private key) and mutually sign a new
self-issued certificate (by using the new and old private keys,
separately). The new self-signed certificate shall be delivered to
relying parties in accordance with Section 6.1.4 while the new
self-issued certificates shall be published in the eCA repository.

CHTCA shall still maintain and protect its old private keys and shall
make the old certificate available to verify CRL or OCSP until all of
the subscriber certificates signed with the private key have expired.

If CHTCA’s certificate has been revoked, CHTCA shall stop using its
private keys and shall change its key pairs.

<a id="section-5-7"></a>
### 5.7 Compromise and Disaster Recovery

<a id="section-5-7-1"></a>
#### 5.7.1 Incident and Compromise Handling Procedures

CHTCA establishes incident and compromise reporting and handling
procedures and conducts drills annually.

<a id="section-5-7-2"></a>
#### 5.7.2 Computing Resources, Software, and/or Data Are Corrupted

CHTCA establishes recovery procedures in the event of computing
resource, software and data corruption and conducts annual drills.

If CHTCA’s computer equipment is damaged or unable to operate, but the
CHTCA signature key has not been destroyed, priority shall be given to
restoring operation of the CHTCA repository and quickly reestablishing
certificate issuance and management capabilities.

<a id="section-5-7-3"></a>
#### 5.7.3 Entity Private Key Compromise Procedures

CHTCA implements the following recovery procedure in the event of
signature key compromise:

1)  Publish in the repository and notify subscribers and relying parties
    about the event of key compromise.

2)  Revoke the CHTCA signature key certificate and issued subscriber
    certificates.

3)  Generate new key pairs in accordance with the procedures in Section
    5.6 and the new certificates are published in the CHTCA repository.

CHTCA shall conduct the drills of CA private key compromise at least
once a year.

<a id="section-5-7-4"></a>
#### 5.7.4 Business Continuity Capabilities after a Disaster

CHTCA has established a disaster recovery procedure and conducts drills
each year. In the event of a disaster, the emergency response team shall
initiate the disaster recovery procedure. Priority shall be given to
restoring the CHTCA repository operations and quickly reestablishing
certificate issuance and management capabilities.

<a id="section-5-8"></a>
### 5.8 CA or RA Termination

CHTCA shall follow CA service termination procedures in accordance with
related regulations in the Electronic Signatures Act during service
termination. CHTCA shall follow the item below to ensure the rights of
subscribers and relying parties:

1)  CHTCA shall notify the competent authority, Ministry of Digital
    Affairs, and subscribers 30 days prior to of the scheduled
    termination of service.

2)  CHTCA shall take the following measures when terminating their
    service:

    - For certificates which are valid at the time of termination,
      arrangements shall be made for other CA to take over the service.
      Matters regarding service termination and service acceptance by
      other CAs shall be published in the repository and subscribers
      with valid certificates stall be notified. This shall not apply if
      notification cannot be made.

    - All records and files during the operation period shall be handed
      over to the other CA that is taking over this service.

    - If there is no CA willing to take over the CHTCA service, a report
      shall be submitted to the competent authority to arrange for other
      CA to take over this service.

    - If the competent authority arranges for other CA to take over the
      service but no other CA takes over the service, CHTCA shall revoke
      the still valid certificates, publish the revoked certificates in
      the repository and notify all certificate-related persons 30 days
      prior to the scheduled termination of service. CHTCA will refund
      the certificate issuance and renewal fees based on the propotion
      of the certificate validity.

    - The competent authorities, if necessary, may publish the
      certificates which are still valid at the time of revocation.

In case that the RA terminates the service, CHTCA shall stop its rights
of review actions.

<a id="section-6"></a>
## 6 Technical Security Controls

This chapter describes the technical security controls implemented by
PublicCA.

<a id="section-6-1"></a>
### 6.1 Key Pair Generation and Installation

<a id="section-6-1-1"></a>
#### 6.1.1 Key Pair Generation

According to the regulations in Section 6.2.2, CHTCA generates key pairs
within the hardware security module using algorithms and procedures that
comply with NIST FIPS 140-2 or FIPS 140-3. If the token used by the
subscriber is an IC chip, the key pair is generated by the card
management center on behalf of the subscriber; for other types of
certificates, subscribers must generate their key pairs with the
hardware security module set forth in Section 6.2.1.

CHTCA key generation is witnessed and videotaped by those related
personnel who have signed key initiation witness document (the public
key of the generated key pair is listed on it). The related personnel
shall include the members of the PMA and/or the qualified auditors.

<a id="section-6-1-2"></a>
#### 6.1.2 Private Keys Delivery to Subscriber

CHTCA should not generate key pairs of Subordinate CA certificates on
behalf of the subscriber.

If the card management center generates a key pair for subscriber, the
RA shall deliver the token (such as IC card) containing the subscriber
key to the subscriber after certificate issuance by CHTCA.

<a id="section-6-1-3"></a>
#### 6.1.3 Public Key Delivery to Certificate Issuer

If the card management center generates a key pair for a subscriber, the
RA shall deliver the subscriber public key to CHTCA via secure channels.

If a subscriber self-generates a key pair, the subscriber shall deliver
the public key to the RA via a CSR file with PKCS# 10 format. The RA
shall delivery the public key to CHTCA via secure channels after it is
verified that the subscriber is in possession of the corresponding
private key in accordance with the regulations in Section 3.2.1.

Secure channels referred in this Chapter are the use of TLS or other
equivalent or higher-level data encryption transmission protocols.

<a id="section-6-1-4"></a>
#### 6.1.4 CA Public Key Delivery to Relying Parties

Commercial web browsers and platform operators are encouraged to embed
Root Certificate Public Keys of CHTCA into their root stores and
operating systems. CHTCA shall deliver the certificates containing the
certificate chain of relevant CAs to the subscriber after certificate
issuance. Relying parties can also download the public key certificates
of the relevant CAs through the repository operated by CHTCA. Excepet
for eCA, CHTCA notes the download location of the relevant public key
certificates in the certificate chain through the Authority Information
Access (AIA) extension of the issued certificate.

<a id="section-6-1-5"></a>
#### 6.1.5 Key Sizes

CHTCA complies with the regulations of the ePKI CP in using key sizes,
as described below:

1)  Root CAs shall use 4096-bit RSA keys with the SHA-256, SHA-384, or
    SHA-512 hash algorithm to issues certificates.

2)  Subordinate CAs and cross-certified CAs shall choose RSA keys with
    the modulus size of at least 2048 bits or ECDSA keys with a valid
    point on the NIST P-256/NIST P-384 elliptic curve. The hash
    algorithm required to issue certificates depends on the
    aforementioned CAs’ key algorithm:

    - RSA keys: SHA-256, SHA-384, or SHA-512.

    - ECDSA keys: SHA-256 (with the P-256 curve) or SHA-384 (with the P-384
  curve).

3)  Subscribers shall use RSA keys with the modulus size of at least
    2048 bits or ECDSA keys with a valid point on the NIST P-256/NIST
    P-384 elliptic curve.

4)  The modulus size of the aforementioned RSA key (in bits) must be
    divisible by 8.

<a id="section-6-1-6"></a>
#### 6.1.6 Public Key Parameters Generation and Quality Checking

The public key parameter of the RSA algorithm is null.

CHTCA shall use the ANSI X9.31 algorithm or the NIST FIPS 186-4 standard
to generate the prime number needed for the RSA algorithm if a RSA key
pair is selected and ensure that the prime number is a strong prime.

Cross-certified CAs must perform appropriate key parameter quality
checking according to the selected algorithm.

There is no need to guarantee that the prime number, which is needed for
the RSA algorithm, is a strong prime when a subscriber generates an RSA
key pairs within the IC card or other software/hardware security
modules. However, the key must pass a weak key check before it is
allowed to be used for the certificate issuance.

According to Section 5.3.3 of NIST SP 800-89, CHTCA confirms that the
value of the public exponent used by the RSA algorithm is an odd number
greater than 3 and is in the range between 2<sup>16</sup>+1 and
2<sup>256</sup>-1. Furthermore, the modulus should also meet the
following characteristics: an odd number, not the power of a prime, and
have no factors smaller than 752.

In addition, CHTCA confirms the validity of all ECDSA keys using either
the Elliptic Curve Cryptography (ECC) Full Public Key Validation Routine
or the ECC Partial Public Key Validation Routine in accordance with NIST
SP 800-56A Revision 3.

<a id="section-6-1-7"></a>
#### 6.1.7 Key Usage Purposes (as per X.509 v3 Key Usage Field)

<a id="section-6-1-7-1"></a>
##### 6.1.7.1 Key Usage Purposes of CAs

The private key corresponding to eCA’s self-signed certificate can only
be used for issuing self-signed certificates, self-issued certificates,
subordinate CA certificates, cross-certificates, CRLs, OCSP responder
certificates, or OCSP responses.

From the second generation of eCA, the self-signed certificates include
a key usage extension. The content of the key usage and extended key
usage extentions in the self-signed certificates and other certificates
(including self-issued certificates, subordinate CA certificates, and
cross-certificates) issued by eCA shall meet the requirements of Section
7.1.2.

<a id="section-6-1-7-2"></a>
##### 6.1.7.2 Key Usage Purposes of Subscribers

The key usage purpose of subscribers is described as follows according
to the type of certificates:

1)  Time-stamp Certificate

    The keyUsage extension of time-stamp certificates has two key usage
bits set: digitalSignature and contentCommitment. The extKeyUsage
extension contains the value id-kp-timeStamping.

2)  Other Certificates

    When the token used by the subscriber is an IC card or a USB token
with integrated IC card and card reader functions, the token may
contain one or more certificates, where the keyUsage extension of each
certificate is set to either keyEncipherment or digitalSignature.

    When the token used by the subscriber is neither an IC card nor a USB
token, a certificate contained in the token may have both
keyEncipherment and digitalSignature bits set in its keyUsage
extension.

    For the dedicated server application software certificates, the rule
of the critical keyUsage extension shall be (digitalSignature \|
keyEncipherment \| dataEncipherment \| nonRepudiation), and the
extKeyUsage extension shall contain only the value
id-cht-ePKI-kp-dedicated (1.3.6.1.4.1.23459.100.1.1), which is defined
by CHTCA. In addition, it does not have a subjectAltName extension.

    For PDF Signing certificates issued by subordinate CAs of CHTCA, the
combination of keyUsage and extKeyUsage extensions complies with the
AATL technical requirements.

<a id="section-6-2"></a>
### 6.2 Private Key Protection and Cryptographic Module Engineering Controls

<a id="section-6-2-1"></a>
#### 6.2.1 Cryptographic Module Standards and Controls

CHTCA uses hardware security modules compliant with FIPS 140-2 Level 3
or FIPS 140-3 Level 3, or providing equivalent security strength.

Storage media for subscriber key pairs may be:

<table>
<colgroup>
<col style="width: 28%" />
<col style="width: 71%" />
</colgroup>
<thead>
<tr>
<th style="text-align: center;"><strong>Storage Media</strong></th>
<th style="text-align: center;"><strong>Certified Standard</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: left;">Chip</td>
<td style="text-align: left;">FIPS 140-2 Level 2, FIPS 140-3 Level 2,
ISO 15408 or Common Criteria EAL 4+ (or higher)</td>
</tr>
<tr>
<td style="text-align: left;">Hardware Security Module</td>
<td style="text-align: left;">FIPS 140-2 Level 3, FIPS 140-3 Level 3 or
other level with equivalent security strength</td>
</tr>
<tr>
<td style="text-align: left;"><p>Other Tokens</p>
<p>(e.g. Software)</p></td>
<td style="text-align: left;">None</td>
</tr>
</tbody>
</table>

Storage media for the private key corresponding to the Adobe PDF Signing
certificate shall be a chip or a hardware security module that is
validated to FIPS 140-2 Level 2 or FIPS 140-3 Level 2, or that provides
equivalent security strength.

<a id="section-6-2-2"></a>
#### 6.2.2 Private Key (n-out-of-m) Multi-person Control

CHTCA’s private keys are controlled in accordance with the multi-person
control process specified in the ePKI CP, and this process can be used
as the activation and deactivation methods for private keys as well as
the backup and recovery methods for private key splitting.

There are no further regulations for multi-person control of subscriber
private keys.

<a id="section-6-2-3"></a>
#### 6.2.3 Private Key Escrow

CHTCA does not escrow its private signing keys. CHTCA may provide
private key escrow services for subscribers in order to provide the
application of cloud signing.

<a id="section-6-2-4"></a>
#### 6.2.4 Private Key Backup

Backups of CHTCA private keys are made according to private key
multi-person control set forth in Section 6.2.2, and high-security IC
cards are used as the storage media for secret sharing. CHTCA does not
provide additional private key backup services.

<a id="section-6-2-5"></a>
#### 6.2.5 Private Key Archival

The private signing keys of CHTCA shall not be archived, and CHTCA does
not perform archival of subscribers’ private signing keys.

<a id="section-6-2-6"></a>
#### 6.2.6 Private Key Transfer into or from a Cryptographic Module

Private keys are allowed to be exported from the cryptographic module
into backup tokens or imported from backup tokens into the cryptographic
module only during key backup/recovery or cryptographic module
replacement. The private keys mentioned in the previous process are
controlled complying with the requirements of Section 6.2.2. The private
keys are encrypted or split when transferred out of the module or
transported between cryptographic modules and never exist in plaintext
form. After the private keys are imported, the related secret parameters
generated during the transport process must be completely destroyed.

If CHTCA becomes aware that its subordinate CA’s or cross-certified CA’s
private key has been communicated to an unauthorized person or an
organization not affiliated with the subordinate CA or cross-certified
CA, then eCA will revoke all certificates that include the public key corresponding to the communicated private key and notify the subordinate CA or cross-certified CA of such revocation.

<a id="section-6-2-7"></a>
#### 6.2.7 Private Key Storage on Cryptographic Module

As stated in Sections 6.1.1 and 6.2.1. When not in use, the hardware
security module must be taken offline and stored in the location
specified in Section 5.1.1.

<a id="section-6-2-8"></a>
#### 6.2.8 Method of Activating Private Key

CHTCA private key activation is controlled by multi-person controls of
the different usage IC cards kept by administrator and CA officer.

Subscribers shall choose a secure computer environment and a trustworthy
application system carefully and keep and use the private keys properly.
The methods to activate the private keys of subscribers are categorized
by the private key storage media as follows:

1)  If it is an IC card, the private keys shall be activated by the
    subscribers’ (whose identity is validated) configuration and the
    PINs only known to the subscribers.

2)  For other private key tokens, subscribers shall use strong passwords
    or other identification with the same level to activate the private
    keys, in order to prevent the unauthorized access or use of the
    private keys.

<a id="section-6-2-9"></a>
#### 6.2.9 Method of Deactivating Private Key

When the private keys of CHTCA is not in use, an appropriate
deactivation method will be selected to deactivate the private keys in
compliance with ePKI CP. CHTCA does not provide the deactivate services
of subscribe private keys.

<a id="section-6-2-10"></a>
#### 6.2.10 Method of Destroying Private Key

In order to prevent the theft of CHTCA private keys which could endanger
the authenticity of the entire certificate, the private key must be
destroyed at the end of the CHTCA key lifecycle. Therefore, when CHTCA
completes the key renewal and eCA issues a new CHTCA certificate, after
no additional certificates or CRL are issued, zeroization is done on the
old CHTCA private key stored inside the hardware security module to
ensure that the old CHTCA private key is destroyed. In addition to
destroying the old CHTCA private key in the hardware security module,
physical destruction of the splitted IC cards with a backed-up key
inside shall be done as well during the CHTCA key renewal.

If services are permanently not provided by a cryptographic module but
it is still accessible, all private keys (already used or possibly used)
stored in that cryptographic module must be destroyed. After destroying
the keys, the key management tools provided by this cryptographic module
must be used to verify that the above keys no longer exist.

Subordinate CAs and cross-certified CAs must follow the ePKI CP
regulations when choosing an appropriate private key destruction method.
The destruction method for subscriber private keys is not stipulated.

<a id="section-6-2-11"></a>
#### 6.2.11 Cryptographic Module Rating

See Section 6.2.1.

<a id="section-6-3"></a>
### 6.3 Other Aspects of Key Pair Management

<a id="section-6-3-1"></a>
#### 6.3.1 Public Key Archival

CHTCA archives certificates issued by it in accordance with Section 5.5.

<a id="section-6-3-2"></a>
#### 6.3.2 Certificate Operational Periods and Key Pair Usage Periods

<a id="section-6-3-2-1"></a>
##### 6.3.2.1 CA Certificate Operational Periods and Key Pair Usage Periods

Certificates and private keys of CHTCA’s issuing CAs have maximum
validity periods of:

<table>
<colgroup>
<col style="width: 27%" />
<col style="width: 46%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr>
<th align="center"><strong>Type of CA</strong></th>
<th align="center"><strong>Private Key Usage</strong></th>
<th align="center"><strong>Certificate Term</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center" nowrap>Root CA</td>
<td><ul>
<li>Issuing self-signed certificates: 15 years</li>
<li>Issuing self-issued certificates: no stipulation</li>
<li>Issuing cross-certificates: no stipulation</li>
<li>Issuing subordinate CA certificates: 15 years</li>
<li>Issuing CRLs, OCSP responder certificates or OCSP responses: 30
years</li>
</ul></td>
<td align="center">30 years</td>
</tr>
<tr>
<td align="center" nowrap>Subordinate CA</td>
<td><ul>
<li>Issuing subscriber certificates: 10 years</li>
<li>Issuing CRLs, OCSP responder certificates or OCSP responses: 20
years</li>
</ul></td>
<td align="center">20 years</td>
</tr>
</tbody>
</table>

The expiry date of subordinate CA certificates or cross-certificates
issued by eCA must not be greater than the end of eCA’s self-signed
certificate’s validity period.

The expiry date of eCA’s self-issued certificates cross-signed with old
and new eCA keys shall be equal to the expiry date of eCA’s self-signed
certificate issued with the old eCA key.

After the expiration of the certificate issuance validity period of the
issuing CA’s private signing key, the issuing CA shall continue to
provide CRLs, OCSP responder certificates, or OCSP responses until all
issued certificates have expired.

The maximum validity period for private keys and certificates of an OCSP
responder is 36 hours. An OCSP response signed by the OCSP reponder’s
private key includes the signature and the OCSP responder certifcate
that can be used by relying parties to verify the signature of the OCSP
response.

<a id="section-6-3-2-2"></a>
##### 6.3.2.2 Subscriber Certificate Operational Periods and Key Pair Usage Periods

The maximum validity periods of the subscriber certificate and private
key are:

<table>
<colgroup>
<col style="width: 36%" />
<col style="width: 35%" />
<col style="width: 27%" />
</colgroup>
<thead>
<tr>
<th style="text-align: center;"><strong>Type of Cert.</strong> </th>
<th style="text-align: center;"><strong>Private Key Usage Period</strong> </th>
<th style="text-align: center;"><strong>Maximum Validity Period</strong> </th>
</tr>
</thead>
<tbody>
<tr>
<td>Time-stamp Certificate</td>
<td align="center">15 months</td>
<td align="center">135 months</td>
</tr>
<tr>
<td>Other Certificate</td>
<td align="center">126 months</td>
<td align="center">126 months</td>
</tr>
</tbody>
</table>

<a id="section-6-4"></a>
### 6.4 Activation Data

<a id="section-6-4-1"></a>
#### 6.4.1 Activation Data Generation and Installation

The activation data of CHTCA’s private key is randomly generated and
written to the hardware cryptographic module after completing identity
verification for administrators of n-out-of-m control IC cards based on
the access control list set during the generation of the afforementioned
private key. Administrators must insert their n-out-of-m control IC
cards into the card reader built in the hardware cryptographic module
and enter the correct personal identification number (PIN) of IC cards
when performing identity verification as mentioned above.

<a id="section-6-4-2"></a>
#### 6.4.2 Activation Data Protection

Activation data is protected by the n-out-of-m control IC cards.
Administrators who hold the IC cards are responsible for the safekeeping
of the card PIN, which shall not be stored in any media. If the
administrator enters the wrong PIN for more than 3 consecutive times,
the IC card is locked. During IC card handover, a new PIN is set by the
new administrator.

<a id="section-6-4-3"></a>
#### 6.4.3 Other Aspects of Activation Data

No stipulation.

<a id="section-6-5"></a>
### 6.5 Computer Security Controls

<a id="section-6-5-1"></a>
#### 6.5.1 Specific Computer Security Technical Requirements

CHTCA and related auxiliary systems provide the following security
control functions through the operating systems, combined operating
systems, software, and physical protection measures:

1)  Trusted role or identity authentication login,

2)  Provide discretionary access control,

3)  Provide security audit capability, and

4)  Access control restrictions for certificate services and PKI trusted
    roles.

The CHTCA equipment is established on work platforms which have
undergone a security assessment and the CA-related systems (hardware,
software, operating system) must be operated with configurations which
have undergone a security assessment. CHTCA enforces multi-factor
authentication for all accounts capable of directly causing certificate
issuance.

<a id="section-6-5-2"></a>
#### 6.5.2 Computer Security Rating

CHTCA servers use Common Criteria EAL 3 or above certified computer
operating systems.

<a id="section-6-6"></a>
### 6.6 Life Cycle Technical Controls

<a id="section-6-6-1"></a>
#### 6.6.1 System Development Controls

CHTCA follows established software engineering methodologies for system
development and quality control.

System development, test and production environments shall operate
independently to prevent unauthorized access or changes. In addition,
CHTCA may only use dedicated and authorized hardware and software.

RA software shall be checked for malicious code before the first use or
any version update, and periodic security scans shall be performed to
prevent the installation of malicious software.

For each product or program delivered to CHTCA, it is required to
provide the delivery list, test report, and source code analysis report,
as well as be under version control.

<a id="section-6-6-2"></a>
#### 6.6.2 Security Management Controls

CHTCA shall not install software, hardware or components that are not
related to its operation. When installing software onto a CA system,
CHTCA shall first confirm the integrity and correctness of the version
and check the integrity of CA software regularly or before each use. In
addition, CHTCA documents and controls any change to the system as well
as detecting unauthorized modifications to system software or
configurations.

CHTCA references the methodologies and standards in the ISO/IEC 27001,
ISO/IEC 27002, ISO/IEC 27005, ISO/IEC 31000, WebTrust Principles and
Criteria for Certification Authorities, and Network and Certificate
System Security Requirements for risk assessment, risk management, and
security management and control measures.

<a id="section-6-6-3"></a>
#### 6.6.3 Life Cycle Security Controls

CHTCA shall conduct a risk assessment at least once a year to determine
if there is any risk of compromise for existing keys.

<a id="section-6-7"></a>
### 6.7 Network Security Controls

CHTCA implements network security control measures in compliance with
the Network and Certificate System Security Requirements.

The CHTCA host and repository have firewalls and are connected to
external networks. The repository is placed in the external service area
of the firewall (de-militarized zone, DMZ) and connected to the
Internet. Except during required maintenance or backup, the repository
provides uninterrupted certificate and CRL inquiry services.

The certificates and CRLs issued by the CHTCA are digitally signed and
transmitted to the repository. The CHTCA repository protects against
denial of service and intrusion attacks by system patch updates, system
vulnerability scans, intrusion defending/detection systems, firewall
systems and filtering routers.

CHTCA monitors the configuration of access control permissions,
continuously monitors system health and security events, and performs
penetration tests. Vulnerability scans of networks are performed at
least once a quarter, and penetration tests at least annually.
Remediation timelines are governed by severity, with critical
vulnerabilities assessed within 96 hours and high/medium issues resolved
within 90 days. Exceptions are documented, assessed for risk, and
recorded.

<a id="section-6-8"></a>
### 6.8 Time-stamping

CHTCA regularly conducts system clock synchronization with a reliable
time source to maintain the correctness of system time and ensure the
accuracy of the following times. Automatic or manual procedures may be
used to adjust the system time, and system clock synchronizations shall
be auditable events.

1)  Time of certificate issuance,

2)  Time of certificate revocation,

3)  Time of CRL issuance, and

4)  Time of system event occurrence.

#

<a id="section-7"></a>
## 7 Certificate, CRL, and OCSP Profiles

<a id="section-7-1"></a>
### 7.1 Certificate Profile

The certificates issued by CHTCA comply with the relevant requirements
specified in ITU-T X.509 and RFC 5280.

The serial number assigned by CHTCA to each certificate shall be a
non-sequential number greater than zero (0) and less than 2¹⁵⁹, and
shall contain at least 64 bits of output generated by a
Cryptographically Secure Pseudorandom Number Generator (CSPRNG).

<a id="section-7-1-1"></a>
#### 7.1.1 Version Number(s)

CHTCA issues certificates in compliance with RFC 5280 and ITU-T X.509
version 3.

<a id="section-7-1-2"></a>
#### 7.1.2 Certificate Extensions

See Appendix 3, 3-1, and 3-2 for details.

<a id="section-7-1-3"></a>
#### 7.1.3 Algorithm Object Identifiers

CHTCA uses the algorithms listed in the table below for signing
certificates and generating key pairs.

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

During ECC algorithm is used for generarting ECDSA key pairs, the OIDs
of the elliptic curve parameter is set as follows according to the key
size:

<table>
<thead>
<tr>
<th align="center" nowrap>Key Size</th>
<th align="center">Elliptic Curve Parameter</th>
<th align="center">OID</th>
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

<a id="section-7-1-4"></a>
#### 7.1.4 Name Forms

The subject DN and issuer DN fields of a certificate must use the X.500
distinguished name and the name attribute type shall comply with the
relevant requirements specified in ITU-T X.509 and RFC 5280.

<a id="section-7-1-4-1"></a>
##### 7.1.4.1 Name Encoding

The encoded content of the issuer DN field of certificates issued by an
issuing CA shall be byte-for-byte identical with the encoded form of the
subject DN field of the issuing CA’s certificate. If there are two or
more CA certificates, including expired and revoked CA certificates,
whose subject DNs can be compared as equal, the encoded content of the
subject DN field of the aforementioned certificates shall be
byte-for-byte identical.

<a id="section-7-1-4-2"></a>
##### 7.1.4.2 Subject Information–CA Certificates

Certificates can be issued after issuing CAs followed the procedures set
forth in the ePKI CP and this CPS to verify that all of the subject
information was accurate. For self-signed certificates issued since the
second-generation of eCA and newly issued subordinate CA certificates,
the subject field includes three attributes, namely “commonName”,
“organizationName”, and “countryName”, described as follows:

1)  commonName

    The name used to identify the issuing CA. It is the unique identifier
of the certificate and can be used to distinguish the issuing CA’s
certificate from other CA certificates.

2)  organizationName

    The official name of the organization to which the issuing CA belongs.
It can be adjusted according to the abbreviation method approved by
our country. The authentication of this organization name shall be
implemented in accordance with Section 3.2.2.

3)  countryName

    The country where the place of business that the issuing CA locates.
It shall be represented by the country codes specified in ISO 3166-1,
which is “TW”.

<a id="section-7-1-4-3"></a>
##### 7.1.4.3 Subject Information–Subscriber Certificates

By issuing the subscriber certificates, CHTCA represents that they
followed the procedures set forth in the ePKI CP and/or this CPS to
verify that, as of the subscriber certificate’s issuance date, all of
the subject information was accurate.

In addition, subject attributes MUST NOT contain only metadata such as
‘.’, ‘-’, and ‘ ’ (i.e. space) characters, and/or any other indication
that the value is absent, incomplete, or not applicable.

<a id="section-7-1-5"></a>
#### 7.1.5 Name Constraints

Name constraints are not applied to CHTCA certificates. Self-signed
certificates, self-issued certificates, subordinate CA certificates and
cross-certificates, which are not technically constrained, will be
disclosed publicly, such as being disclosed in the CCADB.

<a id="section-7-1-6"></a>
#### 7.1.6 Certificate Policy Object Identifier

All certificates issued by CHTCA, excluding self-signed certificates of
the Root CA, shall include the certificate policies extension. The CP
OIDs used are specified in Section 1.2 of the ePKI CP.

<a id="section-7-1-7"></a>
#### 7.1.7 Usage of Policy Constraints Extension

No stipulation.

<a id="section-7-1-8"></a>
#### 7.1.8 Policy Qualifiers Syntax and Semantics

The policy qualifier field in the certificate policies extension of
CHTCA certificates may be used as needed. When using this field, it may
contain a CPS pointer qualifier that points to this CPS.

<a id="section-7-1-9"></a>
#### 7.1.9 Processing Semantics for the Critical Certificate Policies Extension

The certificate policies extension of the certificates issued by CHTCA
are not marked critical.

<a id="section-7-2"></a>
### 7.2 CRL Profile

The CRLs issued by CHTCA comply with the relevant requirements specified
in RFC 5280.

<a id="section-7-2-1"></a>
#### 7.2.1 Version Number(s)

CHTCA issues CRLs complying with RFC 5280 and ITU-T X.509 version 2.

<a id="section-7-2-2"></a>
#### 7.2.2 CRL and CRL Entry Extensions

The CRL and CRL entry extensions in the CRL issued by CHTCA comply with
the relevant requirements specified in ITU-T X.509 and RFC 5280. These
extensions are described below.

1)  CRL Extensions

    <table>
    <colgroup>
    <col style="width: 17%" />
    <col style="width: 16%" />
    <col style="width: 14%" />
    <col style="width: 51%" />
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
    <td style="text-align: left;">This extension contains only the keyIdentifier field, which is the 160-bit 
      SHA-1 hash of the issuing CA's public key. Its value must be identical to the value contained in the subjectKeyIdentifier extension 
      of the issuing CA’s certificate.</td>
    </tr>
    <tr>
    <td>CRL Number</td>
    <td align="center">MUST</td>
    <td align="center">N</td>
    <td style="text-align: left;">The CRL number shall be a monotonically
    increasing non-negative integer.</td>
    </tr>
    <tr>
    <td>Issuing Distribution Point</td>
    <td align="center">OPTIONAL</td>
    <td align="center">Y</td>
    <td style="text-align: left;"><p>This extension is only applicable to a
    partitioned CRL, in which it is defined as a required extension. Its
    content is as follows:</p>
    <ul>
    <li>The distributionPoint field is present and used to specify the
    HTTP URL of the issuing CA’s CRL service.</li>
    <li>The indirectCRL and onlyContainsAttributeCerts fields are set to
    FALSE (i.e., not asserted).</li>
    <li>CHTCA does not simultaneously assert both the
    onlyContainsUserCerts and onlyContainsCACerts fields.</li>
    <li>The onlySomeReasons field is not included.</li>
    </ul></td>
    </tr>
    </tbody>
    </table>

2)  CRL Entry Extensions

    <table>
    <colgroup>
    <col style="width: 17%" />
    <col style="width: 16%" />
    <col style="width: 14%" />
    <col style="width: 51%" />
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
    <td>Reason Code</td>
    <td align="center">OPTIONAL</td>
    <td align="center">N</td>
    <td style="text-align: left;"><p>This extension is used to indicate the
    most appropriate reason for revocation of the certificate. If this CRL
    entry extension is used to identify the revocation reason of self-signed
    certificates, self-issued certificates, subordinate CA certificates and
    cross-certificates, the reasonCode value can be the follows:</p>
    <ul>
    <li>caCompromise(2)</li>
    <li>affiliationChanged(3)</li>
    <li>superseded(4)</li>
    <li>cessationOfOperation(5)</li>
    <li>privilegeWithdrawn(9)</li><br>
    </ul>
    <p>If the CRL entry extension is used to identify the revocation reason
    of subscriber certificates, the reasonCode value is as follows.</p>
    <ul>
    <li>unspecified (0): If the use of this reason code is permitted, the
    extension field will be omitted.</li>
    <li>keyCompromise(1)</li>
    <li>affiliationChanged(3)</li>
    <li>superseded(4)</li>
    <li>cessationOfOperation(5)</li>
    <li>certificateHold(6)</li>
    <li>privilegeWithdrawn(9)</li>
    </ul></td>
    </tr>
    </tbody>
    </table>

<a id="section-7-3"></a>
### 7.3 OCSP Profile

If CHTCA provides OCSP services in compliance with RFC 6960 and/or RFC
5019, the HTTP URL of the issuing CA’s OCSP responder shall be included
in the authority Information access extension of certificates issued by
CHTCA, excluding self-signed certificates issued by the Root CA.

<a id="section-7-3-1"></a>
#### 7.3.1 Version Number(s)

An OCSP request accepted by CHTCA shall contain the following
information:

- Protocol version, and

- Target certificate identifier.

An OCSP response, issued by the OCSP responder, at a minimum consists of
a responseStatus field indicating the processing status of the prior
request. If the value of responseStatus is ‘successful’, the OCSP
response must further include the other fields as follows:

<table>
<colgroup>
<col style="width: 38%" />
<col style="width: 61%" />
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
<td>v1</td>
</tr>
<tr>
<td nowrap>OCSP Responder ID</td>
<td>The subject DN of OCSP responder</td>
</tr>
<tr>
<td nowrap>Produced Time</td>
<td style="text-align: left;">The time at which the OCSP response was
signed</td>
</tr>
<tr>
<td nowrap>Target Certificate Identifier</td>
<td>The contents of this field include the hash algorithm, the hash of
the issuer’s DN, the hash of the issuer’s public key and the serial
number of the target certificate.</td>
</tr>
<tr>
<td nowrap>Certificate Status</td>
<td style="text-align: left;"><p>The meaning of certificate status value
is described below:</p>
<ul>
<li>0: valid</li>
<li>1: revoked</li>
When this status value is used, this field shall also contain the
revocation time and reason of that certificate. The revocationReason
field within the RevokedInfo of the CertStatus shall be identical to the
CRLReason of the revoked certificate noted in the CRL (See Section
7.2.2). 
<li>2: unknown</li>
</ul>
</td>
</tr>
<tr>
<td nowrap>Validity Period</td>
<td style="text-align: left;">Recommended validity period for this OCSP
response, including thisUpdate and nextUpdate</td>
</tr>
<tr>
<td nowrap>Signature Algorithm</td>
<td style="text-align: left;"><p>OCSP response signature algorithm,
which can be either:</p>
<ul>
<li>sha256WithRSAEncryption, or</li>
<li>ecdsaWithsha384</li>
</ul></td>
</tr>
<tr>
<td nowrap>Signature</td>
<td>OCSP responder signature</td>
</tr>
<tr>
<td nowrap>Certificates</td>
<td>OCSP responder certificate</td>
</tr>
</tbody>
</table>

<a id="section-7-3-2"></a>
#### 7.3.2 OCSP Extensions

The singleExtensions of an OCSP response MUST NOT contain the reasonCode
(OID 2.5.29.21) CRL entry extension.

#

<a id="section-8"></a>
## 8 Compliance Audit and Other Assessments

<a id="section-8-1"></a>
### 8.1 Frequency or Circumstances of Assessment

CHTCA shall undergo routine external audits at least once per year (the
audited period may not exceed 12 months) and non-routine internal audits
to confirm that the security regulations and procedures of the ePKI CP
and this CPS are being implemented and enforced.

<a id="section-8-2"></a>
### 8.2 Identity/Qualifications of Assessor

CHTCA entrusts external audit operations to qualified auditors, who is
familiar with the operations of CHTCA and authorized by the WebTrust
Principles and Criteria for Certification Authorities program management
unit to implement relevant WebTrust Principles and Criteria for
Certification Authorities audit criteria in R.O.C., to provide impartial
and objective audit services. Audit personnel shall be a certified
information system auditor or a person who has equivalent qualification;
and shall at least possess the experience of conducting a WebTrust
Principles and Criteria for Certification Authorities seal audit twice
at 4 man-days or the experience of conducting a CA information security
management audit twice at 8 man-days. CHTCA shall conduct identity
identification of auditors during audits.

<a id="section-8-3"></a>
### 8.3 Assessor’s Relationship to Assessed Entity

CHT shall entrust an impartial third party to conduct audits of CHTCA
operations.

<a id="section-8-4"></a>
### 8.4 Topics Covered by Assessment

CHTCA undergoes an audit in accordance with the scheme of “WebTrust
Principles and Criteria for Certification Authorities” and “WebTrust
Principles and Criteria for Certification Authorities - Network
Security”.

The assessment shall include the following topics:

1)  Whether CHTCA is operating in accordance with this CPS, including
    management and technical audit of the physical environment,
    personnel procedural controls, key control, certificate lifecycle
    control, and hardware cryptographic module control;

2)  Whether the RA of CHTCA complies with this CPS and related
    procedures; and

3)  Whether the requirements of this CPS are being implemented and
    enforced subject to the ePKI CP, and whether the requirements are
    suitable for the practical operations of CHTCA.

CHTCA has the right to conduct the review and examination of following
(but not limited to) items to ensure its trustworthiness:

1)  If there is an event of computer emergency or key compromise that
    causes CHTCA to reasonably suspect the RA is unable to comply with
    the ePKI CP and this CPS;

2)  If the compliance audit has not been completed or there are special
    developments, CHTCA has the right to conduct a risk management
    review; or

3)  If action or inaction by the RA causes actual or potential security
    and integrity threat to the ePKI, CHTCA must conduct the related
    review or examination.

CHTCA has the right to retain a third-party auditor to perform audit and
examination functions. The audited RA shall provide full and reasonable
cooperation with CHTCA and the personnel conducting the audit and
examination.

<a id="section-8-5"></a>
### 8.5 Actions Taken as a Result of Deficiency

If audit personnel find a discrepancy between the requirements of this
CPS and the design, operation, or maintenance of CHTCA or its RA, the
following actions shall be taken:

1)  Note the discrepancy,

2)  Notify CHTCA about the discrepancy, and

3)  CHTCA shall submit an improvement plan regarding the discrepancy
    items within 30 days and promptly implement it. The discrepancy
    items shall also be listed as follow-up audit tracking items. The RA
    is notified to make improvements to RA-related deficiencies.

<a id="section-8-6"></a>
### 8.6 Communications of Results

Except for any audit findings that could result in system attacks and
the stipulations in Section 9.3, CHTCA shall make its audit report
publicly available. Audit results are displayed with related WebTrust
Principles and Criteria for Certification Authorities seals on CHTCA’s
homepage. The audit report and management’s assertions may be viewed by
clicking on the seals. CHTCA should make its audit report and
management’s assertions publicly available no later than three months
after the end of the audit period. In the event of a delay greater than
three months, CHTCA shall provide an explanatory letter signed by the
qualified auditor.

<a id="section-9"></a>
## 9 Other Business and Legal Matters

<a id="section-9-1"></a>
### 9.1 Fees

<a id="section-9-1-1"></a>
#### 9.1.1 Certificate Issuance or Renewal Fees

The fee calculation framework for certificate application, issuance, and
renewal between CHTCA and subscribers shall be stipulated in the related
business contract terms and conditions and subscribers may directly
connect to the repository to check related terms and conditions.

<a id="section-9-1-2"></a>
#### 9.1.2 Certificate Access Fees

Certificate access fees are stipulated in related contract terms and
conditions and subscribers may directly connect to the repository to
check related terms and conditions.

<a id="section-9-1-3"></a>
#### 9.1.3 Revocation or Status Information Access Fees

Fees may not be charged for subscriber CRL downloading or access. The
fee calculation framework for OCSP service is stipulated in related
contract terms and conditions. Subscribers may directly connect to the
repository for inquiry.

<a id="section-9-1-4"></a>
#### 9.1.4 Fees for Other Services

No stipulation.

<a id="section-9-1-5"></a>
#### 9.1.5 Refund Policy

With regard to the certificate issuance and renewal fees charged by
CHTCA, if a subscriber is unable to use a certificate due to oversight
by CHTCA, CHTCA shall issue a new certificate after conducting an
investigation. If the subscriber does not accept the newly issued
certificate, CHTCA shall refund the fee to the subscriber. Except for
the above circumstances and circumstances in section 4.9, other fees
shall not be refunded.

<a id="section-9-2"></a>
### 9.2 Financial Responsibility

<a id="section-9-2-1"></a>
#### 9.2.1 Insurance Coverage

CHTCA is owned and operated by CHT. Its financial responsibilities are
the responsibilities of CHT. CHTCA has taken out a Commercial General
Liability insurance of USD 5 million in coverage, and eCA and PublicCA
have taken out an additional Professional Liability/Errors & Omissions
insurance of USD 10 million in coverage.

<a id="section-9-2-2"></a>
#### 9.2.2 Other Assets

CHTCA finances are a part of the overall finances of CHT. CHT is a
publicly listed company. In accordance with Article 36 of the Securities
and Exchange Act, annual financial reports duly audited and attested by
a certified public accountant, approved by the board of directors and
recognized by the supervisors are publically announced and registered
with the competent authority within three months after the close of each
fiscal year. Financial reports duly reviewed by a certified public
accountant and reported to the board of directors are publicly announced
and registered within 45 days after the end of the first, second and
third quarters of each fiscal year. The operating status for the
preceding month is publicly announced and registered within the first 10
days of each month. CHTCA can provide self-insured asset prices based on
CHT’s financial reports.

<a id="section-9-2-3"></a>
#### 9.2.3 Insurance or Warranty Coverage for End-Entities

No stipulation.

<a id="section-9-3"></a>
### 9.3 Confidentiality of Business Information

<a id="section-9-3-1"></a>
#### 9.3.1 Scope of Confidential Information

The following information generated, received and kept by CHTCA or its
RA is deemed confidential information:

1)  Private keys and passphrases used for operations,

2)  Key splitting safekeeping information,

3)  Subscriber application information,

4)  Audit and tracking logs generated or kept by CHTCA,

5)  Audit logs and reports made by audit personnel during the audit
    process, and

6)  Operation-related documents listed as confidential level.

Current and departed personnel in CHTCA and RA and audit personnel shall
keep secrets for the aforementioned confidential information.

<a id="section-9-3-2"></a>
#### 9.3.2 Information Not Within the Scope of Confidential Information

1)  Identification information and information listed in the certificate
    are not deemed confidential information unless stipulated otherwise,
    and

2)  Issued certificates, revoked certificates, suspended information and
    CRLs published in the CHTCA repository are not deemed confidential
    information.

<a id="section-9-3-3"></a>
#### 9.3.3 Responsibility to Protect Confidential Information

CHTCA shall handle subscriber application information in accordance with
the Electronic Signatures Act, WebTrust Principles and Criteria for
Certification Authorities related audit criteria, and Personal
Information Protection Act and its related sub-laws.

<a id="section-9-4"></a>
### 9.4 Privacy of Personal Information

<a id="section-9-4-1"></a>
#### 9.4.1 Privacy Plan

CHTCA has posted its personal information statement and privacy
declaration on its website. CHTCA conducts privacy impact analysis and
personal information risk assessments and has established a privacy
protection plan.

<a id="section-9-4-2"></a>
#### 9.4.2 Information Treated as Private

Private information includes:

1)  The personal information listed on certificate applications should
    not be disclosed without the subscriber’s consent or in accordance
    with related laws,

2)  Subscriber information that cannot be obtained through certificates,
    CRLs or certificate catalog service,

3)  Personnel identifiable information in CHTCA such as names together
    with palmprint or fingerprint biometrics, and

4)  Personal information on confidentiality agreements or contracts.

CHTCA and its RAs implement security control measures to prevent
personally identifiable information from unauthorized disclosure,
leakage, or damage.

<a id="section-9-4-3"></a>
#### 9.4.3 Information Not Deemed Private

The following information not deem as private:

1)  Identification information, information listed in certificates, and
    certificates are not deemed private information unless stipulated
    otherwise, and

2)  Issued certificates, revoked certificates or suspension information
    and CRLs published in the CHTCA repository are not private
    information.

<a id="section-9-4-4"></a>
#### 9.4.4 Responsibility to Protect Private Information

The personal information required for the operation of CHTCA, in
either paper or digital form, must be handled in accordance with
Personal Information Protection Act and its related sub-laws and
privacy rights declaration posted on the website. CHTCA shall
negotiate the liability of protecting private information with its RA.

<a id="section-9-4-5"></a>
#### 9.4.5 Notice and Consent to Use Private Information

Pursuant to the Personal Information Protection Act and its related
sub-laws, personal information shall not be used for other purposes
without the consent of subscriber or unless stipulated otherwise in
Personal Information Protection Act, privacy rights declaration or this
CPS. Subscribers may inquire their application information specified in
Section 9.3.1 paragraph (3); however, CHTCA reserves the right to charge
reasonable fees from subscribers applying for access to this
information.

<a id="section-9-4-6"></a>
#### 9.4.6 Disclosure Pursuant to Judicial or Administrative Process

If judicial, supervisory or law enforcement authorities need to check
private information under Section 9.3.1 due to one of the following
conditions, the matter shall be handled in accordance with law or
regulation:
1)  The provisions of government decrees and the legal authorization of
    the competent authority; or

2)  The court handles disputes arising from the use of certificates and
    legal application needs for arbitration.

Otherwise, the registered personal information and
identification-related information of subscribers will never be
arbitrarily provided to the competent authority or any other person.

<a id="section-9-4-7"></a>
#### 9.4.7 Other Information Disclosure Circumstances

Subscriber personal information obtained during CHTCA operations is
handled in accordance with related laws and may not be disclosed
externally, unless stipulated otherwise under the law.

<a id="section-9-5"></a>
### 9.5 Intellectual Property Rights

The following is the intellectual property of CHTCA:

1)  Related documents or system development for certificate management
    of CHTCA;

2)  Certificates and CRLs issued by CHTCA; and

3)  This CPS.

This CPS is available for free download from the repository or
reasonable use according to the relevant provisions in the Copyright Act
of R.O.C. This CPS can be used reasonably and no fee will be charged.
CHTCA reserves the right to pursue legal action for any violation of the
use or dissemination of this CPS.

<a id="section-9-6"></a>
### 9.6 Representations and Warranties

<a id="section-9-6-1"></a>
#### 9.6.1 CA Representations and Warranties

CHTCA represents and warrants to the Certificate Beneficiaries including
Subscribers, Relying Parties, and Application Software Suppliers that,
during the period when the Certificate is valid, CHTCA complies with the
ePKI CP and this CPS in issuing and managing the Certificate.

The Certificate Warranties specifically include, but not limited to, the
following:

1)  **Right to Use Domain Name or Mailbox Address**: That, at the time
    of issuance, CHTCA (i) implemented a procedure for verifying that
    the Applicant either had the right to use, or had control of, the
    Domain Name(s) or Mailbox Addresses listed in the Certificate’s
    subject field and subjectAltName extension (or, only in the case of
    Domain Names, was delegated such right or control by someone who had
    such right to use or control); (ii) followed the procedure when
    issuing the Certificate; and (iii) accurately described the
    procedure in this CPS (see Section 3.2);

2)  **Authorization for Certificate**: That, at the time of issuance,
    CHTCA (i) implemented a procedure for verifying that the Subject
    authorized the issuance of the Certificate and that the Applicant
    Representative is authorized to request the Certificate on behalf of
    the Subject; (ii) followed the procedure when issuing the
    Certificate; and (iii) accurately described the procedure in this
    CPS (see Section 3.2.5);

3)  **Accuracy of Information**: That, at the time of issuance,
    CHTCA (i) implemented a procedure for verifying the accuracy of all
    of the information contained in the Certificate; (ii) followed the
    procedure when issuing the Certificate; and (iii) accurately
    described the procedure in this CPS (see Sections 3.2.2, 3.2.3 and
    3.2.7);

4)  **No Misleading Information**: That, at the time of issuance,
    CHTCA (i) implemented a procedure for reducing the likelihood that
    the information contained in the Certificate’s
    subject:organizationalUnitName attribute would be misleading; (ii)
    followed the procedure when issuing the Certificate; and (iii)
    accurately described the procedure in this CPS (see Sections 3.2.2,
    3.2.3 and 3.2.7);

5)  **Identity of Applicant**: That, if the Certificate contains Subject
    Identity Information, CHTCA (i) implemented a procedure to verify
    the identity of the Applicant in accordance with Sections 3.2.2 and
    3.2.3; (ii) followed the procedure when issuing the Certificate;
    and (iii) accurately described the procedure in this CPS;

6)  **Subscriber Agreement**: That, if CHTCA and Subscriber are not
    Affiliated, the Subscriber and CHTCA are parties to a legally valid
    and enforceable Subscriber Agreement, or, if CHTCA and Subscriber
    are the same entity or are Affiliated, the Applicant Representative
    acknowledged the Terms of Use;

7)  **Status**: That CHTCA maintains a 24 x 7 publicly-accessible
    Repository with current information regarding the status (valid or
    revoked) of all unexpired Certificates (see Section 4.10.2); and

8)  **Revocation**: That CHTCA will revoke the Certificate for any of
    the reasons specified in the Baseline Requirements (see Section
    4.9.1).

<a id="section-9-6-2"></a>
#### 9.6.2 RA Representations and Warranties

Certificate subject identity check is done for certificates issued by
CHTCA. Its checking level is the review results of the RAO at that time
of validation, but no guarantee is provided for the credit status,
financial capability, technical capability or reliability of the
subscriber.

RAs shall represent and warrant that:

1)  Certificate verification is performed in compliance with the ePKI CP
    and this CPS;

2)  All information provided to the issuing CA does not contain any
    false or misleading information;

3)  Translations performed by the RA are an accurate translation of the
    original information;

4)  All Certificates requested by the RA meet the requirements of this
    CPS;

5)  Identification and authentication procedures for RAO are
    implemented; and

6)  RA private keys are securely managed.

<a id="section-9-6-3"></a>
#### 9.6.3 Subscriber Representations and Warranties

For the express benefit of CHTCA and the Certificate Beneficiaries, the
Applicant shall warrant that, prior to the issuance of a certificate,
CHTCA will obtain, either:

1)  The Applicant’s agreement to the Subscriber Agreement with CHTCA, or

2)  The Applicant’s acknowledgement of the Terms of Use.

Applicant (or human sponsor for device certificates or agent under a
subcontractor or hosting service relationship) shall represent and
warrant to CHTCA that it will:

1)  Securely generate its private keys and prevent its private keys from
    compromise,

2)  Provide accurate and complete information to CHTCA and RA,

3)  Comply with the stipulations and procedures in Chapters 3 and 4,

4)  Confirm the accuracy of certificate data prior to using the
    certificate,

5)  Promptly notify CHTCA, cease using a certificate, and request
    revocation of the certificate, if

    1)  any information in the certificate is or becomes incorrect or
        inaccurate, or

    2)  there is any actual or suspected misuse or compromise of the
        Subscriber’s private key associated with the public key included in
        the certificate (and cease using the private key),

6)  Use the certificate only for legal and authorized purposes,
    consistent with the ePKI CP, this CPS and Subscriber Agreement, and

7)  Promptly cease using the certificate and related private key after
    the certificate’s expiration.

<a id="section-9-6-4"></a>
#### 9.6.4 Relying Party Representations and Warranties

Each relying party represents and warrants to:

1)  Comply with the provisions of this CPS when using a certificate or
    querying the CHTCA repository;

2)  Check the certificate assurance level before using it;

3)  Check the keyUsage field listed in the certificate prior to the use
    of certificates;

4)  Validate a certificate (issued by CHTCA) by using a CRL or OCSP
    published by CHTCA to confirm the validity;

5)  Carefully select secure computer environments and reliable
    application systems. If the rights of subscribers and relying
    parties are infringed due to the use of an untrusted computer
    environment or application system, relying parties shall bear the
    responsibility solely;

6)  Seek other ways for completion of legal acts as soon as possible if
    CHTCA is unable to operate normally for some reason. It may not be a
    cause of defending others that CHTCA is not function properly; and

7)  Have understood and agreed to the legal liability clauses of CHTCA
    and will use the certificate in accordance with Section 1.4.1 when
    accepting the certificate.

If there is a violation, relying parties shall bear liability for
damages in accordance with the Civil Code and related laws and
regulations.

<a id="section-9-6-5"></a>
#### 9.6.5 Representations and Warranties of Other Participants

No stipulation.

<a id="section-9-7"></a>
### 9.7 Disclaimers of Warranties

Except to the extent prohibited by law or as otherwise provided herein,
CHTCA disclaims all express and implied warranties including all
warranties of merchantability or fitness for a particular purpose.

<a id="section-9-8"></a>
### 9.8 Limitations of Liability

Except to the extent CHTCA has issued and managed the certificate in
accordance with the Baseline Requirements and this CPS, CHTCA shall not
be liable to the subscribers or relying parties for any losses suffered
as a result of use or reliance on such certificate. Otherwise, CHTCA
will assume the compensation liability no more than the amount
stipulated in Section 9.9 of this CPS.

<a id="section-9-9"></a>
### 9.9 Indemnities

<a id="section-9-9-1"></a>
#### 9.9.1 Indemnification by CHTCA

If subscribers or relying parties suffer damages due to the intentional
or unintentional failure of CHTCA to follow the ePKI CP, this CPS,
relevant laws or the provisions of contracts signed between CHTCA and
subscribers/relying parties when processing subscriber
certificate-related work, CHTCA shall be held liable. Subscribers may
claim compensation for damages based on the related provisions of the
contract set down between CHTCA (or its RA) and subscribers. Relying
parties shall request compensation in accordance with laws and
regulations. The total compensation limit of CHTCA for each subscriber
or relying party is shown in the Table below. If the subscriber or
relying party has signed a contract with CHTCA, the certificate scope of
use and transaction compensation limit shall be determined separately.

| **Certificate Assurance Level** | **Compensation Limit (NTD)** |
|:-------------------------------:|:----------------------------:|
|             Level 1             |            3,000             |
|             Level 2             |           100,000            |
|             Level 3             |          3,000,000           |
|             Level 4             |          5,000,000           |

These compensation limits are the maximum compensation amounts. The
actual compensation amounts are based on the actual damages incurred by
the subscribers or relying parties.

<a id="section-9-9-2"></a>
#### 9.9.2 Indemnification by RA

If subscribers or relying parties suffer damages due to the RA
intentional or unintentional failure to follow this CPS, related laws or
the provisions of contracts signed between the RA and
subscribers/relying parties when processing subscriber certification
registrations, CHTCA is only responsible for compensation for the RA
established by CHTCA, and the compensation limits are detailed in
Section 9.9.1. For other RA not established by CHTCA, the RA takes the
responsible of compensation. If the RA and subscribers or relying
parties have a contract determing the usage of certificates and
transaction compensation amounts, then the contract takes precedence.
Compensation claims by subscribers shall be made in accordance with
related provisions in the contract set down with the RA. Compensation
claims by relying parties shall be made in accordance with relevant laws
and regulations.

<a id="section-9-10"></a>
### 9.10 Term and Termination

<a id="section-9-10-1"></a>
#### 9.10.1 Term

This CPS is effective when approved by the Electronic Signatures Act
competent authority and published to CHTCA’s repository.

<a id="section-9-10-2"></a>
#### 9.10.2 Termination

The new version of this CPS is announced after being approved by the
Electronic Signatures Act competent authority, and the current version
is terminated.

<a id="section-9-10-3"></a>
#### 9.10.3 Effect of Termination and Survival

The effect of this CPS remains valid until the expiration or revocation
of the last certificate issued according to this CPS.

<a id="section-9-11"></a>
### 9.11 Individual Notices and Communications with Participants

CHTCA, RAs, subscribers, relying parties shall adopt suitable methods
for establishing mutual notification and communication channels
including but not limited to official document, letter, telephone, fax,
email or secure email.

<a id="section-9-12"></a>
### 9.12 Amendments

<a id="section-9-12-1"></a>
#### 9.12.1 Procedure for Amendment

This CPS is reviewed annually, and an assessment is made to determine if
the CPS needs to be amended to maintain its assurance level. This CPS
shall be amended accordingly if the ePKI CP is amended or the OID is
changed, and if so, changes to this CPS are indicated by appropriate
numbering. The new version of this CPS will publish according to the
regulations stated in Section 2.3.

<a id="section-9-12-2"></a>
#### 9.12.2 Notification Mechanism and Period

CHTCA will post appropriate notice on its websites of any major or
significant changes to this CPS as well as any appropriate period by
when the revised CPS becomes effective. If subscribers or relying
parties have any comment on the change items, they can submit the
comment within the comment period. Reassess to the changes and response
may or may not be made by CHTCA according to these comments.

No further notice will be given in case of typesetting of this CPS.

<a id="section-9-12-3"></a>
#### 9.12.3 Circumstances under which OID Must Be Changed

If modifications to ePKI CP do not affect the stated certificate usage
purposes or assurance levels, the CP OID does not need to be changed.
However, if the CP OID is changed, changes shall be made to this CPS
accordingly.

<a id="section-9-13"></a>
### 9.13 Dispute Resolution Provisions

In the event of a dispute between subscribers/RA and CHTCA, the parties
shall resolve the dispute under the principle of good faith. In the
event of litigation, the parties agree that Taiwan Taipei District Court
shall be the court of first instance.

<a id="section-9-14"></a>
### 9.14 Governing Law

For disputes involving CHTCA issued certificates, the applicable ROC
laws shall govern.

<a id="section-9-15"></a>
### 9.15 Compliance with Applicable Law

Related ROC laws must be followed regarding the interpretation of any
agreement signed based on this CPS.

<a id="section-9-16"></a>
### 9.16 Miscellaneous Provisions

<a id="section-9-16-1"></a>
#### 9.16.1 Entire Agreement

The commitments set forth in this CPS constitute the entire agreement
between the participants (CHTCA, RAs, subscribers and relying parties).

<a id="section-9-16-2"></a>
#### 9.16.2 Assignment

The participants describe in this CPS may not assign or delegate their
rights or obligations under this CPS to other parties in any form
without prior notice to CHTCA.

<a id="section-9-16-3"></a>
#### 9.16.3 Severability

If any chapter of this CPS is held invalid or unenforceable by a
competent court or tribunal, the remainder of this CPS will remain valid
and enforceable.

<a id="section-9-16-4"></a>
#### 9.16.4 Enforcement (Attorney’s Fees and Waiver of Rights)

In the event that CHTCA suffers damages attributable to an intentional
or unintentional violation of this CPS by a subscriber or relying party,
CHTCA may seek compensation for damages and indemnification and
attorneys’ fees related to the dispute or litigation from the
responsible party.

CHTCA’s failure to assert rights with regard to the violation of this
CPS to the party does not waive CHTCA’s right to pursue the violation of
this CPS later or in the future.

<a id="section-9-16-5"></a>
#### 9.16.5 Force Majeure

CHTCA is not liable for any delay or failure to perform an obligation
under this CPS to the extent that the delay or failure is caused by a
force majeure or other circumstances not attributable to CHTCA,
including natural disasters, wars, or terrorism which may cause the
interruption of telecommunications network. CHTCA has set clear
limitations for certificate usage and is not bear any legal
responsibility for damages caused by exceeding these usage limitations.

<a id="section-9-17"></a>
### 9.17 Other Provisions

No stipulation.

<a id="appendix-1"></a>
## Appendix 1: Acronyms and Definitions

| **Acronyms** | **Full Name** | **Definition** |
|----|----|:---|
| AATL | Adobe Approved Trust Lis |  |
| AIA | Authority Information Access | See Appendix 2. |
| CA | Certification Authority | See Appendix 2. |
| CARL | Certification Authority Revocation List | See Appendix 2. |
| CP | Certificate Policy | See Appendix 2. |
| CPA | Chartered Professional Accountants Canada | See Appendix 2. |
| CP OID | CP Object Identifier |  |
| CPS | Certification Practice Statement | See Appendix 2. |
| CRL | Certificate Revocation List | See Appendix 2. |
| DN | Distinguished Name |  |
| DNS | Domain Name System | See Appendix 2. |
| eCA | ePKI Root Certification Authority | See Appendix 2. |
| EE | End Entities | See Appendix 2. |
| ePKI | Chunghwa Telecom ecommerce Public Key Infrastructure | See Appendix 2. |
| FIPS | (US Government) Federal Information Processing Standard | See Appendix 2. |
| FQDN | Fully Qualified Domain Name | See Appendix 2. |
| IANA | Internet Assigned Numbers Authority, IANA | See Appendix 2. |
| IETF | Internet Engineering Task Force | See Appendix 2. |
| NIST | (US Government) National Institute of Standards and Technology | See Appendix 2. |
| OCSP | Online Certificate Status Protocol | See Appendix 2. |
| OID | Object Identifier | See Appendix 2. |
| PIN | Personal Identification Number |  |
| PKCS | Public-Key Cryptography Standard | See Appendix 2. |
| PKI | Public Key Infrastructure | See Appendix 2. |
| QGIS | Qualified Government Information Source | See Appendix 2. |
| QTIS | Qualified Government Tax Information Source | See Appendix 2. |
| RA | Registration Authority | See Appendix 2. |
| RFC | Request for Comments | See Appendix 2. |
| TLS | Transport Layer Security | See Appendix 2. |
| UPS | Uninterrupted Power System | See Appendix 2. |

<a id="appendix-2"></a>
## Appendix 2: Glossary

<table>
<colgroup>
<col style="width: 28%" />
<col style="width: 71%" />
</colgroup>
<tbody>
<tr>
<td>Access </td>
<td style="text-align: left;">Use the information processing capabilities of system resources </td>
</tr>
<tr>
<td>Access Control </td>
<td style="text-align: left;">Authorization procedure for access to information system resources
given to subscribers, programs, procedures and other systems. </td>
</tr>
<tr>
<td>Activation Data </td>
<td style="text-align: left;">Private data, other than keys, that are required to access
cryptographic modules and that need to be protected (i.e., unlock
private keys for signing or decryption events). </td>
</tr>
<tr>
<td>Applicant </td>
<td style="text-align: left;">Subscribers who request certificates from a CA and have not yet
completed the certificate procedure. </td>
</tr>
<tr>
<td>Archive </td>
<td style="text-align: left;">A physically separate storage site for long-term information (storage
site for important information) which can be used to support audit,
usage and integrity services. </td>
</tr>
<tr>
<td>Assurance </td>
<td style="text-align: left;">A basis that the trusted entity has complied with certain security
requirements. [Article 2-1, Chapter 1, Regulations on Required
Information for Certification Practice Statements] </td>
</tr>
<tr>
<td>Assurance Level </td>
<td style="text-align: left;">A certain level in a relative assurance tier. [Article 2-2, Chapter
1, Regulations on Required Information for Certification Practice
Statements] </td>
</tr>
<tr>
<td>Audit </td>
<td style="text-align: left;">Assessment of whether system controls are adequate and ensure
conformance with existing policy and operation procedures, and
independent checking and review of recommended required improvements to
existing controls, policies and procedures. </td>
</tr>
<tr>
<td>Audit Data </td>
<td style="text-align: left;">Activity logs of a system organized in the order of time of
occurrence that can be used to reconstruct or investigate the time
sequence or changes that occurred during a certain event. </td>
</tr>
<tr>
<td>Authenticate </td>
<td style="text-align: left;"><ol type="1">
<li>Authentication is the process by which a claimed identity is
verified. [A Guide to Understanding Identification and Authentication in
Trusted Systems, National Computer Security Center]</li>
<li>Determination of identity authenticity when an identity of a
certain entity is shown.</li>
</ol></td>
</tr>
<tr>
<td>Authentication </td>
<td style="text-align: left;"><ol type="1">
<li>The process of establishing confidence in user identities
electronically presented to an information system. [NIST.SP.800-63-2
Electronic Authentication Guideline]</li>
<li>Safety measures used to secure data transmission or ways to
authorize the privilege of individuals upon receiving certain types of
information.</li>
<li>Authentication is the process by which a claimed identity is
verified. [A Guide to Understanding Identification and Authentication in
Trusted Systems]</li>
</ol>
<p>Mutual authentication means that the authentication is performed
between two parties during communication.</p></td>
</tr>
<tr>
<td>Authority Information Access (AIA) </td>
<td style="text-align: left;">Records extensions related to certificate authority information
access. The content may include: OCSP service sites and certificate
issuance authority certificate verification path downloading site. </td>
</tr>
<tr>
<td>Authorization Domain Name </td>
<td style="text-align: left;">The Domain Name used to obtain authorization for certificate issuance
for a given FQDN. The CA may use the FQDN returned from a DNS CNAME
lookup as the FQDN for the purposes of domain validation. If the FQDN
contains a wildcard character, then the CA MUST remove all wildcard
labels from the left most portion of requested FQDN. The CA may prune
zero or more labels from left to right until encountering a Base Domain
Name and may use any one of the intermediate values for the purpose of
domain validation. </td>
</tr>
<tr>
<td>Backup </td>
<td style="text-align: left;">Information or program copying that can be used for recovery purposes
when needed. </td>
</tr>
<tr>
<td>Base Domain Name </td>
<td style="text-align: left;">The portion of an applied-for FQDN that is the first domain name node
left of a registry controlled or public suffix plus the
registry-controlled or public suffix (e.g. "example.co.uk" or
"example.com"). For FQDNs where the right-most domain name node is a
gTLD having ICANN Specification 13 in its registry agreement, the gTLD
itself may be used as the Base Domain Name. </td>
</tr>
<tr>
<td>Baseline Requirements </td>
<td style="text-align: left;">“The Baseline Requirements for the Issuance and Management of
Publicly-Trusted Certificates” issued by CA/Browser Forum, and all the
amendments. </td>
</tr>
<tr>
<td>Binding </td>
<td style="text-align: left;">The process for binding (connecting) two related information
elements. </td>
</tr>
<tr>
<td>Biometric </td>
<td style="text-align: left;">The physical or behavioral attributes of a person. </td>
</tr>
<tr>
<td>CA Certificate </td>
<td style="text-align: left;">Certificates issued by CAs. </td>
</tr>
<tr>
<td>CA Key Pair </td>
<td style="text-align: left;">A Key Pair where the Public Key appears as the Subject Public Key
Info in one or more Root CA Certificate(s) and/or Subordinate CA
Certificate(s). </td>
</tr>
<tr>
<td>Certificate </td>
<td style="text-align: left;"><ol type="1">
<li>Refers to verification information carrying a digital signature
used to verify the identity and qualifications of the signer in
electronic form [Article 2-6, Electronic Signatures Act]</li>
<li>Digital presentation of information. The contents
include:</li>
<ol type="A">
<li>Issuing certificate authority</li>
<li>Subscriber name or identity</li>
<li>Subscriber public key</li>
<li>Certificate validity period</li>
<li>Certification authority digital signature</li>
</ol>
</ol>
The term ‘certificate’ referred to this CPS specifically refers to
ITU-T X.509 v.3 format certificates which states the certificate policy
object identifier in the ‘certificate policy’ field. </td>
</tr>
<tr>
<td>Certification Authority (CA) </td>
<td style="text-align: left;"><ol type="1">
<li>The agency or natural person that issues certificate [Article
2-5, Electronic Signatures Act]</li>
<li>The competent body trusted by the subscriber. Its functions are
the issuance and administration of ITU-T X.509 format public key
certificates, CARLs and CRLs.</li>
</ol></td>
</tr>
<tr>
<td>Certificate Policy (CP) </td>
<td style="text-align: left;"><ol type="1">
<li>Refers to a named set of rules that indicates the applicability
to a certain community or class of application with common security
requirements [Article 2-3, Chapter 1, Regulations on Required
Information for Certification Practice Statements]</li>
<li>Certificate policy refers to the dedicated profile administration
policy established for the electronic transactions performed through
certificate administration. Certificate policy covers a variety of
issues including the formation, generation, delivery, auditing,
administration and restoration after compromise. Certificate policy
indirectly controls the use and operation of certificate security
systems to protect the transactions performed by the communication
systems. The security services required for certain application are
provided through control of the certificate extension methods,
certificate policy and related technology.</li>
</ol></td>
</tr>
<tr>
<td>Certification Practice Statement (CPS) </td>
<td style="text-align: left;"><ol type="1">
<li>External notification by the certificate authority used to
describe the practice statement of the certificate authority governing
certificate issuance and processing of other certification work.
[Article 2-7, Electronic Signatures Act]</li>
<li>Announcement of a statement that certain procedures of the
certificate authority for certificate work (including issuance,
suspension, revocation, renewal and access) comply with certain
requirements (listed in the certificate policy or other service
contracts).</li>
</ol></td>
</tr>
<tr>
<td>Certificate Profile </td>
<td style="text-align: left;">A set of documents or files that defines
requirements for Certificate content and Certificate extensions in
accordance with Section 7 of the Baseline Requirements. e.g. a Section
in a CA’s CPS or a certificate template file used by CA software.</td>
</tr>
<tr>
<td nowrap>Certificate Problem Reports </td>
<td style="text-align: left;">The complaints regarding suspected cracking of keys, certificate
misused, or other types of fraud, cracks, abuse, or inappropriate
behaviors related to certificates. </td>
</tr>
<tr>
<td>Certificate Renewal </td>
<td style="text-align: left;">The procedure for issuing a new certificate to renew the validity of
information bound together with the public key. </td>
</tr>
<tr>
<td>Certificate Revocation </td>
<td style="text-align: left;">Termination of a certificate prior to its expiry date. </td>
</tr>
<tr>
<td>Certificate Revocation List (CRL) </td>
<td style="text-align: left;"><ol type="1">
<li>The certificate revocation list digitally signed by the
certification authority provided for relying party use. [Article 2-8,
Chapter 1, Regulations on Required Information for Certification
Practice Statements]</li>
<li>List maintained by the certificate authority. The expiry dates of
the above revoked certificates issued by the certification authority are
recorded on the list.</li>
</ol></td>
</tr>
<tr>
<td>Chartered Professional Accountants Canada (CPA) </td>
<td style="text-align: left;">Institution which jointly drafted The Trust Services Principles and
Criteria for Security, Availability, Processing Integrity,
Confidentiality and Privacy system standards with the American Institute
of Certified Public Accountants (AICPA) and the management organization
for WebTrust for CA and SSL Baseline Requirement &amp; Network Security
mark. Canadian Institute of Chartered Accountants is abbreviated as
CICA. </td>
</tr>
<tr>
<td style="text-align: left;">Compromise </td>
<td style="text-align: left;">Information disclosed to unauthorized persons or unauthorized
intentional or unintentional disclosure, modification, destruction or
loss of objects which constitutes a violation of information security
policy. </td>
</tr>
<tr>
<td>Confidentiality </td>
<td style="text-align: left;">Information which will not be known or be accessed by unauthorized
entities or programs. </td>
</tr>
<tr>
<td>Cross-Certificate </td>
<td style="text-align: left;">A certificate used to establish a trust relationship between two root
CA. This certificate is a type of CA certificate and not a subscriber
certificate. </td>
</tr>
<tr>
<td>Cryptographic Module </td>
<td style="text-align: left;">A set of hardware, software, firmware or combination of the above
used to run cryptologic or programs (including crypto algorithms) and
included within the cryptographic boundaries of the module. </td>
</tr>
<tr>
<td style="text-align: left;">Data Integrity </td>
<td style="text-align: left;">Information that has been subjected to unauthorized access or
accidental modification, damage or loss. </td>
</tr>
<tr>
<td>Digital Signature </td>
<td style="text-align: left;">An electronic signature generated by use of mathematic algorithm or
other means to create a certain length of digital data encrypted by the
signatory’s private key and capable of being verified by the public key.
[Article 2-3, Electronic Signatures Act] </td>
</tr>
<tr>
<td>Domain Contact </td>
<td style="text-align: left;">The Domain Name Registrant, technical contact, or administrative
contract (or the equivalent under a ccTLD) as listed in the WHOIS record
of the Base Domain Name or in a DNS SOA record. </td>
</tr>
<tr>
<td>Domain Name </td>
<td style="text-align: left;">A node label assigned by the domain name system. Converts the IP
address into a text name that is easily remembered by humans. </td>
</tr>
<tr>
<td>Domain Name Registrant </td>
<td style="text-align: left;">Sometimes referred to as the domain name owner, but it is more
appropriate to say a certain individual or entity who have registered
with the Domain Name Registrar to have the right to use a domain name
and the Domain Name Registrant or WHOIS has listed the ‘registrant’ as a
natural person or legal person. </td>
</tr>
<tr>
<td nowrap>Domain Name Registrar </td>
<td style="text-align: left;">A person or entity that registers Domain Names under the auspices of
or by agreement with: (i) the Internet Corporation for Assigned Names
and Numbers (ICANN), (ii) a national Domain Name authority/registry, or
(iii) a Network Information Center (including their affiliates,
contractors, delegates, successors, or assigns). </td>
</tr>
<tr>
<td>Domain Name System (DNS) </td>
<td style="text-align: left;">A distributed database used to automatically convert the IP address
to domain name. </td>
</tr>
<tr>
<td style="text-align: left;">Duration </td>
<td style="text-align: left;">A certificate field made up of two subfields “start time of the
validity period” (notBefore) and “end time of the validity period”
(notAfter). </td>
</tr>
<tr>
<td>E-commerce </td>
<td style="text-align: left;">Provision of goods for sale and other services through the use of
network technology (specifically the Internet). </td>
</tr>
<tr>
<td style="text-align: left;">End Entity </td>
<td style="text-align: left;">The PKI includes the following two types of entities: 
<ol type="1">
<li>Those responsible for the safeguarding and use of certificate
public keys.</li>
<li>Third parties who trust the certificates issued by the PKI (not
holders of private keys and not a certificate authority). The end
entities are subscribers and relying parties including personnel,
organizations, accounts, devices and sites.</li>
</ol></td>
</tr>
<tr>
<td nowrap>End-Entity Certificate </td>
<td style="text-align: left;">Certificates issued to end-entities. </td>
</tr>
<tr>
<td>Chunghwa Telecom ecommerce Public Key Infrastructure (ePKI) </td>
<td style="text-align: left;">A hierarchical PKI established by CHT in compliance with ITU-T X.509
to promote electronic services. It can be used within various
applications in e-commerce and e-government. </td>
</tr>
<tr>
<td>Chunghwa Telecom Certificate Policy Management Authority (PMA) </td>
<td style="text-align: left;">An organization which was established for electronic certificate
management matters, such as (i) discussion and review of the CP and the
electronic certificate framework of the PKI owned by CHT and (ii) review
of interoperation requests submitted by subordinate CAs and
cross-certified CAs and that of CPS. </td>
</tr>
<tr>
<td>ePKI Root CA (eCA) </td>
<td style="text-align: left;">The Root CA and top-level CA in ePKI, and its public key is the trust
anchor of ePKI. </td>
</tr>
<tr>
<td>Federal Information Processing Standard (FIPS) </td>
<td style="text-align: left;">Except for military organizations in the US Federal Government
System, information processing standard for all government organizations
and government subcontractors. The security requirement standard for the
cryptographic module is FIPS no. 140 standard (FIPS 140). FIPS 140-2
divides the cryptographic module into 11 types of security requirements.
Each security requirement type is then divided into 4 security
levels. </td>
</tr>
<tr>
<td>Firewall </td>
<td style="text-align: left;">An access restriction gateway between networks which complies with
near-end (local area) security policy. </td>
</tr>
<tr>
<td>Fully Qualified Domain Name (FQDN) </td>
<td style="text-align: left;">An unambiguous domain name that specifies the exact location of a
computer within the domain’s hierarchy. The fully qualified domain name
consists of two parts: the host name (service name) and domain name. For
example, ourserver.ourdomain.com.tw, ourserver is the host name and
ourdomain.com.tw is the domain name. In this name, ourdomain is the
third-level domain, com is the second-level domain name and tw is the
country code top-level domain (ccTLD). A fully qualified domain name
always starts with a host name.</p>
<p>For example, www.ourdomain.com，www is the host name. Ourdomain is
the the second-level domain name. com is Generic Top-Level Domain,
gTLD. </td>
</tr>
<tr>
<td>Identification </td>
<td style="text-align: left;">A statement of who the user is. [A Guide to Understanding
Identification and Authentication in Trusted Systems]</p>
<p>A way that can be used to describe or claim the identity of an
individual or entity, e.g., user account, name or email. </td>
</tr>
<tr>
<td>Integrity </td>
<td style="text-align: left;">Protecting information so that it is not subject to unauthorized
modification or damage. Preserve information in an untampered state
during transmission and storage following generation at its source until
receipt by the final recipient. </td>
</tr>
<tr>
<td>Internet Assigned Numbers Authority (IANA) </td>
<td style="text-align: left;">An organization that oversees the allocation of global IP address,
domain names and many other parameters used for Internet. </td>
</tr>
<tr>
<td>Internet Engineering Task Force (IETF) </td>
<td style="text-align: left;">Responsible for the development and promotion of Internet standards.
Official website is at: https://www.ietf.org/. Its vision is the
generation of high quality technical documents affects how man designs,
uses and manages the Internet and allows the Internet to operate
smoothly. </td>
</tr>
<tr>
<td>Issuing CA </td>
<td style="text-align: left;">For a particular certificate, the CA that issues the certificate is
the issuing CA. </td>
</tr>
<tr>
<td>Key Escrow </td>
<td style="text-align: left;">Storage of related information using the subscriber’s private key and
according to the terms of the mandatory subscriber escrow agreement (or
similar contract). The terms of this escrow agreement requires that one
or more than one agencies have possession of the subscriber key provided
it is beneficial to the subscriber, employer or another party in
accordance with the provisions of the agreement. </td>
</tr>
<tr>
<td>Key Exchange </td>
<td style="text-align: left;">Mutual exchange of keys to establish a secure communication
processing procedure. </td>
</tr>
<tr>
<td>Key Pair </td>
<td style="text-align: left;">Two mathematically related keys having the following properties: 
<ol type="1">
<li>One (public) key can be used to encrypt a message that can only
be decrypted by using the other (private) key, and</li>
<li>It is computationally infeasible to determine one key from
another.</li>
</ol></td>
</tr>
<tr>
<td style="text-align: left;">Non-Repudiation </td>
<td style="text-align: left;">Provide proof of delivery to the information sender and proof of
sender identity to the receiver so neither party may repudiate the
processing of this information after the fact. Technically speaking,
non-repudiation refers to the guarantee that this signature must be
signed by the corresponding private key if a certain public key can be
used to verify a certain digital signature for a trusted party. Legally
speaking, non-repudiation refers to the establishment of a possession
and control system for private signature keys. </td>
</tr>
<tr>
<td>Object Identifier (OID) </td>
<td style="text-align: left;"><ol type="1">
<li>One type of unique alphanumeric / numeric identified registered
under the International Standard Organization registration standard
which could be used to identify the uniquely corresponding certificate
policy; where the certificate policy is modified, the OID is not changed
accordingly. [Article 2-4, Chapter 1, Regulations on Required
Information for Certification Practice Statements]</li>
<li>When a special form of code, object or object type is registered
with the International Standard Organization (ISO), the unique code may
be used as an identified. For example, this code can be used in the
public key infrastructure to indicate what certificate policy and
cryptographic algorithms are used.</li>
</ol></td>
</tr>
<tr>
<td>Online Certificate Status Protocol (OCSP) </td>
<td style="text-align: left;">The Online Certificate Status Protocol is a type of online
certificate checking protocol which lets the application software of
relying parties to determine the status (such as revoked or valid) of a
certain certificate. </td>
</tr>
<tr>
<td>OCSP Responder </td>
<td style="text-align: left;">The online server that is authorized, maintained, and operated by the
CA, and connects to the repository to process the certificate status
request. </td>
</tr>
<tr>
<td>Out-of-Band </td>
<td style="text-align: left;">Delivery method other than ordinary information delivery channels. If
the delivery method is by electric cable, a special secure channel may
be the use of physical registered mail. </td>
</tr>
<tr>
<td>Private Key </td>
<td style="text-align: left;"><ol type="1">
<li>The key in the signature key pair used to generate digital
signatures.</li>
<li>The key in the encryption key pair used to decrypt secret
information.</li>
</ol>
This key must be kept secret under these two circumstances. </td>
</tr>
<tr>
<td>Public Key </td>
<td style="text-align: left;"><ol type="1">
<li>The key in the signature key pair used to verify the validity of
the digital signature.</li>
<li>The key in the encryption key pair used for encrypting secret
information.</li>
</ol>
These keys must be made public (usually in a digital certificate
form) under these two circumstances. </td>
</tr>
<tr>
<td>Public-Key Cryptography Standard (PKCS) </td>
<td style="text-align: left;">In order to promote the use of public key technology, the RSA
laboratory under the RSA Information Security Company has developed a
series of public key cryptography standards that are widely used by the
industry. </td>
</tr>
<tr>
<td>Public Key Infrastructure (PKI) </td>
<td style="text-align: left;">A set of law, policy, standards, personnel, equipment, facilities,
technology, processes, audits and services developed on a broad scale
and management of asymmetric cryptography and public key
certificates. </td>
</tr>
<tr>
<td>Qualified Auditor </td>
<td style="text-align: left;">Accountant firms, entities, or individuals that satisfy the auditor
qualification requirements specified in Section 8.2 of the Baseline
Requirements, as well as independent from the audited parties. </td>
</tr>
<tr>
<td>Qualified Government Information Source (QGIS) </td>
<td style="text-align: left;">A regularly-updated and current, publicly available, database
designed for the purpose of accurately providing the information for
which it is consulted, and which is generally recognized as a dependable
source of such information provided that it is maintained by a
Government Entity, such as Ministry of Economic Affairs Bussiness &amp;
Factory Registration Database, the reporting of data is required by law,
and false or misleading reporting is punishable with criminal or civil
penalties.</p>
<p>Nothing in the EV SSL Certificate Guidelines shall prohibit the use
of third-party vendors to obtain the information from the Government
Entity provided that the third party obtains the information directly
from the Government Entity. </td>
</tr>
<tr>
<td>Qualified Government Tax Information Source (QTIS) </td>
<td style="text-align: left;">A Qualified Governmental Information Source that specifically
contains tax information relating to Private Organizations, Business
Entities, or Individuals. Such as Fiscal Information Agency, Ministry of
Finance in Taiwan and IFS in USA. </td>
</tr>
<tr>
<td>Random Value </td>
<td style="text-align: left;">A value specified by a CA to the Applicant that exhibits at least 112
bits of entropy. </td>
</tr>
<tr>
<td>Registration Authority (RA) </td>
<td style="text-align: left;"><ol type="1">
<li>Responsible for checking the identity and other attributes of the
certificate applicant but does not issue or administer certificates. The
nature and scope of obligations borne by the registration authority are
set down in the applicable certificate policy or agreement.</li>
<li>An entity responsible for the identity identification and
authentication of the certificate subject which does not issue
certificates.</li>
</ol></td>
</tr>
<tr>
<td>Re-key </td>
<td style="text-align: left;">Changing the key values used in the cryptographic system application
program. It is commonly achieved by issuing a new certificate for the
new public key. </td>
</tr>
<tr>
<td>Relying Party </td>
<td style="text-align: left;"><ol type="1">
<li>Recipient of a certificate who acts in reliance of that
certificate or a digital signature to verify the public key listed in
the certificate, or the counterpart to identify (or its attributes) of
the subject named in a trusted certificate and public key listed in the
certificate. [Article 2-6, Chapter 1, Regulations on Required
Information for Certification Practice Statements]</li>
<li>The individual or agency which receives information including a
certificate and digital signature (the public key listed on the
certificate may be used to verify the digital signature) and may rely on
this information.</li>
</ol></td>
</tr>
<tr>
<td>Repository </td>
<td style="text-align: left;"><ol type="1">
<li>A system for storing and retrieving certificates or other
information relevant to certificates. [Article 2-7, Chapter 1,
Regulations on Required Information for Certificate Practice
Statements]</li>
<li>A database that contains information and data relating to
certificates as specified in the CP/CPS.</li>
</ol></td>
</tr>
<tr>
<td>Request Token </td>
<td style="text-align: left;">A value derived in a method specified by the CA which binds this
demonstration of control to the certificate request.</p>
<p>The Request Token SHALL incorporate the key used in the certificate
request.</p>
<p>A Request Token MAY include a timestamp to indicate when it was
created.</p>
<p>A Request Token MAY include other information to ensure its
uniqueness.</p>
<p>A Request Token that includes a timestamp SHALL remain valid for no
more than 30 days from the time of creation.</p>
<p>A Request Token that includes a timestamp SHALL be treated as invalid
if its timestamp is in the future.</p>
<p>A Request Token that does not include a timestamp is valid for a
single use and the CA SHALL NOT re-use it for a subsequent
validation.</p>
<p>The binding SHALL use a digital signature algorithm or a
cryptographic hash algorithm at least as strong as that to be used in
signing the certificate request. </td>
</tr>
<tr>
<td>Required Website Content </td>
<td style="text-align: left;">Either a Random Value or a Request Token, together with additional
information that uniquely identifies the Subscriber, as specified by the
CA. </td>
</tr>
<tr>
<td>Reserved IP Addresses </td>
<td style="text-align: left;">IPv4 and IPv6 addresses reserved in the IANA setting. See:</br>
http://www.iana.org/assignments/ipv4-address-space/ipv4-address-space.xml</br>
and </br>
http://www.iana.org/assignments/ipv6-address-space/ipv6-address-space.xml</br></td>
</tr>
<tr>
<td>Request for Comments (RFC) </td>
<td style="text-align: left;">A series of memos issued by the Internet Engineer Task Force that
include Internet, UNIX and Internet community standards, protocols and
procedures for number assignment. </td>
</tr>
<tr>
<td>Secure Sockets Layer </td>
<td style="text-align: left;">Protocol issued by Netscape through introduction of their web browser
which can encrypt network communication in the transport layer and
ensure the integrity of transmitted information and perform identity
authentication on the server and client.</p>
<p>The advantage of the secure socket layer protocol is it is
independent and separate from the application layer protocol. High level
application layer protocol (such as: HTTP, FTP and Telnet) may be
established on top of SSL. The SSL protocol completes encryption
algorithm, communication secret key agreement and server authentication
work before the application layer protocol communication. This protocol
is a successor to the Transport Layer Security (TLS) protocol. </td>
</tr>
<tr>
<td>Signature Certificate </td>
<td style="text-align: left;">Public key certificates which contains a digital signature public key
used for verification purposes (not used for data encryption or other
cryptographic uses). </td>
</tr>
<tr>
<td style="text-align: left;">Subordinate CA </td>
<td style="text-align: left;">In a hierarchical PKI, a CA whose certificate signature key is
certified by another CA, and whose activities are constrained by that
other CA. </td>
</tr>
<tr>
<td>Subscriber </td>
<td style="text-align: left;">An entity that 
<ol type="1">
<li>is the subject named or identified in a certificate issued to
that entity,</li>
<li>holds a private key that corresponds to the public key listed in
the certificate, and</li>
<li>does not itself issue certificates to another party.</li>
</ol>
This includes, but is not limited to, an individual, an organization,
an application or network device. </td>
</tr>
<tr>
<td>Technical Non-Repudiation </td>
<td style="text-align: left;">Technical evidence provided by the public key system to support
non-repudiation security service. </td>
</tr>
<tr>
<td>Threat </td>
<td style="text-align: left;">Any status or event which may cause damage (including destruction,
disclosure, malicious tampering or denial of service) to information
systems. Can be divided into internal threats and outside threats.
Internal threats are use of authorization to employ information
destruction, disclosure, tampering or denial of service methods to
damage the information system. Outside threats are an outside
unauthorized entity which has the potential to damage the information
system (including information destruction, tampering, disclosure and
interruption of service). </td>
</tr>
<tr>
<td>Time-stamp </td>
<td style="text-align: left;">A digitally signed assertion by a trusted authority that a specific
digital object existed at a certain time. </td>
</tr>
<tr>
<td>Transport Layer Security (TLS) </td>
<td style="text-align: left;">TLS 1.0 was first defined in RFC 2246 by the IETF based on the SSL
3.0 and updated in RFC 5246 and RFC 6176 as TLS 1.2. The current version
is TLS 1.3 defined in RFC 8446 by the IETF in 2018. </td>
</tr>
<tr>
<td>Trust List </td>
<td style="text-align: left;">List of trusted certificates used by relying parties to authenticate
certificates. </td>
</tr>
<tr>
<td>Trusted Certificate </td>
<td style="text-align: left;">Certificate trusted by relying party obtained through a secure and
reliable transmission method. The public key contained in this type of
certificate comes from a trusted path. Also called a trust anchor. </td>
</tr>
<tr>
<td>Trustworthy System </td>
<td style="text-align: left;">Computer hardware, software and programs which possess the following
attributes: 
<ol type="1">
<li>Functions that protect again intrusion and misuse.</li>
<li>Provides reasonably accessible, reliable and accurate
operations.</li>
<li>Appropriate implementation of preset function.</li>
<li>Security procedures uniformly accepted by the general
public.</li>
</ol></td>
</tr>
<tr>
<td>Uninterrupted Power System (UPS) </td>
<td style="text-align: left;">Provide uninterrupted backup power to loading equipment in the event
of abnormal power conditions (such as power outage, interference or
power surge) to allow uninterrupted operation of servers, switches and
other critical equipment and precision instruments to prevent loss of
calculation data, communication network interruption and loss of
instrument control. </td>
</tr>
<tr>
<td>Validation </td>
<td style="text-align: left;">The process of identification of certificate applicants. Validation
is a subset of identification and refers to identification in the
context of establishment of the identity of certificate applicants. [RFC
3647] </td>
</tr>
<tr>
<td>WHOIS </td>
<td style="text-align: left;">Information retrieved directly from the Domain Name Registrar or
registry operator via the protocol defined in RFC 3912, the Registry
Data Access Protocol defined in RFC 7482, or an HTTPS website. </td>
</tr>
<tr>
<td>Zeroize </td>
<td style="text-align: left;">Method to delete electronically stored information. Storage of
changed information to prevent information recovery. </td>
</tr>
</tbody>
</table>

<a id="appendix-3"></a>
## Appendix 3: Certificate Extensions

The extensions and their contents of the certificates issued by CHTCA
comply with the relevant requirements specified in ITU-T X.509 and RFC
5280.

CHTCA shall not issue a certificate with:

1)  Extensions that do not apply in the context of the public internet;
    and

2)  Semantics that will mislead a relying party about the certificate
    information verified by CHTCA.

<a id="appendix-3-1"></a>
## Appendix 3-1: CA Certificates

CA certificates issued by CHTCA include the self-signed certificate and
self-issued certificate of root CA, subordinate CA certificate and
cross-certificate. The certificate extensions are described below. Other
optional extensions may be used as applicable, and the methods comply
with the regulations in Appendix 3.

1)  Self-signed Certificate

    <table>
    <colgroup>
    <col style="width: 26%" />
    <col style="width: 15%" />
    <col style="width: 14%" />
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
    <td align="center">OPTIONAL</td>
    <td align="center">N</td>
    <td style="text-align: left;">If present, only the keyIdentifier field
    is present in this extension, and its value must be identical to the
    subjectKeyIdentifier extension.</td>
    </tr>
    <tr>
    <td style="text-align: left;">Subject Key Identifier</td>
    <td align="center">MUST</td>
    <td align="center">N</td>
    <td style="text-align: left;">The 160-bit SHA-1 hash value of the root
    CA’s public key.</td>
    </tr>
    <tr>
    <td style="text-align: left;" nowrap>Basic Constraints</td>
    <td align="center">MUST</td>
    <td align="center">Y</td>
    <td style="text-align: left;"><p>Subject Type=CA</p>
    <p>Path Length Constraint=None</p></td>
    </tr>
    <tr>
    <td style="text-align: left;">Key Usage</td>
    <td align="center">MUST</td>
    <td align="center">Y</td>
    <td style="text-align: left;"><p>Bits contained in this extension are as
    follows:</p>
    <ul>
    <li>keyCertSign (required)</li>
    <li>cRLSign (required)</li>
    <li>digitalSignature (optional)</li>
    </ul></td>
    </tr>
    </tbody>
    </table>

2)  Self-issued Certificate

    <table>
    <colgroup>
    <col style="width: 26%" />
    <col style="width: 15%" />
    <col style="width: 14%" />
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
    <td style="text-align: left;">This extension contains only the keyIdentifier field, which is the 160-bit 
      SHA-1 hash of the public key of the new (old) root CA. Its value must be identical to the value contained in the subjectKeyIdentifier 
      extension of the self-signed certificate issued by the new (old) root CA.</td>
    </tr>
    <tr>
    <td style="text-align: left;">Subject Key Identifier</td>
    <td align="center">MUST</td>
    <td align="center">N</td>
    <td style="text-align: left;">The 160-bit SHA-1 hash value of the old
    (new) root CA’s public key.</td>
    </tr>
    <tr>
    <td style="text-align: left;">CRL Distribution Points</td>
    <td align="center">MUST</td>
    <td align="center">N</td>
    <td style="text-align: left;">The HTTP URL of the new (old) root CA’s
    CRL service.</td>
    </tr>
    <tr>
    <td style="text-align: left;">Authority Information Access</td>
    <td align="center">MUST</td>
    <td align="center">N</td>
    <td style="text-align: left;"><p>This extension shall contain at least
    one of the following:</p>
    <ul>
    <li>The HTTP URL of the new (old) root CA’s self-signed certificate
    (optional)</li>
    <li>The HTTP URL of the new (old) root CA’s OCSP responder
    (optional)</li>
    </ul></td>
    </tr>
    <tr>
    <td style="text-align: left;">Certificate Policies</td>
    <td align="center">MUST</td>
    <td align="center">N</td>
    <td style="text-align: left;">This extension shall contain all CP OIDs
    defined in the ePKI CP, as specified in Section 1.2 of the ePKI CP. The
    policy qualifier field in this extension may be used as needed. When
    using this field, it may contain a CPS pointer qualifier that points to
    this CPS</td>
    </tr>
    <tr>
    <td style="text-align: left;">Key Usage</td>
    <td align="center">MUST</td>
    <td align="center">Y</td>
    <td style="text-align: left;">The content in this extension shall be
    identical to the content of the key usage extension in the old (new)
    root CA’s self-signed certificate.</td>
    </tr>
    <tr>
    <td style="text-align: left;" nowrap>Basic Constraints</td>
    <td align="center">MUST</td>
    <td align="center">Y</td>
    <td style="text-align: left;"><p>Subject Type=CA</p>
    <p>Path Length Constraint=None</p></td>
    </tr>
    </tbody>
    </table>

3)  Subordinate CA Certificate

    <table>
    <colgroup>
    <col style="width: 26%" />
    <col style="width: 15%" />
    <col style="width: 14%" />
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
    <td style="text-align: left;">This extension contains only the keyIdentifier field, which is the 160-bit 
      SHA-1 hash of the root CA's public key. Its value must be identical to the value contained in the subjectKeyIdentifier extension of 
      the self-signed certificate issued by the root CA.</td>
    </tr>
    <tr>
    <td style="text-align: left;">Subject Key Identifier</td>
    <td align="center">MUST</td>
    <td align="center">N</td>
    <td style="text-align: left;">The 160-bit SHA-1 hash value of the
    subordinate CA’s public key.</td>
    </tr>
    <tr>
    <td style="text-align: left;">CRL Distribution Points</td>
    <td align="center">MUST</td>
    <td align="center">N</td>
    <td style="text-align: left;">The HTTP URL of the root CA’s CRL
    service.</td>
    </tr>
    <tr>
    <td style="text-align: left;">Authority Information Access</td>
    <td align="center">MUST</td>
    <td align="center">N</td>
    <td style="text-align: left;"><p>This extension shall contain at least
    one of the following:</p>
    <ul>
    <li>The HTTP URL of the root CA’s self-signed certificate
    (optional)</li>
    <li>The HTTP URL of the root CA’s OCSP responder (optional)</li>
    </ul></td>
    </tr>
    <tr>
    <td style="text-align: left;">Certificate Policies</td>
    <td align="center">MUST</td>
    <td align="center">N</td>
    <td style="text-align: left;">This extension is used to indicate the CP
    OIDs, as specified in Section 1.2 of the ePKI CP, that are approved by
    the Root CA for use by the subordinate CA. The policy qualifier field in
    this extension may be used as needed. When using this field, it may
    contain a CPS pointer qualifier that points to this CPS.</td>
    </tr>
    <tr>
    <td style="text-align: left;">Extended Key Usage (EKU)</td>
    <td align="center">MUST</td>
    <td align="center">N</td>
    <td style="text-align: left;"><p>This extension specifies the extended
    key usages intended for use by the subordinate CA. The rules that must
    be followed are as follows:</p>
    <ul>
    <li>If subordinate CA certificate will be used to issue time-stamp
    certificates, the following requirements shall be met in this
    extension:</p>
    <ul>
    <li>The value id-kp-timeStamping must be present.</li>
    <li>The value id-kp-serverAuth must not be present.</li>
    </ul>
    </li>
    <li>If subordinate CA certificate will not be used to issue
    time-stamp certificates, the following requirements shall be met in this
    extension:</p>
    <ul>
    <li>The value id-kp-serverAuth must not be present.</li>
    <li>Other values may be present, but should not combine multiple
    independent key purposes (e.g. including id-kp-timeStamping with
    id-kp-codeSigning)</li>
    </ul></li></ul></td>
    </tr>
    <tr>
    <td style="text-align: left;">Key Usage</td>
    <td align="center">MUST</td>
    <td align="center">Y</td>
    <td style="text-align: left;"><p>Bits contained in this extension are as
    follows:</p>
    <ul>
    <li>keyCertSign (required)</li>
    <li>cRLSign (required)</li>
    <li>digitalSignature (optional)</li>
    </ul></td>
    </tr>
    <tr>
    <td style="text-align: left;" nowrap>Basic Constraints</td>
    <td align="center">MUST</td>
    <td align="center">Y</td>
    <td style="text-align: left;"><p>Subject Type=CA</p>
    <p>Path Length Constraint=0</p></td>
    </tr>
    </tbody>
    </table>

4)  Cross-Certificate

    The subject of a cross-certificate shall be the root CA of a public key
    infrastructure external to the ePKI, and this root CA shall not directly
    issue subscriber certificates
    
    <table>
    <colgroup>
    <col style="width: 26%" />
    <col style="width: 15%" />
    <col style="width: 14%" />
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
    <td style="text-align: left;">This extension contains only the keyIdentifier field, which is the 160-bit 
      SHA-1 hash of the root CA's public key. Its value must be identical to the value contained in the subjectKeyIdentifier extension of the 
      self-signed certificate issued by the root CA.</td>
    </tr>
    <tr>
    <td style="text-align: left;">Subject Key Identifier</td>
    <td align="center">MUST</td>
    <td align="center">N</td>
    <td style="text-align: left;">The 160-bit SHA-1 hash value of the
    cross-certified CA’s public key.</td>
    </tr>
    <tr>
    <td style="text-align: left;">CRL Distribution Points</td>
    <td align="center">MUST</td>
    <td align="center">N</td>
    <td style="text-align: left;">The HTTP URL of the root CA’s CRL
    service.</td>
    </tr>
    <tr>
    <td style="text-align: left;">Authority Information Access</td>
    <td align="center">MUST</td>
    <td align="center">N</td>
    <td style="text-align: left;"><p>This extension shall contain at least
    one of the following:</p>
    <ul>
    <li>The HTTP URL of the root CA’s self-signed certificate
    (optional)</li>
    <li>The HTTP URL of the root CA’s OCSP responder (optional)</li>
    </ul></td>
    </tr>
    <tr>
    <td style="text-align: left;">Certificate Policies</td>
    <td align="center">MUST</td>
    <td align="center">N</td>
    <td style="text-align: left;">This extension is used to indicate the CP
    OIDs, as specified in Section 1.2 of the ePKI CP, that are approved by
    the Root CA for use by the cross-certified CA. The policy qualifier
    field in this extension may be used as needed. When using this field, it
    may contain a CPS pointer qualifier that points to this CPS.</td>
    </tr>
    <tr>
    <td style="text-align: left;">Policy Mappings</td>
    <td align="center">OPTIONAL</td>
    <td align="center">N</td>
    <td style="text-align: left;">This extension is used to indicate the
    correspondences between the certificate policies of the cross-certified
    CA and the ones of the root CA. It lists one or more pairs of CP OIDs.
    The pairing indicates the root CA considers its CP OID equivalent to the
    cross-certified CA’s CP OID.</td>
    </tr>
    <tr>
    <td style="text-align: left;">Key Usage</td>
    <td align="center">MUST</td>
    <td align="center">Y</td>
    <td style="text-align: left;"><p>Bits contained in this extension are as
    follows:</p>
    <ul>
    <li>keyCertSign (required)</li>
    <li>cRLSign (required)</li>
    <li>digitalSignature (optional)</li>
    </ul></td>
    </tr>
    <tr>
    <td style="text-align: left;" nowrap>Basic Constraints</td>
    <td align="center">MUST</td>
    <td align="center">Y</td>
    <td style="text-align: left;"><p>Subject Type=CA</p>
    <p>Path Length Constraint= Set according to the needed certificate path
    length of the cross-certified CA. It may not be present as
    well.</p></td>
    </tr>
    </tbody>
    </table>

#

<a id="appendix-3-2"></a>
## Appendix 3-2: Subscriber Certificates

For subscriber certificates issued by subordinate CAs of CHTCA, the
certificate extensions are described as follows according to the
certificate type. The usage of extensions not mentioned in this appendix
shall be handled in accordance with the provisions of Appendix 3.

1)  Time-stamp Certificate

    <table>
    <colgroup>
    <col style="width: 26%" />
    <col style="width: 15%" />
    <col style="width: 14%" />
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
    <td style="text-align: left;" nowrap>Certificate Policies</td>
    <td align="center">MUST</td>
    <td align="center">N</td>
    <td style="text-align: left;">The policy qualifier field in this
    extension may be used as needed. When using this field, it may contain a
    CPS pointer qualifier that points to this CPS.</td>
    </tr>
    <tr>
    <td style="text-align: left;">CRL Distribution Points</td>
    <td align="center">MUST</td>
    <td align="center">N</td>
    <td style="text-align: left;">The HTTP URL of the subordinate CA’s CRL
    service.</td>
    </tr>
    <tr>
    <td style="text-align: left;">Authority Information Access</td>
    <td align="center">MUST</td>
    <td align="center">N</td>
    <td style="text-align: left;"><p>The information included in this
    extension are as follows:</p>
    <ul>
    <li>The HTTP URL of the subordinate CA’s OCSP responder
    (optional)</li>
    <li>The HTTP URL of the subordinate CA’s certificate
    (required)</li>
    </ul></td>
    </tr>
    <tr>
    <td style="text-align: left;" nowrap>Basic Constraints</td>
    <td align="center">OPTIONAL</td>
    <td align="center">N</td>
    <td style="text-align: left;"><p>Subject Type=EE</p>
    <p>Path Length Constraint= None</p></td>
    </tr>
    <tr>
    <td style="text-align: left;">Key Usage</td>
    <td align="center">OPTIONAL</td>
    <td align="center">Y</td>
    <td style="text-align: left;">Bit positions for keyCertSign and cRLSign
    must not be set, but the digitalSignature and contentCommitment may be
    set.</td>
    </tr>
    <tr>
    <td style="text-align: left;">Extended Key Usage</td>
    <td align="center">MUST</td>
    <td align="center">Y</td>
    <td style="text-align: left;">The value id-kp-timeStamping must be
    present.</td>
    </tr>
    </tbody>
    </table>

2)  Other Certificate

    <table>
    <colgroup>
    <col style="width: 26%" />
    <col style="width: 15%" />
    <col style="width: 14%" />
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
    <td style="text-align: left;" nowrap>Certificate Policies</td>
    <td align="center">MUST</td>
    <td align="center">N</td>
    <td style="text-align: left;">The policy qualifier field in this
    extension may be used as needed. When using this field, it may contain a
    CPS pointer qualifier that points to this CPS.</td>
    </tr>
    <tr>
    <td style="text-align: left;">CRL Distribution Points</td>
    <td align="center">MUST</td>
    <td align="center">N</td>
    <td style="text-align: left;">The HTTP URL of the subordinate CA’s CRL
    service.</td>
    </tr>
    <tr>
    <td style="text-align: left;">Authority Information Access</td>
    <td align="center">MUST</td>
    <td align="center">N</td>
    <td style="text-align: left;"><p>The information included in this
    extension are as follows:</p>
    <ul>
    <li>The HTTP URL of the subordinate CA’s OCSP responder
    (optional)</li>
    <li>The HTTP URL of the subordinate CA’s certificate
    (required)</li>
    </ul></td>
    </tr>
    <tr>
    <td style="text-align: left;" nowrap>Basic Constraints</td>
    <td align="center">OPTIONAL</td>
    <td align="center">N</td>
    <td style="text-align: left;"><p>Subject Type=EE</p>
    <p>Path Length Constraint= None</p></td>
    </tr>
    <tr>
    <td style="text-align: left;">Key Usage</td>
    <td align="center">OPTIONAL</td>
    <td align="center">Y</td>
    <td style="text-align: left;">Bit positions for keyCertSign and cRLSign
    must not be set. Please refer to Section 6.1.7 for the key usage of each
    type of certifcates.</td>
    </tr>
    <tr>
    <td style="text-align: left;">Extended Key Usage</td>
    <td align="center">OPTIONAL</td>
    <td align="center">N</td>
    <td style="text-align: left;">The value anyExtendedKeyUsage must not be
    present.</td>
    </tr>
    <tr>
    <td style="text-align: left;">Authority Key Identifier</td>
    <td align="center">MUST</td>
    <td align="center">N</td>
    <td style="text-align: left;">It must contain a keyIdentifier field and
    it must not contain an authorityCertIssuer or authorityCertSerialNumber
    field.</td>
    </tr>
    </tbody>
    </table>
