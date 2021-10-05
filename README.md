# CISSP-Notes
Notes for CISSP Course
# Day 1
# Day 2
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
5:21 From  Ross Casanova  to  Everyone:
	•	Data subject - The individual who is the subject of personal data.
	•	Data owner - Accountable for determining the value of the data
	•	Data custodian - Data custodians are responsible for the protection of the data while in their custody.
	•	Data steward- Responsible for data content, context, and associated business rules within the organization.
	•	Data controller - Is accountable for protecting the information based on the controls. The controller determines the purposes for and manner in which any personal data is to be processed and, therefore, protected.
	•	Data processor - Data processors are the entities that process the data on behalf of the data controller, therefore, are given the responsibility to protect the data, although the accountability would always remain with the controller.
09:59:24 From  Ross Casanova  to  Everyone:
	Maintaining Data Integrity & Accuracy
	• Quality Control (QC): An assessment of quality
	– Monitor or evaluate data or systems based on internal standards, processes and procedures 
	• Quality Assurance (QA): An assessment of quality
	– Insuring final products meet predetermined external standards of quality
	– Reviewing of the activities and quality control throughout all stages of data development
10:26:43 From  Ross Casanova  to  Everyone:
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
10:27:57 From  Ross Casanova  to  Everyone:
	Separation of Duties & Responsibilities
	• Separation of duties prescribes that multiple people are required to complete critical or sensitive 
	transactions 
	– Protect critical systems, functions, sensitive data or financial transactions 
	– Reduce employee fraud and access abuse
	– Also called dual control or two man rule
	• Collusion: An agreement between two or more individuals to subvert the security provided by SoD
10:32:58 From  Ross Casanova  to  Everyone:
	Protecting confidentiality of data at rest
	– Encrypt backup tapes, thumb drives, DVDs
	– Primary concern is to secure data on a hard disk or removable media
	– Symmetric (AES) encryption is fast and efficient
10:33:40 From  Ross Casanova  to  Everyone:
	Data in motion (network): Data is being sent across the network (being called or moved) TLS or SSL (TLS is perfered)
10:34:18 From  Ross Casanova  to  Everyone:
	Cloud Computing: Control the keys
	– Use symmetric encryption with strong keys
	– Data remnants or provider-retained backups are concerns
	– Also encrypt data in motion across the Internet
10:35:51 From  Ross Casanova  to  Everyone:
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
10:37:37 From  Ross Casanova  to  Everyone:
	Data remanence is residual information remaining on storage media.
10:45:10 From  Ross Casanova  to  Everyone:
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

12:11:56 From  Ross Casanova  to  Everyone:
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

13:06:03 From  Ross Casanova  to  Everyone:
	Key Exchange Out-of-band, pre-shared or using 
	asymmetric algorithms or other key 
	exchange platform 
	Speed Algorithm is less complex and keys 
	are shorter for faster speeds
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
13:06:16 From  Ross Casanova  to  Everyone:
	Keys A single key is shared between two 
	or more entities
	Both encrypt and decrypt
	Two related keys are generated 
	Public is shared by CA, private is a 
	closely-held secret
13:16:04 From  Ross Casanova  to  Everyone:
	Keys A single key is shared between two 
	or more entities
	Both encrypt and decrypt
	Two related keys are generated 
	Public is shared by CA, private is a 
	closely-held secret
13:16:15 From  Ross Casanova  to  Everyone:
	Registration Authority (RA)
	– A type of licensed certificate distributor or middleman
	– Handles some CA tasks such as processing certificate requests, authenticating users, identity proofing and 
	revoking credentials
13:42:52 From  Ross Casanova  to  Everyone:
	Two primary features: Encryption or Integrity
	1. Authentication Header (AH) provides connectionless data integrity and data origin authentication for IP 
	datagrams and provides protection against replay attacks.
	1. Encapsulating Security Payload (ESP) provides confidentiality, connectionless data integrity, data-origin 
	authentication, an anti-replay service (a form of partial sequence integrity), and limited traffic-flow 
	confidentiality.
13:55:40 From  Ross Casanova  to  Everyone:
	Chosen plaintext (what they analyze)
	– Attacker can choose the plaintext and see the resulting ciphertext
	Chosen ciphertext (what they analyze)
	– Attacker has both some encrypted and decrypted text
	Ciphertext only (attacker has captured)
	– Most common type of attack
	Known plaintext (attacker can only analyze)
	– Attacker has both plaintext and ciphertext but cannot choose what gets encrypted
	Implementation attacks (the way it was)

14:15:34 From  Ross Casanova  to  Everyone:
	Man-in-the-Middle Attack (MiTM)
	– Attacker injects itself between two users and reads messages going back and forth or manipulates messages
	– Digital signatures are countermeasures to this type of attack
	Meet-in-the-Middle Attack
	– An attack designed to compromise algorithms that use multiple keys, such as 3DES
14:18:35 From  Ross Casanova  to  Everyone:
	Stream Cipher (RC4): Encrypt data one bit at a time
	– Symmetric Rivest Cipher 4 is faster and more efficient than a block cipher 
	– More suited for hardware implementation than a block cipher
	– Commonly used with older, slower Wi-Fi devices
14:18:51 From  Ross Casanova  to  Everyone:
	Block Cipher (AES): Encrypt blocks of data (128 bits)
	– Symmetric Advanced Encryption Standard is used to encrypt almost all data
	– For data at rest, keys are generated from a user’s password
	– For data in motion, keys are only used for one session and discarded
