# Day 1

<details>
  <summary>Click to expand!</summary>
 
Defines 12 security controls and their objectives
1. Risk Assessment
2. Security Policy
3. Organization Information Security
4. Asset Management
5. Human Resources Security
6. Physical and Environmental Security
7. Communications and Operations Management
8. Access Controls
9. Information System Acquisition, Development and Maintenance
10. Information Security Incident Management
11. Business Continuity Management
12. Compliance – Ensuring conformance

IEC/ISO 27002 Standard: Best Practices

COSO Elements - Control Environment, Risk, Control Activities, Assessment, Information and Communication, Monitoring Activities

Committee of Sponsoring Organizations (COSO)
• Model for corporate governance
• Dedicated to supporting business leadership
• Risk management frameworks
• Their primary focus is on financial issues
• Fraud deterrence
• Internal financial controls and audits

the COSO framework is a model for corporate governance, COBIT is a model for IT governance.

COSO - is a holistic approach based on five key principles:
13. Meeting stakeholder needs
14. Covering the enterprise end to end
15. Applying a single integrated framework
16. Enabling a holistic approach
17. Separating governance from management
 
Payment Card Industry PCI-DSS Model - The Payment Card Industry (PCI) Data Security Standard represents a common set of industry tools 
and measurements to help ensure the safe handling of sensitive information involved in credit card 
purchases.
• The standard provides an actionable framework for developing a robust account data security 
process — including preventing, detecting and reacting to security incidents.
The Payment Card Industry (PCI) Data Security Standard represents a common set of industry tools 
and measurements to help ensure the safe handling of sensitive information involved in credit card 
purchases.
• The standard provides an actionable framework for developing a robust account data security 
process — including preventing, detecting and reacting to security incidents.

PCI DSS Requirements 3.3 and 3.4 apply only to PAN. If Pan is stored with other elements of cardholder data, only the PAN must be rendered unreadable according to PCI DSS Requirement 3.4.
Sensitive authentication data must not be stored after authorization, even if encrypted. 
This applied even where there is no PAN in the environment. 
Organizations should contact heir acquirer or the individual payment brands directly to understand whether SAD is permitted to be stored prior to authorization, for how long, and any related usage and protection requirements

Goals of the Model: Planning Horizon
Strategic Goals – Upper management
– Over-arching: Supported by tactical and operational goals
Tactical Goals – Typical CISSP Middle Manager
– Mid-Term: Lay the necessary foundation to accomplish upper management’s strategic goals
Operational Goals – Administrator’s Duties
– Day-to-day: Focus on productivity and task-oriented activities

Two Key Terms to Understand
Due Care: The degree of care which a person of ordinary prudence would exercise under the same or 
similar circumstances
– Taking the same steps as a reasonable man
– Acting responsibly as managers preventing breaches
Due Diligence: Duty of a firm's directors and officers to act prudently (professionally and legally)
– Ongoing examination of facts and taking actions
– Evaluating risks using best practices to manage them

Reporting of Data Breaches
• Event – Something of note which happened
• Incident – Negative Impact (May Report)
– A security event that compromises the integrity, confidentiality or availability of an asset or violates security 
policy
• Breach – Unauthorized Access (Sometimes Report)
– An incident that results in the disclosure or potential exposure of private or confidential data to unauthorized 
parties
– The number of reported data security breaches continues to increase while becoming more diverse and 
sophisticated
• Data Disclosure – Confirmed Loss of Control (Often Report)
– A breach where data was actually disclosed (not just exposed) to an unauthorized party has been confirmed
Organizations are often legally responsible to report data breaches or disclosure to the proper 
authorities

 Verizon Data Breach Investigation Reports (DBIR), VERIS Rerports
 https://www.verizon.com/business/resources/reports/dbir/

Types of Statutory (Written) Law:
• Administrative law (or regulatory law) defines regulatory standards (mandatory regulations) for the 
performance and the conduct of public bodies including both private companies and federal 
agencies
• Civil or Tort law deals with legal suits over wrongs against individuals or companies that result 
in damages or loss. Cases are initiated by private parties and the defendant is found “liable” or “not 
liable” for damages and court costs.
• Criminal law is about crimes against society. Violations of these government laws is enforced by the 
state and investigated by law enforcement. If the defendant is guilty it provides for punishment 
by imprisonment and fines
• Intellectual Property law protects products of the mind from piracy and license violation

Licensing & Intellectual Property Rights
• Intellectual property is an intangible (non-physical) asset that is the result of creativity (the use of intellect)
• Intellectual property is recognized as a protected asset in the U.S. copyright law. This also extends to 
electronic formats.
• Copyright ©️ law guarantees the creators of “original works of authorship” protection against the unauthorized duplication of their work (music, movies, paintings) for up to 70 years after death.
• Trade secrets are confidential business secrets (intellectual property) not released to outsiders. If lost or stolen by industrial espionage, this proprietary information would aid others and severely damage the 
business. Can be protected forever
• Trademark®️ is a unique design or phrase used to represent or identify products or services. Can be 
protected for a set period of time
• Patent is used to protect creators of inventions (tangible

In the US: the “fair use” doctrine permits some copying and distribution with limitations –	In the US: the “fair use” doctrine permits some copying and distribution with limitations.

(ISC)2 Code of Ethics Canons
– The primary one on the CISSP Exam
Internet Activities Board – IAB
– States what actions the IAB feels is a violation of the nature of the Internet, such as:
– Attacks on CIA should not exist
Generally Accepted Information Security Principles (GAISP from 2003)
– Support the mission of the organization using sound management and judgmen

 (ISC)2 Code of Ethics Canons:
1. Protect society, the commonwealth (nation) and the infrastructure
2. Act honorably, honestly, justly, responsibly and legally
3. Provide diligent and competent service to principals (employers)
4. Advance and protect the profession

• Security policy categories:
– Regulatory
– Advisory (most policies)
– Informative

Security policy types:
– Organizational: Focus on organization-wide aspects
– Issue-specific: Focus on specific aspects (department, service, etc.)
– System-specific: Focus on secure handling of specific systems or types of systems

• Security policies are mandatory

Functions for Supporting Policies:
• Standards – Binding/mandatory
– Compulsory rules that dictate how hardware and software are to be used and expected behavior of employees
• Baselines – Binding/mandatory
– A minimum level of security that is required throughout the organization
• Procedures – Binding/mandatory
– Detailed step-by-step actions to be taken to achieve a specific task
• Guidelines – Non-binding/recommendations
– Recommended actions and operational guides for users and staff members where standards do not apply

Standards:
• Rules that specify a particular course of action or response to a given situation
• Tactical – serve as specifications for the implementation of policies
– Designed to promote implementation of high-level organization policy rather than to create new policy in and 
of themselves
• Used to measure compliance with policies
• Standards are mandatory

Procedures:
• Define specifically how policies, standards, baselines and guidelines will be implemented in a given
situation
• Ensure the integrity of business processes
• May focus on a single component or an entire system
• Need to be updated with related technologies
• Procedures are mandatory

Baselines
• Baselines: Rules that define a minimum level of 
security that is required throughout the 
organization
– Usually platform-specific
– Often based on industry or government standards
• Tools are developed for automated configuration 
compliance checking:
– Solar Winds: Network Configuration Manager, Log & 
Event Manager, etc.
– Microsoft Baseline Security Analyzer
14:45:07 From  Ross Casanova  to  Everyone : Guidelines
• General statements used to recommend or suggest an approach to implementation of policies, 
standards, and baselines
• Do not specify controls or configuration settings
• Not mandatory! Recommendations to consider when implementing security controls
• Flexible – can be customized

**** (ISC)2 is very big on proactive actions such as preparing written plans, policies and procedures, WHY - CISSP is a document driven certification

Service-Level Agreement (SLA)
SLA
A contract that defines the minimum service levels promised by a provider, as well as remedies and 
penalties for situations when performance falls below those levels
• SLA metrics to be monitored and audited
– Service availability
– Defect rates
– Technical quality
– Security
– Carrot-and-stick: Provide rewards for great service and penalties for poor service
• Two things that must be in every SLA
– Your security requirements
– The Right to Audit

Security/Risk Definitions:
Risk is a function of the likelihood of a given threat source exercising a particular potential vulnerability, 
and the resulting impact of that adverse event on the organization
– Likelihood of a threat to occur over a given time period
– Impact: The magnitude of adverse effect that would arise if the circumstance or event occurs
Risk = Threat x Vulnerability x Likelihood
• Vulnerability: A flaw or weakness of an asset
– Asset: Any resource of value to the organization
• Threat: Potential danger (accidental trigger or intentional exploit) to an asset should a threat agent 
take advantage of an asset’s vulnerability

Everyone : Types of Threats
• Threat: Potential danger (accidental trigger or intentional exploit) to an asset should a threat agent 
take advantage of an asset’s vulnerability
• Threat agent/threat source: Anyone and/or anything that has the potential to cause a threat
Threats can be:
– Natural: Floods, earthquakes, tornadoes, landslides, avalanches, etc.
– Human: Events enabled or caused by human beings
• Unintentional acts (errors)
• Deliberate actions (attacks)
– Environmental: Power failure, pollution, chemicals, etc.

Threat Agents: Hackers
• Black-hat hackers (crackers): Skilled computer hackers exploiting security systems without 
authorization for personal gain or for recognition
• White-hat hackers: Security professionals, pentesters or security researchers breaking into 
computer systems with permission of the system owners
• Gray-hat hackers: Skilled hackers conducting security research without permission from the system 
owners but with no malicious intent
• Script kiddies: Unskilled attacker using hacking tools (scripts) created by other people
• Hacktivists: Black-hat hackers motivated by political or ideological reasons

Quantitative:
– Numeric and monetary values based on experience
– Actuary tables or companies provide needed values
Qualitative
– Subjective rating assigned
– “Intuition” or averaged-out Delphi method
– Most decisions typically include elements of both quantitative and qualitative techniques

Start with a realistic estimate of Asset Value (AV)
Exposure Factor (EF) %
Percentage of value lost in a typical incident
Single Loss Expectancy (SLE)
Asset Value (AV) x Exposure Factor (EF) = SLE
Annualized Loss Expectancy (ALE)
SLE x Annualized Rate of Occurrence (ARO) = ALE
Annualized Rate of Occurrence (ARO)
The value that represents the estimated possibility of a specific threat taking place in a given year

Identifying Types of Risks:
Risk identification consists of determining risks that are likely to affect the organization and 
documenting the characteristics of those risks.
• Total Risk (Inherent Risk): Any risk that exists before controls
• Residual Risk: After countermeasures or safeguards
• Accepted Risk: If a company chooses not to implement countermeasures, choose to live with the total risk of a threat
Risk Calculations for Quantitative
– Threats * Vulnerability * Asset Value = Total Risk
– Total Risk * Controls Gap = Residual Risk

Appropriate Responses to Risk:
Mitigate Risk – Reduce/control the risk
– Implement cost-effective controls
Accept Risk
– After careful consideration, the organization decides to live with it without implementing countermeasures
Risk Transference
– Service-Level Agreement (SLA) or insurance
Risk Avoidance
– Risk avoidance involves changing the activity that is causing the risk
• Ignoring a risk is not a valid option

– Assessment focus areas:
• Are controls implemented correctly?
• Are controls operating as intended?
• Are controls meeting the system security requirements?
• How should we update and improve our business

STRIDE, an acronym for common threats:
– Spoofing
– Tampering
– Repudiation
– Information Disclosure
– Denial of Service
– Elevation of Privilege


</details>


# Day 2

<details>
  <summary>Click to expand!</summary>

	KPI vs KGI = The Key Goal Indicators are the outcome you hope to achieve; the KPI is a metric to let you know how well you’re doing working towards that goal.  

	The Key Goal Indicators are the outcome you hope to achieve; the KPI is a metric to let you know how well you’re doing working towards that goal.  

    Data Ownership & Custodianship  
    • Data Owner (often upper management)  
	– Individual responsible and accountable for the protection and classification of a specific data set  
	– The data owner typically delegates most day to-day responsibility such as backup to others (data custodians)  
	– When using discretionary access control (DAC), the data owner/creator allows or denies access to users or   
	groups based on an access control list (ACL). SharePoint allows users to control access  
	
    • Data Custodian (commonly an administrator)  
	– Individual responsible for implementing and maintaining security controls to meet requirements determined 
	by data owner  
	
    • Data Processors (users)  
	– Individual who accesses the resources within the business  
	– The user is limited by the security controls put in place by the custodian, which were determined by the 
	owner  

	•	Data subject - The individual who is the subject of personal data.
	•	Data owner - Accountable for determining the value of the data
	•	Data custodian - Data custodians are responsible for the protection of the data while in their custody.
	•	Data steward- Responsible for data content, context, and associated business rules within the organization.
	•	Data controller - Is accountable for protecting the information based on the controls. The controller determines the purposes for and manner in which any personal data is to be processed and, therefore, protected.
	•	Data processor - Data processors are the entities that process the data on behalf of the data controller, therefore, are given the responsibility to protect the data, although the accountability would always remain with the controller.

	Maintaining Data Integrity & Accuracy
	• Quality Control (QC): An assessment of quality
	– Monitor or evaluate data or systems based on internal standards, processes and procedures 
	• Quality Assurance (QA): An assessment of quality
	– Insuring final products meet predetermined external standards of quality
	– Reviewing of the activities and quality control throughout all stages of data development

	Need-to-Know & Least Privilege
	• Need-to-Know: This refers to the user’s need to have access to only specific resources in order to 
	perform their stated duty and no more
	– Focused primarily on controlled access to information or data
	– Whitelists state what is allowed per user or per group membership
	• Privilege: A right granted to an individual, program or process. Rights have to do with authorization 
	of subject to object and usually allow modifications
	• Least Privilege: Granting to processes or users only those levels of access that process or user needs 
	to perform their official duties
	– Properly protect resources throughout their life cycle
	– Control both permissions to access and rights to make changes

	Separation of Duties & Responsibilities
	• Separation of duties prescribes that multiple people are required to complete critical or sensitive 
	transactions 
	– Protect critical systems, functions, sensitive data or financial transactions 
	– Reduce employee fraud and access abuse
	– Also called dual control or two man rule
	• Collusion: An agreement between two or more individuals to subvert the security provided by SoD

	Protecting confidentiality of data at rest
	– Encrypt backup tapes, thumb drives, DVDs
	– Primary concern is to secure data on a hard disk or removable media
	– Symmetric (AES) encryption is fast and efficient

	Data in motion (network): Data is being sent across the network (being called or moved) TLS or SSL (TLS is perfered)

	Cloud Computing: Control the keys
	– Use symmetric encryption with strong keys
	– Data remnants or provider-retained backups are concerns
	– Also encrypt data in motion across the Internet

	Properly Securing Data at Rest
	• AES symmetric encryption with strong keys
	– Keys must remain secret to provide for confidentiality
	• Static 128-, 192- or 256-bit keys are reused with AES
	– Users do not need to use or enter keys as hex
	– Users enter a password and a proprietary hash created the key
	• File- and folder-level encryption stays when files are moved
	• Protecting removable media 
	– Physically label media: Title, Data owner, Encryption date
	– Secure storage with limited physical access (vault or offline)
	– Document physical location in database
	– Verify that encrypted data can be decrypted (read)
	– Securely delete before media is reused
	
	Data remanence is residual information remaining on storage media.:
	Data Remanence Countermeasures
	Clearing
	Applying logical techniques (deleting and rewriting) to sanitize data to protect against simple non-invasive 
	forensic data recovery techniques
	Purging
	Applying physical or logical techniques that render data recovery infeasible even when using state-of-the-art 
	laboratory techniques
	Choose the most appropriate purging options:
	– Overwriting (BC Wipe): Overwriting storage media with patterns of new data (zeroization) seven times is now adequate for reuse
	– Encryption (crypto-erase): Encrypting the data and not saving (destroying) the symmetric encryption key (Must be able to mount drive)
	– Degaussing: A strong fluctuating magnetizing field destroys media
	– Physical destruction: Breaking (grinding/shredding), chemical alteration, phase transition (liquefaction/vaporization) or incineration


	• Cryptography Defined: Securing Information
	– “The use of mathematical techniques to provide security services such as confidentiality, data integrity, entity 
	authentication, and data origin authentication.”
	• Understandable plaintext is converted to ciphertext
	• Encryption: Algorithm (formula) and Key (variable)
	– Changing the original binary data into to a secure, scrambled message
	• Decryption: Using the same algorithm and a key
	– Change the encrypted message back to its original form
	• Algorithm: A complex mathematical formula
	– Two general types: symmetric and asymmetric
	• Cryptanalysis: The science of breaking secrecy provided by cryptography
	• Key: A numeric variable (parameter) plugged into an algorithm


	Key Exchange Out-of-band, pre-shared or using asymmetric algorithms or other key exchange platform 
	Speed Algorithm is less complex and keys are shorter for faster speeds
	Algorithm is more complex and 
	slower due to huge keys
	Use
	Bulk encryption, which means both 
	encrypting files and communication 
	sessions
	Public — symmetric key encryption 
	aiding key exchange
	Private key digital signature
	Security Service 
	Provided
	Confidentiality only Confidentiality, authentication and 
	non-repudiation
	Number of Keys Grows with number of users Does not grow exponentially
	Public key is freely available from 
	shared digital certificate
	Private key a closely-held secret –
	stored in hardware

	Keys A single key is shared between two 
	or more entities
	Both encrypt and decrypt
	Two related keys are generated 
	Public is shared by CA, private is a 
	closely-held secret

	Keys A single key is shared between two 
	or more entities
	Both encrypt and decrypt
	Two related keys are generated 
	Public is shared by CA, private is a 
	closely-held secret

	Registration Authority (RA)
	– A type of licensed certificate distributor or middleman
	– Handles some CA tasks such as processing certificate requests, authenticating users, identity proofing and 
	revoking credentials

	Two primary features: Encryption or Integrity
	1. Authentication Header (AH) provides connectionless data integrity and data origin authentication for IP 
	datagrams and provides protection against replay attacks.
	2. Encapsulating Security Payload (ESP) provides confidentiality, connectionless data integrity, data-origin 
	authentication, an anti-replay service (a form of partial sequence integrity), and limited traffic-flow 
	confidentiality.

	Chosen plaintext (what they analyze)
	– Attacker can choose the plaintext and see the resulting ciphertext
	Chosen ciphertext (what they analyze)
	– Attacker has both some encrypted and decrypted text
	Ciphertext only (attacker has captured)
	– Most common type of attack
	Known plaintext (attacker can only analyze)
	– Attacker has both plaintext and ciphertext but cannot choose what gets encrypted
	Implementation attacks (the way it was)

	Man-in-the-Middle Attack (MiTM)
	– Attacker injects itself between two users and reads messages going back and forth or manipulates messages
	– Digital signatures are countermeasures to this type of attack
	Meet-in-the-Middle Attack
	– An attack designed to compromise algorithms that use multiple keys, such as 3DES

	Stream Cipher (RC4): Encrypt data one bit at a time
	– Symmetric Rivest Cipher 4 is faster and more efficient than a block cipher 
	– More suited for hardware implementation than a block cipher
	– Commonly used with older, slower Wi-Fi devices

	Block Cipher (AES): Encrypt blocks of data (128 bits)
	– Symmetric Advanced Encryption Standard is used to encrypt almost all data
	– For data at rest, keys are generated from a user’s password
	– For data in motion, keys are only used for one session and discarded


</details>

